
# Animation Channel Schema

```
```

Targets an animation's sampler at a node's property.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [animation.channel.schema.json](animation.channel.schema.json) |

# Animation Channel Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Animation Channel (this schema) |
| [extras](#extras) | complex | Optional  | No | Animation Channel (this schema) |
| [sampler](#sampler) | complex | **Required**  | No | Animation Channel (this schema) |
| [target](#target) | complex | **Required**  | No | Animation Channel (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## extensions


`extensions`

* is optional
* type: complex
* defined in this schema

### extensions Type

Unknown type ``.

```json
{
  "simpletype": "complex"
}
```





## extras


`extras`

* is optional
* type: complex
* defined in this schema

### extras Type

Unknown type ``.

```json
{
  "simpletype": "complex"
}
```





## sampler

The index of a sampler in this animation used to compute the value for the target.

`sampler`

* is **required**
* type: complex
* defined in this schema

### sampler Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## target

The index of the node and TRS property to target.

`target`

* is **required**
* type: complex
* defined in this schema

### target Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `animation.channel.target.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`



# Animation Schema

```
```

A keyframe animation.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [animation.schema.json](animation.schema.json) |

# Animation Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [channels](#channels) | reference | **Required**  | No | Animation (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Animation (this schema) |
| [extras](#extras) | complex | Optional  | No | Animation (this schema) |
| [name](#name) | complex | Optional  | No | Animation (this schema) |
| [samplers](#samplers) | reference | **Required**  | No | Animation (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## channels

An array of channels, each of which targets an animation's sampler at a node's property. Different channels of the same animation can't have equal targets.

`channels`

* is **required**
* type: reference
* at least `1` items in the array
* defined in this schema

### channels Type


Array type: reference

All items must be of the type:
* []() – `animation.channel.schema.json`








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





## name


`name`

* is optional
* type: complex
* defined in this schema

### name Type

Unknown type ``.

```json
{
  "simpletype": "complex"
}
```





## samplers

An array of samplers that combines input and output accessors with an interpolation algorithm to define a keyframe graph (but not its target).

`samplers`

* is **required**
* type: reference
* at least `1` items in the array
* defined in this schema

### samplers Type


Array type: reference

All items must be of the type:
* []() – `animation.sampler.schema.json`









**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`



# Animation Channel Target Schema

```
```

The index of the node and TRS property that an animation channel targets.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [animation.channel.target.schema.json](animation.channel.target.schema.json) |

# Animation Channel Target Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Animation Channel Target (this schema) |
| [extras](#extras) | complex | Optional  | No | Animation Channel Target (this schema) |
| [node](#node) | complex | Optional  | No | Animation Channel Target (this schema) |
| [path](#path) | complex | **Required**  | No | Animation Channel Target (this schema) |
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





## node

The index of the node to target.

`node`

* is optional
* type: complex
* defined in this schema

### node Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## path

The name of the node's TRS property to modify, or the "weights" of the Morph Targets it instantiates. For the "translation" property, the values that are provided by the sampler are the translation along the x, y, and z axes. For the "rotation" property, the values are a quaternion in the order (x, y, z, w), where w is the scalar. For the "scale" property, the values are the scaling factors along the x, y, and z axes.

`path`

* is **required**
* type: complex
* defined in this schema

### path Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3



#### Option 4



#### Option 5


`string`










**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


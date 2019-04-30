
# Material PBR Metallic Roughness Schema

```
```

A set of parameter values that are used to define the metallic-roughness material model from Physically-Based Rendering (PBR) methodology.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [material.pbrMetallicRoughness.schema.json](material.pbrMetallicRoughness.schema.json) |

# Material PBR Metallic Roughness Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [baseColorFactor](#basecolorfactor) | `number[]` | Optional  | No | `[1,1,1,1]` | Material PBR Metallic Roughness (this schema) |
| [baseColorTexture](#basecolortexture) | complex | Optional  | No |  | Material PBR Metallic Roughness (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Material PBR Metallic Roughness (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Material PBR Metallic Roughness (this schema) |
| [metallicFactor](#metallicfactor) | `number` | Optional  | No | `1` | Material PBR Metallic Roughness (this schema) |
| [metallicRoughnessTexture](#metallicroughnesstexture) | complex | Optional  | No |  | Material PBR Metallic Roughness (this schema) |
| [roughnessFactor](#roughnessfactor) | `number` | Optional  | No | `1` | Material PBR Metallic Roughness (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## baseColorFactor

The material's base color factor.

`baseColorFactor`

* is optional
* type: `number[]`
* between `4` and `4` items in the array

* default: `[1,1,1,1]`
* defined in this schema

### baseColorFactor Type


Array type: `number[]`

All items must be of the type:
`number`

* minimum value: `0`
* maximum value: `1`








## baseColorTexture

The base color texture.

`baseColorTexture`

* is optional
* type: complex
* defined in this schema

### baseColorTexture Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `textureInfo.schema.json`






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





## metallicFactor

The metalness of the material.

`metallicFactor`

* is optional
* type: `number`
* default: `1`
* defined in this schema

### metallicFactor Type


`number`

* minimum value: `0`
* maximum value: `1`





## metallicRoughnessTexture

The metallic-roughness texture.

`metallicRoughnessTexture`

* is optional
* type: complex
* defined in this schema

### metallicRoughnessTexture Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `textureInfo.schema.json`






## roughnessFactor

The roughness of the material.

`roughnessFactor`

* is optional
* type: `number`
* default: `1`
* defined in this schema

### roughnessFactor Type


`number`

* minimum value: `0`
* maximum value: `1`






**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


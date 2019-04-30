
# Material Schema

```
```

The material appearance of a primitive.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [material.schema.json](material.schema.json) |

# Material Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [alphaCutoff](#alphacutoff) | `number` | Optional  | No | `0.5` | Material (this schema) |
| [alphaMode](#alphamode) | complex | Optional  | No | `"OPAQUE"` | Material (this schema) |
| [doubleSided](#doublesided) | `boolean` | Optional  | No | `false` | Material (this schema) |
| [emissiveFactor](#emissivefactor) | `number[]` | Optional  | No | `[0,0,0]` | Material (this schema) |
| [emissiveTexture](#emissivetexture) | complex | Optional  | No |  | Material (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Material (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Material (this schema) |
| [name](#name) | complex | Optional  | No |  | Material (this schema) |
| [normalTexture](#normaltexture) | complex | Optional  | No |  | Material (this schema) |
| [occlusionTexture](#occlusiontexture) | complex | Optional  | No |  | Material (this schema) |
| [pbrMetallicRoughness](#pbrmetallicroughness) | complex | Optional  | No |  | Material (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## alphaCutoff

The alpha cutoff value of the material.

`alphaCutoff`

* is optional
* type: `number`
* default: `0.5`
* defined in this schema

### alphaCutoff Type


`number`

* minimum value: `0`






## alphaMode

The alpha rendering mode of the material.

`alphaMode`

* is optional
* type: complex
* default: `"OPAQUE"`
* defined in this schema

### alphaMode Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3



#### Option 4


`string`









## doubleSided

Specifies whether the material is double sided.

`doubleSided`

* is optional
* type: `boolean`
* default: `false`
* defined in this schema

### doubleSided Type


`boolean`





## emissiveFactor

The emissive color of the material.

`emissiveFactor`

* is optional
* type: `number[]`
* between `3` and `3` items in the array

* default: `[0,0,0]`
* defined in this schema

### emissiveFactor Type


Array type: `number[]`

All items must be of the type:
`number`

* minimum value: `0`
* maximum value: `1`








## emissiveTexture

The emissive map texture.

`emissiveTexture`

* is optional
* type: complex
* defined in this schema

### emissiveTexture Type


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





## normalTexture

The normal map texture.

`normalTexture`

* is optional
* type: complex
* defined in this schema

### normalTexture Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `material.normalTextureInfo.schema.json`






## occlusionTexture

The occlusion map texture.

`occlusionTexture`

* is optional
* type: complex
* defined in this schema

### occlusionTexture Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `material.occlusionTextureInfo.schema.json`






## pbrMetallicRoughness

A set of parameter values that are used to define the metallic-roughness material model from Physically-Based Rendering (PBR) methodology. When not specified, all the default values of `pbrMetallicRoughness` apply.

`pbrMetallicRoughness`

* is optional
* type: complex
* defined in this schema

### pbrMetallicRoughness Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `material.pbrMetallicRoughness.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


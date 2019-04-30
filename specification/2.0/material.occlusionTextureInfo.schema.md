
# Material Occlusion Texture Info Schema

```
```


| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [material.occlusionTextureInfo.schema.json](material.occlusionTextureInfo.schema.json) |

# Material Occlusion Texture Info Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [extensions](#extensions) | complex | Optional  | No |  | Material Occlusion Texture Info (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Material Occlusion Texture Info (this schema) |
| [index](#index) | complex | Optional  | No |  | Material Occlusion Texture Info (this schema) |
| [strength](#strength) | `number` | Optional  | No | `1` | Material Occlusion Texture Info (this schema) |
| [texCoord](#texcoord) | complex | Optional  | No |  | Material Occlusion Texture Info (this schema) |
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





## index


`index`

* is optional
* type: complex
* defined in this schema

### index Type

Unknown type ``.

```json
{
  "simpletype": "complex"
}
```





## strength

A scalar multiplier controlling the amount of occlusion applied.

`strength`

* is optional
* type: `number`
* default: `1`
* defined in this schema

### strength Type


`number`

* minimum value: `0`
* maximum value: `1`





## texCoord


`texCoord`

* is optional
* type: complex
* defined in this schema

### texCoord Type

Unknown type ``.

```json
{
  "simpletype": "complex"
}
```






**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `textureInfo.schema.json`


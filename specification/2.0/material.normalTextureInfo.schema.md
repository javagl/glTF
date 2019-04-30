
# Material Normal Texture Info Schema

```
```


| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [material.normalTextureInfo.schema.json](material.normalTextureInfo.schema.json) |

# Material Normal Texture Info Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [extensions](#extensions) | complex | Optional  | No |  | Material Normal Texture Info (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Material Normal Texture Info (this schema) |
| [index](#index) | complex | Optional  | No |  | Material Normal Texture Info (this schema) |
| [scale](#scale) | `number` | Optional  | No | `1` | Material Normal Texture Info (this schema) |
| [texCoord](#texcoord) | complex | Optional  | No |  | Material Normal Texture Info (this schema) |
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





## scale

The scalar multiplier applied to each normal vector of the normal texture.

`scale`

* is optional
* type: `number`
* default: `1`
* defined in this schema

### scale Type


`number`







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


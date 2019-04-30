
# Texture Info Schema

```
```

Reference to a texture.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [textureInfo.schema.json](textureInfo.schema.json) |

# Texture Info Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [extensions](#extensions) | complex | Optional  | No |  | Texture Info (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Texture Info (this schema) |
| [index](#index) | complex | **Required**  | No |  | Texture Info (this schema) |
| [texCoord](#texcoord) | `integer` | Optional  | No | `0` | Texture Info (this schema) |
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

The index of the texture.

`index`

* is **required**
* type: complex
* defined in this schema

### index Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## texCoord

The set index of texture's TEXCOORD attribute used for texture coordinate mapping.

`texCoord`

* is optional
* type: `integer`
* default: `0`
* defined in this schema

### texCoord Type


`integer`

* minimum value: `0`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


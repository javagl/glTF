
# Image Schema

```
```

Image data used to create a texture. Image can be referenced by URI or `bufferView` index. `mimeType` is required in the latter case.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [image.schema.json](image.schema.json) |

# Image Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [bufferView](#bufferview) | complex | Optional  | No | Image (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Image (this schema) |
| [extras](#extras) | complex | Optional  | No | Image (this schema) |
| [mimeType](#mimetype) | complex | Optional  | No | Image (this schema) |
| [name](#name) | complex | Optional  | No | Image (this schema) |
| [uri](#uri) | `string` | Optional  | No | Image (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## bufferView

The index of the bufferView that contains the image. Use this instead of the image's uri property.

`bufferView`

* is optional
* type: complex
* defined in this schema

### bufferView Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






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





## mimeType

The image's MIME type. Required if `bufferView` is defined.

`mimeType`

* is optional
* type: complex
* defined in this schema

### mimeType Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3


`string`









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





## uri

The uri of the image.

`uri`

* is optional
* type: `string`
* defined in this schema

### uri Type


`string`








**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


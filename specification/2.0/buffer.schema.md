
# Buffer Schema

```
```

A buffer points to binary geometry, animation, or skins.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [buffer.schema.json](buffer.schema.json) |

# Buffer Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [byteLength](#bytelength) | `integer` | **Required**  | No | Buffer (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Buffer (this schema) |
| [extras](#extras) | complex | Optional  | No | Buffer (this schema) |
| [name](#name) | complex | Optional  | No | Buffer (this schema) |
| [uri](#uri) | `string` | Optional  | No | Buffer (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## byteLength

The length of the buffer in bytes.

`byteLength`

* is **required**
* type: `integer`
* defined in this schema

### byteLength Type


`integer`

* minimum value: `1`






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





## uri

The uri of the buffer.

`uri`

* is optional
* type: `string`
* defined in this schema

### uri Type


`string`








**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


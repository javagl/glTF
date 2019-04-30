
# Buffer View Schema

```
```

A view into a buffer generally representing a subset of the buffer.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [bufferView.schema.json](bufferView.schema.json) |

# Buffer View Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [buffer](#buffer) | complex | **Required**  | No |  | Buffer View (this schema) |
| [byteLength](#bytelength) | `integer` | **Required**  | No |  | Buffer View (this schema) |
| [byteOffset](#byteoffset) | `integer` | Optional  | No | `0` | Buffer View (this schema) |
| [byteStride](#bytestride) | `integer` | Optional  | No |  | Buffer View (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Buffer View (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Buffer View (this schema) |
| [name](#name) | complex | Optional  | No |  | Buffer View (this schema) |
| [target](#target) | complex | Optional  | No |  | Buffer View (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## buffer

The index of the buffer.

`buffer`

* is **required**
* type: complex
* defined in this schema

### buffer Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## byteLength

The total byte length of the buffer view.

`byteLength`

* is **required**
* type: `integer`
* defined in this schema

### byteLength Type


`integer`

* minimum value: `1`






## byteOffset

The offset into the buffer in bytes.

`byteOffset`

* is optional
* type: `integer`
* default: `0`
* defined in this schema

### byteOffset Type


`integer`

* minimum value: `0`






## byteStride

The stride, in bytes.

`byteStride`

* is optional
* type: `integer`
* defined in this schema

### byteStride Type


`integer`

* minimum value: `4`
* maximum value: `252`
* must be a multiple of `4`





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





## target

The target that the GPU buffer should be bound to.

`target`

* is optional
* type: complex
* defined in this schema

### target Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`










**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


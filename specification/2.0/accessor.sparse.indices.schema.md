
# Accessor Sparse Indices Schema

```
```

Indices of those attributes that deviate from their initialization value.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [accessor.sparse.indices.schema.json](accessor.sparse.indices.schema.json) |

# Accessor Sparse Indices Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [bufferView](#bufferview) | complex | **Required**  | No |  | Accessor Sparse Indices (this schema) |
| [byteOffset](#byteoffset) | `integer` | Optional  | No | `0` | Accessor Sparse Indices (this schema) |
| [componentType](#componenttype) | complex | **Required**  | No |  | Accessor Sparse Indices (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Accessor Sparse Indices (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Accessor Sparse Indices (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## bufferView

The index of the bufferView with sparse indices. Referenced bufferView can't have ARRAY_BUFFER or ELEMENT_ARRAY_BUFFER target.

`bufferView`

* is **required**
* type: complex
* defined in this schema

### bufferView Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## byteOffset

The offset relative to the start of the bufferView in bytes. Must be aligned.

`byteOffset`

* is optional
* type: `integer`
* default: `0`
* defined in this schema

### byteOffset Type


`integer`

* minimum value: `0`






## componentType

The indices data type.

`componentType`

* is **required**
* type: complex
* defined in this schema

### componentType Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`




#### Option 4


`integer`









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






**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


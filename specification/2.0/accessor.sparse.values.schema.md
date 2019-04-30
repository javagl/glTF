
# Accessor Sparse Values Schema

```
```

Array of size `accessor.sparse.count` times number of components storing the displaced accessor attributes pointed by `accessor.sparse.indices`.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [accessor.sparse.values.schema.json](accessor.sparse.values.schema.json) |

# Accessor Sparse Values Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [bufferView](#bufferview) | complex | **Required**  | No |  | Accessor Sparse Values (this schema) |
| [byteOffset](#byteoffset) | `integer` | Optional  | No | `0` | Accessor Sparse Values (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Accessor Sparse Values (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Accessor Sparse Values (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## bufferView

The index of the bufferView with sparse values. Referenced bufferView can't have ARRAY_BUFFER or ELEMENT_ARRAY_BUFFER target.

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



# Accessor Sparse Schema

```
```

Sparse storage of attributes that deviate from their initialization value.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [accessor.sparse.schema.json](accessor.sparse.schema.json) |

# Accessor Sparse Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [count](#count) | `integer` | **Required**  | No | Accessor Sparse (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Accessor Sparse (this schema) |
| [extras](#extras) | complex | Optional  | No | Accessor Sparse (this schema) |
| [indices](#indices) | complex | **Required**  | No | Accessor Sparse (this schema) |
| [values](#values) | complex | **Required**  | No | Accessor Sparse (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## count

Number of entries stored in the sparse array.

`count`

* is **required**
* type: `integer`
* defined in this schema

### count Type


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





## indices

Index array of size `count` that points to those accessor attributes that deviate from their initialization value. Indices must strictly increase.

`indices`

* is **required**
* type: complex
* defined in this schema

### indices Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `accessor.sparse.indices.schema.json`






## values

Array of size `count` times number of components, storing the displaced accessor attributes pointed by `indices`. Substituted values must have the same `componentType` and number of components as the base accessor.

`values`

* is **required**
* type: complex
* defined in this schema

### values Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `accessor.sparse.values.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`



# Skin Schema

```
```

Joints and matrices defining a skin.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [skin.schema.json](skin.schema.json) |

# Skin Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Skin (this schema) |
| [extras](#extras) | complex | Optional  | No | Skin (this schema) |
| [inverseBindMatrices](#inversebindmatrices) | complex | Optional  | No | Skin (this schema) |
| [joints](#joints) | reference | **Required**  | No | Skin (this schema) |
| [name](#name) | complex | Optional  | No | Skin (this schema) |
| [skeleton](#skeleton) | complex | Optional  | No | Skin (this schema) |
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





## inverseBindMatrices

The index of the accessor containing the floating-point 4x4 inverse-bind matrices.  The default is that each matrix is a 4x4 identity matrix, which implies that inverse-bind matrices were pre-applied.

`inverseBindMatrices`

* is optional
* type: complex
* defined in this schema

### inverseBindMatrices Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## joints

Indices of skeleton nodes, used as joints in this skin.

`joints`

* is **required**
* type: reference
* at least `1` items in the array
* defined in this schema

### joints Type


Array type: reference

All items must be of the type:
* []() – `glTFid.schema.json`








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





## skeleton

The index of the node used as a skeleton root.

`skeleton`

* is optional
* type: complex
* defined in this schema

### skeleton Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


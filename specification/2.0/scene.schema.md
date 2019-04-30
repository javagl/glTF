
# Scene Schema

```
```

The root nodes of a scene.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [scene.schema.json](scene.schema.json) |

# Scene Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Scene (this schema) |
| [extras](#extras) | complex | Optional  | No | Scene (this schema) |
| [name](#name) | complex | Optional  | No | Scene (this schema) |
| [nodes](#nodes) | reference | Optional  | No | Scene (this schema) |
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





## nodes

The indices of each root node.

`nodes`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### nodes Type


Array type: reference

All items must be of the type:
* []() – `glTFid.schema.json`









**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`



# Mesh Schema

```
```

A set of primitives to be rendered.  A node can contain one mesh.  A node's transform places the mesh in the scene.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [mesh.schema.json](mesh.schema.json) |

# Mesh Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Mesh (this schema) |
| [extras](#extras) | complex | Optional  | No | Mesh (this schema) |
| [name](#name) | complex | Optional  | No | Mesh (this schema) |
| [primitives](#primitives) | reference | **Required**  | No | Mesh (this schema) |
| [weights](#weights) | `number[]` | Optional  | No | Mesh (this schema) |
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





## primitives

An array of primitives, each defining geometry to be rendered with a material.

`primitives`

* is **required**
* type: reference
* at least `1` items in the array
* defined in this schema

### primitives Type


Array type: reference

All items must be of the type:
* []() – `mesh.primitive.schema.json`








## weights

Array of weights to be applied to the Morph Targets.

`weights`

* is optional
* type: `number[]`
* at least `1` items in the array
* defined in this schema

### weights Type


Array type: `number[]`

All items must be of the type:
`number`











**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


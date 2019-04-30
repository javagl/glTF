
# Mesh Primitive Schema

```
```

Geometry to be rendered with the given material.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [mesh.primitive.schema.json](mesh.primitive.schema.json) |

# Mesh Primitive Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [attributes](#attributes) | `object` | **Required**  | No |  | Mesh Primitive (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Mesh Primitive (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Mesh Primitive (this schema) |
| [indices](#indices) | complex | Optional  | No |  | Mesh Primitive (this schema) |
| [material](#material) | complex | Optional  | No |  | Mesh Primitive (this schema) |
| [mode](#mode) | complex | Optional  | No | `4` | Mesh Primitive (this schema) |
| [targets](#targets) | `object[]` | Optional  | No |  | Mesh Primitive (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## attributes

A dictionary object, where each key corresponds to mesh attribute semantic and each value is the index of the accessor containing attribute's data.

`attributes`

* is **required**
* type: `object`
* defined in this schema

### attributes Type


`object` with following properties:


| Property | Type | Required |
|----------|------|----------|






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

The index of the accessor that contains the indices.

`indices`

* is optional
* type: complex
* defined in this schema

### indices Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## material

The index of the material to apply to this primitive when rendering.

`material`

* is optional
* type: complex
* defined in this schema

### material Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## mode

The type of primitives to render.

`mode`

* is optional
* type: complex
* default: `4`
* defined in this schema

### mode Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`




#### Option 4


`integer`




#### Option 5


`integer`




#### Option 6


`integer`




#### Option 7


`integer`




#### Option 8


`integer`









## targets

An array of Morph Targets, each  Morph Target is a dictionary mapping attributes (only `POSITION`, `NORMAL`, and `TANGENT` supported) to their deviations in the Morph Target.

`targets`

* is optional
* type: `object[]`
* at least `1` items in the array
* defined in this schema

### targets Type


Array type: `object[]`

All items must be of the type:
`object` with following properties:


| Property | Type | Required |
|----------|------|----------|


  
A dictionary object specifying attributes displacements in a Morph Target, where each key corresponds to one of the three supported attribute semantic (`POSITION`, `NORMAL`, or `TANGENT`) and each value is the index of the accessor containing the attribute displacements' data.








**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


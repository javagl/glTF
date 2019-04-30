
# Node Schema

```
```

A node in the node hierarchy.  When the node contains `skin`, all `mesh.primitives` must contain `JOINTS_0` and `WEIGHTS_0` attributes.  A node can have either a `matrix` or any combination of `translation`/`rotation`/`scale` (TRS) properties. TRS properties are converted to matrices and postmultiplied in the `T * R * S` order to compose the transformation matrix; first the scale is applied to the vertices, then the rotation, and then the translation. If none are provided, the transform is the identity. When a node is targeted for animation (referenced by an animation.channel.target), only TRS properties may be present; `matrix` will not be present.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [node.schema.json](node.schema.json) |

# Node Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [camera](#camera) | complex | Optional  | No |  | Node (this schema) |
| [children](#children) | reference | Optional  | No |  | Node (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Node (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Node (this schema) |
| [matrix](#matrix) | `number[]` | Optional  | No | `[1,0,0,0,0,1,0,0,0,0,1,0,0,0,0,1]` | Node (this schema) |
| [mesh](#mesh) | complex | Optional  | No |  | Node (this schema) |
| [name](#name) | complex | Optional  | No |  | Node (this schema) |
| [rotation](#rotation) | `number[]` | Optional  | No | `[0,0,0,1]` | Node (this schema) |
| [scale](#scale) | `number[]` | Optional  | No | `[1,1,1]` | Node (this schema) |
| [skin](#skin) | complex | Optional  | No |  | Node (this schema) |
| [translation](#translation) | `number[]` | Optional  | No | `[0,0,0]` | Node (this schema) |
| [weights](#weights) | `number[]` | Optional  | No |  | Node (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## camera

The index of the camera referenced by this node.

`camera`

* is optional
* type: complex
* defined in this schema

### camera Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## children

The indices of this node's children.

`children`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### children Type


Array type: reference

All items must be of the type:
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





## matrix

A floating-point 4x4 transformation matrix stored in column-major order.

`matrix`

* is optional
* type: `number[]`
* between `16` and `16` items in the array

* default: `[1,0,0,0,0,1,0,0,0,0,1,0,0,0,0,1]`
* defined in this schema

### matrix Type


Array type: `number[]`

All items must be of the type:
`number`










## mesh

The index of the mesh in this node.

`mesh`

* is optional
* type: complex
* defined in this schema

### mesh Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


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





## rotation

The node's unit quaternion rotation in the order (x, y, z, w), where w is the scalar.

`rotation`

* is optional
* type: `number[]`
* between `4` and `4` items in the array

* default: `[0,0,0,1]`
* defined in this schema

### rotation Type


Array type: `number[]`

All items must be of the type:
`number`

* minimum value: `-1`
* maximum value: `1`








## scale

The node's non-uniform scale, given as the scaling factors along the x, y, and z axes.

`scale`

* is optional
* type: `number[]`
* between `3` and `3` items in the array

* default: `[1,1,1]`
* defined in this schema

### scale Type


Array type: `number[]`

All items must be of the type:
`number`










## skin

The index of the skin referenced by this node.

`skin`

* is optional
* type: complex
* defined in this schema

### skin Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## translation

The node's translation along the x, y, and z axes.

`translation`

* is optional
* type: `number[]`
* between `3` and `3` items in the array

* default: `[0,0,0]`
* defined in this schema

### translation Type


Array type: `number[]`

All items must be of the type:
`number`










## weights

The weights of the instantiated Morph Target. Number of elements must match number of Morph Targets of used mesh.

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


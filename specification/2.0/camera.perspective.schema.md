
# Camera Perspective Schema

```
```

A perspective camera containing properties to create a perspective projection matrix.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [camera.perspective.schema.json](camera.perspective.schema.json) |

# Camera Perspective Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [aspectRatio](#aspectratio) | `number` | Optional  | No | Camera Perspective (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Camera Perspective (this schema) |
| [extras](#extras) | complex | Optional  | No | Camera Perspective (this schema) |
| [yfov](#yfov) | `number` | **Required**  | No | Camera Perspective (this schema) |
| [zfar](#zfar) | `number` | Optional  | No | Camera Perspective (this schema) |
| [znear](#znear) | `number` | **Required**  | No | Camera Perspective (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## aspectRatio

The floating-point aspect ratio of the field of view.

`aspectRatio`

* is optional
* type: `number`
* defined in this schema

### aspectRatio Type


`number`

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





## yfov

The floating-point vertical field of view in radians.

`yfov`

* is **required**
* type: `number`
* defined in this schema

### yfov Type


`number`

* minimum value: `0`






## zfar

The floating-point distance to the far clipping plane.

`zfar`

* is optional
* type: `number`
* defined in this schema

### zfar Type


`number`

* minimum value: `0`






## znear

The floating-point distance to the near clipping plane.

`znear`

* is **required**
* type: `number`
* defined in this schema

### znear Type


`number`

* minimum value: `0`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


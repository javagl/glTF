
# Camera Orthographic Schema

```
```

An orthographic camera containing properties to create an orthographic projection matrix.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [camera.orthographic.schema.json](camera.orthographic.schema.json) |

# Camera Orthographic Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Camera Orthographic (this schema) |
| [extras](#extras) | complex | Optional  | No | Camera Orthographic (this schema) |
| [xmag](#xmag) | `number` | **Required**  | No | Camera Orthographic (this schema) |
| [ymag](#ymag) | `number` | **Required**  | No | Camera Orthographic (this schema) |
| [zfar](#zfar) | `number` | **Required**  | No | Camera Orthographic (this schema) |
| [znear](#znear) | `number` | **Required**  | No | Camera Orthographic (this schema) |
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





## xmag

The floating-point horizontal magnification of the view. Must not be zero.

`xmag`

* is **required**
* type: `number`
* defined in this schema

### xmag Type


`number`







## ymag

The floating-point vertical magnification of the view. Must not be zero.

`ymag`

* is **required**
* type: `number`
* defined in this schema

### ymag Type


`number`







## zfar

The floating-point distance to the far clipping plane. `zfar` must be greater than `znear`.

`zfar`

* is **required**
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


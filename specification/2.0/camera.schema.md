
# Camera Schema

```
```

A camera's projection.  A node can reference a camera to apply a transform to place the camera in the scene.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [camera.schema.json](camera.schema.json) |

# Camera Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Camera (this schema) |
| [extras](#extras) | complex | Optional  | No | Camera (this schema) |
| [name](#name) | complex | Optional  | No | Camera (this schema) |
| [orthographic](#orthographic) | complex | Optional  | No | Camera (this schema) |
| [perspective](#perspective) | complex | Optional  | No | Camera (this schema) |
| [type](#type) | complex | **Required**  | No | Camera (this schema) |
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





## orthographic

An orthographic camera containing properties to create an orthographic projection matrix.

`orthographic`

* is optional
* type: complex
* defined in this schema

### orthographic Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `camera.orthographic.schema.json`






## perspective

A perspective camera containing properties to create a perspective projection matrix.

`perspective`

* is optional
* type: complex
* defined in this schema

### perspective Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `camera.perspective.schema.json`






## type

Specifies if the camera uses a perspective or orthographic projection.

`type`

* is **required**
* type: complex
* defined in this schema

### type Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3


`string`










**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


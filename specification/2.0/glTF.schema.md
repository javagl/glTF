
# glTF Schema

```
```

The root object for a glTF asset.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [glTF.schema.json](glTF.schema.json) |

# glTF Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [accessors](#accessors) | reference | Optional  | No | glTF (this schema) |
| [animations](#animations) | reference | Optional  | No | glTF (this schema) |
| [asset](#asset) | complex | **Required**  | No | glTF (this schema) |
| [bufferViews](#bufferviews) | reference | Optional  | No | glTF (this schema) |
| [buffers](#buffers) | reference | Optional  | No | glTF (this schema) |
| [cameras](#cameras) | reference | Optional  | No | glTF (this schema) |
| [extensions](#extensions) | complex | Optional  | No | glTF (this schema) |
| [extensionsRequired](#extensionsrequired) | `string[]` | Optional  | No | glTF (this schema) |
| [extensionsUsed](#extensionsused) | `string[]` | Optional  | No | glTF (this schema) |
| [extras](#extras) | complex | Optional  | No | glTF (this schema) |
| [images](#images) | reference | Optional  | No | glTF (this schema) |
| [materials](#materials) | reference | Optional  | No | glTF (this schema) |
| [meshes](#meshes) | reference | Optional  | No | glTF (this schema) |
| [nodes](#nodes) | reference | Optional  | No | glTF (this schema) |
| [samplers](#samplers) | reference | Optional  | No | glTF (this schema) |
| [scene](#scene) | complex | Optional  | No | glTF (this schema) |
| [scenes](#scenes) | reference | Optional  | No | glTF (this schema) |
| [skins](#skins) | reference | Optional  | No | glTF (this schema) |
| [textures](#textures) | reference | Optional  | No | glTF (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## accessors

An array of accessors.

`accessors`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### accessors Type


Array type: reference

All items must be of the type:
* []() – `accessor.schema.json`








## animations

An array of keyframe animations.

`animations`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### animations Type


Array type: reference

All items must be of the type:
* []() – `animation.schema.json`








## asset

Metadata about the glTF asset.

`asset`

* is **required**
* type: complex
* defined in this schema

### asset Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `asset.schema.json`






## bufferViews

An array of bufferViews.

`bufferViews`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### bufferViews Type


Array type: reference

All items must be of the type:
* []() – `bufferView.schema.json`








## buffers

An array of buffers.

`buffers`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### buffers Type


Array type: reference

All items must be of the type:
* []() – `buffer.schema.json`








## cameras

An array of cameras.

`cameras`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### cameras Type


Array type: reference

All items must be of the type:
* []() – `camera.schema.json`








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





## extensionsRequired

Names of glTF extensions required to properly load this asset.

`extensionsRequired`

* is optional
* type: `string[]`
* at least `1` items in the array
* defined in this schema

### extensionsRequired Type


Array type: `string[]`

All items must be of the type:
`string`










## extensionsUsed

Names of glTF extensions used somewhere in this asset.

`extensionsUsed`

* is optional
* type: `string[]`
* at least `1` items in the array
* defined in this schema

### extensionsUsed Type


Array type: `string[]`

All items must be of the type:
`string`










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





## images

An array of images.

`images`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### images Type


Array type: reference

All items must be of the type:
* []() – `image.schema.json`








## materials

An array of materials.

`materials`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### materials Type


Array type: reference

All items must be of the type:
* []() – `material.schema.json`








## meshes

An array of meshes.

`meshes`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### meshes Type


Array type: reference

All items must be of the type:
* []() – `mesh.schema.json`








## nodes

An array of nodes.

`nodes`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### nodes Type


Array type: reference

All items must be of the type:
* []() – `node.schema.json`








## samplers

An array of samplers.

`samplers`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### samplers Type


Array type: reference

All items must be of the type:
* []() – `sampler.schema.json`








## scene

The index of the default scene.

`scene`

* is optional
* type: complex
* defined in this schema

### scene Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## scenes

An array of scenes.

`scenes`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### scenes Type


Array type: reference

All items must be of the type:
* []() – `scene.schema.json`








## skins

An array of skins.

`skins`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### skins Type


Array type: reference

All items must be of the type:
* []() – `skin.schema.json`








## textures

An array of textures.

`textures`

* is optional
* type: reference
* at least `1` items in the array
* defined in this schema

### textures Type


Array type: reference

All items must be of the type:
* []() – `texture.schema.json`









**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


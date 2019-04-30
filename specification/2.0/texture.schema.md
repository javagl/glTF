
# Texture Schema

```
```

A texture and its sampler.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [texture.schema.json](texture.schema.json) |

# Texture Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [extensions](#extensions) | complex | Optional  | No | Texture (this schema) |
| [extras](#extras) | complex | Optional  | No | Texture (this schema) |
| [name](#name) | complex | Optional  | No | Texture (this schema) |
| [sampler](#sampler) | complex | Optional  | No | Texture (this schema) |
| [source](#source) | complex | Optional  | No | Texture (this schema) |
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





## sampler

The index of the sampler used by this texture. When undefined, a sampler with repeat wrapping and auto filtering should be used.

`sampler`

* is optional
* type: complex
* defined in this schema

### sampler Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## source

The index of the image used by this texture. When undefined, it is expected that an extension or other mechanism will supply an alternate texture source, otherwise behavior is undefined.

`source`

* is optional
* type: complex
* defined in this schema

### source Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`



# Animation Sampler Schema

```
```

Combines input and output accessors with an interpolation algorithm to define a keyframe graph (but not its target).

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [animation.sampler.schema.json](animation.sampler.schema.json) |

# Animation Sampler Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [extensions](#extensions) | complex | Optional  | No |  | Animation Sampler (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Animation Sampler (this schema) |
| [input](#input) | complex | **Required**  | No |  | Animation Sampler (this schema) |
| [interpolation](#interpolation) | complex | Optional  | No | `"LINEAR"` | Animation Sampler (this schema) |
| [output](#output) | complex | **Required**  | No |  | Animation Sampler (this schema) |
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





## input

The index of an accessor containing keyframe input values, e.g., time.

`input`

* is **required**
* type: complex
* defined in this schema

### input Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## interpolation

Interpolation algorithm.

`interpolation`

* is optional
* type: complex
* default: `"LINEAR"`
* defined in this schema

### interpolation Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3



#### Option 4


`string`









## output

The index of an accessor, containing keyframe output values.

`output`

* is **required**
* type: complex
* defined in this schema

### output Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


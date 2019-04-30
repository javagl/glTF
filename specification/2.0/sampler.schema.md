
# Sampler Schema

```
```

Texture sampler properties for filtering and wrapping modes.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [sampler.schema.json](sampler.schema.json) |

# Sampler Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [extensions](#extensions) | complex | Optional  | No |  | Sampler (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Sampler (this schema) |
| [magFilter](#magfilter) | complex | Optional  | No |  | Sampler (this schema) |
| [minFilter](#minfilter) | complex | Optional  | No |  | Sampler (this schema) |
| [name](#name) | complex | Optional  | No |  | Sampler (this schema) |
| [wrapS](#wraps) | complex | Optional  | No | `10497` | Sampler (this schema) |
| [wrapT](#wrapt) | complex | Optional  | No | `10497` | Sampler (this schema) |
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





## magFilter

Magnification filter.

`magFilter`

* is optional
* type: complex
* defined in this schema

### magFilter Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`









## minFilter

Minification filter.

`minFilter`

* is optional
* type: complex
* defined in this schema

### minFilter Type


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





## wrapS

s wrapping mode.

`wrapS`

* is optional
* type: complex
* default: `10497`
* defined in this schema

### wrapS Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`




#### Option 4


`integer`









## wrapT

t wrapping mode.

`wrapT`

* is optional
* type: complex
* default: `10497`
* defined in this schema

### wrapT Type


**Any** following *options* needs to be fulfilled.


#### Option 1


`integer`




#### Option 2


`integer`




#### Option 3


`integer`




#### Option 4


`integer`










**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


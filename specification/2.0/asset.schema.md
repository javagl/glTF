
# Asset Schema

```
```

Metadata about the glTF asset.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [asset.schema.json](asset.schema.json) |

# Asset Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [copyright](#copyright) | `string` | Optional  | No | Asset (this schema) |
| [extensions](#extensions) | complex | Optional  | No | Asset (this schema) |
| [extras](#extras) | complex | Optional  | No | Asset (this schema) |
| [generator](#generator) | `string` | Optional  | No | Asset (this schema) |
| [minVersion](#minversion) | `string` | Optional  | No | Asset (this schema) |
| [version](#version) | `string` | **Required**  | No | Asset (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## copyright

A copyright message suitable for display to credit the content creator.

`copyright`

* is optional
* type: `string`
* defined in this schema

### copyright Type


`string`







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





## generator

Tool that generated this glTF model.  Useful for debugging.

`generator`

* is optional
* type: `string`
* defined in this schema

### generator Type


`string`







## minVersion

The minimum glTF version that this asset targets.

`minVersion`

* is optional
* type: `string`
* defined in this schema

### minVersion Type


`string`



All instances must conform to this regular expression 
(test examples [here](https://regexr.com/?expression=%5E%5B0-9%5D%2B%5C.%5B0-9%5D%2B%24)):
```regex
^[0-9]+\.[0-9]+$
```






## version

The glTF version that this asset targets.

`version`

* is **required**
* type: `string`
* defined in this schema

### version Type


`string`



All instances must conform to this regular expression 
(test examples [here](https://regexr.com/?expression=%5E%5B0-9%5D%2B%5C.%5B0-9%5D%2B%24)):
```regex
^[0-9]+\.[0-9]+$
```







**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFProperty.schema.json`


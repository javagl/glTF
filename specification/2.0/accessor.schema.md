
# Accessor Schema

```
```

A typed view into a bufferView.  A bufferView contains raw binary data.  An accessor provides a typed view into a bufferView or a subset of a bufferView similar to how WebGL's `vertexAttribPointer()` defines an attribute in a buffer.

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted | [accessor.schema.json](accessor.schema.json) |

# Accessor Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [bufferView](#bufferview) | complex | Optional  | No |  | Accessor (this schema) |
| [byteOffset](#byteoffset) | `integer` | Optional  | No | `0` | Accessor (this schema) |
| [componentType](#componenttype) | complex | **Required**  | No |  | Accessor (this schema) |
| [count](#count) | `integer` | **Required**  | No |  | Accessor (this schema) |
| [extensions](#extensions) | complex | Optional  | No |  | Accessor (this schema) |
| [extras](#extras) | complex | Optional  | No |  | Accessor (this schema) |
| [max](#max) | `number[]` | Optional  | No |  | Accessor (this schema) |
| [min](#min) | `number[]` | Optional  | No |  | Accessor (this schema) |
| [name](#name) | complex | Optional  | No |  | Accessor (this schema) |
| [normalized](#normalized) | `boolean` | Optional  | No | `false` | Accessor (this schema) |
| [sparse](#sparse) | complex | Optional  | No |  | Accessor (this schema) |
| [type](#type) | complex | **Required**  | No |  | Accessor (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

## bufferView

The index of the bufferView.

`bufferView`

* is optional
* type: complex
* defined in this schema

### bufferView Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFid.schema.json`






## byteOffset

The offset relative to the start of the bufferView in bytes.

`byteOffset`

* is optional
* type: `integer`
* default: `0`
* defined in this schema

### byteOffset Type


`integer`

* minimum value: `0`






## componentType

The datatype of components in the attribute.

`componentType`

* is **required**
* type: complex
* defined in this schema

### componentType Type


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









## count

The number of attributes referenced by this accessor.

`count`

* is **required**
* type: `integer`
* defined in this schema

### count Type


`integer`

* minimum value: `1`






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





## max

Maximum value of each component in this attribute.

`max`

* is optional
* type: `number[]`
* between `1` and `16` items in the array
* defined in this schema

### max Type


Array type: `number[]`

All items must be of the type:
`number`










## min

Minimum value of each component in this attribute.

`min`

* is optional
* type: `number[]`
* between `1` and `16` items in the array
* defined in this schema

### min Type


Array type: `number[]`

All items must be of the type:
`number`










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





## normalized

Specifies whether integer data values should be normalized.

`normalized`

* is optional
* type: `boolean`
* default: `false`
* defined in this schema

### normalized Type


`boolean`





## sparse

Sparse storage of attributes that deviate from their initialization value.

`sparse`

* is optional
* type: complex
* defined in this schema

### sparse Type


**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `accessor.sparse.schema.json`






## type

Specifies if the attribute is a scalar, vector, or matrix.

`type`

* is **required**
* type: complex
* defined in this schema

### type Type


**Any** following *options* needs to be fulfilled.


#### Option 1



#### Option 2



#### Option 3



#### Option 4



#### Option 5



#### Option 6



#### Option 7



#### Option 8


`string`










**All** of the following *requirements* need to be fulfilled.


#### Requirement 1


* []() – `glTFChildOfRootProperty.schema.json`


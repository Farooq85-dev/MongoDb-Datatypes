# MongoDb-Datatypes

## This repository contains the important data-types in MongoDb.

### `Data Types:-`

#### Follow this link to study more about MongoDb Datay-types.

https://www.mongodb.com/docs/mongodb-shell/reference/data-types/

#### MongoDB stores data using BSON, which supports additional data types that aren't available in JSON.

### 1) `Date`

#### Mongosh provides various methods to return the date, either as a string or as a Date object.

- Date() method which returns the current date as a string.
- new Date() constructor which returns a Date object using the ISODate() wrapper.
- ISODate() constructor which returns a Date object using the ISODate() wrapper.

### 2) `ObjectId`

#### Mongosh provides the ObjectId() wrapper class around the ObjectId data type. To generate a new ObjectId, use the following operation in mongosh.

```
new ObjectId
```

### 3) `Int32`

#### If a number can be converted to a 32-bit integer, mongosh will store it as Int32. 

### 4) `Long`

#### The Long() constructor can be used to explicitly specify a 64-bit integer.

### 5) `Decimal128`

#### Decimal128() values are 128-bit decimal-based floating-point numbers that emulate decimal rounding with exact precision.

### 6) `Timestamp`

#### MongoDB uses a BSON Timestamp internally in the oplog. The Timestamp type works similarly to the Java Timestamp type. Use the Date type for operations involving dates.

### 7) `Integer`
### 8) `Double`
### 9) `String`

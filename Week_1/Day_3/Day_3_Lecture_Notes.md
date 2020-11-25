# Day 3 Lecture #

**Primitive Data Types**
- string
- number
- symbol
- undefined
- null
- Objects & Arrays are NOT primitves (and they are truthy values)

**Objects**

When we want to list independent items we use arrays, when we want to list dependent items (properties), use objects.

#### Methods ###
- Object.keys() => get back an array of all the keys
- Objects.values() => get back an array of all the values

#### This ####
**this** is the reference to where the initializtion happened.

#### Delete ####
Can use delete to completely remove the key: value pair from object. For example:
``` javascript
delete obj.key
``` 
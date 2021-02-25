### Features 0.1v

- Create data with object model.
- Get data object
- Update Data object

### Docs

###### SC.add(table, model);
```js
let userModel = {
  "name": "Steve",
  "fullname": "Jackson",
  "age": 14
}
SC.add("user", userModel)
```
*`Output: You have creating an table user with name, fullname and age models`*

###### SC.get(table);
```js
SC.get("user")
```
*`Output: Here we get the user table`*

###### SC.update(table, key, value);
```js
SC.update("user", "age", "15");
```
*`Output: Here we edit the age of Steve to 15 year old.`*

###### SC.delete(table);
```js
SC.delete("user");
```
*`Output: We delete the table (key & value)`*

###### SC.infos();
```js
SC.infos();
```
*`Output: Give some informations of API and localStorage`*

##### Parameters
|   Name |  Desc  |
| ------------ | ------------ |
| table | *String*  |
| object | *Object*  |
| key | *String*, *Number*, *Boolean*|


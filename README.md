# Documentation

## What JSON means?

- JSON means JavaScript Object Notation
- JSON is a lightweight format for storing and transporting data
- JSON is often used when data is sent from a server to a web page

## Syntax Rules

- Data is in name/value pairs
- Data is separated by commas
- Curly braces hold objects
- Square brackets hold arrays
- File Type is ".json"

## Data Types

- Numbers
- Strings
- Booleans
- Arrays
- Objects
- Null

## JSON Example

```
{
	"name": "David",
	"age": 20,
	"address": {
		"street": "Heroes of Bucharest 5",
		"city": "Bucharest",
		"phone": "0728171997191"
	},
	"friends": ["Alex", "Sino", "Edwan"]
}
```

## Good Advice

Easy to memorize the data types (think about BASONN) Boolean, Array, String, Object, Null, Number

You could verify your JSON code on https://jsonlint.com/

## How could we send data to the server

To send data to server correctly we will have to change the initial JSON text to a string.

To do that, we can use the following function.

```
var person = { name: "John", age: 31, city: "New York" };

person = JSON.stringify(person);
```

Next, if we want to get data from the server we need to transform the string back to JSON text. (JSON.parse Method)

```
person = JSON.parse(person);
```

## Credits

All notes were taken from the Traversy Media's youtube channel. 
https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA

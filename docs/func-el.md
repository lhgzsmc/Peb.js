# Function `el()`
Last Update: *null*
## Usage
```javascript
el(selector, index)
```
## Parameters
### `selector`  
The selector used to find the element, the usage is the same as the selector in css.  
### `index`
*Optional*. When there are multiple results returned by the selector, use index to declare the index of the item you need in the HTMLCollection. The default value is `0`
## Return Value
`Object {...}`
### Object List
`id()`: Get ID of the HTMLElement  
  
`cls()`: Get class of the HTMLElement  
  
`tag()`: Get tag name of the HTMLElement  
  
`attr(attribute, fixTo)`: Get the attribute attribute. Modify if `fixTo` is passed in, otherwise return the read value
  
`dataset(datasetName, fixTo)`: Get `datasetName` dataset. Modify if `fixTo` is passed in, otherwise return the read value
  
`htm(fixTo)`: Get the HTML content of HTMLElement. Modify if `fixTo` is passed in, otherwise return the read value  

`txt()`: Get the text content of HTMLElement. Modify if `fixTo` is passed in, otherwise return the read value

## Video: Types - Intro 
7 Variable Types in JS (SNOB'N'US)
* String
* Number
* Object
* Boolean
* Null
* Undefined
* Symbol


## Video: Types - Strings
* strings hold text
* 3 different ways to create strings:
  * single quotes
    * Ex: `const name = 'wes';`
  * double quotes
    * Ex: `const middle = "topher";`
  * back ticks
    * Ex: `const last = `bos`;`
* you can escape strings using back slash \
  * Ex: `const sentence = 'she\'s so cool';`
  * escaping a string means you tell JS that this is text not JS
* you can use:
  * single quotes in double quotes
  * double quotes in back ticks
* back ticks maintain line breaks
* Ex: 
``` js
const sentence = `This
is
a sentence.`;
```
* concatenation = adding strings together using a plus sign +
* variable interpolation = put a var inside a string using back ticks
  * Ex: 
  ``` js
        const name = "DeVon";
        const message = `hello ${name}`;
  ```


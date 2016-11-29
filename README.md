# JS ES6 code completion live templates for Webstorm

----

## First - A word about contribution & Extending.

- Purpose of this Repo. is to be created as a Webstorm live templates [plugin](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started.html).
- If you add more snippets/better parctice existing snippets, **please** create a pull request for this repo., Thanks for users will be added ofc.
- If you customize this `XML` for your own needs, keep it and have fun =].

_Thanks_

---
## Getting started

- Download the [live templates.xml file](https://github.com/thehulke/webstorm-js-es6-live-templates/blob/master/lg-webstorm-es6-templates.xml).
- Place it in the template folder:
  - [Cross platform guide](https://www.jetbrains.com/help/webstorm/2016.2/project-and-ide-settings.html).
  - OSX: path is `~/Library/Preferences/WebStorm{Version}/templates`.
- Restart Webstorm.

----

## Snippets

### Misc

`t ⇥` this.

```javascript
this.$END$
```

`clog ⇥` colored console log

```javascript
console.log('%c This is ----> $VAR1$','background: $VAR2$', $VAR1$)
```

`log ⇥`  console log

```javascript
console.log('$VAR1$', $VAR2$);
```






### Declarations

`v ⇥` var statement

```javascript
var $VAR1$;
$END$
```

`va ⇥` var assignment

```javascript
var $VAR1$ = $VAR2$;
$END$
```

`l ⇥` let statement

```javascript
let $VAR1$;
$END$
```

`le ⇥` let assignment

```javascript
let $VAR1$ = $VAR2$;
$END$
```

`co ⇥` const assignment

```javascript
const $VAR1$ = $VAR2$;
$END$
```


### Flow Control

`if ⇥` if statement

```javascript
if ($CONDITION$){
    $BODY$
} $END$
```


`el ⇥` else statement

```javascript
else {
    $BODY$
}
$END$
```

`ei ⇥` else if statement

```javascript
else if ($CONDITION$){
    $ACTION$
} $END$
```

`for ⇥` for loop

```javascript
for (let $INDEX$ = 0; $INDEX$ < $VAR1$; $INDEX$++) {
    $BODY$
}
$END$
```

`fi ⇥` for in loop

```javascript
for (let $VAR1$ in $VAR2$) {
    $BODY$
}
$END$
```

### Functions

`fn ⇥` named function

```javascript
function $NAME$ ($ARGUMENTS$) {
    $BODY$
}
$END$
```

`afn ⇥` anonymous function

```javascript
function ($ARGUMENTS$) {
    $BODY$
}
$END$
```

`iife ⇥` immediately-invoked function expression (IIFE)

```javascript
(($ARGUMENTS$) => {
    $BODY$
})($ARGUMENT2$);
$END$
```

`af ⇥` arrow function

```javascript
($ARGS$) => $RETURNS$
```

`afb ⇥` arrow function with body

```javascript
($ARGS$) => {
    $BODY$
}
$END$
```

### Return values

`r ⇥` return

```javascript
return $PROPERTY$;
```

`rf ⇥` return false

```javascript
return false;
```

`rt ⇥` return true

```javascript
return true;
```

`rn ⇥` return null

```javascript
return null;
```



### Iterables

`map ⇥` map function (chainable)

```javascript
.map(($ITEM$, $INDEX$)=>{
    $BODY$
})$END$
```

`filter ⇥` filter function (chainable)

```javascript
.filter(($ITEM$)=>{
    $BODY$
})$END$
```

### Classes & Objects

`cx ⇥` export class

```javascript
export class $NAME$ {
    $BODY$
}
```

`cf ⇥` class function

```javascript
$NAME$() {
    $BODY$
}
```

`get ⇥` getter

```javascript
get $NAME$() {
    $BODY$
}
```

`set ⇥` setter

```javascript
set $PROPERTY$($VALUE$) {
    $BODY$
}
```

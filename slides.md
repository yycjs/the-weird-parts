# JavaScript - The weird parts

---

## Our Presenters

## David Luecke

* GitHub: [daffl.github.com](http://daffl.github.com), Twitter: [@daffl](http://twitter.com/daffl)

## Eric Kryski

* GitHub: [ekryski.github.com](http://ekryski.github.com), Twitter: [@ekryski](http://twitter.com/ekryski)

---

## Our Sponsors

## Assembly Co-working Space

![Assembly](images/sponsors/assembly_logo.png)

## PetroFeed

![PetroFeed](images/sponsors/pf-logo.png)

---

## Our Sponsors

## Village Brewery

![Village Brewery](images/sponsors/village_brewery_logo_inverted.png)

---

## Last Year

* [Becoming an Open Source, JavaScript, Hipster 101](https://github.com/yycjs/open-source-intro)
* [jQuery, Templating, and Build Tools. Oh My!](https://github.com/yycjs/jquery-templates-builds)
* [Node Up! Server side JavaScript FTW!](https://github.com/yycjs/node-up)
* [NodeJS Auth & Structure](https://github.com/yycjs/node-auth-structure)
* [Client Side MVWTF](https://github.com/yycjs/mvwtf)
* [It's all about the tests, Yo!](https://github.com/yycjs/javascript-testing)
* [Module Loading & Generators](https://github.com/yycjs/module-loading-generators)
* [SEO & i18n](https://github.com/yycjs/seo-i18n)
* [Mobile madness](https://github.com/yycjs/mobile-madness)
* [YYCJSCamp](https://github.com/yycjs/YYCJSCamp-2013)

---

## You know?

- [__O__bject __O__riented __P__rogramming](http://en.wikipedia.org/wiki/Object-oriented_programming) basics (classes, objects, inheritance)
- JavaScript language basics
    - __Operators__ `[]`, `&&`, `==`, `||` 
    - __Arrays__ and __Objects__ `[].push`, `{}`
    - __Functions__ `var fn = function(param1, param2) {}` 
- Some jQuery
    - __Selectors__ `tagname`, `#myId`, `.class`
    - __Event handlers__ `$('selector').click(function() { alert('clicked'); })`

---

## Welcome to the weird side

- truthy and falsyness
- Equality
- Prototypes
- Scope
- `this`
- Asynchronous programming
- EcmaScript 5 and 6

---

## Is there more than one way to...

__Accessing object properties__

    !javascript
    var person = {
      name: 'david',
      '&weird property': 'YYCJS'
    }

    person.name // -> David
    person['name'] // -> David
    person["name"] // -> David
    person['&weird property'] // -> YYCJS

    // ERROR
    persone.&weird property

__Declaring functions__

    !javascript
    var myFunction = function(arg) {

    }
    // (usually) the same as
    function myFunction(arg) {

    }

---

## Truthy- and falsyness

__Truthyness__

    !javascript
    var person = { name: 'David' }
    
    if(person.name) {
      // Do stuff if property exists
    }

    if(1 == 1) {

    }

__Falsy values__

    !javascript
    false
    null
    undefined
    0
    ''
    []
    person.undefinedProperty

---

## Equality or `==` vs `===`

`==` compares value & truthy- falsyness

    !javascript
    1 == 1 // -> true
    1 == '1' // -> true
    1 == 2 // -> true
    '' == false // -> true
    [] == '' // -> true
    null == undefined // -> true

`===` compares value __and__ type

    !javascript
    1 === 1 // -> true
    1 === '1' // -> false
    [] === '' // -> false

### ALWAYS USE ===

---

# Prototypal inheritance

---

## Class based inheritance

---

## JavaScript only knows objects and 

---

## Scope

---

## What is `this`?

---

## Asynchronous programming

---

## Next Month

* Something awesome
* More awesomeness

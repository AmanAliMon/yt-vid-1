# TypeScript For JS Peoples
### (Speed Run)

## Resources
- Github https://github.com/panaverse/learn-typescript
- Node https://nodejs.org/en
- Bun bun.sh/
- Alias vs interface https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#interfaces

##  JSON
### JSON vs JS objects
_JSON_
```js
const detail = { "name": "Vipin", "age": 21 }
```
_JS_
```js
const detail = { name: "Vipin", age: 21 }
```

### How to parse Json

use `JSON.parse(<json data>)`

 
### Modules

*Main Page*
```js
import video as film from './video'
import * from './parts'

```
* : All
*parts*
```js
export let header = 'header'
let footer = console.log
export footer
```
*video*
```js
let video = 'video'
export default video
```

*Main Page*
```js
import rollNO from './ID Card'
import {Name,age,gender} from './NIC'
console.log(`${Name} is of ${age} and is a ${gender}`)
```
> Aman is of 17 and is a male

*NIC*
```js
export let age= 17
export let Name = 'Aman Ali'
export let gender = 'male'
```
*ID Card*
```js
let rollNo= 12345
export default rollNo
```

## Union Literals

is a reference thats allows us to store multiple types of data that are allowed

81821821
03282240997

give me your persona

*example*
```ts
let persona : NIC | Passport | B_form = 1234674
```

## Object Aliased

type Bio = {
male: boolean,
age:number,
phone: number | string
}

let aman : Bio = {
true,
17,
789232
}

let Eman : Bio {
false,
100,
23433
}





## Structural typing object literals

interface Human = {
name:string,
age:number,
nic: number
}

interface Animal = {
name:string,
age:number,
}


let Aman : Human = {'Aman',17,2345677}
let Dog : Animal = {'Pluto',9}

Aman = Dog // Error bhai NIC number toh do
Dog = Aman // name, age















## Arrays
are set of data with defined datatype
{'':''}
[,,,,,,,,,]



Reject Resolve




Eat / Call
sleep
Code


## Callback
patameters that are functions instead of variables


## Tuple
type  person = [string,number,boolean] // Name,age,male

let aman : person = ['Aman',17,true]

let persons : person[] = [
    aman,
    ['Eman',100,false],
    ['Jeff',18,true]
]
console.log(persons)

# Quarter Ends


Js Chocolate Coin
Ts Gold Coin

- Hard to digest
- Useless in case of hunger
- Its nothing except being shiny

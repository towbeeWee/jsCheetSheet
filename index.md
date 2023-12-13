# JS Cheet Sheet
## Ausgabe in der Konsole
Eine Ausgabe in der Konsole ist nur für Entwickler beim testen des Codes wichtig. In richtigen Anwendungen findet es keine Anwendung.
```js
console.log('Hello world!');
// => Hello world!
```

## Kommentare

```JS
// Einzeilliger Kommentar

/*  
Mehrzeilliger Kommentar 
Mehrzeilliger Kommentar 
*/
```

## Arithmetische Operatoren
```JS
5 + 5               // Addition
10 - 5              // Subtraktion
5 * 10              // Multiplikation
10 / 5              // Division
10 % 5              // Modulo (Rest einer Division)
a = b + c - d;      // Addition, Substraktion
a = b * (c / d);    // Multiplikation, Division
x = 100 % 48;       // Modulo. 100 / 48 Rest = 4
3**2                // Potenz = 9
a++; b--;           // erhöht oder vermindert den Wert um 1

let number = 100;
// Beide Befehle addieren 10
number = number + 10;
number += 10;

console.log(number); 
// => 120
```

## Variablen
```JS
let x = null;
let name = "Tammy";
const found = false;

console.log(name, found, x);
// => Tammy, false, null

var d = 1 + 2 + "3";
console.log(d);
// => "33"

var a;
console.log(a); 
// => undefined
```

## Strings
```JS
let single = 'Wheres my bandit hat?';
let double = "Wheres my bandit hat?";

// => 21
console.log(single.length);
```

## Strings verbinden

```JS
let age = 7;

console.log('Tommy is ' + age + ' years old.');
// => Tommy is 7 Years old

console.log(`Tommy is ${age} years old.`);
// => Tommy is 7 Years old
```

## Nummern
```JS
let amount = 6;
let price = 4.99;
```

## Verschiedene Methoden
```JS
console.log(Math.random());
// => 0 - 0.9999999999999999

console.log(Math.floor(5.95)); 
// => 5

console.log(Math.ceil(5.95)); 
// => 6

console.log("hallo".toUpperCase())); 
// => HALLO

console.log("HaLLo".toLowerCase())); 
// => hallo

console.log("HaLLo".startsWith("H"))); 
// => true

let message = 'good nite';
console.log(message.length);
// => 9
```

## if Statement
```JS
const isMailSent = true;

if (isMailSent) {
    console.log('Mail wurde versendet');
} else {
    console.log('Mail wurde NICHT versendet');
}
// => Mail wurde versendet

var x = 1;
result = (x == 1) ? true : false;
// => true
```

## Operatoren
```JS
true || false;       // true
10 > 5 || 10 > 20;   // true
false || false;      // false
10 > 100 || 10 > 20; // false

true && true;        // true
1 > 2 && 2 > 1;      // false
true && false;       // false
4 === 4 && 3 > 1;    // true

1 > 3                // false
3 > 1                // true
250 >= 250           // true
1 === 1              // true
1 === 2              // false
1 === '1'            // false
```
# WIEDERHOLUNG JAVA SCRIPT
---

## Kommentar
Kommentare stehen im Source Code um Anmerkungen jeglicher Art hinzuzufügen.

---

## Primitive Datentypen
Primitive Datentypen stellen nur einen Wert dar.
+ Boolean
+ Null
+ Undefined
+ Number
+ String
+ Symbol 

---

## Variablen
Eine Variable speichert einen genauen Wert und weißt diesen Wert einem Namen zu.
``` js
var geld = 53000;
```

---

## Logische Operatoren
Mit einem Logischen Operator verbindet zwei Bedingungen mit UND (&&) oder ODER (||).
``` js
var a = 3;
var b = -2;

console.log(a > 0 && b > 0);

console.log(a > 0 || b > 0);

console.log(!(a > 0 || b > 0));
```

---

## Arithmetische Operatoren
Arithmetische Operatoren verwenden Zahlenwerte oder Variablen und geben Zahlenwerte aus. Die arithmetischen Standardoperatoren sind _Addition (+)_, _Subtraktion (-)_, _Multiplikation (*)_ und _Division (/)_.
``` js
var a = 2;

console.log(a + 3 - 1);

console.log(4 * 3 / 2);

Vergleichsoperatoren
Vergleichsoperatoren vergleichen 2 Werte mit entweder dem $trikten Vergleich (===) oder dem abstrakten Vergleich (==).
console.log(1 == 1);
// expected output: true

console.log("1" == 1);
// expected output: true

console.log(1 === 1);
// expected output: true

console.log("1" === 1);
// expected output: false
```

---

## Schleifen
Schleifen führen einzelne Schritte wiederholt aus.


(c) Kevin Bulay 2018
Типи даних у JavaScript:

1.
String
Використовується для зберігання текстових значень.
let name = "Alice";  
let greeting = "Hello!";

2.Number 
Зберігає числові значення (цілі або з плаваючою крапкою).
let age = 25;  
let price = 19.99;

3.Boolean 
Зберігає логічні значення: true або false.
let isOnline = true;  
let hasAccess = false;

4.Null 
Вказує на відсутність значення.

5.Undefined 
Значення не визначене (змінна оголошена, але без значення).

let user;  

6.Symbol 
Використовується для унікальних ідентифікаторів.
let id = Symbol("uniqueId");  

7.BigInt
Дозволяє працювати з великими цілими числами.
let bigNumber = 123456789012345678901234567890n;  

8.Object

Зберігає складні структури даних у вигляді ключ-значення.

let person = { name: "Alice", age: 25 };  
let car = { brand: "Toyota", year: 2020 };

/////////
Як працює typeof
Оператор typeof повертає рядок, що вказує тип переданого значення.

typeof "Hello"; // "string"  
typeof 42;      // "number"  
typeof null;    // "object" (особливість реалізації)  
typeof undefined; // "undefined"  

Використовується для перевірки типу змінної.

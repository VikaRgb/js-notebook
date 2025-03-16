Що таке callback-функція?

Callback-функція - це функція, яка передається як аргумент іншій функції.

Навіщо потрібні callback-функції?

Асинхронність: JavaScript є однопотоковою мовою, тобто він виконує код рядок за рядком. Callback-функції дозволяють виконувати асинхронні операції, такі як запити до сервера або таймери, не блокуючи виконання іншого коду.
Обробка подій: Callback-функції використовуються для обробки подій, таких як кліки миші або натискання клавіш.
Розділення логіки: Callback-функції дозволяють розділити логіку програми на окремі частини, що робить код більш читабельним і підтримуваним.

ОСНОВНА ЗАДАЧА callback-функції ЦЕ РОЗШИРИТИ ФУНКЦІОНАЛ СВОЄЇ БАТЬКІВСЬКОЇ ФІНКЦІЇ  

Простий  Приклад
Це й код без  callback-функції
// function makeCulc(a,b,operation) {
// 	if (operation === "/") {
// 	return	a / b
// 	}
// 	else if (operation === "+") {
// 	return	a + b;
// 	}
// 	else if (operation === "*") {
// 	return	a * b
// 	}
// 	else if (operation === "-") {
// 	return	a-b
// 	} 
// 	else {
// 		return "Invalid operation";
// 	}
// }

Цей код з callback-функцією
function makeCulc(a, b,callback) {
	return callback(a,b)
}

function add(x, y) {
	return x+y
}

function subtract(x, y) {
  return x - y;
}

function multiply(x, y) {
	return x*y
}

function divide(x, y) {
	return x/y
}

console.log(makeCulc(1, 2, add))
console.log(makeCulc(11, 2, subtract));
console.log(makeCulc(12, 2, divide));
console.log(makeCulc(22, 2, multiply));




Що таке DOM?
DOM (Document Object Model) — це інтерфейс, який дозволяє JavaScript взаємодіяти з HTML-структурою сторінки.
Він представляє HTML-документ у вигляді дерева об'єктів.

Основні методи вибору елементів

document.getElementById("id") 	Отримує елемент за id
document.querySelector("selector")	 Повертає перший елемент за CSS-селектором
document.querySelectorAll("selector")	 Повертає NodeList (масивоподібний список) елементів
document.getElementsByClassName("class")	 Повертає HTMLCollection за класом


Маніпуляція контентом

Властивість / Метод	                       Опис
element.textContent	                      Змінює або отримує текстовий вміст
element.innerHTML                       	Змінює або отримує HTML-вміст
element.setAttribute("attr", "value")	      Додає або змінює атрибут
element.getAttribute("attr")	             Отримує значення атрибута


Робота з класами
Метод	                                Опис
element.classList.add("class")	     Додає клас
element.classList.remove("class")	   Видаляє клас
element.classList.toggle("class")	   Перемикає клас (додає, якщо немає, і видаляє, якщо є)
element.classList.contains("class")	  Перевіряє, чи є клас


Додавання та видалення елементів
Метод	                                                 Опис
document.createElement("tag")	                        Створює новий елемент
parent.appendChild(child)                            	Додає елемент в кінець батьківського
parent.insertBefore(newElement, existingElement)	    Додає перед певним елементом
element.remove()	                                    Видаляє елемент
element.replaceWith(newElement)	                      Замінює елемент

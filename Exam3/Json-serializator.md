### Json serializator

Създайте абстрактен клас Serializable който има метод  string serialize(). 

Създайте абстрактен клас Json, който държи string data и наследява Serializable.

Създайте клас JsonString, който има конструктор с параметри, наследява Json и имплементира serialize() по следния начин:

Ако в data държим 

dog

serialize() ще върне "dog".



Ако в data държим 

That's "fabulous", bro

 serialize() ще върне "That's "fabulous", bro"





Създайте клас JsonNumber, който има конструктор с параметри, наследява Json и имплементира serialize() по следния начин:

Ако в data държим 

150

 serialize() ще върне 150



Ако в data държим 

43243444321

serialize() ще върне 43243444321





Създайте клас JsonBool, който има конструктор с параметри, наследява Json и имплементира serialize() по следния начин:

Ако в data държим 

true

serialize() ще върне true



Ако в data държим

 false

serialize() ще върне false



Създайте клас JsonObject, който има в себе си JsonString ключ и Json стойност. Класът да наследява Json, и да има конструктор с параметри. Освен това да имплементира serialize() по следния начин:

Ако имаме

 key OOP  и value JsonObject, който има

​						 key CS и value JsonObject, 

​									който има key FMI и  value JsonString "no"

serialize() ще върне 

{"OOP": 

​			{"CS": 

​						{"FMI": :no}}}


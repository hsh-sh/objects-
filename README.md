# 🧱 Objects в JavaScript — Полное руководство 💡

> 🔥 Объекты — это сердце JavaScript.  
> Почти всё в JS основано на объектах: от простых данных до функций и классов.  
> В этом руководстве ты узнаешь, как создавать, изменять и использовать объекты как профи! 🚀

---

## 🧩 Что такое объект?

*Объект (Object)* — это *набор свойств, где каждое свойство состоит из **ключа (name)* и *значения (value)*.

```js
const user = {
  name: "Someone",
  age: 19,
  country: "Tajikistan",
};

console.log(user.name); // ""
console.log(user["age"]); // 19

const car = {
  brand: "Toyota",
  model: "Camry",
  year: 2020,
};

function Person(name, age) {
  this.name = name;
  this.age = age;
}

Синтаксис,Пример,Описание
obj.key,user.name,через точку
obj["key"],user["age"],через строку
obj[variable],user[prop],динамическое имя свойства
const person1 = new Person("John", 30);

Object.keys(user);   // ["name", "age", "country"]
Object.values(user); // ["Shukrona", 19, "Tajikistan"]
Object.entries(user); // [["name","Shukrona"],["age",16],["country","Tajikistan"]]

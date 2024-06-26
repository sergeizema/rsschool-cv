# Sergei Zemnitsky
***
![Изображение](https://pro-rage.ru/data/avatars/h/8/8873.jpg?1700701755 "Ava")

## Contact information:
### [@Telegram](https://t.me/zemnitsky)
### [@Instagram](https://www.instagram.com/mr.chernov17/)
### [@GIT](https://github.com/sergeizema)

## About me:
    I study at Kuleshov University in Mogilev at the Faculty of Mathematics and Natural Sciences. I want to become a web-developer in the future. 
    I am fond of sports. My favorite games are football and volleyball. I like to write programs :)

## My Skills: 
    Programming languages: JavaScript, C#, C++
    DataBase: PostgreSQL, SQLServer, MySQL, PHPMyAdmin
    Control systems: GIT

## Example of completed tasks: 
We count the total amount of goods in the local storage:
```javascript
const LS = localStorage;
let dataLocal = JSON.parse(LS.getItem("basket"));

let generatingTheTotalAmount = () => {
    let array = dataLocal;
    let result = 0;
    for (let key in array) {
        result += dataLocal[key].getPrice * dataLocal[key].getQuantity
    }
    document.getElementById("outResult").innerHTML = '<input name="price" class="smart-basket__total-cost" type="text" value="' + result + ' BYN">';
};
```

## Work experience:
- Website development:
  - https://www.klimat-orsha.by/
  - https://orsha-cheese.by/ (Service/Support)
- Working as a software engineer in Orsha Сheese Factory. https://orsha-cheese.by/

## Education:
    2020 Vitebsk State Polytechnic College / Information Technology Software
    2026 Mogilev State University named after A. A. Kuleshov / Information Technology Software

## My languages: English (A1)
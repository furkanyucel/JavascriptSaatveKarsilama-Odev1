# Patika - Javascript Saat ve Karşılama - Ödev 1
Bu repo [Patika](http://www.patika.dev) sitesi javascript eğitimi Javascript Saat ve Karşılama - Ödev 1 projesi için oluşturulmuştur.


```javascript
let user = prompt("Adınız nedir?");
let myName = document.querySelector('#myName');
myName.innerHTML = ` ${user} `;

function showTime() {
let d = new Date();
let daysOfWeek = ["Pazar","Pazartesi","Salı","Çarşamba","Perşembe","Cuma","Cumartesi"];
let time = document.querySelector('#myClock')

time.innerHTML = `${d.getHours()}:${d.getMinutes()}:${d.getSeconds()} ${daysOfWeek[d.getUTCDay()]}` 
setTimeout(showTime, 1000); }

showTime();

```

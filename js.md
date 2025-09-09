# JavaScript Temelleri – Notlarım

## 1. JavaScript Nedir?
JavaScript, web sayfalarına **dinamizm ve etkileşim** kazandıran programlama dilidir.  
HTML ve CSS ile birlikte web’in temel üçlüsünü oluşturur.

---

## 2. Değişkenler
```javascript
let isim = "Enes";   // Değiştirilebilir
const yas = 27;      // Sabit
var sehir = "Kocaeli"; // Eskiden kullanılırdı
```

---

## 3. Veri Tipleri
- String → `"Merhaba"`
- Number → `10`, `3.14`
- Boolean → `true`, `false`
- Array → `[1, 2, 3]`
- Object → `{ ad: "Enes", yas: 27 }`

---

## 4. Fonksiyonlar
```javascript
function selamla(isim) {
  console.log("Merhaba " + isim);
}
selamla("Enes"); // Merhaba Enes
```

---

## 5. Koşullar ve Döngüler

**Koşul:**
```javascript
let yas = 27;
if(yas >= 18){
  console.log("Reşitsiniz");
} else {
  console.log("Reşit değilsiniz");
}
```

**Döngü:**
```javascript
for(let i = 0; i < 5; i++){
  console.log(i);
}
```

---

## 6. DOM Manipülasyonu (Temel)
```javascript
const baslik = document.getElementById("baslik");
baslik.textContent = "Merhaba Dünya!";
```

---

## 7. Öğrenilecekler
- Event Listener (`click`, `submit`)  
- Array & Object metodları (`map`, `filter`, `reduce`)  
- ES6 özellikleri (`arrow function`, `template literals`)  
- Fetch API ile veri çekme

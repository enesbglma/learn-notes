# CSS Temelleri – Notlarım

## 1. CSS Nedir?
CSS (Cascading Style Sheets), HTML ile oluşturduğumuz sayfaların **tasarımını ve görünümünü** kontrol etmemizi sağlar.

## 2. Temel Kullanım
HTML içine ekleme yolları:

1. Inline CSS:
```html
<p style="color: red;">Merhaba Dünya</p>
```

2. Internal CSS:
```html
<head>
  <style>
    p { color: blue; }
  </style>
</head>
```

3. External CSS:
```html
<link rel="stylesheet" href="styles.css">
```

---

## 3. Temel Seçiciler
- `element` : HTML etiketi seçer  
  ```css
  p { color: green; }
  ```
- `.class` : Sınıf seçici  
  ```css
  .kirmizi { color: red; }
  ```
- `#id` : ID seçici  
  ```css
  #baslik { font-size: 24px; }
  ```

---

## 4. Box Model (Kutu Modeli)
Her HTML elemanı bir kutudur:
- **Content** → İçerik
- **Padding** → İçerik ile kenarlık arası boşluk
- **Border** → Çerçeve
- **Margin** → Kutular arası boşluk

---

## 5. Öğrenilecekler
- Flexbox ve Grid  
- Positioning (`static`, `relative`, `absolute`, `fixed`)  
- Renkler ve Background  
- Transition & Animation

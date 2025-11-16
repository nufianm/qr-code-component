# QR Code Component

Sebuah komponen QR code yang responsive dibuat dengan HTML dan SASS sesuai dengan design dari Frontend Mentor.

## Fitur

- ✅ Design yang responsive untuk mobile (375px) dan desktop (1440px)
- ✅ Menggunakan font Outfit dari Google Fonts
- ✅ Mengikuti color scheme yang telah ditentukan dalam style guide
- ✅ Semantic HTML structure
- ✅ SASS untuk styling yang lebih terorganisir
- ✅ Box shadow dan border radius sesuai design
- ✅ Hover effects pada link

## Teknologi yang Digunakan

- HTML5
- SASS/SCSS
- CSS3
- Google Fonts (Outfit)

## Struktur File

```
qr-code-component/
├── index.html                    # File HTML utama
├── scss/
│   ├── abstracts/
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   ├── base/
│   │   └── _base.scss
│   ├── components/
│   │   └── _card.scss
│   ├── layout/
│   │   ├── _attribution.scss
│   │   └── _responsive.scss
│   └── main.scss                 # File SASS source
├── style.css                     # File CSS yang di-compile dari SASS
├── images/
│   ├── favicon-32x32.png
│   └── image-qr-code.png
├── design/
│   ├── desktop-design.jpg
│   └── mobile-design.jpg
├── style-guide.md                # Panduan styling
├── preview.jpg                   # Preview hasil akhir
└── README.md                     # Dokumentasi project
```

## Cara Menjalankan

1. Clone atau download repository ini
2. Buka file `index.html` di browser
3. Atau gunakan live server untuk development

## Development dengan SASS

Untuk development dengan SASS:

1. Install SASS globally:
   ```bash
   npm install -g sass
   ```

2. Watch SASS file untuk auto-compile:
   ```bash
   sass --watch scss/main.scss style.css
   ```

## Design Specifications

### Colors
- White: `hsl(0, 0%, 100%)`
- Slate 300: `hsl(212, 45%, 89%)` (background)
- Slate 500: `hsl(216, 15%, 48%)` (description text)
- Slate 900: `hsl(218, 44%, 22%)` (title text)

### Typography
- Font Family: Outfit
- Font Weights: 400 (normal), 700 (bold)
- Font Size: 15px (paragraph)

### Layout
- Mobile: 375px
- Desktop: 1440px
- Card max-width: 320px
- Border radius: 20px (card), 10px (image)

## Responsive Behavior

- **Mobile (≤375px)**: Full width dengan padding yang disesuaikan
- **Desktop (≥1440px)**: Centered card dengan ukuran tetap
- **Between**: Fluid responsive behavior

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- Challenge by [Frontend Mentor](https://www.frontendmentor.io)
- Coded by [Mochammad Nufianto]

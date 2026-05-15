# rzezbiarka.pl

**Strona portfolio polskiej rzeźbiarki Doroty Dziekiewicz-Pilich — realizacje pomnikowe, statuetki, medale i rzeźby w małej formie.**

![Angular](https://img.shields.io/badge/Angular-18-dd0031?logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.4-3178c6?logo=typescript&logoColor=white)
![Angular Material](https://img.shields.io/badge/Angular%20Material-18-757575?logo=angular&logoColor=white)

**Strona na żywo:** [rzezbiarka.pl](https://rzezbiarka.pl)

[🇬🇧 English](README.md) | 🇵🇱 Polski

> Kod źródłowy jest prywatny. To repozytorium służy jako dokumentacja projektu.

---

## Czym jest ten projekt

Produkcyjna strona portfolio **Doroty Dziekiewicz-Pilich**, zawodowej rzeźbiarki z ponad 25-letnim dorobkiem obejmującym pomniki publiczne, statuetki z brązu, medale i rzeźby w małej formie. Strona prezentuje pełny katalog prac w układzie kategoriowym, zorientowanym na obraz, z przeglądarką lightbox zawierającą metadane każdej pracy — tytuł, materiały, wymiary i datę.

---

## Zrzuty ekranu

### Strona główna — slider i wyróżnione prace

![Strona główna](images/home.png)

### Kategorie portfolio

![Portfolio](images/portfolio.png)

### Przeglądarka lightbox

![Lightbox](images/lightbox.png.png)

---

## Podstrony

| Ścieżka | Strona |
|---|---|
| `/` | Strona główna — slider, galeria, biografia, karuzela |
| `/portfolio` | Portfolio — 4 foldery kategorii |
| `/portfolio/:category` | Galeria kategorii z przeglądarką lightbox |

**Kategorie portfolio:** Realizacje pomnikowe · Statuetki i medale · Projekty · Mała forma

---

## Funkcjonalności

- **Slider główny** — automatycznie obracająca się karuzela z 7 wyróżnionymi pracami
- **Galeria wyróżnionych prac** — siatka rzeźb z modałem lightbox
- **Karuzela roulette** — animowana próbka portfolio, zatrzymuje się po najechaniu kursorem
- **Sekcja biografii** — nota artystyczna i oś czasu najważniejszych realizacji (1998–2024)
- **Katalog portfolio** — 4 kategorie, 33+ foldery, setki prac z pełnymi metadanymi (tytuł, materiały, wymiary, data)
- **Przeglądarka lightbox** — pełnoekranowy modał z tytułem, opisem i szczegółami dzieła
- **Nawigacja klawiaturą** — Escape / Backspace zamykają modał lub cofają do poprzedniego widoku
- **Responsywne obrazy** — WebP z fallbackiem JPG, pięć punktów przełamania (480 · 768 · 1024 · 1366 · 1920px)
- **Responsywny układ** — hamburger menu na urządzeniach mobilnych, płynne siatki na wszystkich ekranach
- **Kontaktowe chipy w stopce** — przeciągane chipy z linkami do Instagrama, telefonu i e-maila
- **Płynne przewijanie** — własna animacja easeInOutQuad dla nawigacji po fragmentach strony

---

## Stack technologiczny

| Warstwa | Technologia |
|---|---|
| Framework | Angular 18 (lazy-loaded feature modules) |
| Język | TypeScript 5.4 (tryb strict) |
| Komponenty UI | Angular Material (motyw Indigo-Pink) |
| Stylowanie | SCSS + Normalize.css |
| Warstwa reaktywna | RxJS 7 |
| Formaty obrazów | WebP + JPG (responsywny srcset) |
| Build | Angular CLI / esbuild |
| Hosting | Hosting statyczny (bez backendu) |

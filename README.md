# PCForge UZ

Конфигуратор ПК для рынка Узбекистана: подбор компонентов, проверка совместимости, цена в UZS/USD и оценка FPS.

A PC builder for Uzbekistan with compatibility checks, UZS/USD totals and estimated gaming performance.

![Screenshot placeholder](https://placehold.co/1200x675/11141d/4c8dff?text=PCForge+UZ+Screenshot)

## Возможности
- 8 категорий, 15–20+ реальных позиций в каждой; расширенная линейка Intel Core и AMD Ryzen
- Проверка сокета, RAM, БП, корпуса и кулера
- LocalStorage, ссылка на сборку, экспорт PNG
- Оценка офисных задач и FPS в 8 играх для 1080p / 1440p / 4K
- Mobile-first интерфейс, тёмная и светлая темы

## Технологии
HTML5, CSS3, Vanilla JavaScript, html2canvas. Без сборщика и фреймворков.

## Локальный запуск
```bash
python -m http.server 8000
```
Откройте `http://localhost:8000`.

## GitHub Pages
Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save.

Live site: `https://karimov0913.github.io/pcforge-uz/`

## Данные
Цены и FPS ориентировочные. Курс меняется в `js/data.js`. Изображения CPU загружаются с Wikimedia Commons; при недоступности показывается локальная иконка.

## Тесты
```bash
node tests/compatibility.test.js
```

**Автор: Javlonbek Karimov**
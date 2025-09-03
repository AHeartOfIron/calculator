# Cost Calculators / Калькулятори вартості послуг

Professional tools for calculating the cost of demining, survey work, and route planning.

## Features / Функції

- **Multi-language support** (Ukrainian, English, French) / **Підтримка мов** (українська, англійська, французька)
- **Demining Calculator** - Territory demining cost calculation / **Калькулятор розмінування** - розрахунок вартості розмінування території
- **NTS Calculator** - Non-technical survey cost calculation / **NTS Калькулятор** - розрахунок вартості нетехнічного обстеження
- **EORE Calculator** - Explosive Ordnance Risk Education cost calculation / **EORE Калькулятор** - розрахунок вартості навчання з безпеки
- **Route Calculator** - Optimal route planning with multiple waypoints / **Калькулятор маршрутів** - планування оптимального маршруту
- **PDF Export** - Generate professional proposals / **Експорт PDF** - створення професійних пропозицій
- **Coefficient Settings** - Customizable calculation parameters / **Налаштування коефіцієнтів** - настроювані параметри розрахунку

## Technologies / Технології

- HTML5, CSS3, JavaScript
- Bootstrap 5
- Leaflet.js (interactive maps)
- Font Awesome (icons)
- jsPDF (PDF generation)
- OSRM API (route calculation)

## Usage / Використання

1. Open `index.html` in your browser / Відкрийте `index.html` у браузері
2. Select the desired calculator / Оберіть потрібний калькулятор
3. Fill in the parameters / Заповніть параметри
4. Click "Calculate" / Натисніть "Розрахувати"
5. Export results to PDF if needed / Експортуйте результати в PDF за потреби

## File Structure / Структура файлів

```
├── index.html              # Main page / Головна сторінка
├── calc_demining.html      # Demining calculator / Калькулятор розмінування
├── calc_nts.html          # NTS calculator / NTS калькулятор
├── calc_eore.html         # EORE calculator / EORE калькулятор
├── route_calculator.html   # Route calculator / Калькулятор маршрутів
├── route_calculator_mini.html # Mini route calculator / Міні калькулятор маршрутів
├── styles.css             # Main styles / Основні стилі
├── license.html           # License information / Інформація про ліцензію
└── README.md              # This file / Цей файл
```

## Features Details / Деталі функцій

### Demining Calculator / Калькулятор розмінування
- Area calculation (hectares) / Розрахунок площі (гектари)
- Territory complexity factors / Коефіцієнти складності території
- Slope angle considerations / Врахування кута нахилу
- Depth calculations / Розрахунки глибини
- Urgency surcharge / Доплата за терміновість
- Transport costs / Транспортні витрати

### NTS Calculator / NTS Калькулятор
- Survey area calculation / Розрахунок площі обстеження
- Distance to object / Відстань до об'єкта
- Complexity coefficients / Коефіцієнти складності
- Fuel consumption / Розхід палива
- Urgency options / Опції терміновості

### EORE Calculator / EORE Калькулятор
- Base training cost / Базова вартість навчання
- Distance calculations / Розрахунки відстані
- Trip multipliers / Множники поїздок
- Urgency factors / Фактори терміновості

### Route Calculator / Калькулятор маршрутів
- Multiple waypoints support / Підтримка множинних точок
- Real-time route calculation via OSRM API / Розрахунок маршруту в реальному часі через OSRM API
- Interactive map with Leaflet.js / Інтерактивна карта з Leaflet.js
- Route alternatives / Альтернативні маршрути
- Distance optimization / Оптимізація відстані

## Customization / Налаштування

All calculators support coefficient customization through the "Coefficients" button. Settings are saved in browser localStorage.

Всі калькулятори підтримують налаштування коефіцієнтів через кнопку "Коефіцієнти". Налаштування зберігаються в localStorage браузера.

## Browser Support / Підтримка браузерів

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License / Ліцензія

This project is open source. See `license.html` for details.

Цей проект має відкритий код. Дивіться `license.html` для деталей.

## Contributing / Внесок

Contributions are welcome! Please feel free to submit pull requests.

Внески вітаються! Будь ласка, надсилайте pull requests.
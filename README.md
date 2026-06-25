sistechnologies/
├── index.html                 # Главная страница
├── services.html              # Страница услуг
├── process.html               # Этапы работы
├── clients.html               # Клиенты
├── contacts.html              # Контакты
├── 404.html                   # Страница ошибки
├── README.md                  # Этот файл
│
├── services/                  # Страницы услуг (подробно)
│   ├── video-surveillance.html
│   ├── fire-safety.html
│   ├── access-control.html
│   ├── smart-home.html
│   └── water-supply.html
│
└── images/                    # Изображения
    ├── logo.webp              # Логотип компании
    ├── 404-error.webp         # Картинка для 404
    └── solutions/             # Изображения для услуг
        ├── access-cards.webp
        ├── biometric.webp
        ├── intercom.webp
        ├── turnstile.webp
        ├── cctv-integration.webp
        └── time-tracking.webp

        
# ⚙️ Настройка форм обратной связи

Формы на сайте используют **Formspree** (бесплатно до 50 заявок в месяц).

### Как настроить:

1. **Зарегистрируйтесь на Formspree:**
   - Перейдите на https://formspree.io
   - Нажмите "Get Started" → "Free"
   - Введите email, куда будут приходить заявки
   - Подтвердите email

2. **Создайте форму:**
   - В личном кабинете нажмите "New Form"
   - Введите название (например, "Системные Технологии")
   - Скопируйте URL формы (выглядит как: `https://formspree.i…mages/solutions/`
3. Обновите имя файла в HTML коде

## 📱 Мобильное меню

Сайт полностью адаптивный — на мобильных устройствах меню автоматически сворачивается в "гамбургер".

## 🔧 Технологии

- **HTML5** — структура сайта
- **Tailwind CSS** (через CDN) — стили
- **Lucide Icons** — иконки
- **JavaScript** — мобильное меню и слот-машина

## 📊 Разделы сайта

### Главная (index.html)
- Главный экран с призывом к действию
- Преимущества компании
- Краткий список услуг
- Бегущая строка с клиентами

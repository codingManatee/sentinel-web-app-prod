# Sentinel (Сентинел)

[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/codingManatee/sentinel-web-app-prod/blob/main/README.md)
[![ru](https://img.shields.io/badge/lang-ru-red.svg)](https://github.com/codingManatee/sentinel-web-app-prod/blob/main/README-RU.md)

Sentinel — это платформа для детекции и ведения журнала в реальном времени, разработанная для золотодобывающей компании в России.  
Она предназначена для отслеживания и фиксации объема переработанного грунта горнодобывающим оборудованием, а также для генерации аналитики для оценки эффективности.

## Технологии

- **Frontend**: Next.js, Prisma, SQLite
- **Backend**: FastAPI с кастомной моделью YOLOv10 для детекции объектов
- **Поддержка потоков**: RTSP-видеовход, Server-Sent Events (SSE) для обновлений в реальном времени
- **Контейнеризация**: Полностью упаковано в Docker для разработки и продакшена

---

## Лицензия и использование

Это программное обеспечение является **коммерческим** и распространяется в соответствии с ограниченным лицензионным соглашением.

Используя это ПО, вы соглашаетесь со следующими условиями:

### ❌ Запрещенные действия

Вы **не имеете права**:

- Производить обратную разработку, декомпиляцию или дизассемблирование приложения
- Модифицировать или создавать производные работы на основе данного ПО
- Распространять или переупаковывать приложение без письменного разрешения

### ✅ Разрешенное использование

Вы **имеете право**:

- Запускать контейнер Docker в рамках лицензионного соглашения
- Использовать ПО внутри вашей организации
- Получать доступ к результатам детекции и функциям аналитики

### 📄 Интеллектуальная собственность

Весь исходный код, модели и логика детекции являются исключительной собственностью разработчиков **Sentinel**.  
Несанкционированное воспроизведение или распространение строго запрещено и может повлечь гражданскую или уголовную ответственность.

### ⚖️ Юрисдикция

Данное лицензионное соглашение регулируется законодательством Таиланда. Все споры подлежат рассмотрению в юрисдикции Таиланда.

---

Для получения корпоративной лицензии или поддержки по интеграции, пожалуйста, свяжитесь с нами:

**Паттапон Вичанукро**  
📧 pattapon.vichanukroh@outlook.com  
📞 (+66) 88-678-2582

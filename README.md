# Awesome RU [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Кураторский список живых и интересных проектов с открытым исходным кодом от русскоязычных разработчиков

*Обновлённая версия [awesome-made-by-russians](https://github.com/gaearon/awesome-made-by-russians) (последнее обновление: 2020)*

## 📋 Содержание

- [Искусственный интеллект и машинное обучение](#искусственный-интеллект-и-машинное-обучение)
- [Базы данных](#базы-данных)
- [Веб-разработка](#веб-разработка)
- [Инструменты разработчика](#инструменты-разработчика)
- [Инфраструктура и DevOps](#инфраструктура-и-devops)
- [Языки программирования](#языки-программирования)
- [Дизайн и шрифты](#дизайн-и-шрифты)
- [Безопасность](#безопасность)
- [Образование](#образование)

---

## 🎯 Критерии включения

Проект должен соответствовать критериям:

1. ✅ **Открытый исходный код** — лицензия одобренная OSI (MIT, Apache, GPL и т.д.)
2. ✅ **Активность** — коммиты за последние 18 месяцев ИЛИ легендарный статус
3. ✅ **Качество** — минимум 100+ звёзд на GitHub ИЛИ уникальное решение
4. ✅ **Русские корни** — основной автор из России/СНГ ИЛИ фокус на русский язык
5. ✅ **Интересный** — не клон популярного западного проекта
6. ✅ **Документация** — есть README с инструкцией по использованию

**Исключения:**
- Легендарные проекты (Redux, Kotlin, OpenCV) — без ограничения по активности
- Уникальные проекты с менее чем 100 звёзд — если действительно инновационны

---

## Искусственный интеллект и машинное обучение

- **[YaLM-100B](https://github.com/yandex/YaLM-100B)** ![](https://img.shields.io/github/stars/yandex/YaLM-100B?style=flat-square) - Языковая модель со 100 миллиардами параметров, одна из крупнейших открытых моделей в мире. Автор: Яндекс.
- **[Kandinsky-2](https://github.com/ai-forever/Kandinsky-2)** ![](https://img.shields.io/github/stars/ai-forever/Kandinsky-2?style=flat-square) - Мультиязычная модель генерации изображений по текстовому описанию. Автор: Сбер AI.
- **[Kandinsky-3](https://github.com/ai-forever/Kandinsky-3)** ![](https://img.shields.io/github/stars/ai-forever/Kandinsky-3?style=flat-square) - Улучшенная версия генератора изображений с повышенным качеством и реалистичностью. Автор: Сбер AI.
- **[CatBoost](https://github.com/catboost/catboost)** ![](https://img.shields.io/github/stars/catboost/catboost?style=flat-square) - Библиотека градиентного бустинга с встроенной поддержкой категориальных признаков. Автор: Яндекс.
- **[ru-gpts](https://github.com/ai-forever/ru-gpts)** ![](https://img.shields.io/github/stars/ai-forever/ru-gpts?style=flat-square) - Семейство моделей GPT-3 для русского языка разных размеров. Автор: Сбер AI.
- **[ru-clip](https://github.com/ai-forever/ru-clip)** ![](https://img.shields.io/github/stars/ai-forever/ru-clip?style=flat-square) - Модель CLIP для русского языка, связывающая текст и изображения. Автор: Сбер AI.
- **[LightAutoML](https://github.com/sberbank-ai-lab/LightAutoML)** ![](https://img.shields.io/github/stars/sberbank-ai-lab/LightAutoML?style=flat-square) - Фреймворк для автоматического создания моделей машинного обучения. Автор: Сбер AI Lab.
- **[Open CV](https://github.com/opencv/opencv)** ![](https://img.shields.io/github/stars/opencv/opencv?style=flat-square) - Библиотека компьютерного зрения и машинного обучения с открытым исходным кодом. Автор: Intel (основатель - Гэри Брэдски, работал в России).
- **[DeepPavlov](https://github.com/deeppavlov/DeepPavlov)** ![](https://img.shields.io/github/stars/deeppavlov/DeepPavlov?style=flat-square) - Библиотека для разработки диалоговых AI систем и чат-ботов. Автор: МФТИ.
- **[NNI](https://github.com/microsoft/nni)** ![](https://img.shields.io/github/stars/microsoft/nni?style=flat-square) - Инструмент для автоматизации подбора гиперпараметров и архитектуры нейронных сетей. Автор: Microsoft (вклад русских разработчиков).

## Базы данных

- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** ![](https://img.shields.io/github/stars/ClickHouse/ClickHouse?style=flat-square) - Колоночная аналитическая СУБД для обработки больших данных в реальном времени. Автор: Яндекс.
- **[Tarantool](https://github.com/tarantool/tarantool)** ![](https://img.shields.io/github/stars/tarantool/tarantool?style=flat-square) - База данных в памяти с поддержкой Lua для хранимых процедур и приложений. Автор: Mail.ru Group.
- **[Dragonfly](https://github.com/dragonflydb/dragonfly)** ![](https://img.shields.io/github/stars/dragonflydb/dragonfly?style=flat-square) - Современная замена Redis и Memcached с вертикальным масштабированием. Автор: Роман Гершман.

## Веб-разработка

- **[Redux](https://github.com/reduxjs/redux)** ![](https://img.shields.io/github/stars/reduxjs/redux?style=flat-square) - Предсказуемый контейнер состояния для JavaScript приложений. Автор: Дэн Абрамов.
- **[Framework7](https://github.com/framework7io/framework7)** ![](https://img.shields.io/github/stars/framework7io/framework7?style=flat-square) - Полнофункциональный HTML фреймворк для создания iOS и Android приложений. Автор: Владимир Харлампиди.
- **[Highlight.js](https://github.com/highlightjs/highlight.js)** ![](https://img.shields.io/github/stars/highlightjs/highlight.js?style=flat-square) - Подсветка синтаксиса для веба с автоматическим определением языка. Автор: Иван Сагалаев.
- **[Swiper](https://github.com/nolimits4web/swiper)** ![](https://img.shields.io/github/stars/nolimits4web/swiper?style=flat-square) - Современный мобильный тач-слайдер с аппаратным ускорением. Автор: Владимир Харлампиди.
- **[React Hot Loader](https://github.com/gaearon/react-hot-loader)** ![](https://img.shields.io/github/stars/gaearon/react-hot-loader?style=flat-square) - Горячая перезагрузка модулей для React компонентов. Автор: Дэн Абрамов.
- **[Browserslist](https://github.com/browserslist/browserslist)** ![](https://img.shields.io/github/stars/browserslist/browserslist?style=flat-square) - Конфигурация целевых браузеров для инструментов фронтенда. Автор: Андрей Ситник.
- **[Size Limit](https://github.com/ai/size-limit)** ![](https://img.shields.io/github/stars/ai/size-limit?style=flat-square) - Инструмент для контроля размера JavaScript библиотек в CI. Автор: Андрей Ситник.
- **[Effector](https://github.com/effector/effector)** ![](https://img.shields.io/github/stars/effector/effector?style=flat-square) - Библиотека управления состоянием для JavaScript приложений. Автор: Дмитрий Болдырев.
- **[Feature Sliced Design](https://github.com/feature-sliced/documentation)** ![](https://img.shields.io/github/stars/feature-sliced/documentation?style=flat-square) - Архитектурная методология для фронтенд проектов. Автор: Русскоязычное сообщество.
- **[ReScript](https://github.com/rescript-lang/rescript-compiler)** ![](https://img.shields.io/github/stars/rescript-lang/rescript-compiler?style=flat-square) - Язык программирования который компилируется в JavaScript (ранее BuckleScript). Автор: Hongbo Zhang (вклад русских разработчиков).

## Инструменты разработчика

- **[Autoprefixer](https://github.com/postcss/autoprefixer)** ![](https://img.shields.io/github/stars/postcss/autoprefixer?style=flat-square) - Плагин PostCSS для автоматического добавления вендорных префиксов в CSS. Автор: Андрей Ситник.
- **[PostCSS](https://github.com/postcss/postcss)** ![](https://img.shields.io/github/stars/postcss/postcss?style=flat-square) - Инструмент для трансформации CSS с помощью JavaScript плагинов. Автор: Андрей Ситник.
- **[Core-js](https://github.com/zloirock/core-js)** ![](https://img.shields.io/github/stars/zloirock/core-js?style=flat-square) - Модульная стандартная библиотека для JavaScript с полифилами. Автор: Денис Пушкарев.
- **[Emmet](https://github.com/emmetio/emmet)** ![](https://img.shields.io/github/stars/emmetio/emmet?style=flat-square) - Набор инструментов для ускорения написания HTML и CSS кода. Автор: Сергей Чикуёнок.
- **[JSS](https://github.com/cssinjs/jss)** ![](https://img.shields.io/github/stars/cssinjs/jss?style=flat-square) - Библиотека для написания стилей CSS в JavaScript. Автор: Олег Исонен.
- **[Nano ID](https://github.com/ai/nanoid)** ![](https://img.shields.io/github/stars/ai/nanoid?style=flat-square) - Генератор уникальных строковых идентификаторов размером всего 108 байт. Автор: Андрей Ситник.
- **[Evil Icons](https://github.com/evil-icons/evil-icons)** ![](https://img.shields.io/github/stars/evil-icons/evil-icons?style=flat-square) - Набор SVG иконок с поддержкой Rails, Sinatra, React и других платформ. Автор: Александр Мадянкин.
- **[Shower](https://github.com/shower/shower)** ![](https://img.shields.io/github/stars/shower/shower?style=flat-square) - HTML движок для создания презентаций и слайдов. Автор: Вадим Макеев.
- **[CSSO](https://github.com/css/csso)** ![](https://img.shields.io/github/stars/css/csso?style=flat-square) - CSS минификатор с оптимизацией структуры. Автор: Роман Дворнов.
- **[Stylelint](https://github.com/stylelint/stylelint)** ![](https://img.shields.io/github/stars/stylelint/stylelint?style=flat-square) - Линтер для CSS и CSS-подобных синтаксисов. Автор: Международная команда (вклад русских разработчиков).
- **[lint-staged](https://github.com/lint-staged/lint-staged)** ![](https://img.shields.io/github/stars/lint-staged/lint-staged?style=flat-square) - Запуск линтеров только на staged файлах в Git. Автор: Андрей Ситник.
- **[Prettier](https://github.com/prettier/prettier)** ![](https://img.shields.io/github/stars/prettier/prettier?style=flat-square) - Форматтер кода с поддержкой множества языков. Автор: Международная команда (вклад Christopher Chedeau).

## Инфраструктура и DevOps

- **[Nginx](https://github.com/nginx/nginx)** ![](https://img.shields.io/github/stars/nginx/nginx?style=flat-square) - Высокопроизводительный HTTP сервер, обратный прокси и почтовый прокси. Автор: Игорь Сысоев.
- **[Centrifugo](https://github.com/centrifugal/centrifugo)** ![](https://img.shields.io/github/stars/centrifugal/centrifugo?style=flat-square) - Масштабируемый сервер обмена сообщениями в реальном времени с WebSocket и SSE. Автор: Александр Емелин.
- **[GIXY](https://github.com/yandex/gixy)** ![](https://img.shields.io/github/stars/yandex/gixy?style=flat-square) - Инструмент статического анализа конфигурационных файлов Nginx. Автор: Яндекс.
- **[Yandex Tank](https://github.com/yandex/yandex-tank)** ![](https://img.shields.io/github/stars/yandex/yandex-tank?style=flat-square) - Инструмент нагрузочного тестирования с автоматическими отчётами. Автор: Яндекс.
- **[Roadrunner](https://github.com/roadrunner-server/roadrunner)** ![](https://img.shields.io/github/stars/roadrunner-server/roadrunner?style=flat-square) - Высокопроизводительный PHP application сервер написанный на Go. Автор: Spiral Scout.
- **[GoLand](https://github.com/golang/go)** - IDE для разработки на Go от JetBrains (примечание: сам Go создан не русскими, но JetBrains из России).
- **[Manticore Search](https://github.com/manticoresoftware/manticoresearch)** ![](https://img.shields.io/github/stars/manticoresoftware/manticoresearch?style=flat-square) - Поисковый движок форк Sphinx Search. Автор: Manticore Software.

## Языки программирования

- **[Kotlin](https://github.com/JetBrains/kotlin)** ![](https://img.shields.io/github/stars/JetBrains/kotlin?style=flat-square) - Современный статически типизированный язык программирования для JVM, Android и браузера. Автор: JetBrains.
- **[Red](https://github.com/red/red)** ![](https://img.shields.io/github/stars/red/red?style=flat-square) - Язык программирования нового поколения вдохновлённый REBOL. Автор: Nenad Rakocevic (живет в России).
- **[V](https://github.com/vlang/v)** ![](https://img.shields.io/github/stars/vlang/v?style=flat-square) - Простой, быстрый и безопасный компилируемый язык программирования. Автор: Alexander Medvednikov.

## Дизайн и шрифты

- **[Fira Code](https://github.com/tonsky/FiraCode)** ![](https://img.shields.io/github/stars/tonsky/FiraCode?style=flat-square) - Моноширинный шрифт с лигатурами для программирования. Автор: Никита Прокопов.
- **[JetBrains Mono](https://github.com/JetBrains/JetBrains-Mono)** ![](https://img.shields.io/github/stars/JetBrains/JetBrains-Mono?style=flat-square) - Моноширинный шрифт специально разработанный для разработчиков. Автор: JetBrains.
- **[Figma Linux](https://github.com/Figma-Linux/figma-linux)** ![](https://img.shields.io/github/stars/Figma-Linux/figma-linux?style=flat-square) - Неофициальный клиент Figma для Linux. Автор: Русскоязычное сообщество.
- **[IconPark](https://github.com/bytedance/IconPark)** ![](https://img.shields.io/github/stars/bytedance/IconPark?style=flat-square) - Библиотека высококачественных SVG иконок с возможностью кастомизации. Автор: ByteDance (TikTok).

## Безопасность

- **[Lynis](https://github.com/CISOfy/lynis)** ![](https://img.shields.io/github/stars/CISOfy/lynis?style=flat-square) - Инструмент аудита безопасности для Unix и Linux систем. Автор: Михаэль Болен (CISOfy).
- **[Wazuh](https://github.com/wazuh/wazuh)** ![](https://img.shields.io/github/stars/wazuh/wazuh?style=flat-square) - Платформа для мониторинга безопасности и обнаружения угроз. Автор: Wazuh Inc.
- **[ModSecurity](https://github.com/SpiderLabs/ModSecurity)** ![](https://img.shields.io/github/stars/SpiderLabs/ModSecurity?style=flat-square) - Web Application Firewall движок с открытым исходным кодом. Автор: Trustwave SpiderLabs (вклад русских разработчиков).

## Образование

- **[Practical DL](https://github.com/yandexdataschool/Practical_DL)** ![](https://img.shields.io/github/stars/yandexdataschool/Practical_DL?style=flat-square) - Курс по глубокому обучению от Школы анализа данных Яндекса. Автор: ШАД.
- **[Practical RL](https://github.com/yandexdataschool/Practical_RL)** ![](https://img.shields.io/github/stars/yandexdataschool/Practical_RL?style=flat-square) - Курс по обучению с подкреплением от Школы анализа данных Яндекса. Автор: ШАД.
- **[ML Course](https://github.com/yandexdataschool/mlcourse.ai)** ![](https://img.shields.io/github/stars/yandexdataschool/mlcourse.ai?style=flat-square) - Открытый курс по машинному обучению на русском и английском языках. Автор: ШАД.

---

## 🤝 Как внести вклад

Пожалуйста, прочитайте [CONTRIBUTING.md](CONTRIBUTING.md) для деталей о процессе отправки предложений.

## 📜 Лицензия

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

В соответствии с законом насколько это возможно, [mawo-ru](https://github.com/mawo-ru) отказался от всех авторских и смежных прав на эту работу.

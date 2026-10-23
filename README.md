<p align="center"><img src="assets/banner.png" alt="Uncrypted256" width="100%"></p>

Пишу приложения и инструменты для своих задач. Здесь собраны мои проекты и эксперименты с кодом.

[uncrypted.fun](https://uncrypted.fun) · [admin@uncrypted.fun](mailto:admin@uncrypted.fun)

Исходники приложений находятся в приватных репозиториях. Для просмотра нужен доступ.

<a href="https://github.com/uncrypted256/256gram"><img src="assets/256gram.png" alt="256gram" width="100%"></a>

Мой клиент Telegram для iPhone с настройками приватности и интерфейса. В одном приложении собраны работа с несколькими аккаунтами и настройки клиента. Для оформления используется собственный знак 256: объёмная бирюзовая лента на тёмном фоне.

[Репозиторий · private](https://github.com/uncrypted256/256gram)

<a href="https://github.com/uncrypted256/slovo"><img src="assets/slovo.png" alt="SLOVO" width="100%"></a>

Аудиокниги и подкасты в одном приложении для Mac. Можно собрать свою библиотеку и продолжать слушать с сохранённого места. Приложение читает метаданные и главы, ищет книги в нескольких каталогах, сохраняет очередь загрузок. Есть рекомендации, таймер сна, скорость воспроизведения и системное управление плеером.

[Репозиторий · private](https://github.com/uncrypted256/slovo)

<a href="https://github.com/uncrypted256/personal-assistant"><img src="assets/personal-assistant.png" alt="Personal Assistant" width="100%"></a>

Ассистент для личного Telegram-аккаунта. Помнит контекст каждого диалога и готовит ответы с учётом разрешений собеседника. Работает с текстом, фотографиями, голосовыми сообщениями и видео. Память хранится локально; контекст разделён по аккаунтам и контактам. Ответ проходит проверку перед отправкой. В shadow-режиме отправки нет.

[Репозиторий · private](https://github.com/uncrypted256/personal-assistant)

<a href="https://github.com/uncrypted256/astra"><img src="assets/astra.png" alt="Astra" width="100%"></a>

Рабочая среда для рыночных данных и проверки торговых идей в симуляции. Сервер собирает данные, сохраняет аналитические решения вместе с основаниями и ведёт журнал задач. Веб-интерфейс показывает источники и портфели. Есть бумажное исполнение по глубине стакана и наблюдение за подтверждённым демосчётом.

[Репозиторий · private](https://github.com/uncrypted256/astra)

<a href="https://github.com/uncrypted256/pantera-control"><img src="assets/pantera-control.png" alt="Pantera Control" width="100%"></a>

Панель управления магазином: каталог, заказы, переписка, закупки и аналитика. Интерфейс связывает повседневные операции магазина в одном рабочем месте. Для запросов сохраняется состояние; неопределённый ответ сервера не превращается в ложное подтверждение успеха. Деморежим показывает вымышленные заказы и сообщения.

[Репозиторий · private](https://github.com/uncrypted256/pantera-control)

<a href="https://github.com/uncrypted256/shop-orchestrator"><img src="assets/shop-orchestrator.png" alt="Shop Orchestrator" width="100%"></a>

Фоновый обработчик событий магазина. Связывает компоненты через очередь и сохраняет результат каждого задания. Экспорт содержит TypeScript worker, SQLite-очередь и проверки ответов. Частные инструкции вынесены в локальную конфигурацию; исходная база примеров заменена нейтральной. Python-плагины выдачи, изменения лотов и финансовых операций не включены. Для полного развёртывания нужен внешний адаптер отправки.

[Репозиторий · private](https://github.com/uncrypted256/shop-orchestrator)

<a href="https://github.com/uncrypted256/private-email-relay"><img src="assets/private-email-relay.png" alt="Private Email Relay" width="100%"></a>

Отдельный почтовый адрес для каждого сервиса и один основной ящик для входящих писем. Telegram-бот создаёт постоянные алиасы, показывает активные адреса и отключает ненужные. Скрипт экспорта формирует карту виртуальных адресов для Postfix. Данные хранятся в SQLite.

[Репозиторий · private](https://github.com/uncrypted256/private-email-relay)

<a href="https://github.com/uncrypted256/model-viewer"><img src="assets/model-viewer.png" alt="3D Model Viewer" width="100%"></a>

Архитектурная 3D-модель прямо в браузере: ракурс, масштаб и освещение можно менять во время просмотра. Сцена поддерживает переключение камер, дневного и вечернего света, а также экспорт модели. Геометрия и управление сценой выделены в отдельные модули.

[Репозиторий · private](https://github.com/uncrypted256/model-viewer)

<a href="https://github.com/uncrypted256/audio-tools"><img src="assets/audio-tools.png" alt="TTS" width="100%"></a>

Подготовка текста и WAV для озвучки: сегментация, технические метрики и сборка с паузами. Семь функций выделены из многоголосого аудиопроцесса и собраны в CLI. Поддерживаются mono PCM 16 bit 44100 Hz, обрезка тишины и изменение уровня. В экспорте нет провайдерного синтеза и весов своей модели. Тексты книг, голосовые конфигурации и записи исключены.

[Репозиторий · private](https://github.com/uncrypted256/audio-tools)

<a href="https://github.com/uncrypted256/arbitrage-scanner"><img src="assets/arbitrage-scanner.png" alt="Arbitrage Scanner" width="100%"></a>

Сканер межбиржевых спредов, который считает исполнение по глубине стакана. Учитывает комиссии, расходы перевода, частичное исполнение и свежесть локального снимка. Есть настольный интерфейс и командная строка для сохранённых стаканов. Можно отдельно запросить публичный снимок рынка.

[Репозиторий · private](https://github.com/uncrypted256/arbitrage-scanner)

<a href="https://github.com/uncrypted256/stream-learning-lab"><img src="assets/stream-learning-lab.png" alt="Stream Learning Lab" width="100%"></a>

Лаборатория обучения на последовательных данных. Модель сначала делает прогноз, затем получает правильный ответ и обновляется. CSV-бенчмарк сравнивает два SGD-классификатора с базовой стратегией. Синтетический поток меняет правило в середине последовательности, чтобы было видно, как модели адаптируются. Результат сохраняется в JSON и на кривой обучения.

[Репозиторий · private](https://github.com/uncrypted256/stream-learning-lab)

<a href="https://github.com/uncrypted256/reverse-engineering-lab"><img src="assets/reverse-engineering-lab.png" alt="Reverse Engineering Lab" width="100%"></a>

Пять офлайн-инструментов для разбора бинарных файлов, сетевых записей и журналов исследования. Можно получить метаданные PE, сводку PCAPNG, отчёт Windows Firewall, обзор сетевого JSONL и сравнение двух журналов. Отдельные парсеры разбирают доступные DNS/TLS-метаданные. Результаты сохраняются в JSON и читаемых отчётах.

[Репозиторий · private](https://github.com/uncrypted256/reverse-engineering-lab)

<a href="https://github.com/uncrypted256/atlas-license-kit"><img src="assets/atlas-license-kit.png" alt="Atlas License Kit" width="100%"></a>

Подпись лицензий и офлайн-проверка: целостность манифеста, статус, срок действия и переданный хеш устройства. Самостоятельная часть Atlas license gateway / loader. CLI создаёт ключи, подписывает манифест и проверяет подпись. Канонический формат сохранён по Rust signer, реализация перенесена на Node.js без зависимостей из npm.

[Репозиторий · private](https://github.com/uncrypted256/atlas-license-kit)

<a href="https://github.com/uncrypted256/jar-audit-tools"><img src="assets/jar-audit-tools.png" alt="JAR Audit Tools" width="100%"></a>

Инспектор Java-архивов: состав JAR, метаданные классов, хеши, дубли и небезопасные пути. Инструмент читает архив без извлечения и загрузки классов. Проверяет внутренние имена и версии классов, соответствие путям, ограничивает размеры записей. Отмечает наличие файлов подписи, но не выдаёт это за проверку доверия.

[Репозиторий · private](https://github.com/uncrypted256/jar-audit-tools)

<a href="https://github.com/uncrypted256/flight-search-tools"><img src="assets/flight-search-tools.png" alt="Flight Search Tools" width="100%"></a>

Планирование авиа-поиска и сравнение сохранённых предложений по маршруту, бюджету и длительности. Проверяет IATA-коды и даты, считает общую стоимость для группы пассажиров, учитывает часовые пояса. Убирает совпадающие предложения и отклоняет конфликтующие записи. Результат можно сохранить в JSON.

[Репозиторий · private](https://github.com/uncrypted256/flight-search-tools)

<a href="https://github.com/uncrypted256/alas-hotel"><img src="assets/alas-hotel.png" alt="Alas Hotel" width="100%"></a>

Сайт отеля в Теберде: моушен на GSAP и 60 кадрах Remotion, проверка наличия, заявки и панель администратора. Выбор дат не создаёт бронь; заявка отправляется отдельно, затем подтверждается или отменяется в панели. API на Next.js и Prisma записывает изменения вместе с историей. Повторный запрос после потери ответа восстанавливает квитанцию без дубликата. Пройдены 28 тестов и production-сборка, сценарий проверен в браузере. В демо номера и цены вымышлены, пейзаж сгенерирован; оплат и уведомлений нет. Рабочие материалы отеля и внешнее развёртывание ещё нужны.

[Репозиторий · private](https://github.com/uncrypted256/alas-hotel)

<a href="https://github.com/uncrypted256/ai-store"><img src="assets/ai-store.png" alt="AI Store" width="100%"></a>

Операционная часть магазина на Django: каталог на трёх языках, зашифрованный склад, резервирование и выдача товара, промокоды, поддержка и журнал действий. Панель Atlas Control защищена паролем и TOTP. Восстановлены настройки и локальный сценарий на искусственных заказах; прошли 77 тестов. Покупательский бот, реальные платежи и отправка сообщений ещё не подключены. Недоступная интеграция оставляет явную ошибку и не имитирует успешную операцию.

[Репозиторий · private](https://github.com/uncrypted256/ai-store)

<a href="https://github.com/uncrypted256/kymsha"><img src="assets/kymsha.png" alt="Kymsha" width="100%"></a>

Сайт с галереей, видеоблоком и страницами контактов. Сохранены страницы, адаптивная навигация, SEO-маршруты и галерея. Контакты задаются переменными окружения. Недостающие фото и видео обозначены в README; по умолчанию используется абстрактная SVG-подложка.

[Репозиторий · private](https://github.com/uncrypted256/kymsha)

<a href="https://github.com/uncrypted256/eliya-vpn"><img src="assets/eliya-vpn.png" alt="Eliya VPN" width="100%"></a>

Клиент Telegram-мини-апки VPN-сервиса: тарифы, кабинет, инструкции и поддержка. Сохранён клиентский интерфейс с локальной демонстрацией на вымышленных тарифах. Шрифты включены локально; оплата, выдача доступа и внешние переходы в демо отключены. Опубликован клиент с демонстрацией. Полная реализация сервера, проверки initData, VPN-инфраструктуры и платежей в экспорт не входит.

[Репозиторий · private](https://github.com/uncrypted256/eliya-vpn)

<a href="https://github.com/uncrypted256/repo-preflight"><img src="assets/repo-preflight.png" alt="Repo Preflight" width="100%"></a>

Проверка исходников перед публикацией. Находит возможные секреты и личные файлы, отмечает зависимости, кэши и дубли. Составляет план проверки без изменения исходников; значения найденных токенов в отчёт не попадают. Поддерживает UTF-8, UTF-16 и текстовые схемы Prisma. Python 3.12, без зависимостей для CLI; 16 локальных тестов.

[Репозиторий · private](https://github.com/uncrypted256/repo-preflight)

# Ссылки на наиболее важные технологии

Исторически сложилось, что описание различных технологий выполнялись в разных репозитариях, что со временем потребовало либо объединения разных репозитарией, либо создание отдельного рубрикатора. По зравому размышлению было принято решение использовать рубрикатор.

## CMake

- [Базовая инструкция по CMake](https://github.com/Kerminator1973/GTestProject/blob/main/cmake.md)
- [Подготовка рабочего места программиста](https://github.com/Kerminator1973/RPIDev/blob/main/developerworkplace.md)
- [Разработка CMakeLists.txt](https://github.com/Kerminator1973/RPIDev/blob/main/extrasRPi.md)
- [Использование кросс-компиляторов](https://github.com/Kerminator1973/RPIDev/blob/main/linaro.md)
- [Интеграция с Ninja](https://github.com/Kerminator1973/RPIDev/blob/main/ninja_bs.md)
- [CMake и микроконтроллеры](https://github.com/Kerminator1973/RPIDev/blob/main/microcontrollers/pico2040cpp.md)
- [Применение CMake в ProATMEmbedded](https://github.com/Kerminator1973/RPIDev/blob/main/proatmEmb/proAtmBuilding.md)
- [CMake и Google Benchmark](https://github.com/Kerminator1973/GTestProject/blob/main/benchmark.md)
- [CMake и Google Test](https://github.com/Kerminator1973/GTestProject/blob/main/CMake_GoogleTest.md)
- Описание скрипта [Fetch](https://github.com/Kerminator1973/RPIDev/blob/main/cpp/cmakeFetch.md)
- Пример использования [Fetch](https://github.com/Kerminator1973/GTestProject/blob/main/CMakeExamples/PortableCCNET/unittest/CMakeLists.txt) для загрузки Google Test скриптом CMake
- Приложение WEB API для ЭСКД ProIDC - репозитарий SVN КБ ДОРС (SberWebAPI)
- Интеграция с ГДАСУЦ - репозитарий SVN КБ ДОРС (BVSDesktop/BPSConverter)

## Boost.asio

- [Конспект официальной документации Asio](https://github.com/Kerminator1973/TlsProxy/blob/master/asio.md)
- [Пример синхронного режима Asio/TCP](https://github.com/Kerminator1973/curlhttps/tree/master/BoostAsioTcpSyncExample)
- [Асинхронный режим Asio/TCP](https://github.com/Kerminator1973/curlhttps/blob/master/boost_asio_tcp_async_example.md)
- Асинхронное использование Asio/TCP для ЭСКД ProIDC - репозитарий SVN КБ ДОРС (SberWebAPI)
- [Boost.Beast и WebSockets](https://github.com/Kerminator1973/TlsProxy/blob/master/websockets.md)
- Динамическая библиотека в которой используется [Boost.Beast](https://github.com/Kerminator1973/TlsProxy/tree/master/TlsProxyDll)
- Библиотека Portable DSlip, использующая Asio для работы через USB CDC - репозитарий SVN КБ ДОРС (DSlipPortable)
- Упрощённая реализация протокола CCNET, использующая [Asio Serial](https://github.com/Kerminator1973/GTestProject/tree/main/CMakeExamples/PortableCCNET)
- [Реализация web-сервера с использованием Boost.Asio](https://github.com/Kerminator1973/TlsProxy/blob/master/make_shared.md)
- WEB API для ЭСКД ProIDC с использованием Boost.Asio - репозитарий SVN КБ ДОРС (SberWebAPI)

### Дополнительно

- [Kotlin-приложение, управляющее внешним устройством через USB CDC](https://github.com/Kerminator1973/AndroidUsbCDC)
- [Эмуляция CCNET/DSlip на Raspberry Pi Pico](https://github.com/Kerminator1973/RPIDev/blob/main/microcontrollers/pico2040emulateBVS.md)

## Сертификаты/OpenSSL

- [Проверка сертификата сервера](https://github.com/Kerminator1973/curlhttps/blob/master/pem.md) посредством curl, boost.beast, Android/Java, C#
- [Настройка web-приложения в IIS](https://github.com/Kerminator1973/WebDevelopment/blob/master/iis.md) с использованием сертификатов. Более подробная [инструкция настройки клиентских сертификатов в IIS](https://github.com/Kerminator1973/curlhttps/blob/master/configureIIS.md)
- [Проверка сертификатов в Node.js](https://github.com/Kerminator1973/WebDevelopment/blob/master/express.md) и [дополнительно](https://github.com/Kerminator1973/WebDevelopment/blob/master/http2.md)
- [Проверка сертификатов в приложениях .NET на C#](https://github.com/Kerminator1973/curlhttps/tree/master/ClientCertificate)
- [Пример скрипта генерации сертификатов](https://github.com/Kerminator1973/curlhttps/tree/master/MakeCertificates)
- [Использование клиентских сертификатов в C# и C++/curl](https://github.com/Kerminator1973/curlhttps/blob/master/clientCert.md)
- [Загрузка сертификатов из хранилища Windows](https://github.com/Kerminator1973/TlsProxy/blob/master/example.md)
- настройка сертификатов в nginx - репозитарий SVN КБ ДОРС (SberWebAPI)

## Avalonia

- [Пример использования DataGrid](https://github.com/Kerminator1973/Avalonia.DataGridExample) - описание на английском языке
- Приложение [подтверждающее возможность использования Avalonia в Linux](https://github.com/Kerminator1973/BvsDesktopLinux)
- Приложение для тестирования узлов АДМ под Debian/Ubuntu - репозитарий SVN КБ ДОРС (ADMCheck)
- Особенности [верстки XAML в Avalonia](https://github.com/Kerminator1973/BVSDesktopSupport/blob/main/avalonia.md)

## React

- Большой [обзорный документ по React](https://github.com/Kerminator1973/RUFServerLite/blob/main/docs/react.md), включающий MobX, Axios, CORS и хуки
- Ревизия React-проекта [через два года](https://github.com/Kerminator1973/RUFServerLite/blob/main/docs/react_after_two_years.md) - что стухло и/или изменилось
- [Встраивание React-приложения в MPA](https://github.com/Kerminator1973/RUFServerLite/blob/main/docs/react_embed.md)
- SPA [Электронный журнал](https://github.com/Kerminator1973/RUFServerLite/tree/main/journal) на React встроенный в MPA RUFServerLite
- Инструкция по разработке [React-приложения с Redux](https://github.com/Kerminator1973/WebDevelopment/blob/master/reactappsample.md)
- Учебное приложение [Meal recipe](https://github.com/Kerminator1973/MealsRecipes) (курс) на **React Native** от 2020 года
- [Учебные приложения](https://github.com/Kerminator1973/WebDevelopment/tree/master/react_examples) из разных курсов по React

## BVSUpdate/AgentRUF/DSlip.dll/BVS

- Подключение приборов BVS по USB, обмен данными [BVSUpdate и AgentRUF](https://github.com/Kerminator1973/BVSDesktopSupport/blob/main/agent_ruf.md)
- Протокол взаимодействия между [BVSUpdate и AgentRUF](https://github.com/Kerminator1973/BVSDesktopSupport/blob/main/protocol.md)
- [Протоколы взаимодействия](https://github.com/Kerminator1973/RPIDev/blob/main/dslip.md) с приборами BVS
- [Эмуляция прибора BVS](https://github.com/Kerminator1973/RPIDev/blob/main/microcontrollers/pico2040emulateBVS.md) на Raspberry Pi Pico

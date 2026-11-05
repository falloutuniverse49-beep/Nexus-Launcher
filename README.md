<div align="center">
  <img src="https://github.com/user-attachments/assets/21315b4f-24b8-4ea2-a121-bbfa90b74fee" width="150" alt="Nexus Launcher Logo" />
  
  # 🚀 Nexus Launcher
  
  **Современный, быстрый и красивый лаунчер для Minecraft, написанный на C++ и Qt 6.**
  
  [![Скачать](https://img.shields.io/badge/Скачать-Последний_релиз-purple?style=for-the-badge&logo=windows)](https://github.com/falloutuniverse49-beep/Nexus-Launcher/releases/latest)
  [![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-blue?style=for-the-badge&logo=windows)](#)
  [![C++](https://img.shields.io/badge/C++-17-blue?style=for-the-badge&logo=c%2B%2B)](#)
  
</div>

---

## 📖 О проекте

**Nexus Launcher** — это легковесный и эстетичный лаунчер для Minecraft. Он создавался с упором на скорость работы, удобство и приятный глазу дизайн. В основе лежит C++ и фреймворк Qt 6, что обеспечивает мгновенный запуск и плавную анимацию интерфейса. 

Забудьте о тяжелых и перегруженных лаунчерах. Nexus Launcher предоставляет только то, что нужно для комфортной игры, в стильной неоновой обертке.

## 📸 Скриншоты

<div align="center">
  <img src="https://github.com/user-attachments/assets/30a990bf-8bb4-48f8-a69d-555495436161" width="48%" alt="Скриншот 1" />
  <img src="https://github.com/user-attachments/assets/7a9a3a6f-0244-40a0-9cac-7de6769a45ac" width="48%" alt="Скриншот 2" />
</div>

## ✨ Ключевые особенности

*   🎨 **Уникальный дизайн:** Стильный темный интерфейс с неоновыми фиолетовыми акцентами и кастомным пиксельным шрифтом (Minecraft Rus).
*   🧊 **3D-просмотр скинов:** Встроенный OpenGL-просмотрщик с поддержкой классических (Classic) и тонких (Slim) моделей. Скин можно вращать курсором.
*   🧩 **Интеграция с Modrinth:** Прямой доступ к популярным модам и сборкам прямо из лаунчера.
*   ⚙️ **Менеджер версий:** Удобное создание и переключение между сборками (поддерживается Forge, например, 1.20.1).
*   👤 **Профили игроков:** Поддержка оффлайн-профилей с возможностью быстрой смены ника и скина.
*   🚀 **Высокая производительность:** Никакого Electron и лишних фреймворков — только чистый C++.

## 📥 Установка

1. Перейдите в раздел **[Releases](https://github.com/falloutuniverse49-beep/Nexus-Launcher/releases/latest)**.
2. Скачайте файл **`NexusLauncherSetup.exe`**.
3. Запустите установщик и следуйте инструкциям.
4. Готово! Все необходимые библиотеки (Qt, zlib, curl) и шрифты уже встроены в установщик.

> ⚠️ **Системные требования:** 
> * ОС: Windows 10 / 11 (64-bit)
> * Java: Установленная Java 17+ (для версий Minecraft 1.18 и выше).

## 🛠️ Сборка из исходников (для разработчиков)

Если вы хотите собрать лаунчер самостоятельно, вам потребуется:
*   Visual Studio 2022 (с инструментами C++)
*   CMake (версия 3.21+)
*   Git
*   Qt 6.6.3
*   vcpkg (для `libcurl` и `nlohmann-json`)

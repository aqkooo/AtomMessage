# 📢 AtomMessage

**AtomMessage** — современный, легковесный плагин автосообщений, объявлений и ротации сообщений в чате и TAB для серверов Minecraft (**Paper/Spigot 1.16–1.21+**).

Поддерживает плавные HEX-градиенты, MiniMessage, плейсхолдеры PlaceholderAPI и настраиваемые интерактивные кликабельные сообщения с подсказками (hover/click events).

![Java](https://img.shields.io/badge/Java-21-orange?logo=openjdk)
![Platform](https://img.shields.io/badge/Platform-Paper%20%7C%20Spigot-blue)
![PlaceholderAPI](https://img.shields.io/badge/Support-PlaceholderAPI-purple)
![Author](https://img.shields.io/badge/Author-ejyqyl%20(%40aqkooo)-green)

---

## ⚡ Особенности

- **Асинхронный шедулер**: Ротация сообщений происходит в фоновом пуле потоков без малейшего влияния на TPS сервера.
- **Поддержка HEX и MiniMessage**: Красивые градиенты, радуга и современное форматирование без устаревшего API.
- **Интерактивные элементы**: Кликабельные ссылки на сайт/дискорд, выполнение команд по клику, всплывающие подсказки при наведении.
- **Гибкая ротация**: Поддержка последовательного (`sequential`) и случайного (`random`) порядка отправки объявлений.
- **Поддержка PlaceholderAPI**: Автоматическая подстановка никнейма, онлайна, баланса и любых других переменных.

---

## 📋 Команды и права

| Команда | Описание | Алиасы | Право |
| :--- | :--- | :--- | :--- |
| `/atommessage reload` | Перезагрузить конфигурацию и список сообщений | `/am reload`, `/atommsg reload` | `atommessage.admin` |

---

## 🛠️ Сборка из исходников

```bash
git clone https://github.com/aqkooo/AtomMessage.git
cd AtomMessage
mvn clean package
```

Скомпилированный `.jar` файл будет доступен в папке `target/AtomMessage-1.0.0.jar`.

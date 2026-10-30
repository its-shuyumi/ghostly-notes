<div align="center">

# 📝 Desktop Notes & Overlay Widget

[![Java](https://img.shields.io/badge/Java-17%2B-orange?style=flat-square&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Java Swing](https://img.shields.io/badge/UI-Java_Swing-blue?style=flat-square&logo=java&logoColor=white)](https://docs.oracle.com/javase/tutorial/uiswing/)
[![Achievement](https://img.shields.io/badge/Achievement-3rd%20Place%20%2F%20+3%20USE-green?style=flat-square)]()

*Прозрачный бесшовный оверлей для быстрых заметок, написанный за один вечер перед дедлайном. Принес 3-е место в конкурсе проектов и +3 балла к ЕГЭ.*

[Русский](#-русский)

</div>

---

## 🇷🇺 Русский

### 📌 Предыстория
Этот проект появился по классическому сценарию: старая задумка для конкурса пролетела мимо критериев отбора, до дедлайна оставался ровно один вечер, а сдавать что-то было нужно. 

Результат? Код за несколько часов, победа в номинации (3-е место) и официальные **+3 балла к ЕГЭ** при поступлении. Мораль проста: иногда умение быстро собрать рабочий прототип и грамотно презентовать его под нужные критерии важнее многомесячного оверинжиниринга.

### ⚙️ Технические особенности
- **Бесшовный оверлей:** Использование `setUndecorated(true)` и прозрачного фона (`new Color(0, 0, 0, 0)`) для интеграции окна прямо в рабочий стол.
- **Интерактивное перемещение:** Перетаскивание окна за любую область через отслеживание координат мыши (`MouseListener` / `MouseMotionListener`).
- **Быстрый вызов редактора:** Регистрация глобального шортката через `registerKeyboardAction` (клавиша `H`) для вызова всплывающего окна настройки текста.
- **Динамический рендеринг:** Отрисовка через `Graphics2D` с автоматическим центрированием текста под любое разрешение экрана.

---

## ⚙️ Quick Start / Быстрый старт

1. Клонируйте репозиторий:
   ```bashg
   git clone [https://github.com/its-shuyumi/project-notes.git](https://github.com/its-shuyumi/project-notes.git)

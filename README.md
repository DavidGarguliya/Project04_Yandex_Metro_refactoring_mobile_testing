# 🚇 Проект: Тестирование Android приложения **Яндекс Метро**

![Проект](https://img.shields.io/badge/Проект-Яндекс_Метро-orange)  
![Спринт](https://img.shields.io/badge/Спринт-4-blue)  
![Статус](https://img.shields.io/badge/Статус-Завершён-brightgreen)  
![Платформа](https://img.shields.io/badge/Платформа-Android-lightgrey)  
![Баги](https://img.shields.io/badge/Найдено_багов-19-red)  
![Критические](https://img.shields.io/badge/Критические-5-red)  
![Высокие](https://img.shields.io/badge/Высокие-2-orange)  
![Стандартные](https://img.shields.io/badge/Стандартные-12-lightgrey)  

---

## 📝 Описание  

Проект выполнен в рамках **4-го спринта курса “Инженер по тестированию: от новичка до автоматизатора” (Яндекс Практикум)**.  
Задача — протестировать обновлённую версию мобильного приложения **Яндекс Метро (v3.6)** после рефакторинга кода.  

Цель тестирования:
- Проверить стабильность и корректность работы функций, затронутых изменениями;
- Провести регрессионное тестирование приложения;
- Подготовить отчёт о тестировании для менеджера релиза.

---

## 📎 Артефакты  

| Тип документа | Ссылка |
|---------|--------|
| 📑 Требования к Яндекс Метро | [PDF](https://code.s3.yandex.net/qa/files/Yandex_metro.pdf)
| 🖥️ Макеты | [Figma](https://www.figma.com/file/RzH5SqcLWrIPnQQW2fmitu/Metro-Dev?node-id=0%3A1)
| 📱 Готовящаяся сборка | [APK](https://code.s3.yandex.net/qa/files/yandexmetro-android-v3.6.apk)
| ✅ Чек-лист 1. Функциональные проверки по обновлённым требованиям | [Google Sheets](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=899462569#gid=899462569&range=A1:E1) |
| ✅ Чек-лист 2. Регрессионный чек-лист (мобильное тестирование) | [Google Sheets](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1540435533#gid=1540435533&range=A1:E1) |
| 🐞 Таблица баг-репортов (19 дефектов) | [Google Sheets](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862) |
| 📄 Отчёт о тестировании | [GitHub](./Test_Report.md) |

---

## 🔍 Этапы работы  

### 🔹 Этап 1. Подготовка  
- Анализ требований к приложению и обновлённым функциональным сценариям;  
- Составление чек-листа для функционального тестирования;  
- Определение критических сценариев взаимодействия пользователя с приложением.  

### 🔹 Этап 2. Функциональное тестирование  
- Проверка отображения станций, маршрутов и пересадок;  
- Проверка корректности построения маршрутов при вводе разных станций;  
- Валидация работы карты, истории маршрутов и кнопки “Поделиться маршрутом”;  
- Проверка обработки ошибок при отсутствии интернет-соединения.  

### 🔹 Этап 3. Регрессионное тестирование  
- Тестирование сохранения данных после обновления приложения;  
- Проверка работоспособности кнопок и экранных переходов;  
- Тестирование взаимодействия приложения с ОС Android (push, память, выход);  
- Проверка поведения приложения при смене темной/светлой темы.  

### 🔹 Этап 4. Анализ результатов  
- Заведены 19 баг-репортов, классифицированных по приоритетам;  
- Проведён анализ рисков и оценка готовности продукта к публикации;  
- Подготовлен итоговый отчёт для менеджера проекта.  

---

## 🧾 Результаты тестирования  

- Всего проведено: **72 проверки**  
- Пройдено успешно: **49**  
- Не пройдено: **23**

### Распределение дефектов:

| Приоритет | Количество | ID |
|------------|-------------|----|
| 🔴 **Критические** | 5 | [BUG06](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A7), [BUG09](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A10), [BUG10](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A11), [BUG11](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A12), [BUG14](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A15) |
| 🟠 **Высокие** | 2 | [BUG15](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A16), [BUG18](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A19) |
| ⚪ **Стандартные** | 12 | [BUG01](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A2), [BUG02](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A3), [BUG03](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A4), [BUG04](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A5), [BUG05](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A6), [BUG07](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A8), [BUG08](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A9), [BUG12](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A13), [BUG13](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A14), [BUG16](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A17), [BUG17](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A18), [BUG02.1](https://docs.google.com/spreadsheets/d/1GQ7X6VGWhybZASwkEc3HpS8wAvQM_xSJzhU2kClv1rU/edit?gid=1467841862#gid=1467841862&range=A20) |
| 🟢 **Незначительные / UI** | 0 | – |
| ⛔ **Блокирующие** | 0 | – |

---

## 🖼️ Примеры скриншотов  

| ID | Скриншот |
|----|-----------|
| BUG06 | [Отсутствуют кнопки Отсюда и Сюда на карточке станции в свернутом состоянии](https://drive.google.com/file/d/1eZsSgsUnUs71JahtCzg5s__aSULRFyNj/view?usp=drive_link) |
| BUG10 | [Новые станции появляются сверху списка в истории с задержкой](https://drive.google.com/file/d/1AXV0rPabxmZofCUy84iapHlsPGVm8w27/view?usp=drive_link) |
| BUG14 | [При первом запуске приложение не запрашивает права доступа](https://drive.google.com/file/d/110o1IHDu8AP1AnZzGu2GMuWIbn8aItR1/view?usp=drive_link) |

---

## 🚀 Выводы  

- Найдено **19 дефектов**, включая **5 критических** и **2 высоких**.  
- Критические ошибки не затрагивают основные пользовательские сценарии.  
- Приложение стабильно при стандартных операциях, но нуждается в исправлении ряда ошибок.  
- После исправления критических багов рекомендуется провести **повторное регрессионное тестирование**.

---

## ✅ Рекомендации  

1. Исправить **вылеты приложения** при сложных маршрутах.  
2. Проверить корректность **восстановления карты** после возврата из истории.  
3. Исправить работу **функции “Обратная связь”** и **лонг-тапа**.  
4. Доработать **сохранение истории маршрутов и последнего выбора**.  
5. После фиксов выполнить smoke и **полный регрессионный прогон**. 

---

## 👤 Автор  

**Давид Гаргулия**  
QA Engineer | 32-я когорта, Яндекс Практикум  
Функциональное тестирование, тест-дизайн, баг-репорты  
📅 2025 год

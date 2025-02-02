---
title: "Установка сертификата вручную"
reference_version: ce212a2b8afebbee759407bcc26e46a5
---
Если у вас есть проблемы подключения к Akatsuki или переключатель устанавливает сертификат неправильно, вы можете попробовать скачать его вручную.

### Инструкция
- Сначала скачайте сертификат [нажмите сюда](https://old.akatsuki.pw/akatsuki.crt)
- Потом откройте **certificate.cer**
- Нажмите **Установить сертификат...**
- Нажмите **Локальный компьютер, Далее*
- Выберите **Поместить все сертификаты в следующее хранилище** (вторая опция), и нажмите  **Обзор...**
- Появится новое окно, выберите **Доверенные корневые центры сертификации** и нажмите **Ок**
- Нажмите **Далее**
- Нажмите **Готово**

### Если что то еще ломается...
...вы можете попробовать убрать все существующие сертификаты Akatsuki и установить сертификат опять. Следуйте этой инструкции:

- Нажмите **Win+R**  
- Напишите `mmc certmgr.msc` в окне и нажмите **enter** что бы открыть Менеждер сертификатов  
- Выберите **Доверенные корневые центры сертификации** слева   
- Выберите **Сертификаты** справа  
- Вы должны увидеть **[Akatsuki](https://onii-chan-please.come-inside.me/2020-05-05_10-02-46.png)** и **\*.ppy.sh** В списке. Выберите их, **Правая кнопка мыши** и нажмите на **Удалить**  
- Выберите все положительные варианты (Ок/Да и т.д.)  
- Перезапустите переключатель, нажмите на **Inspect**, потом выберите **Install certificate**, потом **Yes**  
- Нажмите на **Test Akatsuki connection** и вы должны увидеть "OK" на каждом столбце  
**Если во вкладке inspect все хорошо, но вы все еще не можете подключиться к Akatsuki в игре, попробуйте запустить osu! как администратор**.

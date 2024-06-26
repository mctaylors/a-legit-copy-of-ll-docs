---
description: О технической поддержке пользователей с читами
---
# Читы
:::info[Разработчики Legacy Launcher не одобряют использование читов]
:::

## У вас лаунчер для читеров? {#cheat-launcher}
Нет. Мы на этом не специализируемся. То, что в нашем лаунчере могут работать читы - это лишь следствие того, что лаунчер поддерживает любую версию, способную к запуску в лицензионном лаунчере. **Мы не одобряем читерство и не оказываем поддержку с крашами читов**.

## Сервер нашел читы в вашем лаунчере и забанил меня! {#cheats-in-launcher}
**Лаунчер сам по себе не содержит читов.** Если в вашей папке игры были найдены файлы читов - значит, когда-то вы (или другой пользователь вашего ПК) их скачали самостоятельно.  
Помните - удаление чита из папки `versions` не удалит все файлы чита целиком. Хотите быть уверены в чистоте папки игры? Сохраните миры и переустановите игру целиком, с удалением папки игры.

## Не могу запустить чит, лаунчер не может скачать файлы! {#download-errors}
Эта проблема актуальна для любой сторонней версии.  
Лаунчеру нужно откуда-то скачать файлы. Если автор версии не озаботился предоставлением работоспособных ссылок на файлы, лаунчер эти файлы скачать не сможет. **При возникновении подобных проблем обращайтесь к автору версии.**

## Не запускается чит без `-noverify`! {#nevorifly}
Невозможность запуска версии без `-noverify` говорит о некорректно проведенных модификациях. Подобная версия, даже если её удастся запустить, будет работать крайне нестабильно. **Не используйте версии, требующие их запуск с `-noverify`, не запускайте обычные версии игры с этим аргументом - это может привести к непредсказуемым последствиям.**

## Чит крашится во время игры! {#crash}
Если вы проигнорировали данный пункт и всё же запустили заведомо неработоспособную версию с `-noverify` - то это ожидаемо. Вам не поможет даже сам "автор" чита, т.к. он явно ничего не понимает в программировании на Java.
В иных случаях - **обращайтесь к автору чита, только он сможет понять, по какой причине случился краш**. Мы же, со своей стороны, можем порекомендовать только удалить читы и играть с немодифицированной версии игры.
:::warning[Обратите внимание!]
Ни в Minecraft, ни в Legacy Launcher, ни в Java **нет античитов**. Опция `-noverify` отвечает не за их отключение, а за отключение проверок исполняемого кода на **корректность и работоспособность**.
:::

## Но мне сказали, что это проблема в лаунчере! {#launcher-problem}
Если автор чита действительно так считает - то мы ждем его обращения к нам с убедительными доказательствами. К сожалению, на данный момент, подобных случаев в нашей практике не было.

## Но почему вы не можете мне помочь? {#why-no-help}
Потому что мы не имеем данных для идентификации причины краша. Всё, что мы видим со своей стороны - "ну, оно не работает". **Информацию для расшифровки краша имеет только автор чита.**

## Но в моей версии нет читов! {#i-am-trying-to-fool-you}
При диагностике ошибки мы не смотрим на названия версии и модов. Если мы находим характерные для читов файлы и техники (использование нестандартных библиотек, твикеров и агентов; обфускация кода; сокрытие или фальсификация имени модификации) - то мы считаем подобные модификации читами и не оказываем техподдержку по вышеописанным причинам. *Под подобные условия попадает большинство читов, "софтов" и "визуалов"*. **При любых крашах подобных модификаций обращайтесь только и только к их авторам.**
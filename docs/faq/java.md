---
description: Инструкция по установке Java
---
# Установка Java

Для запуска [jar-версии](https://llaun.ch/jar), [бета-версии](https://llaun.ch/latest) Legacy Launcher и многих установщиков модов вам потребуется установить Java.
:::tip[Проверка наличия Java]
Проверить наличие установленной Java и её версию можно, открыв Терминал (поищите в "Пуске" командную строку) и выполнив в нем команду `java -version`
:::
:::danger[Java для Minecraft]
Вам не обязательно устанавливать все версии Java вручную. Legacy Launcher будет автоматически скачивать и использовать рекомендуемые Mojang версии Java для запуска игры
:::

## Windows
1. Скачайте установщик Java с сайта [Temurin](https://adoptium.net/temurin/releases/?package=jre) или [Oracle](https://www.java.com/download/)
2. Запустите скачанный файл двойным кликом
3. Следуйте инструкциям
4. Готово!
    :::tip[Вместо запуска jar-файла открывается архив с файлами?]
    Нажмите правой кнопкой мыши по jar-файлу, выберите "открыть с помощью" => "OpenJDK" или "Java"
    ![Выберите "открыть с помощью" и найдите там Java](/img/win11-openwith-java.png)
    :::
    :::danger[Обратите внимание!]
    Если после установки Java по двойному клику на jar-файл ничего не происходит, возможно, вам потребуется помощь программы [JarFix](https://johann.loefflmann.net/downloads/jarfix.exe) для восстановления ассоциаций файлов
    :::

## Linux
Обратитесь к документации вашего дистрибутива.  
Ниже перечислены команды для установки Java на самых популярных дистрибутивах:
* Ubuntu, Mint, Debian и подобные: `apt install openjdk-17-jre`
* CentOS, Fedora и подобные: `yum install java-17-openjdk`
* Arch Linux, Manjaro и подобные: `pacman -S jre-openjdk`

Для запуска jar-файлов двойным кликом вам может потребоваться создать следующий файл:
```dekstop title="/usr/share/applications/jre-openjdk.desktop"
[Desktop Entry]
Name=OpenJDK Default Java Runtime
Comment=OpenJDK Default Java Runtime
Keywords=java;runtime
Exec=java -jar
Terminal=false
Type=Application
Icon=java
MimeType=application/x-java-archive;application/java-archive;application/x-jar;
NoDisplay=true
```

## macOS
:::danger[WIP]
Данный раздел находится в разработке
:::
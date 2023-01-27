# winget-soft

Cmd скрипт для установки набора софта в Windows с использованием winget.

## Как использовать
1. Скачать и распаковать содержимое репозитория.
2. Внутри папки winget-soft открыть Командную строку от имени администратора.
3. Выполнить `install.cmd`.

## Что делает скрипт
1. Удаляет Кортану.
2. Обновляет весь уже установленный софт (если для него присутствует пакет в winget).
3. Устанавливает runtime библиотеки и программы:
   - VC Redistributable 2005-2008-2010-2012-2013-2015+.
   - .Net Framework 3.1-5-6-7
   - Skype
   - Google Chrome
   - 7-zip
   - Adobe Acrobat Reader
   - FastStone Image Viewer
   - Daum PotPlayer
   - Unchecky

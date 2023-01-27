# winget-soft

Cmd скрипт для установки набора софта в Windows с использованием winget.

Как использовать:
- Скачать и распаковать содержимое репозитория.
- Внутри папки winget-soft открыть Командную строку от имени администратора.
- Выполнить `install.cmd`.

Что делает скрипт:
- Удаляет Кортану.
- Обновляет весь уже установленный софт (если для него присутствует пакет в winget).
- Устанавливает runtime библиотеки VC Redistributable 2005-2008-2010-2012-2013-2015+.
- Устанавливает runtime библиотеки .Net Framework 3.1-5-6-7
- Устанавливает набор программ: Skype, Google Chrome, 7-zip, Adobe Acrobat Reader, FastStone Image Viewer, Daum PotPlayer, Unchecky.

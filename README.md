# Obfuscate-BATCH-file
(RU) Скрипт запутывает код пакетных файлов windows.
Автор не несет ответственности за любые последствия в результате установки и использования данного скрипта, пользователь использует его "как есть" на свой страх и риск.

(EN) The script obfuscates the code of windows batch files.
The author is not responsible for any consequences as a result of the installation and use of this script, the user uses it "as is" at his own peril and risk.

----

**Usage:**

Открыть obfuscate.html в браузере, вставить код из Batch файла, который необходимо "обфусцировать", в "Source DATA", например:
```cmd
  net user
```
затем нажимаем "Run" и на выходе в "Obfuscate DATA" получим "запутанный" код:
```cmd
  @set nr=@set
  %nr% re= enrstu
  %re:~2,1%%re:~1,1%%re:~5,1%%re:~0,1%%re:~6,1%%re:~4,1%%re:~1,1%%re:~3,1%
```

# Установка софта

## Установка Node.js

Переходим по ссылке: https://nodejs.org/en/download/current/  
Выбираем нужную ОС и формат:  
![alt text](img/setup_nodejs_win_001.png "Node.js download page")  

### Установка под Windows

Нажимаем на 32 или 64 битный установщик (.msi) в зависимости от вашей системы. После скачивания файла установщика запускаем его.  
Нажимаем Next:  
![alt text](img/setup_nodejs_win_002.png "Welcome to setup wizard")  
Отмечаем что согласны с условиями лицензии:  
![alt text](img/setup_nodejs_win_003.png "End-User License Agreement")  
Выбираем путь куда буде установлен Node.js:  
![alt text](img/setup_nodejs_win_004.png "Node.js install destination folder")  
Настройки оставляем по умолчанию:  
![alt text](img/setup_nodejs_win_005.png "Custom setup")  
Нажимаем Install:  
![alt text](img/setup_nodejs_win_006.png "Ready to install")  
Ждем пока Node.js установиться о чем нам сообщит следующие окно:
![alt text](img/setup_nodejs_win_007.png "Completed install")  
Нажимаем Finish.  
Установка завершенна. Поздравляю!  
Проверим или все установилось правильно. Запускаем окно командной строки (Command prompt). Для этого зажав кнопку WIN нажимаем кнопку R. В открывшемся окне пишем ***cmd*** и нажимаем OK.  
![alt text](img/setup_nodejs_win_008.png "Run window")  
В открывшемся окне пишем команду ***node –v*** нажимаем Enter. На экране должна отобразиться версия установленного Node.js:  
![alt text](img/setup_nodejs_win_009.png "Command prompt")  

## Установка Git

Переходим по ссылке: https://git-scm.com/downloads  
Выбираем нужную ОС и формат:  
![alt text](img/setup_git_win_001.png "Git download page")  

### Установка под Windows

Читамьем условия лицензии, и нажимаем Next:..
![alt text](img/setup_git_win_002.png "GNU General Public License")  
Отмечаем все пункты в настройках (создание иконки на рабочем столе, интеграция с проводником, установка программы по умолчанию для файлов с расширением .git, .sh), нажимаем Next:  
![alt text](img/setup_git_win_003.png "Select components")  
Оставлям настройку по умолчанию (команда git будет доступна в окне командной строки), нажимаем Next:  
![alt text](img/setup_git_win_004.png "git PATH setup")  
Оставлям настройку по умолчанию (настройка символа конца строки при checkout и commit), нажимаем Next:  
![alt text](img/setup_git_win_005.png "setup line ending conversion")  
Оставлям настройку по умолчанию (настройка эмулятора терминалного окна), нажимаем Next:  
![alt text](img/setup_git_win_006.png "configure terminal emulator")  
Оставлям настройку по умолчанию (дополнительные настройки кэширования и доступа), нажимаем Install:  
![alt text](img/setup_git_win_007.png "extra options")  
Ждем пока истановка завершится. Отмечаем первую опцию (запуск терминала Git Bash), нажимаем: Finish:  
![alt text](img/setup_git_win_008.png "complete installation")  
Должно запуститься терминальное окно. Набираем команду ***git --version***. Если все прошло успешно, то отобразиться установленная версия Git:  
![alt text](img/setup_git_win_009.png "check git version in teminal")  
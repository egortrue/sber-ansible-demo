# Ansible + Jenkins в Sber
Базовый уровень
1. Напиши плейбук в ansible, который установит и настроит nginx (используй 2 вируталки, она одном запускается ansible, на ansible будет устанавливать nginx)
2. Плейбук должен при изменении конфига nginx подкладывать и давать команду на перечитку конфига
3. Настрой связку nginx и php-fpm и подложи простой пример странички на php с hello world. Пример странички можно найти в интернете.
 

Бонусное задание
1. Создай гит репо в котором сохрани файлы из первого задания
2. Подними Jenkins (в контейнере или установи на витруалку)
3. Напиши jenkinsfile в котором джоба должна брать файлы из гита и запускать плейбук из первого задания
3. В Jenkins создай multibranch pipeline job и настрой на работу с гит
4. Отпачкуй новую ветку в гите, где поменяй содержимое веб страницы и пересканируй ветки из multibranch pipeline и проверь, что ветки публикуют разные страницы

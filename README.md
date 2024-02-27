# homework1
hw about docker and compose netology SHDEVOPS-4

# Задача 1
https://hub.docker.com/repository/docker/kosschuk/custom-nginx/general

# Задача 2
Порт 8081 указан по причине того, что на этой машине занят порт 8080 по личной необходимости
![image](https://github.com/Shchu4ka/homework1/assets/29621873/bd7e7115-1ad3-40f7-869d-8f00fe2aa572)

# Задача 3
1) Мы отправили сигнал о прерывании системных процессов нажатием Ctrl-C и система аварийно завершилась
   ![image](https://github.com/Shchu4ka/homework1/assets/29621873/38364fab-34ad-4069-a8ee-84377fdde100)
2) Мы переназначили порт, который nginx слушает на вход, в докере же маппинг остался прежним
   ![image](https://github.com/Shchu4ka/homework1/assets/29621873/088f31b6-d5cb-49e5-b4c3-231f13552071)
3) Для удаления используем ключ -f --force
   ![image](https://github.com/Shchu4ka/homework1/assets/29621873/58e2ad93-a589-40f5-bf61-5575d7891f89)

# Задача 4
![image](https://github.com/Shchu4ka/homework1/assets/29621873/43313080-4820-467c-ad26-76807397b103)

# Задача 5
1) Спецификация docker-compose подразумевает предпочтение файла compose.yaml, он запускается первее всех
2) Нужно добавить директиву включения одного файла в другой
```
   include:
     - docker-compose.yaml
```
3) ![image](https://github.com/Shchu4ka/homework1/assets/29621873/df7ea47e-581c-4341-b50f-86e8fe9bbc61)
6) ![image](https://github.com/Shchu4ka/homework1/assets/29621873/2c40eeb7-e400-40a8-be0c-0681b5742d0e)
7) Предупреждение говорит о том, что у нас в проекте есть контейнер, не описанный в маниестах, флаг --remove-orphans позволяет его удалить
![image](https://github.com/Shchu4ka/homework1/assets/29621873/67b7b537-96ad-4209-ba17-ed6ae147dcb7)
![image](https://github.com/Shchu4ka/homework1/assets/29621873/904f8c24-3c11-4455-b878-0db909bd20d5)


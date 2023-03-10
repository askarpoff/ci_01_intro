# ci_01_intro
# Домашнее задание к занятию 7 «Жизненный цикл ПО»

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.
![image](https://user-images.githubusercontent.com/108946489/224374440-176cafd8-0cc9-458c-a65c-015cbc395916.png)

Остальные задачи должны проходить по упрощённому workflow:
1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.
![image](https://user-images.githubusercontent.com/108946489/224374712-d4f7ad22-f440-4b57-af37-ebb68c8cee02.png)


1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done. 
![image](https://user-images.githubusercontent.com/108946489/224373561-e98341cd-bbb4-4a67-912c-2b6a37cb87fe.png)

2. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done. 
![image](https://user-images.githubusercontent.com/108946489/224373659-9e682cf5-3e38-46fa-9c34-2ca3bd166d82.png)

3. При проведении обеих задач по статусам используйте kanban. 
4. Верните задачи в статус Open.
5. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.
![image](https://user-images.githubusercontent.com/108946489/224373992-3929b6e0-96e1-40fe-9c03-e5a00b949d17.png)

6. Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow приложите к решению задания.
https://github.com/askarpoff/ci_01_intro/blob/main/COMMON.xml
https://github.com/askarpoff/ci_01_intro/blob/main/BUG.xml


---

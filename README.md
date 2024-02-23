# Checklist of homework

1. Создать публичный гит-репозиторий с названием %NAME%_%GROUP% , где %NAME% - латиницей фамилия и первая буква имени, например, LookichevD или FomichevA; %GROUP% - номер вашей учебной группы, например, LookichevDGUN27 или FomichevA_GUN29

###### Выполнено. Создан публичный репозитарий SergienkoM_GUN29

2. Клонировать созданный репозиторий на компьютер,

###### Выполнено. Репозитарий клонирован на локальный диск.

3. Создать пустой 3D проект в локальном репозитории.

###### Выполнено. Создан проект TanksPrototype.

4. Скачать Unity-пакет прототипа Танка TankPackage.unitypackage

###### Выполнено. Пакет загружен.

5. Распаковать Unity-пакет прототипа Танка в созданный ранее пустой 3D проект в локальном репозитории

###### Выполнено. Пакет импортирован в проект.

6. Провести донастройку (установка пакетов InputSystem, Cinemachine, настройка физических слоев), как показывал преподаватель в занятии

###### Выполнено. Установлены пакеты InputSystem, Cinemachine. Созданы слои: Projectiles, Obstacles, Ground, Players, PostProcessing. Настроено взаимодействие слоев.

7. Собрать сцену, в которой:
7.1. Пол и простое освещение;

###### Выполнено. Добавлена префаб трассы с Mash Collider.

7.2. Располагается собранный и настроенный танк;

###### Выполнено. Добавлен WheelCollider. Добавлен скрипт Wheel на колеса, скрипты присвоены коллайдеры и Трансформ колес. Добавлен префаб Installer.

7.3. Танк использует для управления компонент Test Input Controller;

###### Выполнено. Добавлен скрипт Test Input Controller, Добавлен и настроен скрипт Tank Controller

7.4. Несколько настроенных кубиков;

###### Выполнено. Созданы и добавлены на сцену зеленый и красный блоки кубиков

8. При запуске игры танк должен автоматически ехать вперед и затем врезаться в кубики. После этого симуляцию можно останавливать.

###### Выполнено. Танк едет и сталкивается с кубиками.
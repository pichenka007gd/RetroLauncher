# Plugins:

- AutoSaveWorld
- bPermissions
- [ChestShop](plugins/chestshop.md)
- [CleanPing](plugins/cleanping.md)
- ClearLag
- CS-CoreLib
- Dynmap-WorldGuard-0.80
- gMoney
- GriefLog
- GriefPreventionData
- HomeSpawnPlus
- JPanel
- LoginSecurity
- LootCrates
- Playtimes
- PluginMetrics
- ServerSigns
- Shopkeepers
- SimpleAutoRestart
- [TPA](plugins/tpa.md)
- Vault
- [WorldEdit](plugins/worldedit.md)
- [WorldGuard](plugins/worldguard.md)

---

### MODS ###

- AdvancedSolarPanel
- ae2stuff
- appliedenergistics2
- bdlib
- BeeBetterAtBees
- BetterFps
- BetterLoadingScreen
- BetterPingDisplay
- BetterQuesting
- ChickenChunks
- CodeChickenCore
- CodeChickenLib
- CraftTweaker
- Dynmap
- excompressum
- Ex-Nihilo
- extrautilities
- forestry
- GlibysVC
- Goki_Stats
- industrialcraft
- ironchest
- Mantle
- MineTweakerRecipeMaker
- Morpheus
- MultiMine
- neiaddons
- NotEnoughItems
- Reliquary
- Ruins
- +unimixins-all
- UpdateCheckerMod
- Xaeros_Minimap





### ClearLag ###

Default

» /lagg check • Узнать состояние сервера
» /lagg tps   • Показывает среднее время тика сервера
» /lagg chunk • Ищет лагающие чанки

Admin

» /lagg clear        • Удаляет сущности из ващего мира
» /lagg area <count> • Удаляет сущности в радиусе
» /lagg check        • Считает кол-во сущностей в вашем мире
» /lagg gc           • Запрос сборщика мусора
» /lagg killmobs     • Удаляет мобов из вашего мира
» /lagg tpchunk      • Телепорт в загруженные чанки
» /lagg unloadchunks • Выгружает неиспользуемые чанки
» /lagg halt         • Останавливает большую часть активности сервера
» /lagg admin        • Настройка модулей Clearlag
» /lagg checkchunk   • Показывает сущности в чанке
» /lagg sampleticks  • Сэмплы тиков чанков
» /lagg memory       • Узнать состояние памяти

### gMoney ###

Внимание!
Чтобы пользоватся плагином нужно создать аккаунт
Для этого нужно хотябы один раз использовать команду баланса:
» /m, /money, /eco, /coins, /cash, /tokens, /pich

Default

» /money                      • Создайте учетную запись или проверьте свои деньги
» /money <player>             • Посмотрите деньги игрока
» /money pay <player> <count> • Отправьте деньги игроку
» /money top                  • Смотрите 5 самых богатых игроков
» /money help                 • Все Команды И Ваше Описание

Admin

» /money give <player> <count> • Добавляет деньги к балансу игрока
» /money set <player> <count>  • Устанавливает баланс игрока
» /money reset <player>        • Сбрасывает учетную запись игрока
» /money converter <plugin>    • Конвертирует плагины из economy в money economy
» /money permissions           • Просмотрите все разрешения

### GriefLog ###

Плагин собирает тотальную статистику о каждом вашем шаге)

• Когда игрок присоединяется к серверу
• Когда игрок разбивает блок
• Когда игрок ставит блок
• Когда игрок использует команду
• Когда игрок меняет мир, в котором он находится
• Когда игрок покидает сервер
• Если блок воспламеняется
• Если ведро опорожнено
• Если Эндермен берет или ставит блок
• Если Зомби выломает дверь
• Если произойдет какой- либо взрыв

И я проверю каждый ваш, ЧЕРТ ВОЗЬМИ, подозрительно поставленный блок
+ сверху намажу плагин на автоматический бан гриферов

Вы все на лодони поэтому: мир, дружба, жвачка ;D

Default

» /glog report • это позволит администраторам сообщить о проблеме. Используйте для любой связи с администраторами

Admin

» /glog report view     • администраторы могут просматривать информацию об репорте проблемы. В нём отображается местоположение отчёта и автор
» /glog help            • это выведет ту же информацию, которую вы видите здесь, но в вашем клиенте Minecraft
» /glog tool            • это инструмент GriefLog. Вы можете настроить инструмент в файле config.yml
» /glog rollback <args> • чтобы использовать откат, пожалуйста, прочтите раздел нашей wiki здесь
» /glog search <args>   • вы можете искать определённые события. Параметры те же, что и при отмене
» /glog page  <id>      • это позволит вам просмотреть другие страницы вашего последнего поиска
» /glog undo <id>       • это отменит откат, связанный с идентификатором. Не указывайте номер, чтобы отменить последний откат

### GriefPrevention ###

там 101 команда
потом настрою



### HomeSpawnPlus ###

жирный плагин домов

Default

» /hsp
» /spawn
» /spawnlist
» /home
» /homelist
» /sethome
» /homerename
» /homedelete
» /homeinvite
» /homeinviteaccept
» /homeinvitedelete
» /homeinvitelist
» /homeinviteteleport


Admin

» /customeventcommand
» /groupquery
» /groupspawn
» /homedeleteother
» /homeinvite
» /homeinviteaccept
» /homeinvitedelete
» /homeinvitelist
» /homeinviteteleport
» /homelistother
» /homeother
» /hspconvert
» /hspdebug
» /permcheck
» /setdefaulthome
» /setdefaultspawn
» /setfirstspawn
» /setgroupspawn
» /sethomeother
» /setmapspawn
» /setplayerspawn
» /setspawn
» /showplayerspawn
» /spawndelete
» /spawnrename

### LoginSecurity ###

Ну как же без регистрации

Время для регистрации: 60 сек
Время сессии: 300 сек (если вы вышли с сервера, то вы можете зайти на него без ввода пароля в течении времени сессии)

Default

» /register <pass>                  • Установите свой пароль
» /login <pass>                     • Войдите используя свой пароль
» /changepass <old pass> <new pass> • Измените свой пароль
» /logout                           • Удалить аккаунт

Admin

» /lac rmpass <player> • Удалить пароль (аккаунт?) игрока
» /lac reload          • Перезагрузка плагина

### LuckPerms ###

Это никому не нужно)

### ServerSigns ###

Инструмент для кастомных механик и тд
Что нибудь сделаю XD

ServerSigns (SVS) позволяет привязывать команды, сообщения и действия, отправляемые игроками и сервером, к знакам и любым другим блокам в Minecraft

Как только игрок нажимает на ServerSign, настроенные действия выполняются в указанном вами порядке и с заданными вами настройками

Без ограничений: Неограниченное количество команд для каждого сервера
Многофункциональность: назначайте различные действия при нажатии на значок (даже определяйте разные команды для нажатия правой/левой кнопкой мыши)
Сообщения: Отправлять сообщения игроку
Широковещательные рассылки: Отправка сообщений на весь сервер
Команды для игроков: Выполняет команды так, как если бы игрок ввёл их в чате
Команды сервера: Выполняет команды так, как если бы они были выполнены с консоли сервера
Отложенные действия: любое действие может быть отложено (от нескольких секунд до нескольких месяцев)
Циклические действия: любой ServerSign можно преобразовать в циклические команды сервера с заданными интервалами
Требуются разрешения: для использования ServerSigns могут потребоваться разрешения
Предоставить разрешения: Предоставляет игрокам временные разрешения на выполнение команд
Стоимость за каждый знак: привяжите опыт, деньги и стоимость предметов к ServerSigns
Защищено: Автоматически защищает каждый серверный знак и любые подключенные блоки
Базовый сценарий: реализуйте операторы if/else и return в командах на ServerSigns

если он конечно работает

### Shopkeepers ###

Плагин для создания NPC обменников
Если ChestShop инструмент для экономики сервера через валюту сервера, то Shopkeepers для обмена предметов на предметы

### SimpleAutoRestart ###

Рестартит сервер, пугает игроков)

/simpleautorestart /sar /autorestart - алиасы

Admin

» /sar cancel • Остановить рестарты
» /sar resume • Продолжить рестатры
» /sar status • Состояние рестартов

### Vault ###

Плагин экономики. Настоящие герои не носят плащи...

Default

» /vault-info • Информация



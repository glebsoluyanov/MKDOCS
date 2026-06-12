# BuilderCmd PTS С1
`//bbs` - открывает html c bypass '_agitmaid' и '_agitdealer'

---
`//setskill [skill id] [level]` - добавить скилл цели   
пример ответа:   
> SYS: set skill for (Lemar : root) ( 10:1 )

---
`//serverstat` - информация о сервере и времени работы   
пример ответа:   
> SYS: Server Build date : Jun 8 2004 15:39:32 Protocol Version : 419 World Time : 16:07   
> SYS: Elapsed Time : O days 0 hours 31 minutes 22 seconds

---
`//create_pet 1~3` - создает питомца *(1 - Wolf Collar, 2 - Dragonflute of Wind, 3 - Dragonflute of Star, 4 - Dragonflute of Twilight)*

---
`//closeauth` -

---
`//eventview` - тут нет реализации   
пример ответа:   
> SYS: No Event

---
`//event` - тут нет реализации   
пример ответа:   
> SYS: No Event

---
`//delskill [skill id]`  - удалить скилл цели   
пример ответа:   
> SYS: delete skill for (Lemar : root) ( 10:1 )

---
`//who` - информация об онлайне   
пример ответа:   
> SYS: current(1), playing(1), private store(0), max(1)

---
`//addbookmark [bookmark name]` - добавить закладку телепорта

---
`//delbookmark [bookmark name]` - удалить закладку телепорта

---
`//telbookmark [bookmark name]` - телепортироваться по указанной закладке

---
`//partytel [bookmark name]` - 

---
`//getbookmark` - список сохраненных закладок телепортов   
пример ответа:   
> SYS: ,dion,giran,aden

---
`//reset_npc_db` - 

---
`//setquest [quest id] [state]` -

---
`//delquest [quest id]` -

---
`//killme` -

---
`//home` - телепортирует в точку -86055, 240921, -3726 (северозападные ворота деревни людей)

---
`//setai` -

---
`//viewpn` - "раскидывает" стрелы на земле по узлам pathNode

---
`//gotopn [node id]` - отправляет персонажа к указанной pathNode

---
`//qmove` - *l2server критует, возможно нужны аргументы*

---
`//setkarma` - 

---
`//setclass` -

---
`//ping` - показывает задержку сохранения, задержка БД и т.д.   
пример ответа: 
> SYS: 1 Ping [0]sec Start   
> SYS: 2 Ping [0]sec db send   
> SYS: 4 Ping [0]m cache thread wait   
> SYS: 5 Ping [1]sec find user   
> SYS: 6 Ping [1]sec save user   
> SYS: 7 Ping [1]sec save item   
> SYS: 8 Ping [1]sec send to server   
> SYS: 9 Ping [0]sec return to server   
> SYS: 10 Ping [0]sec ping end   

---
`//netping` - показывает сетевой roundtrip L2Server→CacheD→L2Server
пример ответа: 
> SYS: Main to Cache network Ping [0]millisec   
> SYS: Cache thread wait [0]millisec   

---
`//dropping` -   
пример ответа: 
> SYS: 1 Ping [O]sec Start   
> SYS: 2 Ping [O]sec db send   
> SYS: 3 Ping [O]m cache thread wait   
> SYS: 4 Ping [1]sec cache process start   
> SYS: 5 Ping [1]sec before drop   
> SYS: 6 Ping [1]sec send to main   
> SYS: 7 Ping [O]sec main receive   
> SYS: 8 Ping [0]sec ping end

---
`//petans` -  
`CPetitionCli::NotifyGmChat`

---
`//endpet` -   
`CPetitionCli::ReqPetitionChatEnd`
пример ответа:    
> SYS: Cannot connect to petition server.    
> SYS: Currently there are no users that have checked out a GM ID.   
> SYS: Request confirmed to end consultation at petition server.   

---
`//startpet` -   
`CPetitionCli::ReqPetitionChatStart`
пример ответа: 
> SYS: Cannot connect to petition server.
> SYS: Currently there are no users that have checked out a GM ID.
> SYS: The client is not logged onto the game server.
> SYS: Request confirmed to begin consultation at petition server.
> SYS: 

---
`//leavepetimsg [username] [msg]` -    

---
`//castleincome [castle_id]`
пример ответа: 
> SYS: id[1] : tax income[161890]/[59861], Crop income[0]   
> SYS: id[2] : tax income[0]/[o], Crop income[o]   
> SYS: id[3] : tax income[o]/[o], Crop income[o]   
> SYS: id[4] : tax income[o]/[o], Crop income[o]   
> SYS: id[5] : tax income[69380]/[25653], Crop income[0]   

---
`//updatecastleincome [castle_id] [income]` -   

---
`//setcastleincome [id] [0..1] [1..2] [0..100000000]`-   
пример ответа:
> SYS: tax income[0], Crop income[0]

---
`//settax [0..100]` -   
пример ответа:   
> SYS: tax rate[15]

---
`//servername` - показывает имя сервера   
пример ответа:   
> SYS: Lineage2

---
`//announce [msg]` - отправить сообщение анонсом
> Announcements: HELLO

---
`//set_interval_announce` - Показать текущий список анонсов
`//set_interval_announce` - посмотреть список   
`//set_interval_announce start` - остановить таймер   
`//set_interval_announce add 60 1 Добро пожаловать на сервер!`      
`//set_interval_announce add 60 2 Голосуйте за нас!`
`//set_interval_announce del 60 3`
`//set_interval_announce end` - запустить\перезапустить + reload
`//set_interval_announce reload` - загрузить из БД   
Слоты аннонсов 1  2  3  4  5 (Строго 1 <= id <= 5)   
Интервал минуты 10  20  30  40  50  60  120  240  360   

---
`//setannounce [ANNOUNCE_ID] [interval] [ANNOUNCE_MESSAGE]`

---
`//delannounce [ANNOUNCE_ID]` -   

---
`//infectedskill` -   
пример ответа:    
> Skill: infected skills : total 0
---
`//skillmod` -   

---
`//diet [on|off]` -   
пример ответа:   
> Currently, you are on diet mode.   
> Currently, you are not on diet mode..   
> Diet mode off.   
> Diet mode on.

---
`//undying [on|off]` - вкл\выкл бессмертие   
пример ответа:   
> SYS: Now, you cannot die.   
> SYS: Currently, you cannot die.   
> SYS: Currently, you can die.   

---
`//hide [on|off]` - вкл\выкл невидимость   
пример ответа:   
> SYS: Now, you cannot be seen.   
> SYS: Currently, you cannot be seen.   
> SYS: Currently, you can be seen.

---
`//gmspeed [0..5]` - увеличить скорость бега 0-5   
пример ответа:   
> SYS: Your speed is [150]% fast

---
`//whisper [on|off]` -   
> Message refusal mode.   
> Message acceptance mode.   

---
`//summonnpc [Object id|Object name] [number]` -   

---
`//social [num]` -   

---
`//set_siege() castle year mon day hour min` - 

---
`//set_quick_siege() castle sec` - 

---
`//play_music music_name` -   

---
`//debug_NPC` - 

---
`//set_freeze_field castle_name [on|off]` -   
> SYS: builder command[set_freeze_field] accepted   
> SYS: invalid castle name   

---
`//set_pausable castle_name [on|off]` -   
> SYS: builder command[set_pausable] accepted
> SYS: invalid castle name   

---
`//set_controltower_status control_tower_name [idle|dest|work|breakable|unbreakable]` -      
> SYS: invalid controltower name    
> SYS: invlaid controltower status   
> SYS: builder command[set_controltower_status] accepted   

---
`//auction_close [agit_name]` -   

---
`//auction_open agit_name` -   

---
`//actorcount` -   
> user[0], npc[45]   

---
`//ask_residence` -   
> SYS: residence type: [Castle], residence id: [2], residence name: [dion_castle]

---
`//set_siege_end castle year mon day hour min` -   

---
`//ask_now` -   
> SYS: Now: Fri Jun 12 02:07:02 2026

---
`//left_peti_chat [char]` -   

---
`//killnpc` - убить нпц

---
`//setparam [param] [value]` - изменить параметр например level, exp, sp, dex, int и тд.

---
`//set_siege_period(공성시간) castle sec` -   
> SYS: builder command[set_siege_period] accepted   

---
`//set_door_hp(문피) door hp` -   
> SYS: builder command[set_door_hp] accepted

---
`//addcomment COMMENT` -   

---
`//viewcomment` -   

---
`//time_limit char_name (Add | Del) min` -   
> SYS: Change time limit success

---
`//reset_time` -   

---
`//reset_respawn npc_db_name` -   

---
`//worlddebug` -   
> worlddebug: worlddata at (-86174, 241061) : index (6, 2)   
> worlddebug: -3728   

---
`//teleport x y [z]` - 
> SYS: invalid teleport position

---
`//summon [Object id|Object name] [number]` - призвать предмет в инвентарь

---
`//summon2 [enchanted] [Object id|Object name]` - призвать "заточенный" предмет в инвентарь

---
`//setonetimequest [quest id] [state]` -   
> SYS: set onetimequest for (Lemar : root) ( 1:1 )

---
`//croplist` - 

---
`//show_castle_door_hp castle` - просмотр hp дверей замка (gludio_castle, giran_castle и тд.)
> SYS: invalid castle   

> SYS: Door[gludio_castle_outter_001]: HP[316500], MaxHP[316500], BaseHP[316500]   
> SYS: Door[gludio_castle_outter_002]: HP[316500], MaxHP[316500], BaseHP[316500]   
> SYS: Door[gludio_castle_inner_001]: HP[158250], MaxHP[158250], BaseHP[158250]   
> SYS: Door[gludio_castle_inner_002]: HP[158250], MaxHP[158250], BaseHP[158250]  
> SYS: Door[gludio_castle_station]: HP[158250], MaxHP[158250], BaseHP[158250]   

---
`//set_skill_all` - выдать все доступные персонажу скилы

---
`//ride` - в c1 судя по всему не сделано еще
> SYS: //ride is blocked now :p

---
`//reset_skill` -   

---
`//healthy` - восстановить hp, mp

---
`//stopsay [CHAR_NAME] [STOP_MINUTE]` -

---
`//stoplogin [CHAR_NAME] [STOP_MINUTE]` -

---
`//cancelgmpeti [username]` -   

---
`//recall [CHAR_NAME]` - призвать персонажа к себе

---
`//sendhome [CHAR_NAME]` - отправить персонажа в город

---
`//teleportto [CHAR_NAME]` - телепортироваться к указанному персонажу

---
`//kick [CHAR_NAME]` - 

---
`//setbuilder [CHAR_NAME] [BUILDER_LEVEL]` -   

---
`//set_pledge_level pledge level` -

---
`//setarea area_name [on|off]` - 

---
`//cease_fire pledge1 pledge2` - имена кланов нужно указывать в нижнем регистре

---
`//cease_fire2 alliance1 alliance2` - имена альянсов нужно указывать в нижнем регистре

---
`//enable_plane_collision collisio_name 1/0` - 

---
`//mid_victory castle pledge` - 
> SYS: not in siege state

---
`//load_pledge pledge` -  
> SYS: builder command[load_pledge] accepted ... wait a while.   
> SYS: the pledge is already loaded

---
`//add_peti_chat char` -   

---
`//force_peti charname message` -   

---
`//gmchat charname message` - 

---
`//unregister castle pledge` - снять регистрацию клана на осаду
> SYS: builder command[unregister] accepted 
---
`//defend castle pledge` - регистрация клана на осаду на защиту
> SYS: builder command[defend] accepted   
> A clan that owns a castle cannot participate in
another siege.   

---
`//attack castle pledge` - регистрация клана на осаду на атаку
> SYS: builder command[attack] accepted   

---
`//time_info [char_name | .(target)]` - 

---
`//view_enemy_list pledge_name` - 

---
`//view_enemy_list2 alliance_name` - 

---
`//door_levelup [doorname|all] level(total%)` - 

---
`//controltower_levelup [controltower|all] level` - 

---
`//gmon` - ГМ режим
> SYS: Now, you cannot be seen.
> SYS: Now, you cannot die.   
> SYS: registered into GM list   
> SYS: Your speed is [150] fast   
> SYS: Diet mode on.   
> Message refusal mode.   
> SYS: builder command[friendaddoff] accepted   
> SYS: builder command[tradeaddoff] accepted   

---
`//gmliston` - регистрация в GM list
> SYS: Now, you can be seen.   
> SYS: registered into GM list   
---
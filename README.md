# gantiControls
This repo contains free controls to implement in Ganti. you'll have subdirectories by business application and by ganti domains.
So you'll have controls for business applications like Gold.
If you don't have Ganti, you can anyway use sql which is in json file

# Repository structure
## Ganti
### CommandManager
This dir will contain Ganti command controls :

- [GTI - Ganti symfony logs.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/CommandManager/GTI%20-%20Ganti%20symfony%20logs.json) : It display all symfony error messages (critical, error and warning) of the day (since 23.09.1 release)
- [GTI - change env level.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/CommandManager/GTI%20-%20change%20env%20level.json) : It allow to switch of env (prod to dev) (since 23.09.1 release)
  
### QueryManager
this dir will contain Ganti queries controls :

- [GTI : Datasources KO.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20Datasources%20KO.json) : It will check all datasources and display all KO datasources (since 23.06 release)
- [GTI - List controls where datasource param is used.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20List%20controls%20where%20datasource%20param%20is%20used.json) : it will list all controls used by a datasource filled by user via a param (since 23.04 release)
- [GTI - number of controls by schedule type.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20schedule%20type.json) : il will indicate the number of controls by schedule type. It takes in parameter number of retention days (since 23.06.1 release)
- [GTI - number of controls by type.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20type.json) : il will indicate the number of controls by type. It takes in parameter number of retention days
- [GTI - number of controls by user.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20user.json) : il will indicate the number of controls by user. It takes in parameter number of retention days
- [GTI - queries with last execution time.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20queries%20with%20last%20execution%20time.json) : il will display all queries with last execution time (since 23.09.1 release)
- [GTI - schedules of the day with execution infos](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20schedules%20of%20the%20day%20with%20execution%20infos.json) : it will display the schedules of the days with the execution informations. If the schedule has not been executed, it will display 'NOT YET EXECUTED' in launched_at column. Same logic if the control failed (since 23.09.1 release)
- [GTI - schedules sent to user.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20schedules%20sent%20to%20user.json) : it will display all schedules linked to a user (in case where a user is replaced or is in vacations)
- [GTI - controls summary.json](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20Control%20summary.json) : it will display your control stats with number of times where it generates an alert


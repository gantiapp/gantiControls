# 🛠️ gantiControls

This repository provides **free reusable controls** to implement in **Ganti**.  

You'll find controls organized by:
- **Business application** (e.g. *Gold*) - in progress
- **Ganti domains** (*CommandManager*, *QueryManager*, etc.)

> 💡 If you're not using Ganti, you can still benefit from the SQL queries stored in the `.json` files.

---

## 📁 Repository Structure

### 📂 Ganti

---

#### ⚙️ CommandManager

This directory contains Ganti **command controls**:

- 🔧 [GTI – Ganti Symfony Logs](https://github.com/gantiapp/gantiControls/blob/main/ganti/CommandManager/GTI%20-%20Ganti%20symfony%20logs.json)  
  Displays all Symfony error messages (*critical*, *error*, *warning*) of the day.  
  _Available since `23.09.1`_

- 🔄 [GTI – Change Env Level](https://github.com/gantiapp/gantiControls/blob/main/ganti/CommandManager/GTI%20-%20change%20env%20level.json)  
  Switch the environment between `prod` and `dev`.  
  _Available since `23.09.1`_

---

#### 📊 QueryManager

This directory contains Ganti **query controls**:

- 📈 [GTI – Controls Summary](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20Control%20summary.json)  
  Shows control statistics, including how many times each triggered an alert.

- 🧮 [GTI – Database Size Control](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20Database%20size%20control.json)  
  Monitors database size and alerts if a threshold is exceeded.

- ❌ [GTI – Datasources KO](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20Datasources%20KO.json)  
  Lists all datasources with KO status.  
  _Available since `23.06`_

- 🔍 [GTI – List Controls Using Datasource Param](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20List%20controls%20where%20datasource%20param%20is%20used.json)  
  Shows controls linked to a datasource set via a parameter.  
  _Available since `23.04`_

- 📅 [GTI – Number of Controls by Schedule Type](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20schedule%20type.json)  
  Lists number of controls by schedule type. Accepts a `retention days` parameter.  
  _Available since `23.06.1`_

- 🧩 [GTI – Number of Controls by Type](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20type.json)  
  Lists number of controls by type. Accepts a `retention days` parameter.

- 👤 [GTI – Number of Controls by User](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20number%20of%20controls%20by%20user.json)  
  Shows how many controls are linked to each user. Accepts a `retention days` parameter.

- ⏱️ [GTI – Queries with Last Execution Time](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20queries%20with%20last%20execution%20time.json)  
  Displays last execution times for all queries.  
  _Available since `23.09.1`_

- 📆 [GTI – Schedules of the Day with Execution Info](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20schedules%20of%20the%20day%20with%20execution%20infos.json)  
  Displays daily schedules with execution status. Includes `"NOT YET EXECUTED"` or `"FAILED"` where appropriate.  
  _Available since `23.09.1`_

- ❗ [GTI – Failed Schedules](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20failed%20schedules.json)  
  Lists all failed schedules of the day.  
  _Available since `25.04`_

- 📤 [GTI – Schedules Sent to User](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20schedules%20sent%20to%20user.json)  
  Shows schedules assigned to specific users (e.g. during replacements or vacations).

- 👥 [GTI – User Details](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20User%20details.json)  
  Lists user information: username, full name, email, creation date, roles, and permissions. Ordered by creation date.

- 🗂️ [GTI – Controls on Ganti DB with Old Menu](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20controls%20on%20Ganti%20db%20with%20old%20menu.json)  
  Lists controls still using the old Ganti menu format.  
  _Available since `25.01.0`_

- 🔡 [GTI – Controls on Ganti DB with OrderBy](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20controls%20on%20Ganti%20db%20with%20orderby.json)  
  Identifies controls using `ORDER BY` in SQL.  
  _Available since `25.01.0`_

- 🔍 [GTI – Table Name Index](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20table%20name%20index.json)  
  Displays all controls and schedules where a given table (via parameter) is used.  
  _Available since `24.10`_

- 🔍 [GTI - Search in controls](https://github.com/gantiapp/gantiControls/blob/main/ganti/QueryManager/GTI%20-%20search%20in%20controls.json)  
  Displays all controls and sql which contains a datasource and/or a table and/or a business object.  
  _Available since `24.10`_

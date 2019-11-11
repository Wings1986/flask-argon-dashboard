# [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon)

**[Open-Source Admin Dashboard](https://appseed.us/admin-dashboards/flask-dashboard-argon)** coded in **Flask Web Framework** on top of **Argon Dashboard** design, crafted by Creative-Tim agency. **Dashboard** features:

<br />

- SQLite database
- SQLAlchemy ORM
- Session-Based authentication flow (login, register)

<br />

![Flask Dashboard Argon - Open-Source Flask Dashboard.](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-argon-intro.gif)

<br />

## Build from sources

```bash
$ # clone the sources
$ git clone https://github.com/app-generator/flask-argon-dashboard.git
$ cd flask-argon-dashboard
$
$ # install modules using a virtualenv
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # install deps
$ pip install -r requirements.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix) export FLASK_APP=app.py
$ (Windows) set FLASK_APP=app.py
$ (Powershell) $env:FLASK_APP = ".\app.py"
$ 
$ # Create SQLite database using the Flask console
$ flask shell
>> from app import db
>> db.create_all()
>> quit()
$ # SQLite database.db should be created in the app folder:
$ # app\database.db
$
$ flask run
$ # app is running on port 5000
```

<br />

## Want more? Go PRO!

<br />

| [Flask Dashboard Material](https://appseed.us/admin-dashboards/flask-dashboard-material-pro) | [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro) | [Flask Dashboard Black](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) |
| --- | --- | --- |
| [![Flask Dashboard Material PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-material-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-material-pro)  | [![Flask Dashboard Argon PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-argon-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro) | [![Flask Dashboard Black PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-black-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-black-pro)

<br />

## Support
---

- Free support via eMail < [support @ appseed.us](https://appseed.us/support) > and [Github](https://github.com/app-generator/flask-argon-dashboard/issues/)
- 24/7 Live Support via [Discord](https://discord.gg/fZC6hup) for paid plans and commercial products.

<br />

## Resources

- [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon) - Product page
- [Flask Dashboard Argon](https://flask-argon-dashboard.appseed.us/) - Live DEMO
- [Flask Framework](https://www.palletsprojects.com/p/flask/) - The offcial website
- [Flask Dashboard - Open-Source Boilerplates](https://dev.to/sm0ke/flask-dashboard-open-source-boilerplates-dkg) - A popular article published on Dev.to platform
- [Flask Dashboard](https://admin-dashboards.com/tags/flask-dashboard) - Index provided by **Admin-Dashboards.com**

<br />

---
[Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon) provided by **AppSeed**

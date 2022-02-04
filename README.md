---
title: Grafana
description: A Grafana instance with a PostgreSQL database
tags:
  - postgresql
  - grafana
  - monitoring
  - observability
  - kubernetes
  - prometheus
---

## Grafana example

This example deploys self-hosted version of [Grafana](https://grafana.com). Internally it uses a PostgreSQL database to store the data.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new?template=https://github.com/yesoreyeram/grafana-railway-app-template&plugins=postgresql&envs=PORT,GF_SECURITY_ADMIN_PASSWORD,GF_DATABASE_SSL_MODE,GF_DATABASE_TYPE,GF_DATABASE_URL,GF_INSTALL_PLUGINS&PORTDefault=3000&GF_SECURITY_ADMIN_PASSWORDDefault=admin&GF_DATABASE_SSL_MODEDefault=require&GF_DATABASE_TYPEDefault=postgres&GF_DATABASE_URLDefault=postgres%3A%2F%2F%24%7B%7B+PGUSER+%7D%7D%3A%24%7B%7B+PGPASSWORD+%7D%7D%40%24%7B%7B+PGHOST+%7D%7D%3A%24%7B%7B+PGPORT+%7D%7D%2F%24%7B%7B+PGDATABASE+%7D%7D&GF_INSTALL_PLUGINSDefault=yesoreyeram-infinity-datasource,grafana-worldmap-panel,grafana-clock-panel)

## ✨ Features

- PostgreSQL
- Grafana

## 💁‍♀️ How to use

- Click the **Deploy on Railway** button 👆
- Modify the list of plugins as required
- Visit your console after the deployment is complete
- Login to grafana using `admin:admin` credentials
- Make sure to change the default admin password after your first visit

## 📝 Notes

- This starter automatically provisions a PostgreSQL database for you when you click the `Deploy on Railway`.

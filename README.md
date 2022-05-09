<div align="center">

# Coronavirus tracker tool


![App Screenshot](https://github.com/richardmogyoro/tracker-tool/blob/8ece9e86d41255f9f1283c82d98edaaaaeef3a10/App.JPG)

</div>

---

### Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Install](#install)


# Introduction

This is a simple tool for tracking the cumulated number of COVID-19 infections. It includes a counter for total infections so far, number of new infections since yesterday and a detailed table braking down these numbers to countries and territories.


# Features

- Written in Java, using Spring Boot and Thymeleaf
- [Uses the daily updated COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University as data source.](https://github.com/CSSEGISandData/COVID-19)
- Data source is in CSV, it gets fetched and then parsed with Apache Commons CSV
- Styling is done with Bootstrap


# Install
``` sh
git clone git@github.com:richardmogyoro/tracker-tool.git
```

After the repository is successfully cloned, you can open the folder in your IDE of choice (e.g.: IntelliJ IDEA). Running the application from the IDE, you can access the application in any browser at localhost:8080. 



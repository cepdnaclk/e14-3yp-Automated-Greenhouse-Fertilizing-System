---
layout: home
permalink: index.html
repository-name: e14-3yp-Automated-Greenhouse-Fertilizing-System
title: Automated Greenhouse Fertilizing System
---
# Automated Greenhouse Fertilizing System

---
## Team
-  E/14/287, R.M.K.D Rathnayake, [e14287@ce.pdn.ac.lk](mailto:e14287@ce.pdn.ac.lk)
-  E/14/335, K.R.W.R Subasinghe, [e14335@ce.pdn.ac.lk](mailto:e14335@ce.pdn.ac.lk)
-  E/14/402, G.A.A.M.B Wimalasena, [e14402@ce.pdn.ac.lk](mailto:e14402@ce.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Links](#links)

---

## Introduction


This project aims to calculate the component(N , K , P) levels which are responsible for the growth of the plant in a real time basis and maintain the component level which is required for the relevant plant. Using this system we can increase the lifetime of a plant and can get the maximum harvest out of the plant.

In the traditional system we won't get the perfect component levels as we are not checking the current component level. (We are adding the same amount of water or fertilizers to the every plant irrespective of the component level in that plant).

First using sensors we will get the current component level of each and every plant. Then the data will be transmitted to a centralized server. Then the server will check whether the component level of each plant are up to the required level. For different varities of plants the component levels are also differ. If a component level of a certain plant is not up to the required level the server will send a command  to the automated pipeline system asking it to send the relevant amount of required components through the pipeline to the relevant plant.

## Solution Architecture

Project Plan

Embedded Systems Design

PH sensors and Humidity sensors are used to measure the PH level and the humidity level of the soil in a particular plant.
Temperature sensors are used to measure the temperature within the greenhouse.
Node mcu is used to transfer data from the sensors to the server.
Arduino uno will be used to control the fertilizer dispersion system.
![image](https://user-images.githubusercontent.com/73756777/120117793-87188980-c1ac-11eb-8f84-c89fdc34bdff.png)
![image](https://user-images.githubusercontent.com/73756777/120117796-8d0e6a80-c1ac-11eb-97a1-b2f8176538e8.png)
![image](https://user-images.githubusercontent.com/73756777/120117802-9bf51d00-c1ac-11eb-8716-bf7f4a424e21.png)
![image](https://user-images.githubusercontent.com/73756777/120117931-67ce2c00-c1ad-11eb-9e08-8ee3d67d944d.png)



## Links

- <a href = "https://github.com/cepdnaclk/e14-3yp-Automated-Greenhouse-Fertilizing-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e14-3yp-Automated-Greenhouse-Fertilizing-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://ce.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

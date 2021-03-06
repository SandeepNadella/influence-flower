# Influence Flowers

## Dataset

- Link: <https://drive.google.com/open?id=1nK0kXxA4OIdPX5A87awZCWNt53Xi7p9N>

> **NOTE:** Download this file into the root folder of the project

## Environment Setup

### Deployed Environment

- <http://euler.la.asu.edu:8002/>

### Testing

#### Some tested flowers

- <http://euler.la.asu.edu:8002/moviesflower/?genre_list=Adventure,Action>
- <http://euler.la.asu.edu:8002/loadairbnbflower?city_name=Austin>


### Deployment Environment Setup

- Download the dataset files from the above section and put it under the root folder. The project setup should look like this

```bash
-- Influence-Flowers-Sai-Akshit-Sandeep-Raghul-Akshay  
  |__ .vscode  
  |__ flowerapp  
  |__ .gitignore  
  |__ db.sqlite3  
  |__ manage.py  
  |__ README.md  
```

- Make sure you have the latest version of python3 installed in the deployment environment 
- Install Sympy using  

```bash
(base) ➜ Influence-Flowers-Sai-Akshit-Sandeep-Raghul-Akshay git:(master) pip3 install sympy
```

- Install Django version 2.2.6 using  

```bash
(base) ➜ Influence-Flowers-Sai-Akshit-Sandeep-Raghul-Akshay git:(master) pip3 install Django==2.2.6  
```

> **NOTE:** The project doesn't work with latest version of Django since the configuration for serving staticfiles has changed since this project was developed

- Run server using  

```bash
(base) ➜ Influence-Flowers-Sai-Akshit-Sandeep-Raghul-Akshay git:(master) python manage.py runserver 127.0.0.1:8001
```

- The server should start on port 8001 and can be accessed by opening [http://127.0.0.1:8001/](http://127.0.0.1:8001/) in the browser. The flower is tested primarily on Google Chrome browser.

### Development Environment Setup

- Install Visual Studio Code
- Open the github repo folder and select debug icon
- Select the Debug icon on the Activity bar and select Python: Django configuration
- You can see other configurations which allow you to launch the Chrome Browser or [Browser Preview extension](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview) for debugging
- The default port is 8001 and can be changed in the launch.json file under .vscode folder

### Overview

![Directors for Adventure, Action genre](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.31.28%20PM.png)
*Directors for Adventure, Action genre set*

![Top 5 movies of Steven Spielberg in Adventure, Action genre](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.31.53%20PM.png)
*Top 5 movies of Steven Spielberg in Adventure, Action genre*

![Flower Construction](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/InfluenceFlowers.png)
*Flower Construction*

![Details on Demand Extension Construction](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/InfluenceFlowerExtension.png)
*Details on Demand Extension Construction*

[Find more images under the screenshots folder](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots)

### Web application screenshots

#### Movies

![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.30.12%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.30.32%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.30.56%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.28.25%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.31.28%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.31.53%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.40.35%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.40.59%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.41.10%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.41.36%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.42.09%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.42.43%20PM.png)

#### Property Listings

![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.43.39%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.44.00%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.44.14%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.44.34%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.44.42%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.44.50%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.45.24%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.46.26%20PM.png)
![](https://github.com/SandeepNadella/influence-flower/blob/master/screenshots/Screen%20Shot%202019-12-04%20at%2012.45.40%20PM.png)

### Development Commands

```bash
Import CSV into sqlite
(base) ➜  Influence-Flowers-Sai-Akshit-Sandeep-Raghul-Akshay git:(master) ✗ sqlite3 db.sqlite3
SQLite version 3.29.0 2019-07-10 17:32:03
Enter ".help" for usage hints.
sqlite> .mode csv
sqlite> .import /Users/sanadell/test.csv Test
```

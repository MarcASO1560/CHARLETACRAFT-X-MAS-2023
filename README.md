![CharletaCraft2](img/charletaTitle.png)
## 🎄About the game:
Welcome to the thrilling second edition of Charletacraft's Hardcore Server! In the coming days, you're set to embark on an unparalleled survival adventure, a standout journey in our server saga.

Here's the catch: death is final. Should you perish, your journey ends, relegating you to a spectator, never to rejoin the fray.

The challenge is formidable. Navigating in small teams is wise, especially during explorations. Excitingly, this edition features an expanded health pool with 30 hearts. A word of caution: overconfidence can be your downfall. Stay sharp, stay alive!

![CharletaCraft2](img/capturaHUD.png)

This server's map may not boast the largest scale in terms of admin-crafted expanses, yet it stands as our most finely tuned and optimized creation to date. 

![CharletaCraft2](img/charletaMap.png)

Prepare to be captivated by an eclectic array of structures and natural wonders. From sprawling underground rivers stretching kilometers in length to towering mountains that soar over 270 blocks high, each element has been meticulously designed.

![CharletaCraft2](img/captura(1).png)
![CharletaCraft2](img/captura(2).png)
![CharletaCraft2](img/captura(3).png)
This map represents a pinnacle of my work, skillfully balancing stability and maintaining the essence of playability. Explore and enjoy these marvels in a world crafted with precision and care.

## ⭐ Mods & game instalation guide:
### 1. Game instalation:

To correctly install the game, first you need to buy Minecraft, since this server a **premium** server so if you have not bought the game but you wish to, [I will leave the link for its purchase.](https://www.minecraft.net/es-es/store/minecraft-deluxe-collection-pc)

Once we have installed the game's launcher, it will look like the following image: 

<p align="center">
  <img width="800" height="600" src="img/tutorial/launcher.png">
</p>

We have to start by selecting the game version that we will modify, to do so we choose the **Instalations** (Instalaciones in the image) tab and create a new installation. Inside the configuration of the new installation you should see the following information:

You need to select the version 1.20.1 of the game.
<p align="center">
  <img width="800" height="600" src="img/tutorial/NuevaInstalacion1.png">
</p>

Now all that we need to do is, open the game once and try it. So, start the game and create a new world. Once we have checked that everything is in order and that the games works correctly, we will instal the mods.

### 2. Java installation:

To better help the file's organitzation, here is [a drive link with different folders](https://drive.google.com/drive/folders/1zxdvSaePYwKg1KBMIgJeHxxiiT1dLvw0?usp=sharing).

- Right now the important folder is [Java](https://drive.google.com/drive/folders/1zxdvSaePYwKg1KBMIgJeHxxiiT1dLvw0?usp=sharing), where, mainly, we must confirm that everything works accordingly. Because it is likely that even if the game has worked  in its default setting, once we add the mods, it can break down and give us a bad headache.
- Inside **Carpeta de Java** (Java folder) we find two different files, one includes [Java Cliente](https://www.java.com/en/) and another one that consists of the developer version of Java or [JDK](https://www.oracle.com/java/technologies/javase/jdk19-archive-downloads.html) with which **Minecraft** works.

<p align="center">
  <img width="400" height="200" src="img/tutorial/javaVersions.png">
</p>

- To begin with, let us install **JDK**. So, execute the file and install it like any other software:

<p align="center">
  <img width="600" height="500" src="img/tutorial/Java19.png">
</p>

- Then, just to make sure, we repeat the process with **Java 8** and we install it:

<p align="center">
  <img width="800" height="450" src="img/tutorial/Java8.png">
</p>

From now on, it can prove beneficial to restart the computer, we strongly recommend it.

## 3. Forge instalation:

To install **Forge** we will go to the Drive folder that is named [Forge](https://drive.google.com/drive/folders/1zxdvSaePYwKg1KBMIgJeHxxiiT1dLvw0?usp=sharing) and we will install it in the computer. (Friendly reminder that we must execute it, we do not put it inside any folder)

<p align="center">
  <img width="450" height="450" src="img/tutorial/Forge.png">
</p>

We click **OK** and it should install itself into the folder where **Minecraft** is installed.

## 4. Mods Installation for the server:

By this point, you will have to install, from the Drive folder, the [mods](https://drive.google.com/drive/folders/1qgNKS9qWQXf8tUvSjGfNlCQWvLEJWtbP?usp=sharing) folder somewhere we can easily find it, be it the desktop, an empty folder... Now, we will look for the directory where we will find all the game files. To do so we will do the following:
- First, press the command **Win + R** and type **%appdata%**:

<p align="center">
  <img width="400" height="230" src="img/tutorial/appdata.png">
</p>

- Then, acces the **.minecraft** folder:

<p align="center">
  <img width="600" height="550" src="img/tutorial/puntomine.png">
</p>

-Inside that folder, we will find a folder named **mods**, if it does not exist, you will have to create a folder named **mods**:

<p align="center">
  <img width="600" height="550" src="img/tutorial/mods.png">
</p>

- To put an end to this bullet point, we will place all the mods we have downloaded into said folder:

<p align="center">
  <img width="600" height="550" src="img/tutorial/mods2.png">
</p>

## 5. Minecraft configuration:

Now that everything is set, we can re-open **Minecraft Launcher**:

<p align="center">
  <img width="800" height="650" src="img/tutorial/launcher5.png">
</p>

But before that, we have to make a few adjustments to **Forge** so that it can launch with more thant 2GB of RAM (the minimum required is 4GB). Consequently, we will go to de **Instalations** (Instalaciones) tab, we click on edit the instalation with **Forge**'s symbol:

<p align="center">
  <img width="800" height="650" src="img/tutorial/editarForge.png">
</p>

- We change the **JVM Arguments** (Argumentos JVM) with the following argument:
```
-Xmx6G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```

---

### And with that the instalation guide is over, enjoy the server :)

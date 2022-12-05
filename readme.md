# Task 01
<b>Créer une nouvelle machine Linux/debian</b></br>

![image info](./images/1.png)

<b>se rendre dans stockage</b></br>

![image info](./images/2.png)

<b>Dans controlleur IDE ajouter un nouveau disque et choisir l'iso <a href="https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-11.5.0-amd64-netinst.iso"> télécharger</a></b></br>
<b>suivre les étapes et choisir langue anglais</b></br>
<b>se connecter avec root pour éviter les sudo</b></br>

# Task 02

`adduser -u 4242 marvin`</br>
<b>remplir le QCM</b></br>

# Task 03

`addgroup -gid 42400 H2G2 --force_badname`</br>
`usermod -gid 42400 marvin`</br>
`adduser -uid 4200 -gid 42400 zaphod`</br>
<b>remplir le qcm</b>
`cd home`</br>
`mkdir HeartOfGold`</br>
`chmod 775 HeartOfGold`</br>
`chgrp employees HeartOfGold`</br>

# Task 04

`cd etc/ssh`</br>
`nano sshd_config`</br>
<h2>config :</h2>

![image info](./images/3.png)

![image info](./images/4.png)

![image info](./images/5.png)

![image info](./images/6.png)


# Task 05

<b>Ajouter <u>DenyUser</u> zaphod dans</b> `sshd_config`

# Task 06

`apt_get install fail2ban`</br>
`cd ..`</br>
`cd fail2ban`</br>
`nano jail.conf`</br>

<h2>config :</h2>

![image info](./images/7.png)


# Task 07


`nano /etc/iptables/rules.v4`</br>

écrire à l'intérieur ce qu'il y a dans le screen puis donner les droits : </br>

![image info](./images/8.png)

`chmod +x /etc/iptables/rules.v4`</br>
`nano /etc/rc.local`</br>

écrire le script suivant : </br>
`#!/bin/bash`</br>
`./etc/iptables/rules.v4`</br>

puis lui donner les droits : </br>
`chmod +x rc.local`</br>

Petit conseil, supprimez les règles imposées sinon vous pourrez pas utiliser l'autograder : </br>

`iptables -F ; iptables -X`

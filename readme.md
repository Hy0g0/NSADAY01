# Task 01
<b>Créer une nouvelle machine Linux/debian</b>
![28a6099d9f2cd1e2e2bf45a05345ebf3.png](:/959d0e0461aa418f999d9e63c6441aab)
<b>se rendre dans stockage</b>
![66fb1c9fa886fbe9016dc99f05f6919f.png](:/706f205af6ef4141ac24e0b122ed90ec)
<b>Dans controlleur IDE ajouter un nouveau disque et choisir l'iso <a href="https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-11.5.0-amd64-netinst.iso"> télécharger</a></b>
<b>suivre les étapes et choisir langue anglais</b>
<b>se connecter avec root pour éviter les sudo</b>

# Task 02

`adduser -u 4242 marvin`
<b>remplir le QCM</b>

# Task 03

`addgroup -gid 42400 H2G2 --force_badname`
`usermod -gid 42400 marvin`
`adduser -uid 4200 -gid 42400 zaphod`
<b>remplir le qcm</b>
`cd home`
`mkdir HeartOfGold`
`chmod 775 HeartOfGold`
`chgrp employees HeartOfGold`

# Task 04

`cd etc/ssh`
`nano sshd_config`
<h2>config :</h2>

![0f584ef9bb602d7f5dc2924d1c013929.png](:/1a153ca10594432f8f15f6510cea4ff6)

![d5c6e679c2efb14fa52047800fe0e33d.png](:/136946454c324b0da460ca78737f9cb1)

![d6ecbbb2c7e6ad675f917b35f19e78ed.png](:/637e90bb5b544c0b890a41ebd48ec84d)

![811fdbf8dc1a64057287d62d9144f86f.png](:/33408b6d7b0e428d93139e60b7ea7aca)

# Task 05

<b>Ajouter DenyUser zaphod dans</b> `sshd_config`

# Task 06

`apt_get install fail2ban`
`cd ..`
`cd fail2ban`
`nano jail.conf`

<h2>config :</h2>
![2a2481f301741e1e18e1dadff8babf30.png](:/608f3311918b44fbb9ff7d3d4981b622)

# Task 07

<h1>Bonne chance</h1>

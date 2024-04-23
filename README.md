# h4-demoni
kotitehtävät

a) Hello sls

Ensiksi loin hello -kansion ja init.sls -tiedoston. 

```bash
sudo mkdir -p /srv/salt/hello
sudo nano /srv/salt/hello/init.sls
```
Sitten tarkistin, että tiedosto näkyy hello-kansiossa

![ls init sls](https://github.com/JohannaLap/h4-demoni/assets/165195836/6903c44d-87fb-4750-bffa-588ed0bb8c0b)

b) Top
Top -tiedoston loin seuraavalla komennolla

```bash
sudo nano /srv/salt/top.sls
```
.. ja tarkistin että top.sls näkyy toivotulla tavalla.
![ls top sls](https://github.com/JohannaLap/h4-demoni/assets/165195836/6adb2050-1370-4bf0-bba4-9a10b4771111)

c) Apache easy mode
Varmistin, että Apache2 on aktiivinen
![apache active](https://github.com/JohannaLap/h4-demoni/assets/165195836/d158aa8c-1472-42e4-be5c-9236e7f8d100)

```bash
echo "Tämä on uusi testisivu" | sudo tee /var/www/html/index.html
```
![echo tämä on testisivu](https://github.com/JohannaLap/h4-demoni/assets/165195836/57440f58-1164-48a6-9c3d-4846d8dc6ca7)

Varmistin demonin käynnistymisen
![enable apache2](https://github.com/JohannaLap/h4-demoni/assets/165195836/f3dfb44f-7788-4378-aff6-2f2da6ac70ed)

d) SSHouto
```bash
systemctl status sshd
```
![systemctl status sshd](https://github.com/JohannaLap/h4-demoni/assets/165195836/f524ae17-4dbe-4709-9ba7-7676c10467fe)



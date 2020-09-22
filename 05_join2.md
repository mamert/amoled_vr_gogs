
## Szufladka + ekran

![zestaw](_pics/szufladka_cut03.jpg)<br>
To są2 części któe się nie trzymają siebie nawzajem, a powinny.
Na ratunek: PCL (Polymorph) zabarwiony na czarno!

Nie chcemy jednak trwale skleić ekranu - nie gdy możemy użyć śrub.<br>
Szufladka będzie trzymać podkładki, a ekran będzie do nich przykręcany śrubami.<br>
Wpierw przygotować wszystko, i odizolować folią PCL od elektroniki:<br>
![zestaw](_pics/szufladka_mont01.jpg)<br>
I tak przy każdej śrubie:<br>
![zestaw](_pics/szufladka_mont02.jpg)<br>


Odkształcone od folii, ale ma z grubsza poprawny kształt...<br>
![zestaw](_pics/szufladka_mont03.jpg)<br>
![zestaw](_pics/szufladka_mont04.jpg)<br>
... i pasuje do śrub.
![zestaw](_pics/szufladka_mont05.jpg)<br>

Ekran jest dobrze trzymany w szufladce, pasuje do dziury w goglach idealnie (z minimalnym tylko odstępem),<br>
a sama szufladka swobodnie się przesuwa:
![zestaw](_pics/szufladka_mont06.jpg)<br>
![zestaw](_pics/szufladka_mont07.jpg)<br>
PCL zespaja podkładki z resztą szufladki, i utrzymuje odstęp od elektroniki:
![zestaw](_pics/szufladka_mont08.jpg)<br>

No, ale choć przesuwa sięswobodnie, szufladka nie trzyma się reszty gogli bez części je domykającej<br>
- a ta została zdjęta by zmieścić Raspberry Pi.

Ale nie problem, mamy więcej PCL :)<br>
Njpierw nawiercić tam gdzie chcemy coś trzymać...<br>
![zestaw](_pics/szufladka_drill01.jpg)<br>
NałożyćPCL i przecisnąć trochę przez dziurkę..<br>
![zestaw](_pics/szufladka_drill02.jpg)<br>
... i uformować uchwyt pod którym szufladka może się ślizgać :)<br>
![zestaw](_pics/szufladka_drill03.jpg)<br>
Podobnie na drugim kńcu:<br>
![zestaw](_pics/szufladka_drill04.jpg)<br>
![zestaw](_pics/szufladka_drill05.jpg)<br>
I gotowe :)<br>
![zestaw](_pics/joined01.jpg)<br>
Całość szugladki siętrzyma mocno, a jednocześnie może byćłatwo wyjęta i rozkręcona na części.<br>
![zestaw](_pics/joined02.jpg)<br>



## Oprogramowanie
Do tego celu bierzemy świeżuteńką nową kartę pamięci kompatybilną z Raspberry Pi:<br>
![zestaw](_pics/os_card01.jpg)<br>

Ściągamy obraz [systemu operacyjnego - Raspbian, czy - obecnie - Raspberry Pi OS](https://www.raspberrypi.org/downloads/raspberry-pi-os/)

Nie używam "Raspberry Pi Imager", zwykła komenda dd wystarcza:
```
sudo dd bs=4M if=2020-05-27-raspios-buster-armhf.img  of=/dev/sdb conv=fsync
```
I pozostaje czekać.

![zestaw](_pics/os_card02.jpg)<br>
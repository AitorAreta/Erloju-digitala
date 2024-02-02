#Sarrera

###Azken erronka bezala hainbat proiektu ezberdin burutu zitzaigun, baina azkenik erloju digital bat egitea erabaki genuen. Erloju honek ordua eta tenperatura denbora errealean adieraziko digu.

Alde batetik, gure erloju digitalaren karkasa edo diseinua dotoretasun garaikidea eta praktikotasuna nahastuaz dago, estilo eta aukera guztiak osatzen dituen diseinu dotore eta minimalista osatuz. Horretarako 3D inpresora tamaina ezberdinetakoak erabili dugu proiektu honen pieza bakoitza inprimatzeko.

Beste aldetik, desplazamenduko LED matrize-pantaila baterako softwarea erabiltzen du, erloju askorentzat idatzitako softwarean oinarrituta, ESP32 erabiliz Internetera konektatzeko. Desplazamendua duen pantaila baten ezaugarririk onena da informazio gehiago ikus daitekeela pantaila estatiko batekin alderatuta.  LED matrize-pantailak desplazamendudun pantaila bat sortzeko modu egokia dira. Proiektu honetan erabilitako espezifikoak kolore gorrikoak dira, eta 32 LEDeko zabalera eta 8 LEDeko altuera dute. Egia esan, 8x8ko lau LED modulu daude plaka horietan muntatuta, bakoitzak LED MAX7219 kontrolagailu bat du eta elkarren artean elkartutak daude.  

Azkenik, erlojua eta tenperatura denbora errealean aipatuko diguna bi sensore izango dira. Lehenengoa, DS3231 denbora errealeko erloju-modulua (RTC) modulu elektroniko bat da, eta DS3231SN bat eta EEPROM AT24C32 memoria bat ditu, bateriarako oinarri batekin, euskarri-osagaiekin eta konektoreekin batera, egungo data eta ordua ezagutzea eskatzen duten prototipo elektronikoak egitea errazteko. Bigarrena, ESP32 modulua Wi-Fi/Bluetooth soluzio bat da, guztia batean, integratua eta ziurtatua, hari gabeko irratia ez ezik, interfazeekin integratutako prozesadore bat ere ematen duena, zenbait periferikorekin konektatzeko.

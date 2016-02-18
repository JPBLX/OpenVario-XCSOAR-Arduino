# OpenVario-XCSOAR-Arduino
Utiliser directement trois senseurs (AMS5915,MS5611,DHT12) et un Arduino (Nano) pour envoyer la vitesse air, la pression, la température, l'hygrométrie via BlueTooth (HC05) dans des trames (protocole Vega) à XCSOAR. Le logiciel implémente les équations de Bernouilli (pitot), de Magnus (densité de l'air humide), un filtre de Kalman pour l'altitude (vario) et conclue les trames par CRC.

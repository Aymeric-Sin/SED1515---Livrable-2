# SED1515---Livrable-2
Contrôle et vérification bidirectionnels du PWM entre deux Raspberry Pi Pico (MicroPython)

Deux Raspberry Pi Pico communiquent via UART : le Pico A génère un signal PWM et envoie la valeur désirée.
Le Pico B mesure la valeur moyenne du PWM via un filtre RC + ADC et renvoie la mesure à Pico A.
Les deux appareils calculent et affichent la différence ; le projet inclut code MicroPython, protocole série et scripts de test.

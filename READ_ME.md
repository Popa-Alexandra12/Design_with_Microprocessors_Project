# Follow the leader robot

Proiectul are ca scop controlarea prin intermediul unei aplicatii mobile a unui robot experimental, care la randul sau va trimite comenzile primite unui al doilea robot pentru a le executa.

  - Robotii folosesc placi de dezvoltare Arduino UNO si module Bluetooth HC-05.
  - Primul robot este controlat prin aplicatia mobila Arduino Bluetooth controller.
  - Robotii pot executa 5 comenzi (deplasare in fata, in spate, rotire stanga, rotire dreapta, stop).

# Resurse necesare

  - 2 roboti experimentali (2 placi Arduino UNO)
  - 3 module Bluetooth HC-05
  - aplicatia mobila [Arduino Bluetooth controller](https://play.google.com/store/apps/details?id=com.giumig.apps.bluetoothserialmonitor&hl=ro)

Robotii includ fiecare urmatoarele componente: 
  - doua motoare DC, 
  - driver motoare L298N Dual H-Bridge, 
  - doua roti conectate la motoare, 
  - suport plexiglas,
  - doua placi de prototipizare (Breadboard)
  
Robotul comandat de telefon (master) are nevoie de 2 module Bluetooth : 
  - pentru comunicarea cu telefonul
  - pentru transmiterea comenzilor catre cel de-al doilea robot (slave)

Cele 2 module Bluetooth utilizate pentru transmiterea comenzilor intre roboti trebuie configurate pentru a se conecta doar intre ele. Detaliile cu privire la modalitatea de configurare se regasesc in documentatie la sectiunea "Specificatii software".

Pasii ce trebuie urmati pentru testarea functionalitatii proiectului se afla in documentatie, la sectiunea "Manual de utilizare".

# Tool-ul necesar
- [Arduino IDE](https://www.arduino.cc/en/main/software)
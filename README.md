# Vaja7-PWM-STM32F4-

Odgovori na vprašanja in komentar:

b)	V levem Pinout oknu razširite nabor možnosti za Timers ter za časovnik TIM1. Clock Source nastavite kot Internal Clock. Prvi kanal aktivirajte kot PWM Generation CH1. Kateri pin ste omogočili? __PE9________. Kaj se izpiše poleg pina? TIM_CH1.

d)	V Oknu Configuration kliknemo za TIM1  Vrednost Prescaler v zavihku Counter Settinngs določite tako, da bo časovnik delal s frekvenco 1 MHz. Koliko je vrednost Perscaler (namig; delitelj) ? ____16_____________.

e)	Parameter Counter Period nastavimo na 100 in s tem še dodatno znižamo takt časovnika. Koliko znaša sedaj? ________10__kHz.

f)	V PWM Generation Chanel nastavite Pulse (16 bits value) na 50. Kaj pomeni ta parameter? Namig – največja vrednost je lahko 100 odstotkov (znak za odstotek v polja ne pišemo).  Ta parameter pomeni širina signala.

b)	Poiščite prenastavljeni parameter Pulse (ki je 50) v vaši kodi in prepišite ukaz, ki ga je generiral CubeMX:
____________________sConfigOC.Pulse = 50;____________________.


a)	V kodi spremenite vrednost širine pulza na 25 %. Zapišite popravljeni ukaz v kodi:
_______sConfigOC.Pulse = 12,5;________________ . 


Zapišite kaj počnejo ukazi v  1.,2. in 3. vrstici (v user code begin 3):
1.	Nastavi spremenljivko duty cycle.
2.	Spremeljivki prišteje 10.
3.	Če ima spremenljivka duty cycle vrednost ki je večja od 90, nastavi spremenljivko na 10.


KOMENTAR:
Vse kar smo priključili je lepo delovalo. Na srečo nismo imeli težav, vendar sonda bi bila lahko boljše kvalitete, predusem zaradi stika! 

Luka Nograšek, Luka Buzina, Žiga Kuder


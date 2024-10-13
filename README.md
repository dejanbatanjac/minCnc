#GRBL Servo motor SG 90 i dva step motora 28BYJ48 

GRBL je open-source firmware za mikrokontrolere koji se koristi za upravljanje CNC mašina. Ovaj softver se instalira na mikrokontroler Arduino Uno i omogućava mu da Uno komunicira sa računarom i kontroliše kretanje CNC mašine.

GRBL se koristi za različite vrste CNC mašina, a ovde za crtanje.
GRBL je popularan izbor za CNC mašine jer je besplatan, dobro podržan i relativno jednostavan za korišćenje. 

Motori 28BYJ48 su spojeni na kontrolnu ploču koja koristi čip ULN2003. Ova ploča se povezuje na pinoве A0, A1, A2, A3 za Y-osu i digitalne pinove 2, 3, 4, 5 za X-osu.

Servomotor je spojen na pin 11.

**Zasluge:**

* costycnc koji je modifikovao grbl sa bipolarnog na unipolarni: [https://github.com/costycnc/costycnc-costycnc-grbl-1.1-unipolar](https://github.com/costycnc/costycnc-costycnc-grbl-1.1-unipolar)
* robottini koji je dodao podršku za servomotor: [https://github.com/robottini/grbl-servo](https://github.com/robottini/grbl-servo)

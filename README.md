## Ogólne informacje

NAZWA: "Patrol"

MOTTO:
„I have never thought to myself that realism is fun. I go play games to have fun.” - Gabe Newell \
„Nigdy nie postrzegałem realizmu w kategoriach zabawy. Gram w gry, żeby mieć z nich frajdę”. \

## GRAFIKA

### LOGO-POMYSŁ: 
tło - Stary żółty papier gazetowy \
tekst - za pomocą fontu mom's typewriter napisać "Patrol" \
dod. detale - prawy brzeg logo ma się leciutko palić \

### MODELE-3D: 
Robione w blenderze, jakość średnio-dobra, nie powinny być bardzo obciążające komputer.


## OPIS

### LOGIKA:

```
Odpalenie gry → Menu → Graj → SOLO → WYBÓR SŁUŻBY → GRA → Gra samemu → Zapis → Koniec
				 └──→ HOST → Kod dołączenia → Ludzie dołączają → Wybierzasz służbę → WYBÓR SŁUŻBY → GRA → Gra wspólna → Zapis → Koniec
```

### SŁUŻBY:
* Policja - mechanika interakcji z otoczeniem oraz NPC
Przykłady zadań:
pościg, sprawdzanie prędkości, inspekcja auta, kontorola ruchu, ochrona obywateli przed przystępcząścią

* Pogotowie - pracuje na mechanice minigier dla rożnych poszkodowań
Przykłady zadań:
ratowanie poszkodowanych

* Straż Pożarna - mieszanka minigier i interakcji z otoczeniem
Przykłady zadań:
ugaszenie pożaru, usunięcie reagentów chemicznych, wydostanie zablokowanych poszkodowanych z samochodu 

* Dyspozytor - kontroluje oraz koordynuje pracę służb, za pomocą widoku specjalnego, nadaje komunikaty głosowe które są odbierane przez służby
Zadania:
Odebranie dzwonku z miejsca zdarzenia → Analiza wymaganej pomocy → Nadanie prawidłowego komunikatu do poszczególnych kanałów radiowych słóżb 

### GRA: 
Po wyborze służby. Gracz dostanie zadania od dyspozytora przez ogólny kanał wybranej służby krótkofalówki przenośnej / CB-radia w samochodzie. Zadanie się pojawi w Panelu w którym gracz będzie miał wskazówki jak go wykonać. W zależności od zadania będą różne limity oraz warunki jakie muszą być spełnione na maksymalną nagrodę, np. czas wykonania, ilość przetrwałych poszkodowanych, jakość regulacji ruchu na miejscu wypadku, koordynacja z innymi służbami, stan w jakim poszkowany / NPC dostał dostarczony itp.. Po wykonaniu zadania gracz dostaje nagrodę. \
Co jakiś czas będą tzw. "Misje" dla gracza dla każdej z służb, będą one zawierały większą fabułę oraz wydawały większą nagrodę za wykonanie całego ciągu zadań. Po wykonaniu misji będzie większa zwykła nagroda, oraz nagroda specjalna. \
Jest również system reputacji, którego wynik zależy od wyboru gracza. Gracz będzie stawał przed wyborami moralnymi, np. jako policjant będzie mógł wziąść łapówkę na przekroczenie limitu prędkości. Każdy wybór będzie skutkował na reputacji. \

### KOMUNIKACJA:
Gracz ma 3 sposoby komunikacji w grze.

1. Proximity chat
Działa on na prostej zasadzie, "Push to Talk". Są trzy poziomy głośności mówienia: szept(5m), zwykły(10m) i krzyk(15m). Ta funkcja może być wykorzystana w niektórych misjach, np. dla uspokojenia poszkodowanego

2. Krótofalówki / CB-radia
Jest określona ilość kanałów przez którą przechodzą komunikaty głosowe, działą na tej samej zasadzie "Push to Talk". Są 3 specjalne kanały radiowe przez które są nadawane wiadmości do konretnych służb. Na kanale radiowym może się komunikować dowolny gracz z krótkąfalówką podłączony do tego samego kanału.

3. Telefony
Telefon ma funkcje czatu prywatnego między graczami. Tzn. gracz będzie mógł pisać do innego gracza. Jeżeli obojga z graczy znajduje się w tym samym świecie to dostępna będzie funkcja dzwonienia. Natomiast są również i słabości, zasięg jest tylko w miastach, oraz niektórych wsiach. Ta mechanika będzie zmuszała gracza do wykorzystywania różnych metod komunikafcji.

### SETUP:
Czas i miejsce akcji odbywa się w latach 90ych w Polsce. Otwiera się okno na swiat, i przez szpary zaczynają przemykać zagraniczne rzeczy i produkty. A Polska dopierdo kształtuje swoją niepodleglą władzę. Ty, jako dopiero skończywszy pełnolecie człowiek próbując podzarobić na uniezależnienie się od rodziców decydujesz na wstąpenie do jednej z służb publicznej i podzarobić, w ten czy inny sposób.

### REPUTACJA I ETYKA:
System reputacji jest oparty na dwóch wskaźnikach: "Reputacja Służbowa" oraz "Portfel". \
Gracz musi balansować między moralnością a chęcią szybkiego zarobku. \
Konswekencje tego wyboru są następujące:

* Wysoka Reputacja
  Dostęp do misji fabularnych, lepsze wyposażenie, szacunek na kanale radiowym, szybsze awanse na lepsze pojazdy.

* Niska Reputacja:
  Problemy z dyspozytorem (daje gorsze zlecenia), częstsze kontrole wewnętrzne, blokada dostępu do lepszego sprzętu, konieczność dłuższego jeżdżenia starszmy pojazdami.

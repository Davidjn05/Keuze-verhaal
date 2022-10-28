from cgi import print_arguments
from random import choice, choices
import time
popo=0
racist=0
tijd=0
paspoort=0
#Keuzeverhaal code
print ("Je gaat verhuizen naar Nederland voor werk. Hopelijk maak je goede keuzes voor een goede start in Nederland.")
time.sleep(3)
print("Wil je dubbel checken of je alles hebt Ja of Nee?")
choice = input()
if choice == "Ja":
    print("Je hebt niet veel tijd dus ga je naar de Keuken? Slaapkamer? Kelder?")
    choice = input()
    if choice == "Keuken":
     print("Je kan geen eten meenemen in het vliegtuig")
    elif choice =="Kelder":
     print("Er ligt niks in de kelder") 
    elif choice =='Slaapkamer':
        paspoort=1
        print("je gaat naar de slaapkamer en je paspoort ligt er!, best handig")
elif choice == "Nee":
  print("Je gaat direct naar het vliegveld")
if paspoort == 0:
    time.sleep(2)
    print("Je bent aangekomen op het vliegveld maar je bent je paspoort vergeten GAME OVER")
    quit
if paspoort == 1:
    time.sleep(2)
    print("Gelukkig heb je je paspoort gepakt voor de vlucht")
    time.sleep(2)
    print("Je bent bij de douane ze pakken je water af en gooien het weg")
    print("Ga je? 1.Verder of in 2.Discusie")
    choice=input()
   
if choice =="Verder":
    time.sleep(1)
    print("Je gaat verder met je dag met dorst")
    tijd=1
elif choice =="Discusie":
    time.sleep(1)
    print("Je had een lang gesprek en je krijgt je water niet terug")
    time.sleep(1)
    print("Nu kom je bijna te laat voor het vliegtuig. Mischien is er een kortere weg")
    time.sleep(1)
    print("Ga je naar links of rechts?")
    choice=input()
if choice == "links":
    print("Verkeede kant GAMEOVER")
if choice == "rechts":
    print("Je bent net op tijd aangekomen")
    tijd=1

if tijd == 1:
 time.sleep(1)
 print("Je zit nu lekker in het vliegtuig op weg naar Nederland")\

print("Je bent aangekomen in Nederland.")
time.sleep(2)
print("Voor dat je kan uitrusten zijn er een paar dingen die je eerst moet dan")
time.sleep(2)
print("Je gaat naar de winkel om wat eten te halen")
time.sleep(1)
print("Je komt in de winkel er is een racist die je uitscheld wat doe je?")
print("Hem Slaan? Schoppen? Negeren?")
choice=input()
if choice == "Slaan":
 print("Je slaat hem knockout met een mooie uppercut! je gaat maar snel naar de zelfscan")
 racist = 1
elif choice== "Schoppen": 
    print("Je trapt hem tegen zijn ")  

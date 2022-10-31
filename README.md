from cgi import print_arguments
from random import choice, choices
import time
popo=0
racist=0
tijd=0
paspoort=0
pont=0
laat=0
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
    quit(),
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
    quit(),
if choice == "rechts":
    print("Je bent net op tijd aangekomen")
    tijd=1

if tijd == 1:
 time.sleep(1)
 print("Je zit nu lekker in het vliegtuig op weg naar Nederland")\

time.sleep(2)
print("Je bent aangekomen in Nederland.")
time.sleep(2)
print("Voor dat je kan uitrusten zijn er een paar dingen die je eerst moet dan")
time.sleep(2)
print("Je gaat naar de winkel om wat eten te halen")
time.sleep(3)
print("Je komt in de winkel er is een racist die je uitscheld wat doe je?")
print("Hem Slaan? Schoppen? Negeren?")
choice=input()
if choice == "Slaan":
 print("Je slaat hem knockout met een mooie uppercut! je gaat maar snel naar de zelfscan")
 racist = 1
elif choice== "Schoppen": 
    print("Je trapt hem maar geweld is niet altijd het antwoord.")
    time.sleep(1)
    print("Hij belt de politie") 
    popo=1

if choice=="Negeren":
    print("Je hebt geen tijd voor onzin en je gaat verder met je dag.") 


if popo==1:
    time.sleep(1)
    print("De politie kan er elk moment aan komen ga je Rennen?Blijven?Hulp vragen? ")
choice=input()
if choice == "Rennen":
    racist=1
elif choice =="Hulp vragen":
    print("Je vraagt hulp aan een medewerker.")
    time.sleep(1)
    print("Ze zegt dat jullie beide de winkel moeten verlaten. Dan maar ergens anders boodschappen doen")

if choice=="Blijven":
    print("Je wacht tot de politie komt")
    popo=2

if racist == 1:
    print("Gelukkig ben je weg gekomen van de racist en je gaat weer verder met je dag")

if popo==2:
 print("De politie is aangekomen. Ze ondervragen je.")
 time.sleep(1)
 print("De racist vertelt er wat jij hebt gedaan wat zeg jij? Ik heb gelijk?niks?Hij is een racist")
choice=input()
if choice == ("Ik heb gelijk"):
    popo=4
elif choice== ("Niks"):
    print("Je zegt niks en wordt meegenomen door de politie GAME OVER")
    quit(),

if choice== ("Hij is een racist"):
    popo=5

if popo==4:
    time.sleep(1)
    print("De politie zegt dat je een onschuldige man hebt aangevallen")
    print("Geef je de politie gelijk Ja of Nee")
    choice=input()
    if choice== ("Ja"):
     popo=5
    elif choice == ("Nee"):
     print("De politie zegt dat je een onschuldige man hebt aangevallen en je word meegenomen GAMEOVER") 
     quit()
if popo==5:
 print("Je zegt dat de racistische man racistisch deed en je heeft lastig gevallen")
 time.sleep(1)
 print("Jullie worden beide uit de winkel gestuurd")

print("Je woont nu al een paar jaar in Nederland")
time.sleep(1)
print("Je hebt vandaag een belangerijk gesprek op werk,Als het goed gaat krijg je een promotie!")
time.sleep(2)
print("Maar je bent door je wekker geslapen nu moet je zo snel mogelijk naar je werk gaan")
time.sleep(2)
("Je stapt op je fiets maar de route die je normaal neemt is afgesloten")
print("Ga je naar Links of Rechts?")
choice=input()
if choice == ("Rechts"):
    print("Je fietst een beetje door en kan naar Links of Rechts") 
    choice=input()
    if choice==("Rechts"):
        pont=1
elif choice==("Links"):
        print("Je bent optijd bij de pont aangekomen")
        print("Gelukkig ben je optijd bij je werk aangekomen het gesprek ging goed")
        time.sleep(1)
        print("Je hebt een promotie gekregen goedzo!")
        time.sleep(3)
        print("Bedankt voor het spelen van mij spel! tot ziens")
        quit()
if pont==1:
    print("Je weet niet of je in de buurt bent van de pont")
    time.sleep(1)
    print("Je ziet iemand lopen ga je vragen welke kant je op moet Ja of Nee")
    choice=input()
    if choice==("Ja"):
        time.sleep(1)
        print("Je vraagt voor richting maar de persoon weet de weg ook niet")
        laat=1
    elif choice==("Nee"):
        print("Je fietst door maar helaas loopt het dood en kom je te laat")
        laat=1

if laat==1:
    time.sleep(2)
    print("Je bent te laat aangekomen,als je moet een goed excuus hebben om er nog een succesvol gesprek van te maken")
    time.sleep(2)
    print("Vertel je een Leugen of de Waarheid")
    choice= input()
    if choice==("Leugen"):
        print("Je zegt dat je fiets was gestolen en hier naar toe was gerend")
        time.sleep(1)
        print("Ze geloofden het niet het gesprekt ging niet zo goed helaas")
        time.sleep(2)
        print("Bedankt voor het spelen van mijn spel hopelijk kies je volgende keer betere opties")
    elif choice == ("Waarheid"):
        print("Je zegt: Bedankt voor het wahten sorry dat ik te laat was de weg was afgesloten")
        time.sleep(2)
        print("Het gesprek ging wel goed hopelijk krijg je een promotie ")
        time.sleep(2)
        print("Bedankt voor het spelen van mijn spel hopelijk kies je volgende keer betere opties")

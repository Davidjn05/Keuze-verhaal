
  from cgi import print_arguments
from random import choice, choices
import time
A= ["A","a","1"]
B=["B","b","2"]
C=["C","c","3"]
D=["D","d","4"]
a=["a","A"]
b=["b","B"]
c=["c","C"]
Ja=["Ja","JA","ja","Y","jA"]
Nee=["NEE","nee","Nee","N"]
racist=0
tijd=0
paspoort=0
pont=0
laat=0
popo=0
w=0
#Keuzeverhaal code
print ("Je gaat verhuizen naar Nederland voor werk. Hopelijk maak je goede keuzes voor een goede start in Nederland.")
time.sleep(3)
print("Wil je dubbel checken of je alles hebt Ja of Nee?")
choice = input(">>> ")
if choice in Ja:
    print("Je hebt niet veel tijd dus ga je naar de A.Keuken? b.Slaapkamer? C.Kelder?")
    choice = input(">>> ")
    if choice in A:
     print("Je kan geen eten meenemen in het vliegtuig")
    elif choice in C:
     print("Er ligt niks in de kelder") 
    elif choice in B:
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
    print("Ga je in discussie? Ja of Nee")
    choice=input(">>> ")
   
if choice in Nee:
    time.sleep(1)
    print("Je gaat verder met je dag met dorst")
    tijd=1
elif choice in Ja:
    time.sleep(1)
    print("Je had een lang gesprek en je krijgt je water niet terug")
    time.sleep(1)
    print("Nu kom je bijna te laat voor het vliegtuig. Mischien is er een kortere weg")
    time.sleep(1)
    print("Ga je naar A.links of B.rechts?")
    choice=input(">>> ")
if choice in A:
    print("Verkeede kant GAMEOVER")
    quit(),
if choice in B:
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
print("Hem A.Slaan? B.Schoppen?C.Negeren?")
choice=input(">>> " )
if choice in A:
 print("Je slaat hem knockout met een mooie uppercut! je gaat maar snel naar de zelfscan")
 racist = 1
elif choice in B: 
    print("Je trapt hem maar geweld is niet altijd het antwoord.")
    time.sleep(1)
    print("Hij belt de politie") 
    popo=1

if choice in C:
    print("Je hebt betere dingen te doen")
    racist=1


if popo==1:
    time.sleep(1)
    print("De politie kan er elk moment aan komen ga je A.Rennen?B.Blijven?C.Hulp vragen? ")
choice=input(">>> ")
if choice in A:
    racist=1
elif choice in C:
    print("Je vraagt hulp aan een medewerker.")
    time.sleep(1)
    print("Ze zegt dat jullie beide de winkel moeten verlaten. Dan maar ergens anders boodschappen doen")

if choice in B:
    print("Je wacht tot de politie komt")
    popo=2

if racist == 1:
    print("Gelukkig ben je weg gekomen van de racist en je gaat weer verder met je dag")
    w=1
if popo==2:
 print("De politie is aangekomen. Ze ondervragen je.")
 time.sleep(1)
 print("De racist vertelt er wat jij hebt gedaan wat zeg jij? A.Ik heb gelijk?B.niks?C.Hij is een racist")
choice=input(">>> ")
if choice in A:
    popo=4
elif choice in B:
    print("Je zegt niks en wordt meegenomen door de politie GAME OVER")
    quit(),

if choice in C:
    popo=5

if popo==4:
    time.sleep(1)
    print("De politie zegt dat je een onschuldige man hebt aangevallen")
    print("Geef je de politie gelijk Ja of Nee")
    choice=input(">>> ")
    if choice in Ja:
     popo=5
    elif choice in Nee:
     print("De politie zegt dat je een onschuldige man hebt aangevallen en je word meegenomen GAMEOVER") 
     quit()
if popo==5:
 print("Je zegt dat de racistische man racistisch deed en je heeft lastig gevallen")
 time.sleep(1)
 print("Jullie worden beide uit de winkel gestuurd")
 w=1
if w==1:
    print("Je woont nu al een paar jaar in Nederland")
time.sleep(1)
print("Je hebt vandaag een belangerijk gesprek op werk,Als het goed gaat krijg je een promotie!")
time.sleep(2)
print("Maar je bent door je wekker geslapen nu moet je zo snel mogelijk naar je werk gaan")
time.sleep(2)
("Je stapt op je fiets maar de route die je normaal neemt is afgesloten")
print("Ga je naar A.Links of B.Rechts?")
choice=input(">>> ")
if choice in B:
    print("Je fietst een beetje door en kan naar A.Links of B.Rechts") 
    choice=input(">>> ")
    if choice in B:
        pont=1
elif choice in A:
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
    print("Je ziet iemand lopen ga je vragen welke kant je op moet Ja of Nee?")
    choice=input(">>> ")
    if choice in Ja:
        time.sleep(1)
        print("Je vraagt voor richting maar de persoon weet de weg ook niet")
        laat=1
    elif choice in Nee:
        print("Je fietst door maar helaas loopt het dood en kom je te laat")
        laat=1

if laat==1:
    time.sleep(2)
    print("Je bent te laat aangekomen,als je moet een goed excuus hebben om er nog een succesvol gesprek van te maken")
    time.sleep(2)
    print("Vertel je een A.Leugen of B.de Waarheid")
    choice= input(">>> ")
    if choice in A:
        print("Je zegt dat je fiets was gestolen en hier naar toe was gerend")
        time.sleep(1)
        print("Ze geloofden het niet het gesprekt ging niet zo goed helaas")
        time.sleep(2)
        print("Bedankt voor het spelen van mijn spel hopelijk kies je volgende keer betere opties")
    elif choice in B:
        print("Je zegt: Bedankt voor het wahten sorry dat ik te laat was de weg was afgesloten")
        time.sleep(2)
        print("Het gesprek ging wel goed hopelijk krijg je een promotie ")
        time.sleep(2)
        print("Bedankt voor het spelen van mijn spel hopelijk kies je volgende keer betere opties")

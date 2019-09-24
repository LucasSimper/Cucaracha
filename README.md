Cucaracha
Se på dette projekt for at få styr på opsætningen af opgaven:
https://github.com/mwndigi/techstack

ALDRIG COMMIT TIL MASTER

## Kort beskrivelse :
En hjemmeside hvorpå man kan reservere et bord (eller flere) efter udfyldelse af personlige kontaktoplysninger og derefter kan man som kunde/ vælge et tilgængeligt bord. 

## Kravspecifikation 
Login side :
  Velkomstbesked
  Login kræver at kunden har oprettet bruger
  Opret bruger- hvis kunden ikke har gjort det endnu
GUI :
  Brugeren ser en oversigt over borde med angivelse af ledighed for hvert bord
  Brugeren kan vælge dato og tidspunkt for ankomst, og kan derved filtere listen af borde
  Brugeren kan vælge et bord som personen ønsker at booke
 Bekræftelse :
  Brugeren skal bekræfte bestillingen.
  Sender bestilling til Cucarachas admin profil
 Admin profil :
 Login- en master bruger som alle Cucarachas ansatte logger ind på
 Ser bekræftede bestillinger og persondata på bestillinger
 Bekræfte eller afvise nye bestillinger- besked til bruger profil.
 
 
Kravspecifikationer

1. Kunden kommer ind på vores hjemmeside for at bestille bord.

2. Kunden får nu mulighed for at logge ind eller oprette bruger.

2a. (Kunden har allerede oprettet bruger) Her logger kunden ind og kommer videre til GUI.

2b. (Kunden har ikke oprettet bruger) Kunden opretter bruger med fulde navn, køn, password og kontaktoplysninger. Derefter sendes kunden videre til GUI

3. Øverst på siden oplyser brugeren antallet af mennesker til bordet, samt dato og tidspunkt for ankomst. Her ses det fra fugleflugt, hvilke borde der er ledige og optaget på den angivne dato. Her kan man "trykke" sig ind på et ledigt bord for at komme videre. Se evt. vedhæftet billede (X)

4. Til sidst skal kunden bekræfte sin bestilling. Ved bekræftigelse sendes bookingen videre til Cucaracha som skal godkende bestillingen.

5. Cucaracha skal for at bekræfte bestillingen gå ind på samme hjemmeside og logge ind via en adminbruger der oprettes specifikt til Cucarachas administratorer.

6. I Cucarachas administrative system ses samme GUI som brugeren ser. Der er dog tilføjelse af en hover-funktion, hvor der ved bestilte borde kan ses navn på kunden, antallet af mennesker der kommer, tidspunkt for ankomst og telefonnummer. Se evt. vedhæftet billede(Y)

7. Ved en bestilling der ikke er bekræftet eller afvist endnu, vil der være en bookingliste øverst på siden, hvor en booking enten bekræftes alle afvises.

8. Ved bekræftelse eller afvisning sender admin besked til bruger om at den enten er bekræftiget eller afvist.

Meddelandesystem (DA343A - Utvecklingsprojekt)

Projektbeskrivning
Detta projekt är ett meddelandesystem designat och implementerat för kursen DA343A vid Fakulteten för Teknik och Samhälle, Institutionen för Datavetenskap och Medieteknik, VT22. Systemet består av en klientapplikation som tillåter användare att skicka och ta emot text- och bildmeddelanden genom ett server-klientsystem, med kommunikation via TCP.

Funktioner
- Klientapplikation: Användare kan koppla upp sig till systemet med ett användarnamn och en användarbild, skicka och ta emot meddelanden, samt hantera sina kontakter.
- Serverapplikation: Servern hanterar alla klienters anslutningar, meddelanden, och säkerställer att meddelanden levereras till rätt användare. Servern lagrar också osända meddelanden och loggar systemets trafik.
- Trådar och Strömmar: Systemet använder trådar och strömmar för att hantera samtidiga anslutningar och säkerställa smidig kommunikation mellan klienter och server.
- Objektorienterad Design: Projektet följer en objektorienterad designprincip med klasser för användare, meddelanden och serverhantering, och har dokumenterats med klassdiagram och sekvensdiagram.

Teknologier
- Språk: Java
- Kommunikation: TCP/IP, ObjectInputStream, ObjectOutputStream
- GUI: Java Swing för klientapplikationens användargränssnitt
- Databas: Ingen extern databas används, men systemet hanterar lokal lagring av användarkontakter och meddelanden.
- Versionhantering: Git och GitHub
- Byggmetod: Projektet använder sig av manuell kompilering och körning.


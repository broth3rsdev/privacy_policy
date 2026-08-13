---
title: "Politica de confidențialitate - On Air Radio"
lang: ro
---

# Politica de confidențialitate pentru On Air Radio

**Ultima actualizare:** 13 august 2026

On Air Radio este un player gratuit de radio pe internet pentru posturi de radio românești, dezvoltat de broth3rsdev. Această politică explică ce se întâmplă cu datele tale atunci când folosești aplicația.

## Rezumat

Nu există cont și nu există autentificare. On Air Radio nu are analiză de utilizare, nu are raportarea erorilor, nu are publicitate și nu conține niciun kit de urmărire. Nu primesc niciodată datele tale personale. Tot ce reține aplicația despre tine - favoritele, alarmele, istoricul ascultărilor și setările - rămâne pe dispozitivul tău.

Aplicația folosește totuși un serviciu pe care îl administrez eu: o bază de date găzduită, care conține directorul de posturi de radio. Aceasta stochează doar detalii despre posturi, niciodată ceva despre tine. Restul comunicării merge direct către posturile pe care le asculți și către serviciile enumerate mai jos, exact cum s-ar întâmpla dacă ai deschide acele fluxuri chiar tu.

## Informații stocate pe dispozitivul tău

Aplicația stochează local, în spațiul ei privat de stocare, următoarele:

- Directorul de posturi pe care îl descarcă: numele, țara, adresa fluxului, adresa siglei și site-ul fiecărui post.
- Favoritele tale și posturile ascultate recent. Acestea există doar pe dispozitivul tău și nu sunt trimise nicăieri.
- Alarmele tale: ora, zilele de repetare, postul ales, durata amânării și durata creșterii treptate a volumului.
- Preferințele aplicației, cum ar fi culoarea și modul temei, limba, afișarea în listă sau grilă, pornirea automată și ultimul post redat.
- O memorie cache cu siglele posturilor, păstrată pentru ca imaginile să apară și atunci când ești offline.

Nimic din toate acestea nu îmi este transmis mie. Dezinstalarea aplicației sau ștergerea datelor ei din setările sistemului elimină tot ce este listat mai sus.

Aplicația permite copierea de rezervă automată standard a Android, deci elementele de mai sus pot fi incluse în propria ta copie de rezervă Google Drive, criptată și asociată contului tău Google. Eu nu am acces la acea copie. O poți dezactiva din setările de copiere de rezervă ale dispozitivului.

## Informații trimise către terți

Utilizarea aplicației face ca dispozitivul tău să contacteze direct următoarele servicii:

- **Directorul de posturi**, găzduit pe Supabase (`khktcoshqvnrhpsdkxti.supabase.co`). Aplicația citește lista de posturi și urmărește actualizările acesteia. Aceste cereri ajung la serviciu împreună cu adresa ta IP. Nu sunt trimise niciodată favorite, istoric de ascultare sau identificatori de dispozitiv. Supabase asigură găzduirea; vezi [supabase.com/privacy](https://supabase.com/privacy).
- **Posturile de radio.** Când redai un post, dispozitivul tău se conectează direct la serverul de streaming al acelui post, care primește adresa ta IP și poate păstra propriile jurnale. Fiecare post este operat independent și aplică propria politică. Unele posturi transmit prin HTTP simplu, nu prin HTTPS, deci acele conexiuni nu sunt criptate.
- **Serverele care găzduiesc siglele.** Imaginile posturilor sunt preluate de la adresele publicate de posturi, iar acele servere primesc adresa ta IP.
- **Serviciile Google Play**, pentru Google Cast și Android Auto. Când trimiți sunetul prin Cast, adresa fluxului este trimisă către dispozitivul receptor, iar serviciile Google Play se ocupă de descoperirea dispozitivelor și de sesiune. Google Play colectează de asemenea date de instalare și de diagnosticare, în calitate de operator al magazinului, independent de această aplicație. Vezi [policies.google.com/privacy](https://policies.google.com/privacy).
- **Magazinul Google Play**, doar dacă apeși pe "Recenzie aplicație", care deschide pagina aplicației în magazin.
- **Orice site pe care îl deschizi.** Accesarea site-ului unui post îl deschide într-un browser integrat, iar acel site aplică propria politică și poate seta propriile cookie-uri.

## Analiză, raportarea erorilor și publicitate

Nu există niciuna. Aplicația nu conține kituri de analiză, telemetrie, atribuire sau publicitate, iar rapoartele de eroare nu sunt transmise nicăieri. Jurnalele de diagnosticare există doar în memorie, cât timp aplicația rulează.

Vizualizatorul audio din player este desenat pe baza sunetului pe care aplicația îl decodează oricum pentru redare. Aplicația nu are permisiune de microfon și nu înregistrează nimic.

Dacă folosești opțiunea "Trimite feedback", se deschide aplicația ta de email, cu adresa și subiectul completate. Nu se trimite nimic până când nu trimiți tu mesajul, iar până atunci poți modifica sau șterge orice.

## Cookie-uri

Aplicația nu setează cookie-uri în scopuri proprii și nu păstrează nicio sesiune de autentificare. Site-urile pe care le deschizi în browserul integrat pot seta propriile cookie-uri, care aparțin acelor site-uri.

## Permisiuni

- **Internet și starea rețelei:** pentru a descărca lista de posturi și a reda fluxurile.
- **Notificări:** pentru a afișa comenzile de redare și notificarea alarmei.
- **Serviciu în prim-plan, menținerea procesorului activ și menținerea conexiunii Wi-Fi:** pentru ca redarea să continue cu ecranul stins.
- **Alarme și mementouri (alarme exacte):** pentru ca alarmele radio să sune la ora pe care o stabilești.
- **Rulare la pornirea dispozitivului:** pentru a-ți reface alarmele după repornire.

Aplicația nu solicită acces la locație, contacte, microfon, cameră foto sau fotografii.

## Temeiul legal și drepturile tale (SEE/Regatul Unit)

Acolo unde se aplică GDPR, prelucrarea limitată efectuată de aplicație se întemeiază pe interesul legitim de a face aplicația să funcționeze: livrarea directorului de posturi și conectarea ta la fluxul pe care îl alegi. Nu există cont și nu păstrez nicio copie a datelor tale, așa că cererile de acces, rectificare, ștergere, portabilitate sau opoziție sunt satisfăcute pe dispozitivul tău, prin ștergerea datelor aplicației sau prin dezinstalarea ei. Cererile privind datele deținute de un post de radio sau de alt terț trebuie adresate părții respective. Poți depune o plângere la autoritatea locală de protecție a datelor (în România, ANSPDCP).

## Contact

Întrebări despre această politică: [broth3rsdev@gmail.com](mailto:broth3rsdev@gmail.com)

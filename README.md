# restaurant_rating
Restaurant rating system - Project in Backend 1 course

Ni ska bygga en applikation för att betygsätta/recensera restauranger

Ni får samarbeta med att sätta upp en startuppsättning med restauranger om ni vill. Ni kan även samarbeta med design/skisser (sätta upp wireframes) om ni vill. Ni får använda frameworks (typ bootstrap, angular el liknande).

Applikationen ska använda MySQL.
All CRUD-funktionalitet ska ske genom API:er
G-krav
Vilken användare som helst ska kunna CRUD:a restauranger med ett gränssnitt.
Användare ska kunna skriva recensioner om restaurangerna
Användare ska betygsätta restaurangerna i recensionen på en skala 1-5 (betyget är alltså required)
Användare måste logga in för att skriva recensioner. Välj mellan JWT eller Passport.
Applikationen ska publiceras på heroku eller något liknande.
VG-krav
Enbart admin kan CRUD:a restauranger
Kontrollera indata mot skadlig kod
Aggregerade funktioner:
- På förstasidan ska ni visa:
    - de tio bästa restaurangerna genom snittbetyg
    - genres av restauranger (pizzeria, vegetariskt osv)
Gränsfallsfeatures
Användarvänligt, användbart, presentabelt, responsivt
Betygsätta genom att klicka på stjärna, typ: ***** <- klicka på en av stjärnorna

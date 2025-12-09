# vocea-elevilor-cni
Platformă internă de raportare, sugestii și comunicare pentru elevii CNI Piatra Neamț.


Jurnal de Lucru și Raport de Implementare 

Proiect: Platforma „Vocea Elevilor”
Perioada de Lucru: 27 Noiembrie 2025 – 9 Decembrie 2025
I. Etapa 1: Fundația și Structura (27 Noiembrie – 28 Noiembrie)
Această etapă a avut ca scop stabilirea bazei vizuale și funcționale a întregii platforme.
•	Design Unificat: Am creat structura de bază a site-ului (meniul de navigare, subsolul și secțiunile principale) și am stabilit culorile și stilurile pentru a asigura un aspect modern și curat al tuturor elementelor.
•	Salvarea Datelor (Persistență): Am implementat un sistem care folosește memoria locală a browserului (localStorage) pentru a asigura că toate sesizările, sugestiile și setările nu se pierd la reîncărcarea paginii.
•	Formulare Inițiale: Am creat primele formulare unde elevii pot raporta Probleme în Școală sau pot lăsa Sugestii de îmbunătățire.
II. Etapa 2: Administrare și Control (29 Noiembrie – 1 Decembrie)
Obiectivul principal a fost crearea instrumentelor necesare Consiliului Elevilor pentru a gestiona datele.
•	Panoul de Administrare: Am creat o secțiune secretă, protejată de parolă, care este vizibilă doar administratorilor, asigurând separarea rolurilor.
•	Afișarea Listelor: Am dezvoltat sistemul care permite administratorilor să vadă toate sesizările primite (Probleme, Sugestii, Bullying etc.) într-o listă detaliată și să le poată șterge.
•	Notițe Admin: Am introdus posibilitatea ca administratorii să adauge comentarii sau notițe private la fiecare sesizare, pentru a urmări și documenta progresul rezolvării.
III. Etapa 3: Extensii și Funcții Cheie (2 Decembrie – 5 Decembrie)
În această fază s-au adăugat funcționalități esențiale pentru transparență și eficiență.
•	Categorii Suplimentare: Am adăugat formulare dedicate pentru raportarea Cazurilor de Bullying (cu accent pe anonimat) și pentru Probleme Academice / Solicitări de Sprijin.
•	Sondaje și Vot: Am creat secțiunea de Sondaj, unde elevii pot vota o singură dată. Rezultatele sunt afișate imediat sub formă de bare de progres vizuale (procente).
•	Prioritizare: Am introdus funcții în Panoul Admin pentru a Marca o sesizare ca Urgentă (acestea ies în evidență cu o margine roșie) și pentru a schimba statusul (din Nou în Rezolvat).
•	Măsurarea Eficienței: Am implementat o Bară de Progres dinamică în Panoul Admin care arată procentual câte sesizări din total au fost rezolvate, măsurând astfel performanța Consiliului.
•	Conținut Public: Am creat formularele necesare pentru ca administratorii să poată publica rapid Anunțuri Oficiale și Evenimente în Calendar, care apar imediat pe paginile dedicate.
IV. Etapa 4: Optimizare și Finalizare (8 Decembrie – 9 Decembrie)
Această etapă a inclus corecțiile finale, îmbunătățiri de utilizare și funcționalități interactive.
•	Corecții de Utilizare (UX): Am remediat un defect vizual unde culorile cardurilor nu erau afișate corect. De asemenea, am setat câmpurile de descriere (textarea) să poată fi redimensionate doar pe verticală, pentru a nu strica aspectul paginii.
•	Funcții Avansate Admin:
o	Am implementat funcția de Ștergere TOATE Datele, care permite resetarea completă a aplicației, utilă pentru testare sau repornire.
o	Am finalizat administrarea: Butonul de logare se schimbă acum în "Deconectare" după autentificare, iar ordinea butoanelor din meniu a fost optimizată.
•	Atașare Imagini: Am adăugat posibilitatea ca elevii să atașeze imagini la raportările de probleme, iar administratorii le pot vizualiza în Panoul Admin.
•	Animație Interactivă: Am adăugat o animație subtilă și rapidă: la click pe steluța din subsol, sunt generate exact 3 particule stelate, oferind un feedback vizual plăcut.

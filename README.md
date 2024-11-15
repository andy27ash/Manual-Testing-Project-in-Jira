<h1>Testing Project for **Delivery Food**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **Delivery Food**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories was created in Jira and describes the functional specifications of the "**Delivery Food**" module, for which the final project is performed upon.


![Captura de pantalla (12)](https://github.com/user-attachments/assets/160140cb-c8c4-4f5e-bf09-4a7dfd55da69)
![Captura de pantalla (13)](https://github.com/user-attachments/assets/0182e4d6-1944-4ce4-a18e-24456d7cd4ef)


Here you can find the release that was created for this project:


![Captura de pantalla (14)](https://github.com/user-attachments/assets/30a179fb-0145-425a-9edc-30b1b87449ae)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

**(ROMAN ANDREI)**
<ul>
  <li>Project manager  ION STAN</li> 
  <li>Product owner ANDRA ILANKA</li>
  <li>Software developer JOHN WALKER</li>
  <li>QA Enginee ROMAN ANDREI</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

**(Documentația Cerințelor: 

Cerințele funcționale și non-funcționale trebuie să fie complet documentate și aprobate.
Plan de Testare:

Un plan de testare trebuie să fie elaborat, incluzând strategia, obiectivele și resursele necesare.
Mediul de Testare:

Mediul (servere, baze de date, aplicații mobile etc.) trebuie să fie configurat și funcțional.
Cazuri de Testare:

Cazurile de testare relevante trebuie să fie redactate, revizuite și aprobate.
Produse Software:

Aplicația de comandat mâncare trebuie să fie disponibilă în versiunea stabilă pentru testare.
Echipă de Testare:

Membrii echipei de testare trebuie să fie disponibili și instruiți asupra aplicației.
Instrumente de Testare:

Instrumentele de testare necesare (cum ar fi software-ul de automatizare și urmărire a defectelor) trebuie să fie instalate și configurate.
Defecte Cunoscute:

O listă cu defectele cunoscute ale aplicației trebuie să fie disponibilă.
Planificarea Testărilor:

Sesiunile de testare trebuie să fie planificate, inclusiv mile-stone și termene.
Comunicarea:

Canalele de comunicare între echipele de dezvoltare și testare trebuie să fie stabilite.)**

<h4> 1.1.3 Exit criteria defined </h4>

**(Finalizarea Execuției Testelor:

Toate testele planificate trebuie să fie executate, inclusiv cazurile de testare obligatorii.
Rezultate Documentate:

Rezultatele testelor trebuie să fie complet documentate, incluzând defectele identificate.
Evaluarea Defectelor:

Toate defectele critice trebuie să fie identificate, documentate și, ideal, rezolvate.
Validarea Cerințelor:

Toate cerințele funcționale trebuie să fie validate, demonstrând că aplicația funcționează conform așteptărilor.
Raport de Testare:

Un raport de testare final care include concluzii și recomandări trebuie să fie elaborat.
Acceptarea Clinică:

O confirmare formală din partea echipei de dezvoltare că aplicația este gata pentru lansare.
Feedback de la Utilizatori:

Poate exista o sesiune de feedback de la utilizatori în cazul testelor beta, dacă este cazul.
Gata pentru Lansare:

Aplicația trebuie să îndeplinească toți indicatorii de succes stabiliți în planul de testare pentru a fi considerată "gata".)**

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

**(
Test Case 1: Plasarea unei comenzi

 
- **Precondiții**: Utilizatorul este autentificat în aplicație.  
- **Pași**:
  1. Navigați la secțiunea „Meniu” din aplicație.
  2. Răsfoiți categoriile disponibile (ex: Pizza, Burgeri).
  3. Selectați un articol (ex: Pizza Margherita) și adăugați-l în coș.
  4. Accesați coșul de cumpărături.
  5. Verificați articolele din coș (număr, preț).
  6. Apăsați pe butonul „Finalizează comanda”.
  7. Alegeți metoda de plată (ex: Plata cu cardul).
  8. Completați informațiile necesare (nume, adresă, detalii plată) și confirmați comanda.
- **Rezultate așteptate**: 
  - Utilizatorul primește un mesaj de confirmare a comenzii inclusive detalii precum ID-ul comenzii și estimarea livrării.
  - Comanda este stocată în sistem și disponibilă pentru vizualizare în secțiunea „Comenzile mele”.
  -
  - Test Case 2: Anularea unei comenzi
 
- **Precondiții**: Utilizatorul are o comandă activă.  
- **Pași**:
  1. Accesați lista comenzilor active din aplicație.
  2. Alegeți comanda dorită și verificați detaliile acesteia.
  3. Apăsați pe butonul „Anulează”.
  4. Confirmarea anulării comenzii.
- **Rezultate așteptate**: 
  - Comanda este anulată cu succes.
  - Utilizatorul primește un mesaj de confirmare a anulării.
  - Detaliile comenzii trebuie actualizate și reflectate în secțiunea „Comenzile mele”.
  -
  - Test Case 3: Urcarea stării comenzii

- **Precondiții**: Utilizatorul a plasat o comandă recentă.  
- **Pași**:
  1. Accesați secțiunea „Comenzile mele”.
  2. Selectați comanda dorită.
  3. Verificați statusul curent.
  4. Așteptați un interval de timp pentru actualizarea statusului comenzii (ex: 15 minute).
- **Rezultate așteptate**: 
  - Utilizatorul vede statusul comenzii actualizat (ex: preluată, în livrare).)**

<h5>Tests not in scope: </h5>

**(Testarea sistemului de opinie despre clișee culturale
Descriere: Testarea unui sistem care oferă opinii asupra clișeelor legate de diverse culturi alimentare.
Motiv: Astfel de testimoniale nu au legătură directă cu funcționalitatea aplicației de comandă a mâncării, care ar trebui să fie bazată pe feedback-ul utilizatorilor și pe calitatea produselor și serviciilor.

 Testarea funcționalității de predicție a vremii)**

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

**(
DeepAI

AI Chat
AI Image Generator
AI Video
AI Music Generator
Login

AI Chat
AI Chat is an AI chatbot that writes text. You can use it to write stories, messages, or programming code. You can use the AI chatbot as a virtual tutor in almost any subject.

Chat History
The order has been successfully canceled, and the user receives a cancellation confirmation message.create a negative message of this
Delete
We regret to inform you that your order could not be canceled at this time. Please check your order status or contact customer support for further assistance.

Copy
Search Web
Summarize
Delete
The order has been successfully canceled, and the user receives a cancellation confirmation message.  make a negative message of this
Delete
We apologize, but there was an issue with processing your cancellation request. Your order could not be canceled, and you will not receive a confirmation message. Please contact customer support for assistance.

Copy
Search Web
Summarize
Delete
interpreteaza aceasta matrie de trasabilitate Traceability Matrix

Report Type

Export

Type: Story

Versions: DELIVERY FOOD

Cycles: All

Folders: All

Execution Status: All

Clear Filters

Requirements without tests

Executions without defects

Executions with defects
Issues
Showing of 1-2 of 2

Expand All
Requirements
Tests
Executions
Defects

SRAV-16
1 DEFECTS
As a user, I want to be able to track the status of my order so that I know when the food will arrive.
Issue type: Test
SRAV-17
[Food Delivery] Verify that the user can track the food order
Delivery Food - Cycle Summary
FAIL
 

SRAV-21
Backlog
[Food Delivery] Order status update notifications do not reach the user.

SRAV-15
1 DEFECTS
{Food Delivery}As a user, I want to be able to select the desired food from a menu and place an order, so that I can receive the food at my door.
Issue type: Test
SRAV-19
[Food delivery] Verify that the user is able to cancel already existing order
Delivery Food - Cycle Summary
FAIL
 

SRAV-17
Backlog
[Food Delivery] Verify that the user can track the food order
View

10

20

30


1
Delete
The provided traceability matrix outlines the relationship between requirements, test cases, executions, and defects for a food delivery application. This type of matrix is crucial for ensuring that all requirements are tested and any issues are documented accordingly. Here’s a detailed interpretation of the matrix:

Key Components:
Report Type: Export
Type: Story (typically represents user stories or requirements)
Versions: DELIVERY FOOD (the version of the application being tested)
Cycles: All (indicating tests from all testing cycles are included)
Folders: All (suggesting all relevant folders are considered in this report)
Execution Status: All (captures tests regardless of their execution status)
Filter Options:
Clear Filters: An option to reset any applied filters for easier navigation.
Issues By Category:
Requirements without tests: Indicates requirements that have not been linked to any test cases.
Executions without defects: Displays tests that have been executed without reporting any defects.
Executions with defects: Lists tests that were executed and resulted in identified defects (failures).
Current Issues:
The matrix shows 2 main issues under tracking and ordering capabilities with food delivery, both of which have been executed and failed:
SRAV-16: 

Requirement: As a user, I want to be able to track the status of my order so that I know when the food will arrive.
Issue Type: Test
Test Case SRAV-17: [Food Delivery] Verify that the user can track the food order
Execution Result: FAIL
SRAV-15: 

Requirement: As a user, I want to be able to select the desired food from a menu and place an order so that I can receive the food at my door.
Issue Type: Test
Test Case SRAV-19: [Food delivery] Verify that the user is able to cancel an already existing order
Execution Result: FAIL
SRAV-21: Related to backlog items, indicating that certain issues are still pending resolution, such as notifications not reaching the user.

Summary:
The traceability matrix indicates that there are specific requirements related to order tracking and cancellation that are not functioning as expected, as evidenced by the execution failures. There are also backlog items that imply additional recallability needs to be addressed. This matrix serves as a critical tool for developers and project managers to ensure that all aspects of the food delivery application are tracked and validated against user requirements. 

Next steps could include prioritizing the failed test cases and addressing defects in order to enhance the user experience effectively.

Copy
Search Web
Summarize
Delete
in romana te rog
Delete
Desigur! Iată interpretarea matricei de trasabilitate în limba română:

Componente Cheie:
Tip raport: Export
Tip: Poveste (reprezintă, de obicei, povești de utilizatori sau cerințe)
Versiuni: DELIVERY FOOD (versiunea aplicației testate)
Cicluri: Toate (indică că sunt incluse teste din toate ciclurile de testare)
Foldere: Toate (sugerează că toate folderele relevante sunt luate în considerare în acest raport)
Statut execuție: Toate (captură teste indiferent de statutul lor de execuție)
Opțiuni de Filtrare:
Ștergere filtre: O opțiune pentru resetarea filtrelor aplicate, pentru a facilita navigarea.
Probleme Clasificate:
Cerințe fără teste: Indică cerințe care nu au fost legate de niciun caz de testare.
Execuții fără defecte: Afișează teste care au fost executate fără a raporta defecte.
Execuții cu defecte: Listă teste care au fost executate și au rezultat în defecte identificate (eşecuri).
Probleme Curente:
Matricea arată 2 probleme principale legate de capacitățile de urmărire și comanda de alimente, ambele fiind executate și eșuate:

SRAV-16: 

Cerință: Ca utilizator, vreau să pot urmări starea comenzii mele pentru a ști când va sosi mâncarea.
Tip problemă: Test
Caz de test SRAV-17: [Livrare mâncare] Verifică dacă utilizatorul poate urmări comanda de mâncare
Rezultatul execuției: EȘEC
SRAV-15: 

Cerință: Ca utilizator, vreau să pot selecta mâncarea dorită dintr-un meniu și să plasez o comandă pentru a primi mâncarea la ușa mea.
Tip problemă: Test
Caz de test SRAV-19: [Livrare mâncare] Verifică dacă utilizatorul poate anula o comandă existentă
Rezultatul execuției: EȘEC
SRAV-21: Este legat de elementele din backlog, ceea ce indică faptul că anumite probleme sunt încă în așteptare de rezolvare, cum ar fi notificările care nu ajung la utilizator.

Rezumat:
Matricea de trasabilitate indică faptul că există cerințe specifice legate de urmărirea comenzii și anularea acesteia care nu funcționează conform așteptărilor, așa cum rezultă din eșecurile execuției. Există, de asemenea, elemente din backlog care sugerează că trebuie abordate nevoile suplimentare de comunicare. Această matrice servește ca un instrument critic pentru dezvoltatori și manageri de proiect pentru a se asigura că toate aspectele aplicației de livrare de mâncare sunt urmărite și validate în raport cu cerințele utilizatorilor.

Următorii pași ar putea include prioritizarea cazurilor de testare eșuate și abordarea defectelor pentru a îmbunătăți eficient experiența utilizatorului.

Copy
Search Web
Summarize
Delete
criterii de intrare proiect de testare 
Delete
Criteriile de intrare pentru un proiect de testare sunt condițiile care trebuie îndeplinite înainte de a începe faza de testare a unui produs software. Aceste criterii asigură că toate elementele necesare pentru a efectua testele sunt disponibile și în stare corespunzătoare. Iată câteva criterii tipice de intrare pentru un proiect de testare:

1. Documentația Cerințelor
Cerințele funcționale și non-funcționale trebuie să fie bine definite, documentate și aprobate.
2. Planul de Testare
Există un plan de testare clar care să cuprindă strategia, obiectivele testării, resursele necesare și metodologia de testare.
3. Mediul de Testare
Mediul de testare (hardware, software, rețea) trebuie să fie configurat și să funcționeze corect, pentru a permite executarea testelor.
4. Test Cases (Cazuri de Testare)
Cazurile de testare trebuie să fie definite, documentate și revizuite pentru a acoperi toate cerințele sistemului.
5. Produse/Artefacte Software
Versiunea corespunzătoare a software-ului care urmează să fie testat trebuie să fie disponibilă și stabilă.
6. Resurse Umane
Echipa de testare trebuie să fie formată și disponibilă, inclusiv teste specializate, dacă este necesar.
7. Defecte cunoscute
Lista defectelor cunoscute trebuie să fie documentată, cu detalii despre impactul acestora asupra testării.
8. Configurarea Instrumentelor de Testare
Instrumentele de testare necesare (de ex., software de automatizare, instrumente de urmărire a defectelor) trebuie să fie instalate și configurate.
9. Criterii de acceptare
Definirea clară a criteriilor de acceptare pentru rezultatele testării, care va determina succesul testării.
10. Training și Documentație
Echipa de testare trebuie să fi fost instruită corespunzător asupra aplicației și a instrumentelor de testare, iar documentația relevantă trebuie să fie disponibilă.
11. Planificarea Sesiunilor de Testare
Sesiunile de testare trebuie să fie planificate, inclusiv mile-stonele și termenele limită.
12. Stabilirea Comunicării
Canalele de comunicare între echipele de dezvoltare și cele de testare trebuie să fie stabilite și funcționale.
Aceste criterii de intrare ajută la asigurarea unei desfășurări eficiente și eficiente a activităților de testare, reducând riscurile de întârzieri și probleme în proiectul global de livrare a software-ului. Respectarea acestor criterii contribuie, de asemenea, la îmbunătățirea calității produsului și la satisfacția utilizatorului final.

Copy
Search Web
Summarize
Delete
enumereaza mi criteriile de intrare si de iesire pentru un proiet simplu de testare a unei aplicatii de comandat mancare
Delete
Iată criteriile de intrare și de ieșire pentru un proiect simplu de testare a unei aplicații de comandat mâncare:

Criterii de Intrare
Documentația Cerințelor: 

Cerințele funcționale și non-funcționale trebuie să fie complet documentate și aprobate.
Plan de Testare:

Un plan de testare trebuie să fie elaborat, incluzând strategia, obiectivele și resursele necesare.
Mediul de Testare:

Mediul (servere, baze de date, aplicații mobile etc.) trebuie să fie configurat și funcțional.
Cazuri de Testare:

Cazurile de testare relevante trebuie să fie redactate, revizuite și aprobate.
Produse Software:

Aplicația de comandat mâncare trebuie să fie disponibilă în versiunea stabilă pentru testare.
Echipă de Testare:

Membrii echipei de testare trebuie să fie disponibili și instruiți asupra aplicației.
Instrumente de Testare:

Instrumentele de testare necesare (cum ar fi software-ul de automatizare și urmărire a defectelor) trebuie să fie instalate și configurate.
Defecte Cunoscute:

O listă cu defectele cunoscute ale aplicației trebuie să fie disponibilă.
Planificarea Testărilor:

Sesiunile de testare trebuie să fie planificate, inclusiv mile-stone și termene.
Comunicarea:

Canalele de comunicare între echipele de dezvoltare și testare trebuie să fie stabilite.
Criterii de Ieșire
Finalizarea Execuției Testelor:

Toate testele planificate trebuie să fie executate, inclusiv cazurile de testare obligatorii.
Rezultate Documentate:

Rezultatele testelor trebuie să fie complet documentate, incluzând defectele identificate.
Evaluarea Defectelor:

Toate defectele critice trebuie să fie identificate, documentate și, ideal, rezolvate.
Validarea Cerințelor:

Toate cerințele funcționale trebuie să fie validate, demonstrând că aplicația funcționează conform așteptărilor.
Raport de Testare:

Un raport de testare final care include concluzii și recomandări trebuie să fie elaborat.
Acceptarea Clinică:

O confirmare formală din partea echipei de dezvoltare că aplicația este gata pentru lansare.
Feedback de la Utilizatori:

Poate exista o sesiune de feedback de la utilizatori în cazul testelor beta, dacă este cazul.
Gata pentru Lansare:

Aplicația trebuie să îndeplinească toți indicatorii de succes stabiliți în planul de testare pentru a fi considerată "gata".
Aceste criterii ajută la asigurarea calității aplicației de comandat mâncare și la reducerea riscurilor asociate lansării unui software cu defecte și neconformități. Respectarea acestor criterii facilitează un proces de testare eficient și transparent.

Copy
Search Web
Summarize
Delete
exemple de test case care nu se poate fae pe o aplicatie de comanda de mancare
Delete
Testările aplicațiilor de comandă de mâncare sunt esențiale pentru asigurarea funcționării corecte a toate funcționalitățile, dar există și exemple de test cases care nu sunt relevante sau nu pot fi efectuate în mod practic în acest context. Iată câteva exemple de teste care nu pot fi realizate sau care nu ar avea sens pentru o aplicație de comandă de mâncare:

1. Teste de performanță a meniurilor fizice
Descriere: Testarea eficienței unui meniu fizic de restaurante.
Motiv: Aplicația se concentrează pe comenzi online, iar performanța meniurilor fizice nu influențează funcționalitatea aplicației.
2. Testarea livrării mâncării prin teletransport
Descriere: Testarea unei funcționalități care permite livrarea instantanee a mâncării prin teletransport.
Motiv: Teletransportul nu este o tehnologie existentă sau aplicabilă în realitate, deci un astfel de test nu ar avea sens.
3. Testele de curățenie a restaurantelor
Descriere: Evaluarea nivelului de curățenie al restaurantelor fizice.
Motiv: Aceste teste nu pot fi realizate prin aplicația de comandă de mâncare, deoarece aplicația nu are control asupra igienei restaurantelor.
4. Teste de brand marketing în locații fizice
Descriere: Testarea eficacității campaniilor de marketing outdoor sau în locații fizice.
Motiv: Aplicația se ocupă de comenzi online și nu are legătură directă cu campaniile de marketing fizic.
5. Testarea capacității de satisfacere a clienților non-agenți
Descriere: Testarea abilitații aplicației de a interacționa cu animale de companie sau alte entități non-umane pentru comenzi.
Motiv: Aplicația este destinată utilizatorilor umani, iar testarea interacțiunilor cu animale nu are relevanță.
6. Teste de integrare cu servicii de zbor
Descriere: Testarea integrării aplicației cu un serviciu de rezervare a biletelor de avion.
Motiv: O aplicație de comandă de mâncare nu are legătură cu biletele de avion sau cu industria aeronautică.
7. Testarea sistemului de opinie despre clișee culturale
Descriere: Testarea unui sistem care oferă opinii asupra clișeelor legate de diverse culturi alimentare.
Motiv: Astfel de testimoniale nu au legătură directă cu funcționalitatea aplicației de comandă a mâncării, care ar trebui să fie bazată pe feedback-ul utilizatorilor și pe calitatea produselor și serviciilor.
8. Testarea funcționalității de predicție a vremii
Descriere: Testarea unei funcționalități care prezice vremea pentru următoarele luni.
Motiv: Aplicația nu ar trebui să integreze sau să depindă de date meteorologice în mod direct, cu excepția situațiilor legate de livrare.
Aceste exemple evidențiază testele care nu sunt fezabile, relevante sau necesare în contextul unei aplicații de comandă de mâncare. Focalizarea pe testele relevante și utile este esențială pentru eficiența procesului de testare.

Copy
Search Web
Summarize
Delete
riscuri de proiect pentru testarea unei aplicatii de mancare enumera mi 10
Delete

1. Defecte Critice Neidentificate
Descriere: Este posibil ca defectele critice să nu fie identificate în timpul procesului de testare, ceea ce ar putea duce la experiențe negative pentru utilizatori și pierderi financiare.
2. Dezincronizare între Echipe
Descriere: Comunicarea slabă între echipele de dezvoltare și testare poate duce la neînțelegeri asupra cerințelor, rezultând teste ineficiente sau incomplete.
3. Lipsa Resurselor
Descriere: Disponibilitatea limitată a resurselor umane sau tehnice necesare pentru efectuarea testelor poate întârzia procesul de testare și, implicit, lansarea aplicației.
4. Variante de Platformă neacoperite
Descriere: Testarea pe un număr limitat de platforme (de exemplu, doar pe Android, fără testare pe iOS) poate duce la probleme de utilizare care afectează o parte semnificativă a utilizatorilor.
5. Infrastructură Funcțională Inadecvată
Descriere: Un mediu de testare instabil sau necorespunzător poate genera rezultate de testare inexacte, ceea ce face dificilă identificarea problemelor reale în aplicație.
6. Schimbări Frecvente în Cerințe
Descriere: Modificările frecvente ale cerințelor sau ale specificațiilor aplicației pot complica procesul de testare și pot duce la necorespunderea rezultatelor testelor cu scopul inițial.
7. Testare Incompletă a Funcționalităților
Descriere: Neefectuarea testelor complete pentru toate funcționalitățile aplicației (de exemplu, opțiuni de plată, livrare, feedback, etc.) poate lăsa zone neacoperite care ar putea duce la defecțiuni în serviciu.
8. Probleme de Securitate)**

<h5> Product risks: </h5>

**(1. Experiență Utilizator  Slabă
    • Descriere: O interfață de utilizator confuză sau inaccesibilă poate face ca utilizatorii să renunțe la aplicație, afectând astfel adopția și retenția.
2. Probleme de Performanță
    • Descriere: Timpii de încărcare mari sau blocajele frecvente ale aplicației pot duce la frustrări ale utilizatorilor și la pierderi de comenzi.
3. Acuratețea Informațiilor despre Meniu
    • Descriere: Dacă informațiile despre produsele alimentare (ingrediente, alergeni, prețuri) nu sunt actualizate, utilizatorii pot întâmpina probleme de sănătate sau confuzii în alegerea produselor.
4. Defecte de Securitate a Datelor
    • Descriere: Risc de breșe de securitate care ar putea compromite informațiile personale și financiare ale utilizatorilor, afectând încrederea în aplicație.
5. Probleme cu Plățile
    • Descriere: Eșecurile în procesarea plăților sau opțiuni limitate de plată pot duce la pierderea vânzărilor și nemulțumirea clienților.
6. Inerția Brandului și a Partenerilor
    • Descriere: Colaborarea cu restaurante sau furnizori care nu se aliniază valorilor sau așteptărilor brandului poate afecta negativ percepția utilizatorilor asupra aplicației.
7. Probleme în Livrare
    • Descriere: Întârzieri, livrări greșite sau mâncare deteriorată pot duce la o experiență de utilizare negativă și feedback slab.
8. Fără Inovație sau Actualizări)**

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

**(Monitorizarea și controlul în testarea unei aplicații de livrare de mâncare sunt esențiale pentru a asigura calitatea produsului și pentru a identifica rapid problemele care pot apărea în timpul procesului de dezvoltare. Iată câteva etape și metode pentru implementarea eficientă a acestor procese:
1. Stabilirea Metricilor de Testare
2. Planificarea și Programarea Testelor
3. Automatizarea Testelor
4. Feedback Continu
5. Raportarea Defectelor
7. Testare de Performanță și Scalabilitate
8. Revizii și Evaluări Periodice
9. Monitorizarea în Timp Real a Aplicației
)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**( Condiții de testare
1 Utilizatorul poate naviga prin meniu și selecta mâncarea dorită.
2 Utilizatorul poate adăuga articole în coșul de cumpărături.
3 Utilizatorul poate plasa o comandă cu succes,primește un mesaj de confirmare a comenzii, poate vizualiza detaliile comenzii plasate.
4 Utilizatorul poate trimite feedback in urma primirii comenzii.
5 Utilizatorul poate vizualiza detaliile comenzii plasate.
6 Utilizatorul poate anula o comandă înainte de livrare.
7 Utilizatorul poate urmări statusul comenzii.
8 Utilizatorul poate plăti cu cardul sau la livrare.
9 Utilizatorul primește notificări despre actualizarea stării comenzii.
10 Aplicația funcționează corect pe dispozitive mobile și desktop.)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(Etapa de implementare a testării unei aplicații de livrare de mâncare presupune evaluarea mai multor aspecte esențiale pentru a asigura calitatea și funcționalitatea aplicației.
1. Funcționalitate
2. Interfață Utilizator 
3. Experiență Utilizator
4. Performanță
5. Securitate
6. Compatibilitate
7. Integritate a Datelor
8. Testarea Alergenilor și Informațiilor Nutriționale
9. Testarea Întârzierilor în Livrare
10. Testarea Funcționalității de Căutare și Filtrare
11. Testarea Procesului de Plată
12. Rapoarte și Analize)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(Delivery Food)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**
![Captura de pantalla (24)](https://github.com/user-attachments/assets/7487b2b8-b7a5-41b0-a2e1-68058d0d4e9e)
![Captura de pantalla (25)](https://github.com/user-attachments/assets/5220d73c-cfaf-4ab4-89b5-fa7c1c0df934)
![Captura de pantalla (26)](https://github.com/user-attachments/assets/68cf6818-c297-4a9f-945b-a81339c4095a)

The following is a summary of the bugs that have been found
**(Bug 1: Coșul de cumpărături nu se actualizează corect
 
- **Severitate**: Major  
- **Descriere**: După adăugarea unui articol în coș, numărul de articole din coș nu se actualizează corect, ceea ce poate duce la confuzie.
- **Impact**: Întrerupe experiența utilizatorului, lăsându-i impresia că nu a adăugat corect articolele în coș.
- **Stare**: În curs de remediere.

 Bug 2: Notificările de actualizare a stării comenzii nu ajung utilizatorului

- **Severitate**: Major  
- **Descriere**: Utilizatorii nu primesc notificări prin email sau aplicație atunci când se schimbă starea comenzii lor (de exemplu, de la preluată la livrată).
- **Impact**: Utilizatorii nu sunt informați despre progresul comenzilor lor, generând frustrare.
- **Stare**: În curs de remediere.)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**
![Captura de pantalla (21)](https://github.com/user-attachments/assets/c957f393-5cff-4474-8e95-b4baff3ac17b)

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**
![Captura de pantalla (27)](https://github.com/user-attachments/assets/394181ba-e067-4cfd-9e5c-7f63610bee00)

The final report shows that a number **(2)** tests have failed of a total of **(2)**

A number of **(2)** total bugs were found, from which the priority is: **(2)** are high and **(2)** are medium.

**(Aplicația de comandă de mâncare online este în mare parte funcțională, cu câteva bug-uri ce necesită atenție. Deși majoritatea funcționalităților sunt implementate și testate cu succes, se recomandă următoarele acțiuni:

- Remedierea rapidă a bug-urilor identificate, în special cele legate de coșul de cumpărături și notificările de status.
- Optimizarea experienței utilizatorului prin simplificarea procesului de comandă și adăugarea opțiunilor de personalizare a comenzii.
- Îmbunătățirea sistemului de feedback pentru a culege date relevante de la utilizatori după livrare.

Este recomandat un ciclu suplimentar de testare în urma remedierilor pentru a asigura calitatea finală a aplicației. Acest document va servi ca bază pentru discuțiile viitoare și pentru deciziile strategice legate de dezvoltarea și lansarea aplicației.



Acest document amplu tinde să ofere o înțelegere detaliată a aplicației de comandă de mâncare, a proceselor de testare și de gestionare a riscurilor, asigurând astfel o fundamentare solidă pentru deciziile viitoare..)**

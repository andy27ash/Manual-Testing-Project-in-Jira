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
Plan de Testare:Un plan de testare trebuie să fie elaborat, incluzând strategia, obiectivele și resursele necesare.

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

**(Testările aplicațiilor de comandă de mâncare sunt esențiale pentru asigurarea funcționării corecte a toate funcționalitățile, dar există și exemple de test cases care nu sunt relevante sau nu pot fi efectuate în mod practic în acest context. Iată câteva exemple de teste care nu pot fi realizate sau care nu ar avea sens pentru o aplicație de comandă de mâncare:

1. Teste de performanță a meniurilor fizice

2. Testarea livrării mâncării prin teletransport

3. Testele de curățenie a restaurantelor

4. Teste de brand marketing în locații fizice

5. Testarea capacității de satisfacere a clienților non-agenți

6. Teste de integrare cu servicii de zbor

7. Testarea sistemului de opinie despre clișee culturale

8. Testarea funcționalității de predicție a vremii
)**

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

# Prasību formulējums: basketbola spēles rezultāta prognozēšanas sistēma

## 1. Konteksts un mērķis

Sistēmas mērķis ir izstrādāt mašīnmācīšanās prognozēšanas rīku, kas, izmantojot vēsturiskos un pirmsspēles statistikas datus, automātiski prognozē basketbola spēles iznākumu. Sistēmas efektivitāte paredzēta gan kvantitatīvai veiktspējas, gan izmantoto faktoru būtiskuma izvērtēšanai.

Prasību formulējumā ņemti vērā arī līdzīgo risinājumu aprakstā izceltie aspekti: komandu uzbrukuma un aizsardzības efektivitāte, pēdējo spēļu forma, sezonas uzvaru attiecība, mājas spēles priekšrocība, spēļu grafiks, atpūtas dienas, ceļošana, spēlētāju pieejamība/traumas, kā arī uzvaras varbūtības un punktu starpības prognozēšana.

## 2. Sistēmas funkcijas / iezīmes

| Nr. | Sistēmas funkcija / iezīme | Apraksts | Prioritāte |
|---|---|---|---|
| 1 | Vēsturisko datu ievade | Sistēmai jāspēj saņemt vēsturisko basketbola spēļu statistikas datus. | Must |
| 2 | Pirmsspēles datu ievade | Sistēmai jāspēj saņemt konkrētai spēlei pieejamos pirmsspēles statistikas datus. | Must |
| 3 | Datu apstrāde prognozēšanai | Sistēmai jāapkopo un jāizmanto ievaddati tā, lai no tiem varētu iegūt prognozei nepieciešamos rādītājus. | Must |
| 4 | Komandu salīdzinošo rādītāju izmantošana | Sistēmai jāņem vērā abu komandu savstarpēji salīdzināmi rādītāji, tostarp uzbrukuma un aizsardzības efektivitāte. | Must |
| 5 | Komandu aktuālās formas ņemšana vērā | Sistēmai jāņem vērā komandu pēdējo spēļu rezultāti un aktuālā forma. | Must |
| 6 | Spēles konteksta ņemšana vērā | Sistēmai jāņem vērā spēles apstākļi, piemēram, mājas spēles priekšrocība, spēļu grafiks un atpūtas dienas, ja šādi dati ir pieejami. | Should |
| 7 | Spēlētāju pieejamības ņemšana vērā | Sistēmai jāņem vērā nozīmīgu spēlētāju pieejamība vai traumu statuss, ja šādi dati ir pieejami. | Should |
| 8 | Spēles iznākuma prognoze | Sistēmai jāprognozē konkrētās spēles uzvarētājs. | Must |
| 9 | Uzvaras varbūtības prognoze | Sistēmai jānorāda katras komandas uzvaras varbūtība procentos, ja izvēlētais prognozes modelis to nodrošina. | Should |
| 10 | Prognozētās punktu starpības iegūšana | Sistēmai jāspēj nodrošināt prognozēto punktu starpību kā papildu prognozes rezultātu. | Could |
| 11 | Prognozes skaidrojums | Sistēmai jāparāda faktori, kas būtiski ietekmējuši prognozi. | Should |
| 12 | Sistēmas veiktspējas novērtēšana | Sistēmai jānodrošina iespēja kvantitatīvi novērtēt prognožu veiktspēju uz testdatiem. | Must |
| 13 | Faktoru būtiskuma novērtēšana | Sistēmai jānodrošina iespēja noteikt, kuri ievaddati visvairāk ietekmē prognozes rezultātu. | Must |
| 14 | Reāllaika spēles datu prognozēšana | Sistēmai jāspēj izmantot spēles laikā iegūtus datus un atjaunot prognozi. | Won't |

## 3. Lietotāju stāsti (User Stories)

### Must

**US-01.** Kā datu analītiķis, es vēlos ielādēt vēsturisko spēļu statistikas datus, jo man ir nepieciešami dati prognozēšanas modeļa izmantošanai un izvērtēšanai.

**US-02.** Kā sistēmas lietotājs, es vēlos ievadīt konkrētās spēles pirmsspēles statistikas datus, jo vēlos iegūt prognozi pirms spēles sākuma.

**US-03.** Kā sistēmas lietotājs, es vēlos, lai sistēma apstrādā ievadītos datus, jo vēlos automātiski sagatavot informāciju spēles iznākuma prognozēšanai.

**US-04.** Kā sistēmas lietotājs, es vēlos, lai prognozēšanā tiktu salīdzināta abu komandu uzbrukuma un aizsardzības efektivitāte, jo vēlos, lai prognoze balstītos uz komandu snieguma rādītājiem.

**US-05.** Kā sistēmas lietotājs, es vēlos, lai prognozēšanā tiktu ņemta vērā komandu pēdējo spēļu forma, jo vēlos, lai prognoze atspoguļotu aktuālo komandu sniegumu.

**US-06.** Kā sistēmas lietotājs, es vēlos saņemt prognozēto spēles uzvarētāju, jo vēlos pirms spēles zināt sistēmas prognozēto iznākumu.

**US-07.** Kā datu analītiķis, es vēlos novērtēt prognožu veiktspēju uz testdatiem, jo vēlos kvantitatīvi izvērtēt sistēmas efektivitāti.

**US-08.** Kā datu analītiķis, es vēlos noteikt būtiskākos prognozes ietekmējošos faktorus, jo vēlos saprast, kuri rādītāji ir nozīmīgākie spēles iznākuma prognozēšanā.

### Should

**US-09.** Kā sistēmas lietotājs, es vēlos, lai prognozēšanā tiktu ņemta vērā mājas spēles priekšrocība, spēļu grafiks un atpūtas dienas, jo vēlos iekļaut spēles kontekstu prognozē.

**US-10.** Kā sistēmas lietotājs, es vēlos, lai prognozēšanā tiktu ņemta vērā nozīmīgu spēlētāju pieejamība vai traumas, jo vēlos ņemt vērā komandas sastāva ietekmi uz spēles iznākumu.

**US-11.** Kā sistēmas lietotājs, es vēlos redzēt uzvaras varbūtību procentos, jo vēlos saprast prognozes varbūtisko raksturu, nevis tikai prognozēto uzvarētāju.

**US-12.** Kā sistēmas lietotājs, es vēlos redzēt prognozes ietekmējošos faktorus, jo vēlos saprast, kāpēc sistēma ir nonākusi pie konkrētā prognozes rezultāta.

### Could

**US-13.** Kā sistēmas lietotājs, es vēlos redzēt prognozēto punktu starpību, jo vēlos iegūt detalizētāku informāciju par sagaidāmo spēles iznākumu.

### Won't (šajā versijā)

**US-14.** Kā sistēmas lietotājs, es vēlos saņemt prognozi, kas tiek automātiski atjaunota spēles laikā, jo vēlos sekot prognozes izmaiņām reāllaikā.

> Šī funkcionalitāte šajā darba versijā netiek iekļauta; avotos reāllaika prognozēšana ir aprakstīta kā nozīmīgs nozares izaicinājums, nevis kā darba mērķī obligāti definēta sistēmas funkcija.

## 4. Prioritizēšana pēc MoSCoW metodes

### Must have — obligāti

Šīs funkcijas ir nepieciešamas, lai sistēma izpildītu darba pamatmērķi: izmantotu vēsturiskos un pirmsspēles datus un prognozētu spēles iznākumu, kā arī ļautu novērtēt sistēmas efektivitāti un faktoru būtiskumu.

- F-1: Vēsturisko datu ievade
- F-2: Pirmsspēles datu ievade
- F-3: Datu apstrāde prognozēšanai
- F-4: Komandu salīdzinošo rādītāju izmantošana
- F-5: Komandu aktuālās formas ņemšana vērā
- F-8: Spēles iznākuma prognoze
- F-12: Sistēmas veiktspējas novērtēšana
- F-13: Faktoru būtiskuma novērtēšana

### Should have — svarīgi

Šīs funkcijas būtiski papildina prognozes kvalitāti un interpretējamību, taču pamatprognozi iespējams definēt arī bez tām.

- F-6: Spēles konteksta ņemšana vērā
- F-7: Spēlētāju pieejamības ņemšana vērā
- F-9: Uzvaras varbūtības prognoze
- F-11: Prognozes skaidrojums

### Could have — vēlams

Šīs funkcijas piešķir papildu vērtību, bet nav nepieciešamas pamatfunkcionalitātes nodrošināšanai.

- F-10: Prognozētās punktu starpības iegūšana

### Won't have — nav šīs versijas tvērumā

- F-14: Reāllaika spēles datu prognozēšana

## 5. Prasību kopsavilkums

Sistēmas minimālajai versijai jāspēj saņemt vēsturiskos un pirmsspēles datus, izmantot komandu snieguma un aktuālās formas rādītājus, prognozēt spēles uzvarētāju un izmērīt prognozēšanas veiktspēju, kā arī noteikt būtiskākos prognozes faktorus.

Paplašinātā versija paredz uzvaras varbūtības un prognozes skaidrojuma attēlošanu, izmantojot arī spēles konteksta un spēlētāju pieejamības informāciju. Prognozētā punktu starpība ir definēta kā papildu funkcionalitāte, bet reāllaika spēles prognozēšana atstāta ārpus šīs versijas tvēruma.

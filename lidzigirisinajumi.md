## Risinājumi

T-Rank: Šis modelis darbojas uz ļoti līdzīgiem pamatiem kā KenPom, analizējot komandu uzbrukuma un aizsardzības efektivitāti uz 100 bumbas kontrolēm un izmantojot spēka reitingu sistēmu ar nosaukumu Barthag. Tā galvenā atšķirība un unikālā iezīme ir matemātiski iebūvētais "nesenuma faktors". Algoritms pakāpeniski samazina vecāku spēļu statistisko nozīmi, ļaujot modelim daudz precīzāk atspoguļot komandas pašreizējo sportisko formu vai izmaiņas sastāvā. Prognozējot konkrētā spēles uzvarētāju un punktu starpību, algoritms tieši salīdzina abu komandu Barthag reitingus un pielāgo rezultātu mājas spēles priekšrocībai.[[1]](https://adamcwisports.blogspot.com/p/every-possession-counts.html)

KenPom: Šis modelis pamatā izmanto no spēles tempa neatkarīgu statistiku, lai objektīvi salīdzinātu komandas. Algoritms aprēķina komandas koriģēto efektivitāti, mērot gūtos un ielaistos punktus uz 100 bumbas kontrolēm un pielāgojot tos pretinieku spēkam. Spēļu iznākumu un uzvaras varbūtības prognozēšanai savstarpējos mačos tas izmanto matemātisko Log5 formulu un komandas Pitagora izredzes, kas novērtē komandas patieso spēku, balstoties uz iegūto un zaudēto punktu attiecību, nevis tikai parastu uzvarēto un zaudēto spēļu skaitu.[[2]](https://kenpom.com/blog/ratings-glossary/)

ESPN BPI (Basketball Power Index): Šis modelis ir izstrādāts, lai novērtētu komandas patieso spēku nākotnes spēlēs, salīdzinot komandu efektivitāti uzbrukumā un aizsardzībā vienas bumbas kontroles ietvaros. Modeļa spēcīgākā īpašība ir padziļināta ārējā konteksta un spēļu grafika dati. Algoritms aprēķina uzvaras varbūtību, matemātiski pielāgojot bāzes reitingus tādiem faktoriem kā mājas spēles priekšrocība, ceļošanas attālums, atpūtas dienu skaits starp spēlēm un nozīmīgu spēlētāju pieejamība vai traumas. [[3]](https://www.espn.co.uk/nba/story/_/id/13984129/what-espn-nba-basketball-power-index)

XGBoost: Šis mašīnmācīšanās modelis izmanto lēmumu koku ansambļa algoritmu, lai atklātu sarežģītas kopsakarības vēsturisko spēļu datos. Atšķirībā no iepriekš definētām ekspertu formulām, šis modelis datu nozīmīgumu nosaka automātiski, un eksperimentos ir secināts, ka vislielāko matemātisko svaru spēles iznākuma prognozēšanā tas piešķir komandu pēdējo piecu spēļu uzvaru procentuālajai starpībai un sezonas kopējās uzvaru attiecības starpībai. Papildus šiem dinamiskajiem un ilgtermiņa rādītājiem algoritms aprēķinos būtiski balstās arī uz mājas spēles priekšrocību, efektīvās metienu precizitātes un atlēkušo bumbu kontroles atšķirībām starp abām komandām. Veicot bināru klasifikāciju, modelis analizē šos faktorus, lai prognozētu uzvaru vai zaudējumu, un neatkarīgā testu kopā tas uzrādīja 73,6% prognožu precizitāti.[[4]](https://www.researchgate.net/publication/398545691_Research_on_Predicting_the_Probability_of_Winning_Basketball_Games_Based_on_Machine_Learning_Models)

## Atsauces

[1] [Adam's WI Sports Blog](https://adamcwisports.blogspot.com/p/every-possession-counts.html)

[2] [kenpom.com, Ratings Glossary](https://kenpom.com/blog/ratings-glossary/)

[3] [What is ESPN's NBA Basketball Power Index?](https://www.espn.co.uk/nba/story/_/id/13984129/what-espn-nba-basketball-power-index)

[4] Zhang, Zhiqing. (2025). [Research on Predicting the Probability of Winning Basketball Games Based on Machine Learning Models](https://www.researchgate.net/publication/398545691_Research_on_Predicting_the_Probability_of_Winning_Basketball_Games_Based_on_Machine_Learning_Models).  

## Risinājuma tabula

| Risinājuma nosaukums | Galvenā aprēķinu bāze un dati | Unikālā analītiskā iezīme | Prognozes iznākums |
| --- | --- | --- | --- |
| **KenPom** | No spēles tempa neatkarīga statistika, mērot komandu efektivitāti uz 100 bumbas kontrolēm. | Novērtē komandas patieso spēku, objektīvi salīdzinot gan ātri, gan lēni spēlējošas komandas. | Uzvaras varbūtība procentos un prognozētā punktu starpība. |
| **T-Rank** | Uzbrukuma un aizsardzības efektivitāte uz 100 bumbas kontrolēm. | Matemātisks "nesenuma faktors" – automātiski samazina par 40 dienām vecāku spēļu statistisko nozīmi aprēķinos. | Konkrēta spēles uzvarētājs un gaidāmā punktu starpība. |
| **ESPN BPI** | Efektivitāte uz vienu bumbas kontroli un spēļu grafika dati. | Kvantitatīvi aprēķina ārējo apstākļu ietekmi – ceļošanas attālumu, atpūtas dienu trūkumu un traumu ietekmi. | Spēles uzvaras varbūtība un spēka reitinga pielāgojumi nākotnei. |
| **XGBoost** | Algoritms, kas apmācīts ar 6152 vēsturiskajām spēlēm un 35 ievaddatu pazīmēm. | Vislielāko nozīmi piešķir komandu uzvaru starpībai pēdējās 5 spēlēs. | Paredz uzvaru vai zaudējumu ar 73,6% precizitāti. |

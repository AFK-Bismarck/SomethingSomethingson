# Basketbola spēles rezultāta prognozēšana

## Ievads

Basketbola spēļu rezultātu prognozēšana tiek plaši atzīta par aktuālu izpētes jomu datu analītikā un sporta zinātnē. [[1]](https://www.researchgate.net/publication/330116252_NBA_Game_Result_Prediction_Using_Feature_Analysis_and_Machine_Learning) Līdz ar datu ievākšanas tehnoloģiju attīstību, sporta nozare kļūst arvien analītiskāka, un spēja precīzi paredzēt spēles iznākumu vai identificēt uzvaru nesošos faktorus sniedz tiešu praktisko labumu treneriem, komandu menedžmentam un sporta stratēģiem lēmumu pieņemšanā.

## Problēmas nostāde

Basketbols ir augstas dinamikas sporta veids, kurā spēles gala rezultātu ietekmē komplicēts savstarpēji saistītu faktoru kopums. Pie šiem faktoriem pieder individuālo spēlētāju sniegums un veselības stāvoklis, komandas stratēģija, spēļu kalendāra blīvums (piemēram, atpūtas dienas un izbraukumi), kā arī psiholoģiskie faktori un spēles iekšējā dinamika. [[2]](https://www.researchgate.net/publication/361384889_Basketball_players'_score_prediction_using_artificial_intelligence_technology_via_the_Internet_of_Things)

Aktualitāti pamato vairāki būtiski izaicinājumi, ko izceļ jaunākie pētījumi:
* **Datu sarežģītība un nelinearitāte:** Tradicionālās statistikas metodes (korelācija, lineārā regresija) bieži vien nespēj identificēt slēptās likumsakarības liela apjoma daudzdimensionālos datos. Pētnieki norāda, ka sarežģītu modeļu, piemēram, grafu neironu tīklu (*GCN*), atbalsta vektoru mašīnu (*SVM*) un gradientu palielināšanas algoritmu (*XGBoost*), izmantošana ir kļuvusi par nepieciešamību [[3]](https://pmc.ncbi.nlm.nih.gov/articles/PMC10217531/).
* **Reāllaika lēmumu pieņemšana:** Mūsdienu izaicinājums ir radīt modeļus, kas spēj apstrādāt spēles datus reāllaikā un nodrošināt augstu precizitāti dažādos spēles posmos [[4]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11265715/).
* **Izskaidrojamības trūkums (*Black-box* problēma):** Lai gan mašīnmācīšanās modeļi sasniedz augstu precizitāti, sporta nozarei ir kritiski svarīgi saprast *kāpēc* modelis pieņēmis šādu lēmumu. Pētījumos tiek uzsvērta nepieciešamība integrēt izskaidrojamā mākslīgā intelekta (*XAI*) metodes, piemēram, *SHAP* vērtības, lai identificētus svarīgākos spēles rādītājus (piemēram, aizsardzības atlēkušās bumbas un kļūdu skaitu) [[4]](https://pmc.ncbi.nlm.nih.gov/articles/PMC11265715/).


## Darba un novērtēšanas mērķis

**Darba mērķis**
Izstrādāt mašīnmācīšanās prognozēšanas rīku (modeli), kas, integrējot un apstrādājot vēsturiskos un pirmsspēles statistikas datus, spēj automātiski un ar augstu precizitāti prognozēt basketbola spēļu iznākumu.

**Novērtēšanas mērķis**
Kvantitatīvi un kvalitatīvi izvērtēt izstrādātās sistēmas efektivitāti:
1. **Veiktspējas novērtēšana:**
2. **Faktoru būtiskuma novērtēšana:**


## Līdzīgo risinājumu pārskats

Pilnu līdzīgo risinājumu aprakstu un analīzi skatīt [šeit](lidzigirisinajumi.md).


## Atsauces

[1] Thabtah, F., Zhang, L., & Abdel-Jaber, H. (2019). [NBA Game Result Prediction Using Feature Analysis and Machine Learning](https://www.researchgate.net/publication/330116252_NBA_Game_Result_Prediction_Using_Feature_Analysis_and_Machine_Learning). *ResearchGate*.

[2] Su, F., & Chen, M. (2022). [Basketball players' score prediction using artificial intelligence technology via the Internet of Things.](https://www.researchgate.net/publication/361384889_Basketball_players'_score_prediction_using_artificial_intelligence_technology_via_the_Internet_of_Things) *The Journal of Supercomputing*.


[3] Li, Y., et al. (2023). [Enhancing Basketball Game Outcome Prediction through Fused Graph Neural Networks](https://pmc.ncbi.nlm.nih.gov/articles/PMC10217531/). *PMC / NIH*.

[4] Zhou, Y., et al. (2024). [Integration of machine learning XGBoost and SHAP models for NBA game outcome prediction and quantitative analysis methodology](https://pmc.ncbi.nlm.nih.gov/articles/PMC11265715/). *PMC / NIH*.

# AMALEA – Learning Path für Bewerbungsgespräche

> Diese Datei ist Marcos persönliche Vorbereitungshilfe für Interviews, in denen
> AMALEA als Portfolio-Projekt zur Sprache kommt. Sie fasst zusammen, was im
> Repo tatsächlich steckt, was Marcos ehrliche Rolle dabei war, und wie er
> inhaltlich zu den Kursthemen sprechfähig bleibt.

---

## 1. Elevator-Pitch (auswendig lernen)

> "AMALEA ist ein sechswöchiger Online-Kurs für angewandtes Machine Learning,
> den der KI-Campus zusammen mit dem KIT anbietet – von Pandas-Grundlagen über
> Klassifikation, Clustering und Regression bis zu neuronalen Netzen, CNNs und
> einem LSTM-Textgenerator. Ich habe die Kursinhalte als Mitarbeiter des ITIV
> am KIT mit einem kleinen Team mitgeschrieben und den Kurs anschließend als
> Co-Dozent begleitet. Dieses Repository ist mein persönlicher Fork zu
> Portfolio-Zwecken; das Original wird weiterhin vom KI-Campus gehostet und
> versioniert."

Drei Sätze, die man notfalls einzeln zitieren kann – wichtig ist die Balance:
klarer Beitrag ("mitgeschrieben", "Co-Dozent"), klare Grenze ("mit einem Team",
"Fork, nicht das Original").

---

## 2. Rollen-Klarheit – wie im Interview ehrlich UND überzeugend erklären

**Fakten aus dem Repo (verifiziert):**
- `git log` in diesem Fork zeigt drei Committer-Identitäten auf den
  Notebook-Änderungen: `Marco <maggo.stang@googlemail.com>`, `InaStein` und
  `Simon Klug`. Das bestätigt objektiv: AMALEA war Teamarbeit, keine
  Ein-Personen-Leistung – und Marcos eigene Commits sind real nachweisbar
  (z. B. `Update 4 Künstlicher Ghost-Writer.ipynb`, `Update 3 Wie geht's
  eigentlich weiter.ipynb`, mehrere Woche-4/5-Notebooks).
- `git remote -v` zeigt `origin` = Marcos eigener Fork
  (`maggostang-droid/AMALEA`), `upstream` = das offizielle Repo
  (`KI-Campus/AMALEA`). Der Kommentar oben im README bestätigt das nochmal
  explizit: Original wird vom KI-Campus gehostet/versioniert, in dessen
  Historie tauchen andere Namen als Committer auf als in diesem Fork.
- Der Kurs ist als Jupyter-Notebook-Reihe mit Übungsaufgaben, Kontrollfragen
  ("Frage 6.4.1", "Aufgabe 3.4.3" etc.) und Lösungshinweisen aufgebaut –
  didaktisches Material, kein Software-Produkt mit User-Base oder Deployment.

**Wie das im Interview formuliert wird:**

- *"Was genau war dein Beitrag?"* → "Ich habe als wissenschaftlicher
  Mitarbeiter am ITIV die Kursinhalte mit Kolleg:innen gemeinsam erarbeitet –
  konkret Notebook-Kapitel geschrieben, Übungsaufgaben und Kontrollfragen
  entworfen, Beispieldatensätze und Erklärungen ausgewählt – und den Kurs dann
  live als Co-Dozent begleitet, also Teilnehmerfragen beantwortet und Inhalte
  vermittelt. Ich bin nicht alleiniger Autor, das war Teamarbeit; genauso
  wenig würde ich behaupten, ich hätte hier ein Softwareprodukt gebaut."
- *"Warum ist das dann in deinem Portfolio?"* → "Weil es zeigt, dass ich
  komplexe ML/DL-Inhalte nicht nur anwenden, sondern auch didaktisch
  aufbereiten und vermitteln kann – das ist für eine Rolle mit Mentoring-,
  Wissenstransfer- oder Kundenschulungs-Anteil relevant, und es zeigt inhaltliche
  Tiefe über den kompletten klassischen ML/DL-Stack."
- **Warum ehrliche Attribution hier eine Stärke ist, keine Schwäche:** Wer im
  Interview unaufgefordert sauber zwischen "mitgeschrieben" und "allein
  gebaut" unterscheidet, demonstriert genau die Integrität, die in einem
  Team-Arbeitsumfeld (Code Reviews, Co-Autorenschaft an Papers, gemeinsame
  Repos) tatsächlich gebraucht wird. Es ist glaubwürdiger, ehrlich "Team-
  Content, von mir mitverfasst und gelehrt" zu sagen, als eine übertriebene
  Solo-Erzählung zu riskieren, die bei Nachfragen (z. B. "zeig mir deinen
  Commit-Verlauf") auffliegen würde.

---

## 3. Kursüberblick Woche für Woche (aus den tatsächlichen Notebooks)

**Woche 1 – Python/Pandas-Grundlagen für Data Science**
`0 Installation und FAQ`, `1 Erste Schritte`, `2 Pandas retten den Tag`,
`3 Sherlock Pandas und Data Watson`, `4 Wie skaliert eigentlich das ganze?`.
Einstieg in Jupyter, Einlesen von CSV-Daten mit Pandas (u. a. `iris.csv`,
`pima-indians-diabetes.csv`), deskriptive Statistik, Klassenverteilung,
Korrelationsanalyse, Visualisierung (Histogramme, Dichtediagramme,
Box-Plots, Scatter-Matrix, Schiefe von Verteilungen) und Datenvorverarbeitung
(Normalisieren, Standardisieren, Binarisieren).

**Woche 2 – Grundlagen des überwachten Lernens & Evaluationsmetriken**
`1 Maschinelles Lernen und seine Anwendungen`, `2 100% Genauigkeit, das muss
doch gut sein, oder?`, `3 Oh sorry, das war ein Falsch-Positiv`. Einführung in
Regressions-, Klassifikations- und Clustering-Probleme, Train/Test-Split,
k-fache Kreuzvalidierung, geschichtete Stichproben (Stratification), Datensatz
`pima-indians-diabetes` (Klassifikation) und `housing.csv` (Regression).
Regressionsmetriken (MAE, MSE, RMSE) und Overfitting/Underfitting;
Klassifikationsmetriken (Konfusionsmatrix, Accuracy, Precision/Recall,
Classification Report, Log-Loss).

**Woche 3 – Klassische überwachte & unüberwachte Verfahren**
`2 Willkommen in der Baumschule!` (Decision Trees / CART, Gini-Index,
Random Forests, Grid-Search-Hyperparameteroptimierung auf Baumtiefe,
Einfluss von Feature-Scaling), `3 Schöne Nachbarschaft` (K-Nearest-Neighbors
und Radius-Classifier, Optimierung der Nachbarzahl, Visualisierung via PCA
und parallele Koordinaten – Datensatz: UCI Human Activity Recognition,
`X_train.txt`/`y_train.txt`/`features.txt`), `4 K-Means-Clustering`
(unüberwachtes Lernen, k-Means von Hand implementiert, Silhouetten-Koeffizient
und Ellbogenmethode zur Wahl von k, Mean-Shift, DBSCAN/HDBSCAN, praktische
Bildkompression, optional: PCA-Theorie und -Implementierung von Hand,
angewandt auf Iris- und HAR-Datensatz).

**Woche 4 – Neuronale Netze von Grund auf**
`1 Jetzt geht's in die Tiefe` (künstliches Neuron als Regressionsmodell),
`2 Wir trainieren nur bergab?` (Aktivierungsfunktionen, Hidden Layers,
Backpropagation "DIY" – Gradientenverfahren von Hand nachgebaut),
`3 Regression II: Künstliche Gehirne erzeugen für Dummies` (dasselbe Problem
in Keras, optional TensorFlow und PyTorch – Framework-Vergleich),
`4 Classification: Softmax-Eis für einen one-hot day` (Übergang lineare →
logistische Regression, Cross-Entropy-Loss, One-Hot-Encoding, Softmax,
XOR-Gatter als klassisches nichtlinear-trennbares Klassifikationsbeispiel,
Training in Keras).

**Woche 5 – Convolutional Neural Networks (CNNs)**
`1 Falten, Ausschneiden und fertig ist das CNN` (Grundlagen der Faltung,
Mean-/Prewitt-Filter, einfache Gesichtserkennung), `2 Inhaltsstoffe: Kann
Spuren von Intelligenz enthalten` (Faltungsschicht, Pooling-Schicht,
ReLU-Aktivierung, RGB-Bilder, Receptive Field), `3 Datenmangel? Copy &
augmentated Paste` (CIFAR-10-Klassifikation, Vergleich MLP vs. CNN,
Datenaugmentation, Visualisierung gelernter Filtergewichte und
Aktivierungen), `4 Abschauen ist erwünscht!` (Autoencoder für semantische
Segmentierung, SegNet-Architektur, Transfer Learning mit vortrainiertem
VGG-16-Encoder).

**Woche 6 – Zeitreihen und generative Sprachmodelle**
`3 Wie geht's eigentlich weiter?` (Zeitreihenvorhersage: Zerlegung von
Zeitreihen, Limitationen von MLPs, rekurrente neuronale Netze, LSTM-Zellen,
Vanilla- und gestapeltes LSTM, Walk-Forward-Validierung, Diagnose von
Over-/Underfitting – Datensatz: deutscher Stromverbrauch `Load_DE_2017_2019`),
`4 Künstlicher Ghost-Writer` (wortbasierter Text-Generator mit LSTM +
Embedding-Layer, trainiert auf den Grimm'schen Märchen bzw. Simpsons-
Skripten; das ist das "generative Modell" des Kurses – kein GAN, sondern
klassische autoregressive Sprachmodellierung nach dem Prinzip von
word2vec-Embeddings + LSTM-Vorhersage des nächsten Worts).

---

## 4. Vier bis sechs inhaltliche Vertiefungs-Stationen

### Station 1 – Bias/Variance, Overfitting & Cross-Validation (Woche 2)
**Kernkonzept:** Ein Modell mit 100 % Trainingsgenauigkeit ist nicht
automatisch gut – das Notebook heißt bewusst "100% Genauigkeit, das muss doch
gut sein, oder?". Overfitting bedeutet, dass das Modell Rauschen statt Muster
lernt; Underfitting, dass es zu simpel ist, um die Struktur der Daten
abzubilden. k-fache Kreuzvalidierung (Daten in k Folds teilen, k-mal trainieren/
testen, Ergebnisse mitteln) schätzt die Generalisierungsfähigkeit robuster als
ein einzelner Train/Test-Split, und geschichtete Stichproben (Stratified
Sampling) verhindern, dass seltene Klassen in einem Fold komplett fehlen.
**Selbstkontrollfrage:** Warum kann ein Modell mit sehr niedrigem
Trainingsfehler trotzdem einen hohen Testfehler haben, und wie hilft
k-fache Kreuzvalidierung, das frühzeitig zu erkennen?

### Station 2 – Decision Trees, Gini-Index & Random Forests (Woche 3.2)
**Kernkonzept:** Entscheidungsbäume (CART) teilen den Featureraum rekursiv
anhand des Merkmals/Schwellwerts, das die Unreinheit einer Aufteilung am
stärksten reduziert (Gini-Index). Ohne Tiefenbegrenzung überfitten Bäume
leicht; Grid-Search-Cross-Validation über die maximale Baumtiefe findet einen
guten Kompromiss. Random Forests trainieren viele Bäume auf zufälligen
Teilmengen der Daten/Features und mitteln ihre Vorhersagen (Bagging) – das
reduziert die Varianz einzelner Bäume erheblich.
**Selbstkontrollfrage:** Warum reduziert das Mitteln vieler Bäume in einem
Random Forest die Overfitting-Neigung eines einzelnen, unbegrenzt tiefen
Baums?

### Station 3 – Clustering vs. Klassifikation & Wahl von k (Woche 3.4)
**Kernkonzept:** K-Means ist unüberwachtes Lernen: Es werden k Zentroide
zufällig initialisiert, dann abwechselnd Punkte dem nächsten Zentroid
zugeordnet und Zentroide neu berechnet (Erwartungs-Maximierungs-Prinzip), bis
das Verfahren konvergiert. Ohne Labels lässt sich Clustering-Qualität über
den Silhouetten-Koeffizienten oder die Ellbogenmethode bewerten. Anders als
DBSCAN/HDBSCAN setzt K-Means implizit konvex-runde, ähnlich große Cluster
voraus – bei nicht-konvexen Strukturen (z. B. `make_moons`-Datensatz im
Notebook) versagt es sichtbar.
**Selbstkontrollfrage:** Was ist der fundamentale Unterschied zwischen
Klassifikation (z. B. Diabetes-Vorhersage in Woche 2) und Clustering
(K-Means in Woche 3), und warum kann man Clustering-Ergebnisse nicht mit
Accuracy bewerten?

### Station 4 – Backpropagation und Aktivierungsfunktionen von Hand (Woche 4.2)
**Kernkonzept:** Das Notebook "Wir trainieren nur bergab?" lässt Teilnehmer
Backpropagation und Gradientenabstieg selbst nachbauen, statt sie nur als
Keras-Blackbox zu nutzen: Vorwärtsdurchlauf berechnet die Vorhersage, der
Fehler wird über die Kettenregel rückwärts durch die Schichten propagiert, um
die Gradienten jedes Gewichts zu bestimmen; die Gewichte werden dann entgegen
dem Gradienten aktualisiert ("bergab" im Fehlergebirge). Nichtlineare
Aktivierungsfunktionen (statt einer reinen linearen Summe) sind notwendig,
damit ein mehrschichtiges Netz überhaupt nichtlineare Zusammenhänge lernen
kann – ein rein lineares mehrschichtiges Netz wäre äquivalent zu einer
einzigen linearen Schicht.
**Selbstkontrollfrage:** Warum bräuchte ein neuronales Netz ohne
nichtlineare Aktivierungsfunktion beliebig viele Schichten nicht mehr
Ausdruckskraft als eine einzige lineare Schicht?

### Station 5 – CNNs: Faltung, Pooling und Data Augmentation (Woche 5.1–5.3)
**Kernkonzept:** Eine Convolutional Layer schiebt lernbare Filter über das
Bild und erkennt dadurch lokale Muster (Kanten, Texturen) unabhängig von
ihrer Position im Bild (Parameter-Sharing, im Gegensatz zu einem voll
verbundenen MLP, das jedes Pixel einzeln gewichtet). Pooling-Schichten
reduzieren die räumliche Auflösung und machen die Repräsentation robuster
gegen kleine Verschiebungen; das Receptive Field wächst mit der Netztiefe.
Im CIFAR-10-Vergleich schlägt ein CNN ein gleich großes MLP deutlich, weil es
diese Bildstruktur ausnutzt statt sie zu ignorieren. Data Augmentation
(Drehen, Spiegeln, Verschieben der Trainingsbilder) simuliert zusätzliche
Trainingsdaten und reduziert Overfitting bei kleinen Datensätzen.
**Selbstkontrollfrage:** Warum benötigt ein CNN für dieselbe Bildklassifikations-
aufgabe typischerweise deutlich weniger Parameter als ein vergleichbar
"tiefes" MLP, und was hat das mit Parameter-Sharing zu tun?

### Station 6 – Generative Textmodellierung mit LSTM (Woche 6.4)
**Kernkonzept:** Der "Künstliche Ghost-Writer" ist ein wortbasiertes
Sprachmodell: Der Grimm-Märchentext wird bereinigt, tokenisiert und in feste
Wortsequenzen zerlegt; ein Embedding-Layer bildet jedes Wort auf einen dichten
Vektor ab (statt Integer- oder One-Hot-Kodierung, die weder Ähnlichkeit noch
Kompaktheit bieten); ein LSTM verarbeitet die Sequenz und sagt das
wahrscheinlichste nächste Wort voraus. Wiederholtes Anwenden erzeugt Wort für
Wort neuen, stilistisch ähnlichen Text – ein einfaches, aber vollständiges
Beispiel für autoregressive generative Modellierung, wie sie (in viel
größerem Maßstab) auch modernen LLMs zugrunde liegt.
**Selbstkontrollfrage:** Warum ist eine Embedding-Schicht einer reinen
One-Hot-Kodierung von Wörtern vorzuziehen, insbesondere bei großem
Vokabular?

---

## 5. Recruiter-Simulation: 8–10 Fragen mit Musterantworten

1. **"Was war deine Rolle bei AMALEA genau?"**
   → "Ich habe als ITIV-Mitarbeiter am KIT die Kursinhalte mit einem kleinen
   Team mitentwickelt – Notebook-Kapitel, Übungsaufgaben, Kontrollfragen –
   und den Kurs danach live als Co-Dozent begleitet. Das lässt sich auch an
   den Commits in meinem Fork nachvollziehen, z. B. an mehreren
   Woche-4/5/6-Notebooks."

2. **"Hast du den Kurs allein geschrieben?"**
   → "Nein, explizit nicht. Es gibt mindestens zwei weitere Co-Autor:innen in
   der Commit-Historie. Ich will hier keine Alleinurheberschaft behaupten,
   sondern zeigen, dass ich an einem mehrwöchigen, technisch breiten
   ML-Kurs im Team mitgearbeitet und ihn unterrichtet habe."

3. **"Warum ist ein Kurs, den du nicht gebaut, sondern mitgeschrieben hast, in
   deinem Portfolio?"**
   → "Weil Lehrkompetenz und die Fähigkeit, komplexe ML/DL-Konzepte
   verständlich zu strukturieren, für viele Rollen relevant ist – Onboarding,
   Wissenstransfer im Team, Kommunikation mit nicht-technischen
   Stakeholdern. Und weil es zeigt, dass ich den kompletten klassischen
   ML/DL-Stack inhaltlich beherrsche, nicht nur ein Ausschnitt davon."

4. **"Was hast du dabei über Lehre/Kommunikation gelernt?"**
   → "Dass die größte Hürde beim Erklären von ML nicht die Mathematik ist,
   sondern die Intuition davor – deshalb sind die Notebooks bewusst mit
   Alltagsmetaphern betitelt ('Willkommen in der Baumschule', 'Wir trainieren
   nur bergab') und bauen Konzepte erst visuell/interaktiv auf, bevor Code
   folgt. Als Co-Dozent merkt man außerdem sehr schnell, an welcher Stelle
   Teilnehmende typischerweise hängen bleiben, z. B. bei Backpropagation oder
   bei One-Hot-Encoding vs. Embeddings."

5. **"Erklär mir, was ein CNN ist und warum man es für Bilder nutzt."**
   → "Ein CNN nutzt lernbare Faltungsfilter, die ortsunabhängig lokale
   Muster wie Kanten erkennen, plus Pooling zur Verdichtung. Im Kurs zeigen
   wir das direkt am CIFAR-10-Vergleich: Ein CNN schlägt ein gleich großes
   MLP klar, weil das MLP die Bildstruktur (Nachbarschaft von Pixeln)
   komplett ignoriert, während das CNN sie explizit ausnutzt."

6. **"Was ist der Unterschied zwischen Klassifikation und Clustering?"**
   → "Klassifikation ist überwachtes Lernen mit bekannten Labels – z. B. der
   Pima-Indians-Diabetes-Datensatz in Woche 2, wo wir Diabetes ja/nein
   vorhersagen. Clustering ist unüberwacht: K-Means in Woche 3 gruppiert
   Datenpunkte nur anhand ihrer Ähnlichkeit, ohne dass es 'richtige' Labels
   gibt – Erfolg misst man dann nicht mit Accuracy, sondern z. B. mit dem
   Silhouetten-Koeffizienten."

7. **"Was ist Overfitting, und wie erkennt man es?"**
   → "Wenn ein Modell Trainingsdaten (inklusive Rauschen) auswendig lernt
   statt zu generalisieren – erkennbar an einer großen Lücke zwischen
   Trainings- und Testfehler. Im Kurs behandeln wir das explizit in Woche 2
   und wieder bei den LSTMs in Woche 6, wo Diagnosekurven für
   Over-/Underfitting eingeführt werden."

8. **"Was ist ein LSTM, und wofür wird es im Kurs verwendet?"**
   → "Ein LSTM ist ein rekurrentes Netz mit einer Zellstruktur, die
   gezielt Informationen über längere Sequenzen hinweg behalten oder
   vergessen kann – das löst das Problem von Standard-RNNs, dass Gradienten
   über lange Sequenzen verschwinden. Im Kurs nutzen wir es zweimal: für
   Zeitreihenvorhersage (Stromverbrauch) und für Textgenerierung (Grimms
   Märchen), wo es zusammen mit einem Embedding-Layer Wort für Wort
   plausiblen neuen Text erzeugt."

9. **"Wie stellst du sicher, dass du bei einem 'geerbten' Kursprojekt wirklich
   den Inhalt verstehst und nicht nur die Struktur kennst?"**
   → "Indem ich zu jedem Notebook die Kernidee in eigenen Worten erklären
   kann, ohne den Text vorzulesen – genau das übe ich mit den
   Vertiefungsstationen in dieser Datei, z. B. warum Backpropagation ohne
   nichtlineare Aktivierung nutzlos wäre, oder warum Embeddings besser
   skalieren als One-Hot-Encoding."

10. **"Was würdest du am Kurs heute anders machen?"**
    → Ehrliche, reflektierte Antwort vorbereiten statt Standardsatz, z. B.:
    "Manche Wochen wie Woche 3 sind mit optionalen PCA-/Clustering-Vertiefungen
    sehr dicht; ich würde heute stärker priorisieren, was Kernstoff vs.
    Enrichment ist, gerade weil ein Online-Kurs die Aufmerksamkeitsspanne der
    Teilnehmenden nicht unterschätzen darf."

---

## 6. Checkliste – Bist du bereit?

- [ ] Ich kann den Elevator-Pitch (Abschnitt 1) frei sprechen, ohne abzulesen.
- [ ] Ich kann in einem Satz erklären, was Fork vs. Original bedeutet, ohne
      zu zögern oder auszuweichen.
- [ ] Ich kann für jede der sechs Kurswochen mindestens ein konkretes
      Notebook-Thema und einen verwendeten Datensatz nennen.
- [ ] Ich kann zu allen sechs Vertiefungsstationen die Selbstkontrollfrage
      beantworten, ohne diese Datei zu öffnen.
- [ ] Ich kann den Unterschied zwischen Klassifikation, Clustering und
      Regression an konkreten Kurs-Beispielen erklären (nicht nur abstrakt).
- [ ] Ich kann CNNs und das Ghost-Writer-LSTM je in unter zwei Minuten
      erklären, inklusive Datensatz und Kernidee.
- [ ] Ich habe eine ehrliche, nicht-defensive Antwort auf "Was würdest du
      heute anders machen?" parat.
- [ ] Ich fühle mich wohl damit, explizit zu sagen "das war Teamarbeit,
      mein Beitrag war X" – ohne dass es wie eine Entschuldigung klingt.

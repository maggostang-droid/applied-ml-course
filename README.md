# Applied ML Course (KIT)

**Sechs Kurswochen praktisches Machine Learning für den KI-Campus: Jupyter-Notebooks von
Pandas-Grundlagen bis zu CNNs, die Marco als Mitarbeiter des KIT mitgeschrieben und als
Co-Dozent begleitet hat.**

![Jupyter](https://img.shields.io/badge/Jupyter-6_Kurswochen-a78bfa?style=flat-square&labelColor=0a0716)
![Python](https://img.shields.io/badge/Python-scikit--learn_·_Keras-a78bfa?style=flat-square&labelColor=0a0716)
![KI-Campus](https://img.shields.io/badge/KI--Campus-KIT_/_ITIV-a78bfa?style=flat-square&labelColor=0a0716)
[![Kursseite](https://img.shields.io/badge/▶_Zum_Kurs-ki--campus.org-0a0716?style=flat-square&labelColor=a78bfa)](https://ki-campus.org/amalea?locale=de)

> **Hinweis zu diesem Fork:** Ich (Marco Stang) habe die Kursinhalte als Mitarbeiter des
> [ITIV](https://www.itiv.kit.edu/) am KIT geschrieben und war Co-Dozent. Gehostet und
> versioniert wird das Original vom [KI-Campus](https://github.com/KI-Campus/AMALEA),
> daher tauchen in der Git-Historie dort andere Namen als Committer auf, nicht meiner.
> Dieser Fork ist meine persönliche Kopie zu Portfolio-Zwecken.
> Offizielle Kursseite: [ki-campus.org/amalea](https://ki-campus.org/amalea?locale=de).

<details>
<summary><b>🇬🇧 English summary</b></summary>

Practical programming exercises for the German-language KI-Campus course AMALEA (Applied
Machine Learning Algorithms): six weeks of Jupyter notebooks covering pandas, classification,
clustering, regression, CNNs and generative models. Marco co-authored the course material at
KIT/ITIV and co-taught the course. This is a personal fork for portfolio purposes; the
original is hosted by KI-Campus. Course content in German below.
</details>

---

Die Notebooks lassen sich lokal, in Google Colab oder über MyBinder ausführen, die
jeweiligen Links stehen in der Tabelle unten. Da es sich um Kursmaterial handelt und nicht
um ein eigenes Softwareprojekt, gibt es hier bewusst keine Architektur, keine Metriken und
keine Limitierungen im Sinne der übrigen Portfolio-Repos.

---

# Willkommen
Herzlich Willkommen bei den praktischen Programmierübungen für den [Kurs AMALEA - AMALEA - Angewandte Machine Learning Algorithmen](https://learn.ki-campus.org/courses/amalea-kit2021). Hier finden Sie alle Aufgaben und weitere Hinweise für die praktischen Programmieraufgaben. 

Die insgesamt sechs Kurswochen werden mit [Jupyter Notebooks](https://jupyter.org/) begleitet, die Sie hier in den einzelnen Ordnern finden können.
Als Verbindungsglied von Text und Python-Code sind Notebooks perfekt für einen Einstieg in Machine Learning geeignet. Die Bedienung ist simpel und [hier](Woche%201/1%20Erste%20Schritte.ipynb) nochmal im Detail beschrieben.

# Anwendungsmöglichkeiten

Im Allgemeinen stehen für den praktischen Teil (Jupyter Notebooks) drei Anwendungsalternativen zur Verfügung:

* Lokal: hier installieren Sie alles auf Ihren eigenen Rechner.
* Google Colaboratory:  Online Plattform - keine Installation nötig, aber Google Account
* MyBinder: Online Plattform ohne Anmeldung

Weitere Information finden sich [hier](Woche%201/0%20Installation%20und%20FAQ.md).

<table>
    <tbody>
        <tr>
            <td><a href='Woche%201'><strong>Woche&nbsp;1</strong></a></td>
            <td>
                <a href='Woche%201/0%20Installation%20und%20FAQ.md'>0 Installation und FAQ</a>
                </br>
            </td>
            <td>
                <a href='Woche%201/1%20Erste%20Schritte.ipynb'>1 Erste Schritte</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%201/1%20Erste%20Schritte.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%201/1%20Erste%20Schritte.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%201/2%20Pandas%20retten%20den%20Tag.ipynb'>2 Pandas retten den Tag</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%201/2%20Pandas%20retten%20den%20Tag.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%201/2%20Pandas%20retten%20den%20Tag.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%201/3%20Sherlock%20Pandas%20und%20Data%20Watson.ipynb'>3 Sherlock Pandas und Data Watson</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%201/3%20Sherlock%20Pandas%20und%20Data%20Watson.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%201/3%20Sherlock%20Pandas%20und%20Data%20Watson.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%201/4%20Wie%20skaliert%20eigentlich%20das%20ganze.ipynb'>4 Wie skaliert eigentlich das ganze?</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%201/4%20Wie%20skaliert%20eigentlich%20das%20ganze.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%201/4%20Wie%20skaliert%20eigentlich%20das%20ganze.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
        <tr>
            <td><a href='Woche%202'><strong>Woche&nbsp;2</strong></a></td>
            <td>
                <a href='Woche%202/1%20Maschinelles%20Lernen%20und%20seine%20Anwendungen.ipynb'>1 Maschinelles Lernen und seine Anwendungen</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%202/1%20Maschinelles%20Lernen%20und%20seine%20Anwendungen.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%202/1%20Maschinelles%20Lernen%20und%20seine%20Anwendungen.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%202/2%20100%20Genauigkeit%2C%20das%20muss%20doch%20gut%20sein%2C%20oder.ipynb'>2 100% Genauigkeit, das muss doch gut sein, oder?</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%202/2%20100%20Genauigkeit%2C%20das%20muss%20doch%20gut%20sein%2C%20oder.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%202/2%20100%20Genauigkeit%2C%20das%20muss%20doch%20gut%20sein%2C%20oder.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%202/3%20Oh%20sorry%2C%20das%20war%20ein%20Falsch-Positiv.ipynb'>3 Oh sorry, das war ein Falsch-Positiv</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%202/3%20Oh%20sorry%2C%20das%20war%20ein%20Falsch-Positiv.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%202/3%20Oh%20sorry%2C%20das%20war%20ein%20Falsch-Positiv.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
        <tr>
            <td><a href='Woche%203'><strong>Woche&nbsp;3</strong></a></td>
    <td></td>
            <td>
                <a href='Woche%203/2%20Willkommen%20in%20der%20Baumschule%21.ipynb'>2 Willkommen in der Baumschule!</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%203/2%20Willkommen%20in%20der%20Baumschule%21.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%203/2%20Willkommen%20in%20der%20Baumschule%21.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%203/3%20Sch%C3%B6ne%20Nachbarschaft.ipynb'>3 Schöne Nachbarschaft</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%203/3%20Sch%C3%B6ne%20Nachbarschaft.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%203/3%20Sch%C3%B6ne%20Nachbarschaft.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%203/4%20K-Means-Clustering.ipynb'>4 K-Means-Clustering</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%203/4%20K-Means-Clustering.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%203/4%20K-Means-Clustering.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
        <tr>
            <td><a href='Woche%204'><strong>Woche&nbsp;4</strong></a></td>
            <td>
                <a href='Woche%204/1%20Jetzt%20geht%E2%80%99s%20in%20die%20Tiefe.ipynb'>1 Jetzt geht’s in die Tiefe</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%204/1%20Jetzt%20geht%E2%80%99s%20in%20die%20Tiefe.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%204/1%20Jetzt%20geht%E2%80%99s%20in%20die%20Tiefe.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%204/2%20Wir%20trainieren%20nur%20bergab.ipynb'>2 Wir trainieren nur bergab?</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%204/2%20Wir%20trainieren%20nur%20bergab.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%204/2%20Wir%20trainieren%20nur%20bergab.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%204/3%20Regression%20II%20K%C3%BCnstliche%20Gehirne%20erzeugen%20f%C3%BCr%20Dummies.ipynb'>3 Regression II: Künstliche Gehirne erzeugen für Dummies</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%204/3%20Regression%20II%20K%C3%BCnstliche%20Gehirne%20erzeugen%20f%C3%BCr%20Dummies.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%204/3%20Regression%20II%20K%C3%BCnstliche%20Gehirne%20erzeugen%20f%C3%BCr%20Dummies.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%204/4%20Classification%20Softmax-Eis%20f%C3%BCr%20einen%20one-hot%20day.ipynb'>4 Classification: Softmax-Eis für einen one-hot day</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%204/4%20Classification%20Softmax-Eis%20f%C3%BCr%20einen%20one-hot%20day.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%204/4%20Classification%20Softmax-Eis%20f%C3%BCr%20einen%20one-hot%20day.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
        <tr>
            <td><a href='Woche%205'><strong>Woche&nbsp;5</strong></a></td>
            <td>
                <a href='Woche%205/1%20Falten%2C%20Ausschneiden%20und%20fertig%20ist%20das%20CNN.ipynb'>1 Falten, Ausschneiden und fertig ist das CNN</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%205/1%20Falten%2C%20Ausschneiden%20und%20fertig%20ist%20das%20CNN.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%205/1%20Falten%2C%20Ausschneiden%20und%20fertig%20ist%20das%20CNN.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%205/2%20Inhaltsstoffe%20Kann%20Spuren%20von%20Intelligenz%20enthalten.ipynb'>2 Inhaltsstoffe: Kann Spuren von Intelligenz enthalten</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%205/2%20Inhaltsstoffe%20Kann%20Spuren%20von%20Intelligenz%20enthalten.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%205/2%20Inhaltsstoffe%20Kann%20Spuren%20von%20Intelligenz%20enthalten.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%205/3%20Datenmangel%20Copy%20augmentated%20Paste.ipynb'>3 Datenmangel? Copy & augmentated Paste</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%205/3%20Datenmangel%20Copy%20augmentated%20Paste.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%205/3%20Datenmangel%20Copy%20augmentated%20Paste.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%205/4%20Abschauen%20ist%20erw%C3%BCnscht%21.ipynb'>4 Abschauen ist erwünscht!</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%205/4%20Abschauen%20ist%20erw%C3%BCnscht%21.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%205/4%20Abschauen%20ist%20erw%C3%BCnscht%21.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
        <tr>
            <td><a href='Woche%206'><strong>Woche&nbsp;6</strong></a></td>
    <td></td><td></td>
            <td>
                <a href='Woche%206/3%20Wie%20geht%27s%20eigentlich%20weiter.ipynb'>3 Wie geht's eigentlich weiter?</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%206/3%20Wie%20geht%27s%20eigentlich%20weiter.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%206/3%20Wie%20geht%27s%20eigentlich%20weiter.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
            <td>
                <a href='Woche%206/4%20K%C3%BCnstlicher%20Ghost-Writer.ipynb'>4 Künstlicher Ghost-Writer</a>
                </br>
                <a href='https://colab.research.google.com/github/KI-Campus/AMALEA/blob/master/Woche%206/4%20K%C3%BCnstlicher%20Ghost-Writer.ipynb'><img src='https://colab.research.google.com/assets/colab-badge.svg' alt='Open In Colab'></a>
                </br>
                <a href='https://mybinder.org/v2/gh/KI-Campus/AMALEA/HEAD?filepath=Woche%206/4%20K%C3%BCnstlicher%20Ghost-Writer.ipynb'><img src='https://mybinder.org/badge_logo.svg' alt='Open In myBinder'></a>
            </td>
        </tr>
    </tbody>
</table>

---

```console
marco@portfolio:~$ open marco-os --project amalea
```

**[▸ Dieses Projekt in MARCO.OS öffnen](https://maggostang-droid.github.io/marco-os/#amalea)**,
dem interaktiven Portfolio von Marco Stang.

**Schwesterprojekte:**
[SQL Copilot](https://github.com/maggostang-droid/sql-copilot) (LangGraph-Agent mit Guardrails) ·
[Review Risk Predictor](https://github.com/maggostang-droid/review-risk-predictor) (erklärbares ML, React/FastAPI) ·
[Medical Coding Extractor](https://github.com/maggostang-droid/medical-coding-extractor) (LoRA-Finetuning gegen RAG)

<sub>Marco Stang · Dr.-Ing. · [LinkedIn](https://www.linkedin.com/in/marco-stang) · stang.marco@t-online.de · Kursinhalte: Lizenz des KI-Campus-Originals</sub>

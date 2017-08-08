# Eine Einführung in Github

Github is eines von mehreren Plattformen, auf der Open-Source-Entwickler
ihren Code tauschen und gemeinsam weiterentwickeln. Wir wollen diese
Plattform genauso nutzten.

- Zuerst müssen wir uns registrieren.
- Dann steuern wir die [Python-Recherche-Repo](https://github.com/barjacks/pythonrecherche)
an.
- Nun wählen wir rechts oben Fork. Nun hast Du Deine "gegabelte" Version der
Repo. Gratuliere! Gehen wir zurück auf die Commandline und geben Folgendes ein,
um Deine Kopie der Repo (Repository) auf Deinem Gerät zu haben:
    ```
    + _git clone 'Link auf Deinen Fork'_
    ```
- Wenn Du nur für Dich an diesem Projekt arbeiten möchtest, wäre das Setup
nun zu Ende. Wir können Änderungen vornehmen. Und dann mit folgenden Befehlen
auf der Kommandozeile ausführen.
    + Zuerst steuern wir mit _cd_ in die Repo
    + Dann geben wir folgendes ein _git add ._, das ergänzt alles, was wir
    verändert haben
    + Dann schreiben wir dazu eine Mitteilung. _git commit -m 'hello'_
    + Und dann schieben wir das auf Github. _git push_
- Doch wir wollen Code teilen, deshalb sind noch ein paar Schritte nötig.
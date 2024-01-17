# Schraubentool

Dieses Programm berechnet anhand von Schraubeneigenschaften, wie Abmaße und Materialeigenschaften, und der Größe einer angreifenden Zugkraft, ob die Schrauben diese Kraft aushalten. Zwischenergebnisse werden auch angezeigt und LaTeX Code für den Festigkeitsnachweis lässt sich generieren - mit Formeln.

## Inhaltsangabe

- [Installation](#installation)
- [Anwendung](#anwendung)
- [Troubleshooting](#troubleshooting)
- [Beitragen](#beitragen)
- [Lizenz](#lizenz)

## Installation

Um die App zu installieren, lade die Datei [`schraubentoolInstaller.exe`](https://objects.githubusercontent.com/github-production-release-asset-2e65be/744030336/82491901-1467-4c23-b5dd-b70ef718c83a?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240117%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240117T095303Z&X-Amz-Expires=300&X-Amz-Signature=4d25bc323f337f639255907e1463613ea121b1a4d16a3dfa7b899da9104fea63&X-Amz-SignedHeaders=host&actor_id=98911509&key_id=0&repo_id=744030336&response-content-disposition=attachment%3B%20filename%3DschraubentoolInstaller.exe&response-content-type=application%2Foctet-stream) herunter und führe sie aus. Folge dann den Anweisungen im Installationsmenü.

## Anwendung

Wenn du die App asuführst und auf 'Berechne' drückst, sollte dein Fenster so aussehen:

![Bild zeigt die Hauptanzeige der App.](assets/readme/app.png)

Mit der linken spalte steuerst du die App. Hier gibst du relevante Parameter ein, startest die Berechnung und generierst den LaTeX code.

Die zwei rechten Spalten zeigen dir die Ergebnisse.

Falls du wissen möchtest, wie die Werte berechnet werden, lies bitte das [Wiki](https://github.com/muederotter/schraubentool/wiki).

## Troubleshooting

Ich habe zwei Errorlämpchen eingebaut. Wenn das linke lämpchen leuchtet, dann liegt das meistens daran, dass der Ordner `C:\temp` nicht existiert. Hier wird nämlich die  In diesem fall erstelle den Ordner bitte manuell, dann sollte alles funktionieren.

Wenn du sonstige Probleme mit der App hast oder Fehler entdeckst, dann erstelle bitte ein [Issue](https://github.com/muederotter/schraubentool/issues).

## Beitragen

Hilfe ist immer willkommen! Bitte folge den Richtlinen in [CONTRIBUTING.md](CONTRIBUTING.md).

## Lizenz

Dieses Projekt ist lizensiert unter der [MIT License](LICENSE).

# Maturitaetsarbeit-Ali-Chbani
Dieses Repository enthält alle finalen Programme meiner Maturitätsarbeit, darunter drei Tic-Tac-Toe-Programme und drei 4-Gewinnt-Programme. Die Erste Version für beide Spiele ermöglicht ein Spiel zwischen zwei menschlichen Spielern. Die zwei weitere hochgeladene Versionen bieten zudem die Möglichkeit, gegen eine KI zu spielen. Diese Programme wurden im Rahmen meiner Maturitätsarbeit zwischen April und November 2023 programmiert. 

## Einstieg in die Arbeit
Hier sind die wichtige Installationen, um mit einer Kopie dieses Codes arbeiten zu können.
### Module
Für diese Projekt habe ich 2 Python Module verwendet: Tkinter und Random. Beide sind in der Python Standardbibliothek integriert und sollten in allen Standard-Python-Distributionen enthalten sein.

### Importieren
```python
from tkinter import *
from tkinter import messagebox
import random
```
## Resultate
Meine Implementierung der Minimax- und Alpha-Beta-Pruning Algorithmen erweist sich als äusserst leistungsfähig. Die Algorithmen haben vielversprechende Ergebnisse in den Spielen „Tic-Tac-Toe“ und „4Gewinnt“ hervorgebracht. Beim „Tic-Tac-Toe“ spielt die künstliche Intelligenz bei einer Suchtiefe von 0 zufällige Züge und ist leicht zu schlagen. Ab einer Suchtiefe von 1 bewertet sie ihre Züge anhand der verliehenen Werte für die unterschiedlichen Schaltflächen. Ab einer Suchtiefe von zwei antizipiert sie den ersten gegnerischen Zug und erkennt einfache Gefahren im Voraus. Unschlagbar wird der Algorithmus ab einer Suchtiefe von 3. Hier sind auch Täuschungen ineffektiv und werden mühelos vom Computer durchschaut. Die Mehrheit der Partien enden schliesslich unentschieden. Das optimierende Alpha-Beta-Pruning hat zu identischen Resultaten und Spielzügen geführt, macht das Spielerlebnis jedoch mit einer schnelleren gegnerischen Antwort angenehmer. Beide Algorithmen konnten den Spielbaum mit einer Suchtiefe von 9 sondieren.

Im Gegensatz zum Spiel „Tic-Tac-Toe“ waren unentschiedene Spielenden beim „4 Gewinnt“ deutlich seltener. Die Auswertung gestaltet sich hier weniger eindeutig. Die Suchtiefen 0 bis 2 ergeben ähnliche Resultate wie beim „Tic-Tac-Toe“. Ab einer Suchtiefe von 3 wird der Computer zu einem anspruchsvollen Gegner, der schwer zu schlagen ist(falls er die Partie beginnt, ansonsten ist er ab einer Suchtiefe von 4 anspruchsvoll). Da die Partien beim „4 Gewinnt“ länger sind und mehr Fehlermöglichkeiten bieten, konnte ich im Gegensatz zum „Tic-Tac-Toe“ keine klar definierten Auswertungen erhalten. Klar wurde jedoch, dass ab einer Suchtiefe von 3 der Gegner zum Sieg kommen kann, und je tiefer gesucht wird, desto wahrscheinlicher werden seine Chancen auf einen Sieg. Auch hier sorgte der Alpha-Beta-Pruning Algorithmus für einen angenehmeren Spielfluss und ermöglichte es mir, auf meinem Computer mit einer Suchtiefe von 11 zu spielen, wobei das Limit des Minimax Algorithmus bei 8 lag.

## Zukunftsaussicht

Ausblick in die Zukunft:
Als ich im April mit dieser Arbeit begonnen habe, existierte die generative KI noch nicht. Mit der Einführung von ChatGPT und seinen Konkurrenten im Internet begann eine digitale Revolution. Solche künstlichen Intelligenzen können Geschichten und Lieder aufführen sowie anhand von Bildern visualisieren. Im Bereich der Informatik dienen sie zudem als umfangreiche Wissens- und Könnens Datenbank. Diese Revolution wird in Zukunft die Programmierung erleichtern und uns als Co-Piloten auf unseren Programmierabenteuern unterstützen. Heutzutage wäre eine derart leistungsfähige KI in der Lage, ähnliche Projekte zu kodieren und zu verbessern. Um den letzten Punkt zu belegen, habe ich nach Abschluss meiner praktischen Arbeit ChatGPT gefragt, wie ich sie in Zukunft verbessern könnte. Hier sind seine Antworten (Prompt: Bewerte diesen Code und gib mir   Verbesserungsmöglichkeiten):

•	Funktionen für die UI-Elemente

•	Vermeidung von globalen Variablen

•	Kommentare zu den Funktionen

•	Trennung von Logik und UI

•	Benennung von Funktionen und Variablen

Die Fortschritte in der künstlichen Intelligenz werden zweifellos die Art und Weise, wie wir programmieren, revolutionieren und unseren Alltag umstossen.

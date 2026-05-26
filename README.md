# Git Shell Hausaufgabe

Dieses Repository enthält ein kleines Bash-Skript für einfache IT-Support-Aufgaben.

Geübte Git-Themen:

- git add
- git commit
- git push
- git branch
- git checkout
- git merge


--------------------------------------------
# 11. Theorie: Merge-Konflikt verstehen 
--------------------------------------------

## Was ist ein Merge-Konflikt?

Ein Merge-Konflikt entsteht, wenn Git Änderungen aus zwei Branches nicht automatisch zusammenführen kann. Git weiß dann nicht, welche Version richtig ist.

## Warum entsteht ein Merge-Konflikt meistens dann, wenn zwei Branches dieselbe Stelle in derselben Datei verändert haben?

Git vergleicht die Änderungen aus beiden Branches. Wenn beide Branches dieselbe Zeile unterschiedlich geändert haben, kann Git nicht automatisch entscheiden. Deshalb entsteht ein Merge-Konflikt.

## Warum haben Sie in dieser Aufgabe keinen Merge-Konflikt bekommen?

In dieser Aufgabe wurden die Branches nacheinander erstellt. Jeder Branch wurde erst gemergt, bevor der nächste Branch erstellt wurde.

## Was zeigt Git in einer Datei an, wenn ein Merge-Konflikt entsteht?
?????

## Welche Schritte muss man grundsätzlich durchführen, um einen Merge-Konflikt sauber zu lösen?

Man öffnet zuerst die betroffene Datei und schaut sich die markierten Stellen an. Dann entscheidet man, welche Änderung behalten werden soll. Danach entfernt man die Konfliktmarkierungen, speichert die Datei.

## Warum sollte man nach dem Lösen eines Merge-Konflikts das Programm oder Skript noch einmal testen?

Beim Lösen eines Konflikts kann man versehentlich etwas falsch zusammenfügen. Deshalb sollte man prüfen, ob das Programm noch funktioniert.



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------
## 12. Theorie: Merge und Rebase vergleichen
----------------------------------------------

## Was macht git merge?

Git merge fügt die Änderungen eines Branches in einen anderen Branch ein. So werden die Arbeiten zusammengeführt.

## Was macht git rebase?

Git rebase setzt die Änderungen eines Branches auf den neuesten Stand eines anderen Branches.

## Was ist der wichtigste Unterschied zwischen merge und rebase?

Merge verbindet Branches miteinander. Rebase ordnet die Commits neu an und verändert die Historie.

## Warum bleibt bei merge oft besser sichtbar, wann ein Branch zusammengeführt wurde?

Bei merge wird meistens ein zusätzlicher Merge-Commit erstellt. Dadurch kann man sehen, wann die Zusammenführung stattgefunden hat.

## Warum kann rebase die Git-Historie sauberer aussehen lassen?

Rebase vermeidet zusätzliche Merge-Commits. Dadurch wirkt die Historie übersichtlicher.

## Warum sollte man mit rebase vorsichtig sein, wenn ein Branch bereits mit anderen geteilt wurde?

Rebase verändert die Historie eines Branches. Das kann Probleme verursachen, wenn andere Personen bereits damit arbeiten.

## Wann würden Sie eher merge verwenden?

Merge eignet sich gut für Teamprojekte.

## Wann könnte rebase sinnvoll sein?

Rebase ist sinnvoll, wenn man eine saubere und übersichtliche Historie haben möchte.

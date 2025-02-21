# Kiosk-SB

Kiosk SB ist ein super simples Shop-System für den Hobbygebrauch unter Kollegen. Benutzer und Artikel können über CSV-Listen verwaltet werden. Jeder Nutzer kann Guthaben anlegen oder anschreiben. Artikel können im Warenkorb summiert und mit dem Guthaben verrechnet oder als bezahlt markiert werden.

Du kannst das Tool herunterladen und einfach im Browser ausführen. Ich habe jeweils eine CSV-Datei beigefügt, mit einigen Beispieldaten für Artikel und Benutzer. Die Artikel, und insbesondere die EANs sind der Einfachheit halber vereinfacht (001, 002, etc.). So kannst du sie durch händische Eingaben testen, ohne einen Barcode-Leser. Hast du einen Barcode-Leser zur Hand, kannst du natürlich einfach eigene EANs scannen und in die CSV-Datei einfügen, und diese anschließend importieren.

Das Admin-Panel ist im Normalfall ausgeblendet und wird nur eingeblendet, wenn ein Admin eingeloggt ist. Der Einfachheit halber habe ich es standardmäßig jedoch eingeblendet. Um die normale Funktionalität herzustellen, musst du die Variable "adminPanelActive" auf false setzen.

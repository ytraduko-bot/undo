# undo
Mit diesem AddOn kann ein gelöschter Artikel oder eine gelöschte Kategorie wiederhergestellt werden. Das Wiederherstellen funktioniert nur einen einzigen Pageload lang. Sobald die Seite oder ein neuer Tab geladen wird, ist ein Revert nicht mehr möglich (soll nur vor versehentlichem Löschen schützen).

![Screenshot](https://raw.githubusercontent.com/FriendsOfREDAXO/undo/assets/screenshot.png)

ToDo
-----
Ich würde gerne noch die Möglichkeit für Templates und Module anbieten, hierzu gibt es aber aktuell noch keine EPs. Sobald das REX-Core Team diese zur Verfügung gestellt hat, wird diese Funktion nachgereicht.

Weitere Hinweise
-----
Da REDAXO aktuell noch keinen EP bei einem Core-Update zur Verfügung stellt, sollte dieses AddOn nach jedem Core-Update deinstalliert und wieder installiert werden (reinstallieren funktioniert nicht). Dadurch werden Änderungen an der Tabelle rex_article und rex_article_slice automatisch übernommen.

# IOS-Testapp

## Manuelles Deployen (AdHoc / Webseite)
1. Im XCode BuildType (oben in der Leiste) auf Betatest umstellen
2. danach unter "Product > Archive" die App builden lassen
3. Wenns fertig ist
   1. Distribute App
   2. Release Testing
   3. Export
4. Speicher Ort angeben
5. Im GitHub auf Upload File gehen
6. Im exportierten Ordner nur die gebuildete App hochladen ("Red Betatest.ipa")
7. Danach wird automatisch eine GitHub Action getriggert, welche die "Download Website" aktualisiert

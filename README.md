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

## Testflight
Versionsnummer gegebenenfalls anpassen
1. Im XCode BuildType (oben in der Leiste) auf Release umstellen
2. danach unter "Product > Archive" die App builden lassen
3. Wenns fertig ist
   1. Distribute App
   2. TestFlight & App Store
   3. Done (App wird standartmässig für alle Developer Accounts verfügbar gemacht)
4. im App Store Connect -> Testflight
   1. App für weitere Gruppen freigeben
   2. Redline Small (Timo private Adresse) / Redline Intern (Redline Tester Team, Yves Daniel, Timo privat)
   3. Testanweisung angeben, zur Prüfung übermitteln
   4. Dauert normalerweise wenige Stunden

Release Prüfung dauert normalerweise nochmals einige Stunden bis wenige Tage.
 - Login Daten überprüfen, ob sie noch aktiv sind

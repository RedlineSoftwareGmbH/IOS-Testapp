# IOS-Testapp

## Manuelles Deployen
1. Im XCode BuildType (oben in der Leiste) auf Betatest umstellen
2. danach unter "Product > Archive" die App builden lassen
3. Wenns fertig ist
   1. Distribute App
   2. Ad Hoc
      1. App thinning: None
      2. Strip Swift Symbols: Ja
      3. Include manifest...: Nein
   6. Automatically manage signing
   7. Export
 8. Speicher Ort angeben
 9. Im GitHub auf Upload File gehen
 10. Im exportierten Ordner nur die gebuildete App hochladen ("Red Betatest.ipa")
 11. Danach wird automatisch eine GitHub Action getriggert, welche die "Download Website" aktualisiert

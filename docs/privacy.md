# Datenschutz für Picardly

Stand: 5. Oktober 2026 · Android-App com.picambo.picardly.preview, Version 0.4.0; ältere Ausgaben ohne Kontofunktion bleiben lokal

## Verantwortlicher

Picambo UG (haftungsbeschränkt), An der Storchenhecke 1, 36251 Ludwigsau Rohrbach, Deutschland. Vertreten durch Hendrik Rößing. Datenschutz: legal@picambo.com. Allgemeiner Kontakt: kontakt@picambo.com.

## Lokale Nutzung ohne Konto

Picardly speichert Kartennamen, statische Codes, Notizen, Kategorien sowie bestätigte Kartenbilder verschlüsselt im privaten App-Speicher. Texterkennung und Barcode-/QR-Auswertung verarbeiten Inhalte auf dem Gerät. Für die lokale Nutzung ist kein Benutzerkonto erforderlich. Ohne ausdrücklich eingeschaltete Synchronisation werden Karteninhalte nicht in eine Picardly-Cloud übertragen. Fotos und Kartentexte werden nicht für Training oder eine externe KI-Auswertung hochgeladen. Es gibt keine Werbung und kein eigenes Analyse-SDK.

## Freiwilliges Konto und Synchronisation

Ab Version 0.4.0 ist die Kontofunktion optional verfügbar. Erst beim Öffnen dieser eingerichteten Kontofunktion beziehungsweise beim Fortsetzen einer zuvor eingeschalteten Synchronisation wird Firebase für das Konto verwendet.

Auf Wunsch kannst du ein Konto mit E-Mail-Adresse und Passwort erstellen. Firebase Authentication von Google verarbeitet hierfür E-Mail-Adresse, Kontokennung, Anmeldeinformationen und technische Verbindungs-/Sicherheitsdaten. E-Mail-Bestätigung und Passwort-Zurücksetzen gehören zur Kontoverwaltung. Kontodaten von Firebase Authentication werden laut Google in den USA verarbeitet. Google-Datenschutzhinweise: https://policies.google.com/privacy. Firebase-Verarbeitungsinformationen: https://firebase.google.com/support/privacy/.

Die Synchronisation wird gesondert eingeschaltet. Dann werden alle Karten, Codes, Notizen, Kategorien und Bilder einschließlich geschützter Karten vor der Übertragung auf dem Gerät mit AES-256-GCM verschlüsselt und per HTTPS in Firebase Realtime Database übertragen. Datenbankstandort ist Belgien. Picambo und Google erhalten den Entschlüsselungsschlüssel nicht. Technisch sichtbar bleiben Kontokennung, verschlüsselte Datenmenge, Revisionskennung, Schlüsselprüfwert, Änderungszeit und Verbindungsdaten. Es erfolgt kein Training mit Karteninhalten.

Dein zufällig erzeugter Wiederherstellungsschlüssel wird geschützt auf dem Gerät gespeichert. Du musst ihn selbst sicher aufbewahren und auf weiteren Geräten eingeben. Picambo kann ihn nicht wiederherstellen. Ein neues Kontopasswort ersetzt keinen verlorenen Schlüssel. Auf einem entsperrten, verbundenen Gerät können berechtigte Personen deine Karten lesen.

Der Abgleich erfolgt bei eingeschalteter Funktion beim Öffnen und im Vordergrund nach Änderungen beziehungsweise regelmäßig. Ohne Internet bleiben Änderungen lokal. Gleichzeitige widersprüchliche Änderungen benötigen eine Auswahl. Löschungen werden ebenfalls auf verbundene Geräte übertragen. Die Cloud ist keine unveränderliche Sicherung; eigene Sicherungsdateien bleiben empfohlen.

Die Verarbeitung dient der von dir angeforderten Kontoführung und geräteübergreifenden Kartenverwaltung (Art. 6 Abs. 1 lit. b DSGVO). Firebase wird als Dienstleister eingesetzt; Informationen zu Googles Auftragsverarbeitungsbedingungen und Übermittlungsmechanismen findest du unter https://firebase.google.com/terms/data-processing-terms. Die Funktion ist freiwillig und abschaltbar. Beim Abschalten bleibt die Cloud-Kopie erhalten, bis du das Konto löschst.

## Cloud-Konto löschen

Unter Mehr → Konto & Synchronisation kannst du das Konto samt Cloud-Karten nach erneuter Passwortbestätigung löschen. Ohne Zugriff auf die App kannst du die Löschung über legal@picambo.com anfordern; zur Zuordnung und Missbrauchsvermeidung wird die Kontoinhaberschaft geprüft. Sende keine Passwörter, Schlüssel oder Ausweiskopien.

Cloud-Karten und Fotos werden beim erfolgreichen Löschvorgang entfernt, anschließend das Authentifizierungskonto. Nur eine technische Löschsperre unter der bisherigen Kontokennung bleibt bestehen, damit andere noch angemeldete Geräte keine Karten erneut hochladen. Sie enthält keine E-Mail-Adresse, Karteninhalte oder Fotos. Bei unterbrochener Kontolöschung kann der Vorgang wiederholt werden. Lokale Karten auf deinen Geräten, externe Sicherungen sowie gegebenenfalls gesetzlich aufzubewahrende Kontaktunterlagen werden getrennt behandelt.

## Kamera, Galerie und Gerätesperre

Die Kamera dient freiwilligen Aufnahmen. Die Systemauswahl gibt die von dir ausgewählten Bilder oder Dateien frei; Picardly durchsucht nicht selbst deine gesamte Galerie. Eigene temporäre Arbeitskopien werden nach der Verarbeitung entfernt. Externe Kamera- und Galerie-Apps behalten gegebenenfalls ihre Originale. Ausweis- und Zugangskarten können die Android-Gerätesperre verwenden. Biometrische Merkmale oder dein Geräte-PIN werden dabei nicht an Picardly übermittelt. Standort, Kontakte und Mikrofon werden nicht angefordert.

## Google ML Kit

Texterkennung und Barcode-Erkennung verwenden Google ML Kit. Google beschreibt die Verarbeitung von Bildern, Texten und Erkennungsergebnissen als lokal. Die SDKs können jedoch technische Geräte-/Appinformationen, Installationskennungen, Nutzung von Erkennungsfunktionen, Leistungswerte und Fehlercodes für Diagnose und Nutzungsanalyse per HTTPS übertragen. Diese Daten sind von deinen Karteninhalten zu unterscheiden. Die App bietet keine globale Abschaltung dieser SDK-Telemetrie.

Quellen: https://developers.google.com/ml-kit/terms und https://developers.google.com/ml-kit/android-data-disclosure. Googles Datenschutzhinweise: https://policies.google.com/privacy.

## Optionale Firmenlogos

Bei bekannten Anbietern lädt Picardly Logos von Wikimedia Commons. Übertragen werden der öffentliche Logo-Dateiname und übliche technische Verbindungsdaten wie die IP-Adresse, keine Kartennummern, Fotos oder OCR-Texte. Die Abfrage kann erkennen lassen, welches Firmenlogo angefordert wird. Geschützte Ausweis-/Zugangskarten lösen keine Logoabfrage aus. Logos werden lokal zwischengespeichert, bei Bedarf nach sieben Tagen erneuert und bleiben offline sichtbar. Du kannst den Abruf unter Mehr ausschalten. Bereits gespeicherte öffentliche Logos bleiben im Cache, bis der App-Speicher entfernt wird. Hinweise: https://foundation.wikimedia.org/wiki/Policy:Privacy_policy.

## Sicherungen, Export und Löschen

Eine Sicherung wird erst auf deinen Wunsch erstellt und mit deinem gewählten Passwort verschlüsselt. Dieses Passwort wird nicht gespeichert. Du wählst die Datei beziehungsweise das Speicherziel selbst; bei einem Cloud-Ziel gelten die Bedingungen des jeweiligen Anbieters. Einzelne Karten kannst du in der Detailansicht löschen. Exporte und Originale außerhalb der App müssen dort getrennt gelöscht werden. Automatisches Android-App-Backup ist deaktiviert. Deinstallation oder Entfernen des App-Speichers kann alle lokalen Karten und Schlüssel löschen.

## Updates und externe Seiten

Die Google-Play-Ausgabe prüft und installiert keine externen APK-Updates. Updates werden von Google Play bereitgestellt. Die direkt verteilte APK fragt GitHub nach neueren Versionen und lädt eine APK erst nach deiner Auswahl. GitHub erhält übliche IP-/HTTP-Verbindungsdaten, keine Karteninhalte. Hinweise: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement. Beim Öffnen externer Seiten gelten deren Datenschutzhinweise.

## Zweck und Aufbewahrung

Die Verarbeitung dient der von dir gewünschten lokalen Kartenverwaltung, Erkennung und Sicherung. Wenn du Picambo kontaktierst, verarbeiten wir deine freiwilligen Angaben zur Bearbeitung der Anfrage nach Art. 6 Abs. 1 lit. b DSGVO oder bei nicht vertragsbezogenen Anfragen nach Art. 6 Abs. 1 lit. f DSGVO. Kontaktangaben bleiben nur so lange gespeichert, wie dies erforderlich ist beziehungsweise gesetzliche Pflichten bestehen. Sende keine vollständigen Ausweise oder Zugangscodes an den Support. SDK- und Serverdaten liegen beim jeweiligen Anbieter nach dessen Aufbewahrungsregeln.

## Deine Rechte

Soweit Picambo personenbezogene Daten verarbeitet, bestehen unter den gesetzlichen Voraussetzungen Rechte auf Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit, Widerspruch und Widerruf einer Einwilligung. Kontakt: legal@picambo.com. Du kannst dich bei einer Datenschutzaufsichtsbehörde beschweren, insbesondere beim Hessischen Beauftragten für Datenschutz und Informationsfreiheit: https://datenschutz.hessen.de. Bei Daten anderer Anbieter kannst du dich zusätzlich an diese wenden.

## Änderungen

Bei Änderungen der Funktionen oder Datenverarbeitung werden diese Hinweise aktualisiert und in der App bereitgestellt. Karteninhalte werden nicht verkauft.

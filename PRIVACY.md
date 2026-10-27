# Datenschutzerklärung für „Claude Gmail“

Stand: 27. Oktober 2026

„Claude Gmail“ ist eine private OAuth-App von Florian Kern. Sie wird ausschließlich mit seinen eigenen Google-Konten genutzt.

## Welche Daten die App abruft

Mit dem Scope `https://www.googleapis.com/auth/gmail.readonly` liest die App Mails, Konversationen, Anhänge und Labels. Mit `https://www.googleapis.com/auth/gmail.compose` legt sie auf Florians Anweisung Entwürfe an. Ein Sendebefehl ist in der lokalen Software abgeschaltet, Entwürfe verschickt Florian selbst. Über `userinfo.email` und `userinfo.profile` erhält sie die E-Mail-Adresse und den Namen des angemeldeten Kontos. Löschen, Verschieben oder Labels ändern kann die App nicht.

## Wo die Daten verarbeitet werden

Der MCP-Server läuft lokal auf Florians Mac. Die OAuth-Token liegen dort in einer nur für seinen Benutzer lesbaren Datei. Die App betreibt keinen eigenen Server und speichert keine Mails dauerhaft.

Mailinhalte, die Florian ausdrücklich abfragt, gehen an den KI-Assistenten, den er dafür nutzt. Die Verarbeitung dort richtet sich nach den Bedingungen dieses Anbieters.

## Weitergabe

Die Daten werden nicht verkauft, nicht für Werbung verwendet und nicht an Dritte weitergegeben. Die Nutzung von Daten aus Google-APIs hält sich an die [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), einschließlich der Limited-Use-Anforderungen.

## Zugriff widerrufen

Der Zugriff lässt sich jederzeit unter https://myaccount.google.com/permissions entfernen. Danach kann die App das Postfach nicht mehr lesen.

## Kontakt

snoopynose2@gmail.com

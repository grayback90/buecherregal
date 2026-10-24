# Bücherregal

Eine Android-App als virtuelles Bücherregal.
Du sammelst deine Bücher an einem Ort und sortierst sie in Regale.

Die App ist hauptsächlich für den privaten Gebrauch gedacht. Für uns zwei.

## Idee

Bücher gehören in Regale. Diese App macht das digital.
Jedes Buch liegt in genau einem Regal. Du kannst es jederzeit verschieben.

## Regale

| Regal | Bedeutung |
|-------|-----------|
| Gelesen | Bücher, die du durch hast |
| TBR | To Be Read. Bücher, die du als Nächstes lesen willst |
| Want to buy | Bücher, die du dir noch kaufen willst |

Weitere eigene Regale sind später denkbar.

## Geplante Funktionen

- Anmeldung mit Google
- Buch mit Titel und Autor hinzufügen
- Buch in ein Regal einsortieren
- Buch zwischen Regalen verschieben
- Buch bearbeiten und löschen
- Daten liegen in der Cloud, nicht nur auf dem Gerät

Die genaue Liste und Reihenfolge steht in der `ToDo.txt`.

## Datenspeicherung

Die Daten sollen nicht nur lokal liegen.
Wenn das Handy kaputt geht oder gewechselt wird, bleiben die Bücher erhalten.
Nach dem Login auf einem neuen Gerät ist alles wieder da.

Erste Version: Die App läuft zunächst ohne Login und ohne Cloud.
Login und Cloud-Speicherung kommen in einem späteren Schritt.

## Tech-Stack

- Kotlin
- Jetpack Compose
- Firebase Authentication (Google Login)
- Cloud Firestore (Datenspeicherung)
- Minimum SDK: API 26

Der Stack ist ein Vorschlag und kann sich im Laufe des Projekts ändern.

## Projektstatus

Frühe Planungsphase. Das Projekt wird Schritt für Schritt aufgebaut.

## Arbeitsweise

Die Aufgaben stehen in der `ToDo.txt`.
Immer ein Schritt nach dem anderen, danach wird der Stand im Repo geprüft.

## Lizenz

Noch offen.
# buecherregal
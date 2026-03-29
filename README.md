<div align="center">

# 🏋️ ForceTrack

### Privacy Policy / Datenschutzerklärung

<br>

![Platform](https://img.shields.io/badge/Platform-Android-4E87A0?style=for-the-badge&logo=android&logoColor=white)
![Framework](https://img.shields.io/badge/Framework-React_Native_/_Expo-4C4C4C?style=for-the-badge&logo=react&logoColor=white)
![Storage](https://img.shields.io/badge/Storage-Local_Only-808C24?style=for-the-badge&logo=sqlite&logoColor=white)
![Tracking](https://img.shields.io/badge/Tracking-None-DAAA00?style=for-the-badge&logo=shieldsdotio&logoColor=white)

<br>

<table>
<tr>
<td align="center" width="150">

**🔒 Local Data**<br><sub>All training data stays on your device</sub>

</td>
<td align="center" width="150">

**🚫 No Tracking**<br><sub>No analytics, ads, or cookies</sub>

</td>
<td align="center" width="150">

**🛡️ GDPR**<br><sub>Fully compliant</sub>

</td>
<td align="center" width="150">

**📤 Your Control**<br><sub>Export & import anytime</sub>

</td>
</tr>
</table>

<br>

**Choose your language / Sprache wählen**

[![Deutsch](https://img.shields.io/badge/🇩🇪_Deutsch-4C4C4C?style=for-the-badge)](#-datenschutzerklärung)
&nbsp;&nbsp;
[![English](https://img.shields.io/badge/🇬🇧_English-4E87A0?style=for-the-badge)](#-privacy-policy)

</div>

<br>

---

<br>

<div align="center">
<h2>🇩🇪 Datenschutzerklärung</h2>
<sub>Stand: Februar 2026</sub>
</div>

<br>

### 1 · Einleitung

Diese Datenschutzerklärung informiert Sie über die Art, den Umfang und den Zweck der Verarbeitung personenbezogener Daten innerhalb der mobilen Anwendung **ForceTrack** (nachfolgend „App"). Wir nehmen den Schutz Ihrer persönlichen Daten sehr ernst und behandeln Ihre personenbezogenen Daten vertraulich und entsprechend der gesetzlichen Datenschutzvorschriften sowie dieser Datenschutzerklärung.

> **Verantwortlicher**
> Patrick Pfüller · [app-patrick@web.de](mailto:app-patrick@web.de)

---

### 2 · Übersicht der App-Funktionen

ForceTrack ist eine Trainings-App für das Tracking von Krafttraining. Die App ermöglicht es Ihnen:

|     | Funktion                                          |
| --- | ------------------------------------------------- |
| 📋  | Trainingspläne erstellen und verwalten            |
| 💪  | Trainingsübungen anlegen und konfigurieren        |
| ▶️  | Trainingseinheiten durchführen und dokumentieren  |
| 📊  | Trainingsfortschritte und Statistiken analysieren |
| 📅  | Trainingsverlauf einsehen                         |

---

### 3 · Welche Daten werden erhoben?

<details open>
<summary><strong>3.1 — Lokal gespeicherte Daten (auf Ihrem Gerät)</strong></summary>

<br>

Die App speichert folgende Daten **ausschließlich lokal auf Ihrem Gerät** in einer SQLite-Datenbank:

| Kategorie              | Datenfelder                                                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Trainingspläne**     | Name, Symbol                                                                                               |
| **Trainingsübungen**   | Name, Notizen, Geräteeinstellung, Gewicht, Gewichtseinheit, Wiederholungen, Reihenfolge, Symbol            |
| **Trainingssitzungen** | Übungs-ID, durchgeführtes Gewicht, absolvierte Wiederholungen, Status (erledigt/übersprungen), Zeitstempel |

> 🔒 Diese Daten verlassen Ihr Gerät nicht und werden nicht an Server oder Dritte übertragen.

</details>

<details>
<summary><strong>3.2 — Feedback-Funktion (optional)</strong></summary>

<br>

Wenn Sie die optionale Feedback-Funktion nutzen, werden folgende Daten **anonym** übermittelt:

- Ihre Sternebewertung (1–5 Sterne)
- Ihr optionaler Feedback-Text

> ⚠️ Es werden dabei **keine personenbezogenen Daten** erhoben. Das Feedback wird über Google Apps Script an eine Google Tabelle übermittelt. Es werden keine Identifizierungsmerkmale wie Geräte-ID, IP-Adresse oder Nutzername gespeichert.

</details>

<details>
<summary><strong>3.3 — App-Updates und Drittanbieter-Dienste (Expo)</strong></summary>

<br>

Die App wurde mit dem Framework **Expo** (650 Industries, Inc., USA) entwickelt. Im Rahmen der Nutzung können durch Expo folgende technische Daten verarbeitet werden:

**Expo Updates**

Die App nutzt den Dienst „Expo Updates" zur Bereitstellung von App-Aktualisierungen. Bei der Prüfung auf Updates werden folgende **nicht-personenbezogene** technische Daten übermittelt:

- Betriebssystem des Geräts
- Projekt-ID des Entwicklers
- Ein zufällig generierter Token zur Feststellung, ob ein Update bereits heruntergeladen wurde

> Es werden dabei **keine** eindeutigen Geräte-Identifikatoren oder personenbezogenen Daten übertragen.

**Datenverarbeitung durch Expo**

Expo agiert als Auftragsverarbeiter und verarbeitet die genannten technischen Daten ausschließlich zur Bereitstellung der Update-Funktionalität. Expo ist DSGVO-, CCPA- und Data Privacy Framework-konform.
Weitere Informationen: [expo.dev/privacy](https://expo.dev/privacy)

**Keine Push-Benachrichtigungen** — Die App verwendet keine Push-Benachrichtigungen, daher werden keine Push-Tokens erhoben oder an Expo übermittelt.

</details>

---

### 4 · Welche Berechtigungen benötigt die App?

| Berechtigung                                     | Zweck                                                                            |
| ------------------------------------------------ | -------------------------------------------------------------------------------- |
| 📁 **Speicherzugriff** (`READ_EXTERNAL_STORAGE`) | Import & Export von Datenbank-Backups zur Wiederherstellung Ihrer Trainingsdaten |

---

### 5 · Datenspeicherung und Sicherheit

**5.1 — Lokale Speicherung**

Alle Ihre Trainingsdaten werden **ausschließlich lokal** auf Ihrem Gerät in einer SQLite-Datenbank gespeichert. Die App verfügt über keine eigenen Server oder Cloud-Dienste zur Datenspeicherung.

**5.2 — Export und Import**

| Funktion      | Beschreibung                                                                          |
| ------------- | ------------------------------------------------------------------------------------- |
| 📤 **Export** | Datenbank-Datei exportieren und an einem Ort Ihrer Wahl speichern (z. B. für Backups) |
| 📥 **Import** | Zuvor exportierte Datenbanken importieren, um Ihre Daten wiederherzustellen           |

> Diese Funktionen dienen der Datensicherung und dem Transfer zwischen Geräten. Die Verantwortung für die sichere Aufbewahrung exportierter Daten liegt bei Ihnen.

---

### 6 · Datenweitergabe an Dritte

Wir geben Ihre personenbezogenen Daten **nicht** an Dritte weiter, es sei denn:

- Sie haben Ihre ausdrückliche Einwilligung gegeben
- Es besteht eine gesetzliche Verpflichtung

Bei Nutzung der Feedback-Funktion werden die anonymen Feedback-Daten über Google Apps Script verarbeitet und in einer Google Tabelle gespeichert. Dies geschieht auf Grundlage Ihrer freiwilligen Nutzung.

---

### 7 · Keine Werbung, kein Tracking

<table>
<tr>
<td>🚫 Keine Werbung</td>
<td>🚫 Keine Analyse- oder Tracking-Tools</td>
</tr>
<tr>
<td>🚫 Keine Social Media Plugins</td>
<td>🚫 Keine Cookies</td>
</tr>
</table>

---

### 8 · Ihre Rechte

| Recht                       | Details                                                                                  |
| --------------------------- | ---------------------------------------------------------------------------------------- |
| 🔍 **Auskunft**             | Jederzeit Ihre in der App gespeicherten Daten einsehen (Trainingshistorie, Statistiken)  |
| 🗑️ **Löschung**             | Einzelne Übungen, Trainingseinheiten oder gesamte Datenbank durch Deinstallation löschen |
| 📤 **Datenübertragbarkeit** | Daten über die Export-Funktion in den Einstellungen exportieren                          |
| 🎛️ **Volle Kontrolle**      | Alle Daten liegen lokal auf Ihrem Gerät — Sie haben jederzeit volle Kontrolle            |

---

### 9 · Datensicherheit

Wir empfehlen folgende Maßnahmen zum Schutz Ihrer Daten:

- 🔐 Nutzen Sie die Bildschirmsperre Ihres Geräts
- 💾 Erstellen Sie regelmäßig Backups über die Export-Funktion
- 🗄️ Bewahren Sie exportierte Backups sicher auf

---

### 10 · Aufbewahrungsdauer

- **Lokale Daten** — Ihre Trainingsdaten bleiben auf Ihrem Gerät gespeichert, bis Sie diese manuell löschen oder die App deinstallieren
- **Feedback-Daten** — Übermittelte Feedback-Daten werden auf unbestimmte Zeit in der Google Tabelle des Entwicklers gespeichert

---

### 11 · Kinder

Die App ist nicht speziell für Kinder unter 16 Jahren konzipiert. Wir erheben wissentlich keine personenbezogenen Daten von Kindern unter 16 Jahren.

---

### 12 · Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung bei Bedarf anzupassen, um sie an geänderte Rechtslage oder bei Änderungen der App anzupassen. Die aktuelle Version ist immer in der App bzw. im App Store einsehbar.

---

### 13 · Kontakt

Bei Fragen zum Datenschutz oder zur Ausübung Ihrer Rechte:

> 📧 **E-Mail:** [app-patrick@web.de](mailto:app-patrick@web.de)

---

### 14 · Technische Informationen

|                             |                             |
| --------------------------- | --------------------------- |
| **App-Name**                | ForceTrack                  |
| **Entwickler**              | Patrick Pfüller             |
| **Plattform**               | Android                     |
| **Mindest-Android-Version** | Android 7.0 (API Level 24)  |
| **Datenbank**               | SQLite (lokale Speicherung) |
| **Framework**               | React Native / Expo         |

---

### 15 · Haftungsausschluss für Drittanbieter-Dienste

Diese App nutzt Dienste von Drittanbietern (insbesondere Expo / 650 Industries, Inc.). Obwohl wir sorgfältig Drittanbieter auswählen, die angemessene Datenschutzstandards einhalten, haben wir keine direkte Kontrolle über deren Datenverarbeitungspraktiken.

**Wir übernehmen keine Haftung für:**

- Datenverarbeitung durch Drittanbieter, die über das in dieser Datenschutzerklärung Beschriebene hinausgeht
- Änderungen an den Datenschutzpraktiken der Drittanbieter
- Sicherheitsvorfälle bei Drittanbietern

**Datenschutzrichtlinien der Drittanbieter:**

- [Expo — expo.dev/privacy](https://expo.dev/privacy)
- [Google — policies.google.com/privacy](https://policies.google.com/privacy)

---

### 16 · Rechtsgrundlagen der Verarbeitung (DSGVO)

| Verarbeitung                          | Rechtsgrundlage                                                                          |
| ------------------------------------- | ---------------------------------------------------------------------------------------- |
| Lokale Speicherung von Trainingsdaten | Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung)                                           |
| Feedback-Funktion                     | Art. 6 Abs. 1 lit. a DSGVO (Einwilligung durch freiwillige Nutzung)                      |
| App-Updates über Expo                 | Art. 6 Abs. 1 lit. f DSGVO (Berechtigtes Interesse an Bereitstellung aktueller Software) |

---

<div align="center">

> **Zusammenfassung:** ForceTrack ist eine datenschutzfreundliche Trainings-App. Alle Ihre Trainingsdaten werden ausschließlich lokal auf Ihrem Gerät gespeichert. Es erfolgt kein Tracking, keine Werbung und keine automatische Datenübertragung. Nur bei Nutzung der optionalen Feedback-Funktion werden anonyme Daten übermittelt.

<sub>Letzte Aktualisierung: Februar 2026</sub>

</div>

<br>

---

<br>

<div align="center">
<h2>🇬🇧 Privacy Policy</h2>
<sub>Last updated: February 2026</sub>
</div>

<br>

### 1 · Introduction

This privacy policy informs you about the nature, scope, and purpose of the processing of personal data within the mobile application **ForceTrack** (hereinafter "App"). We take the protection of your personal data very seriously and treat your personal data confidentially and in accordance with statutory data protection regulations and this privacy policy.

> **Data Controller**
> Patrick Pfüller · [app-patrick@web.de](mailto:app-patrick@web.de)

---

### 2 · Overview of App Functions

ForceTrack is a fitness training app for tracking strength training. The app allows you to:

|     | Feature                                  |
| --- | ---------------------------------------- |
| 📋  | Create and manage training plans         |
| 💪  | Add and configure training exercises     |
| ▶️  | Perform and document training sessions   |
| 📊  | Analyze training progress and statistics |
| 📅  | View training history                    |

---

### 3 · What Data is Collected?

<details open>
<summary><strong>3.1 — Locally Stored Data (on your device)</strong></summary>

<br>

The app stores the following data **exclusively locally on your device** in a SQLite database:

| Category               | Data Fields                                                                                 |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| **Training plans**     | Name, icon                                                                                  |
| **Training exercises** | Name, notes, equipment settings, weight, weight unit, repetitions, order, icon              |
| **Training sessions**  | Exercise ID, performed weight, completed repetitions, status (completed/skipped), timestamp |

> 🔒 This data does not leave your device and is not transmitted to servers or third parties.

</details>

<details>
<summary><strong>3.2 — Feedback Function (optional)</strong></summary>

<br>

If you use the optional feedback function, the following data is transmitted **anonymously**:

- Your star rating (1–5 stars)
- Your optional feedback text

> ⚠️ **No personal data** is collected. The feedback is transmitted via Google Apps Script to a Google Spreadsheet. No identifying information such as device ID, IP address, or username is stored.

</details>

<details>
<summary><strong>3.3 — App Updates and Third-Party Services (Expo)</strong></summary>

<br>

The app was developed using the **Expo** framework (650 Industries, Inc., USA). When using the app, the following technical data may be processed by Expo:

**Expo Updates**

The app uses the "Expo Updates" service to provide app updates. When checking for updates, the following **non-personal** technical data is transmitted:

- Device operating system
- Developer's project ID
- A randomly generated token to determine if an update has already been downloaded

> **No** unique device identifiers or personal data are transmitted.

**Data Processing by Expo**

Expo acts as a data processor and processes the aforementioned technical data solely for providing update functionality. Expo is GDPR, CCPA, and Data Privacy Framework compliant.
More information: [expo.dev/privacy](https://expo.dev/privacy)

**No Push Notifications** — The app does not use push notifications, therefore no push tokens are collected or transmitted to Expo.

</details>

---

### 4 · What Permissions Does the App Require?

| Permission                                      | Purpose                                                        |
| ----------------------------------------------- | -------------------------------------------------------------- |
| 📁 **Storage Access** (`READ_EXTERNAL_STORAGE`) | Import & export database backups to restore your training data |

---

### 5 · Data Storage and Security

**5.1 — Local Storage**

All your training data is stored **exclusively locally** on your device in a SQLite database. The app does not have its own servers or cloud services for data storage.

**5.2 — Export and Import**

| Function      | Description                                                                            |
| ------------- | -------------------------------------------------------------------------------------- |
| 📤 **Export** | Export your database file and save it to a location of your choice (e.g., for backups) |
| 📥 **Import** | Import previously exported databases to restore your data                              |

> These functions are for data backup and transfer between devices. The responsibility for the secure storage of exported data lies with you.

---

### 6 · Data Sharing with Third Parties

We do **not** share your personal data with third parties unless:

- You have given your explicit consent
- There is a legal obligation

If you use the feedback function, the anonymous feedback data is processed via Google Apps Script and stored in a Google Spreadsheet. This is done based on your voluntary use of the feedback function.

---

### 7 · No Advertising, No Tracking

<table>
<tr>
<td>🚫 No advertising</td>
<td>🚫 No analytics or tracking tools</td>
</tr>
<tr>
<td>🚫 No social media plugins</td>
<td>🚫 No cookies</td>
</tr>
</table>

---

### 8 · Your Rights

| Right                   | Details                                                                                        |
| ----------------------- | ---------------------------------------------------------------------------------------------- |
| 🔍 **Access**           | View your data stored in the app at any time (training history, statistics)                    |
| 🗑️ **Deletion**         | Delete individual exercises, training sessions, or the entire database by uninstalling the app |
| 📤 **Data Portability** | Export your data via the export function in settings                                           |
| 🎛️ **Full Control**     | All data is stored locally on your device — you have full control at all times                 |

---

### 9 · Data Security

We recommend the following measures to protect your data:

- 🔐 Use your device's screen lock
- 💾 Create regular backups via the export function
- 🗄️ Store exported backups securely

---

### 10 · Retention Period

- **Local data** — Your training data remains stored on your device until you manually delete it or uninstall the app
- **Feedback data** — Submitted feedback data is stored indefinitely in the developer's Google Spreadsheet

---

### 11 · Children

The app is not specifically designed for children under 16 years of age. We do not knowingly collect personal data from children under 16 years of age.

---

### 12 · Changes to This Privacy Policy

We reserve the right to adapt this privacy policy as necessary to comply with changed legal requirements or when changes are made to the app. The current version is always available in the app or in the app store.

---

### 13 · Contact

For questions about data protection or to exercise your rights:

> 📧 **Email:** [app-patrick@web.de](mailto:app-patrick@web.de)

---

### 14 · Technical Information

|                             |                            |
| --------------------------- | -------------------------- |
| **App Name**                | ForceTrack                 |
| **Developer**               | Patrick Pfüller            |
| **Platform**                | Android                    |
| **Minimum Android Version** | Android 7.0 (API Level 24) |
| **Database**                | SQLite (local storage)     |
| **Framework**               | React Native / Expo        |

---

### 15 · Disclaimer for Third-Party Services

This app uses services from third-party providers (in particular Expo / 650 Industries, Inc.). Although we carefully select third-party providers that maintain appropriate privacy standards, we have no direct control over their data processing practices.

**We assume no liability for:**

- Data processing by third parties beyond what is described in this privacy policy
- Changes to the privacy practices of third-party providers
- Security incidents at third-party providers

**Third-party privacy policies:**

- [Expo — expo.dev/privacy](https://expo.dev/privacy)
- [Google — policies.google.com/privacy](https://policies.google.com/privacy)

---

### 16 · Legal Basis for Processing (GDPR)

| Processing                     | Legal Basis                                                              |
| ------------------------------ | ------------------------------------------------------------------------ |
| Local storage of training data | Art. 6(1)(b) GDPR (Contract performance)                                 |
| Feedback function              | Art. 6(1)(a) GDPR (Consent through voluntary use)                        |
| App updates via Expo           | Art. 6(1)(f) GDPR (Legitimate interest in providing up-to-date software) |

---

<div align="center">

> **Summary:** ForceTrack is a privacy-friendly fitness training app. All your training data is stored exclusively locally on your device. There is no tracking, no advertising, and no automatic data transmission. Only when using the optional feedback function is anonymous data transmitted.

<sub>Last updated: February 2026</sub>

</div>

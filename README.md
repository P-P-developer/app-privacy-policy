# Datenschutzerklärung für Dortler / Privacy Policy for Dortler

**Sprache wählen / Choose language:**

- [Deutsch (German)](#deutsch)
- [English](#english)

---

<a name="deutsch"></a>

# 🇩🇪 Datenschutzerklärung für Dortler

**Stand: Februar 2026**

## 1. Einleitung

Diese Datenschutzerklärung informiert Sie über die Art, den Umfang und den Zweck der Verarbeitung personenbezogener Daten innerhalb der mobilen Anwendung "Dortler" (nachfolgend "App"). Wir nehmen den Schutz Ihrer persönlichen Daten sehr ernst und behandeln Ihre personenbezogenen Daten vertraulich und entsprechend der gesetzlichen Datenschutzvorschriften sowie dieser Datenschutzerklärung.

**Verantwortlicher:**  
Patrick Pfüller  
E-Mail: app-patrick@web.de

## 2. Übersicht der App-Funktionen

Dortler ist eine Trainings-App für das Tracking von Krafttraining. Die App ermöglicht es Ihnen:

- Trainingspläne zu erstellen und zu verwalten
- Trainingsübungen anzulegen und zu konfigurieren
- Trainingseinheiten durchzuführen und zu dokumentieren
- Trainingsfortschritte und Statistiken zu analysieren
- Trainingsverlauf einzusehen

## 3. Welche Daten werden erhoben?

### 3.1 Lokal gespeicherte Daten (auf Ihrem Gerät)

Die App speichert folgende Daten **ausschließlich lokal auf Ihrem Gerät** in einer SQLite-Datenbank:

- **Trainingspläne:** Name und Symbol des Trainingsplans
- **Trainingsübungen:** Name, Notizen, Geräteeinstellung, Gewicht, Gewichtseinheit, Wiederholungen, Reihenfolge, Symbol
- **Trainingssitzungen:** Übungs-ID, durchgeführtes Gewicht, absolvierte Wiederholungen, Status (erledigt/übersprungen), Zeitstempel

Diese Daten verlassen Ihr Gerät nicht und werden nicht an Server oder Dritte übertragen.

### 3.2 Feedback-Funktion (optional)

Wenn Sie die optionale Feedback-Funktion nutzen, werden folgende Daten **anonym** übermittelt:

- Ihre Sternebewertung (1-5 Sterne)
- Ihr optionaler Feedback-Text

**Wichtig:** Es werden dabei **keine personenbezogenen Daten** erhoben. Das Feedback wird über Google Apps Script an eine Google Tabelle übermittelt. Es werden keine Identifizierungsmerkmale wie Geräte-ID, IP-Adresse oder Nutzername gespeichert.

### 3.3 App-Updates und Drittanbieter-Dienste (Expo)

Die App wurde mit dem Framework **Expo** (650 Industries, Inc., USA) entwickelt. Im Rahmen der Nutzung der App können durch Expo folgende technische Daten verarbeitet werden:

#### Expo Updates

Die App nutzt den Dienst "Expo Updates" zur Bereitstellung von App-Aktualisierungen. Bei der Prüfung auf Updates werden folgende **nicht-personenbezogene** technische Daten übermittelt:

- Betriebssystem des Geräts
- Projekt-ID des Entwicklers
- Ein zufällig generierter Token zur Feststellung, ob ein Update bereits heruntergeladen wurde

**Es werden dabei keine eindeutigen Geräte-Identifikatoren oder personenbezogenen Daten übertragen.**

#### Datenverarbeitung durch Expo

Expo agiert als Auftragsverarbeiter und verarbeitet die genannten technischen Daten ausschließlich zur Bereitstellung der Update-Funktionalität. Expo ist DSGVO-, CCPA- und Data Privacy Framework-konform. Weitere Informationen finden Sie in der Datenschutzerklärung von Expo: [https://expo.dev/privacy](https://expo.dev/privacy)

#### Keine Push-Benachrichtigungen

Die App verwendet **keine Push-Benachrichtigungen**, daher werden keine Push-Tokens erhoben oder an Expo übermittelt.

## 4. Welche Berechtigungen benötigt die App?

Die App benötigt folgende Berechtigungen:

| Berechtigung                                | Zweck                                                                                               |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Speicherzugriff (READ_EXTERNAL_STORAGE)** | Ermöglicht den Import sowie Export von Datenbank-Backups zur Wiederherstellung Ihrer Trainingsdaten |

## 5. Datenspeicherung und Sicherheit

### 5.1 Lokale Speicherung

Alle Ihre Trainingsdaten werden **ausschließlich lokal** auf Ihrem Gerät in einer SQLite-Datenbank (`workout_dortler.db`) gespeichert. Die App verfügt über keine eigenen Server oder Cloud-Dienste zur Datenspeicherung.

### 5.2 Export und Import

Die App bietet die Möglichkeit, Ihre Daten zu exportieren und zu importieren:

- **Export:** Sie können Ihre Datenbank-Datei exportieren und an einem Ort Ihrer Wahl speichern (z.B. für Backups)
- **Import:** Sie können zuvor exportierte Datenbanken importieren, um Ihre Daten wiederherzustellen

Diese Funktionen dienen der Datensicherung und dem Transfer zwischen Geräten. Die Verantwortung für die sichere Aufbewahrung exportierter Daten liegt bei Ihnen.

## 6. Datenweitergabe an Dritte

### 6.1 Grundsatz

Wir geben Ihre personenbezogenen Daten **nicht** an Dritte weiter, es sei denn:

- Sie haben Ihre ausdrückliche Einwilligung gegeben
- Es besteht eine gesetzliche Verpflichtung

### 6.2 Feedback-Übermittlung

Wenn Sie die Feedback-Funktion nutzen, werden die anonymen Feedback-Daten über Google Apps Script verarbeitet und in einer Google Tabelle gespeichert. Dies geschieht auf Grundlage Ihrer freiwilligen Nutzung der Feedback-Funktion.

## 7. Keine Werbung, kein Tracking

Die App enthält:

- **Keine Werbung**
- **Keine Analyse- oder Tracking-Tools** (wie Google Analytics, Firebase Analytics, etc.)
- **Keine Social Media Plugins**
- **Keine Cookies**

## 8. Ihre Rechte

Sie haben folgende Rechte bezüglich Ihrer Daten:

### 8.1 Recht auf Auskunft

Sie können jederzeit Ihre in der App gespeicherten Daten einsehen (Trainingshistorie, Statistiken).

### 8.2 Recht auf Löschung

Sie können:

- Einzelne Trainingsübungen löschen
- Einzelne Trainingseinheiten aus der Historie löschen
- Die gesamte Datenbank durch Deinstallation der App löschen

### 8.3 Recht auf Datenübertragbarkeit

Sie können Ihre Daten über die Export-Funktion in den Einstellungen exportieren.

### 8.4 Kontrolle über Ihre Daten

Da alle Daten lokal auf Ihrem Gerät gespeichert werden, haben Sie jederzeit volle Kontrolle über Ihre Trainingsdaten.

## 9. Datensicherheit

Wir empfehlen folgende Maßnahmen zum Schutz Ihrer Daten:

- Nutzen Sie die Bildschirmsperre Ihres Geräts
- Erstellen Sie regelmäßig Backups über die Export-Funktion
- Bewahren Sie exportierte Backups sicher auf

## 10. Aufbewahrungsdauer

- **Lokale Daten:** Ihre Trainingsdaten bleiben auf Ihrem Gerät gespeichert, bis Sie diese manuell löschen oder die App deinstallieren
- **Feedback-Daten:** Übermittelte Feedback-Daten werden auf unbestimmte Zeit in der Google Tabelle des Entwicklers gespeichert

## 11. Kinder

Die App ist nicht speziell für Kinder unter 16 Jahren konzipiert. Wir erheben wissentlich keine personenbezogenen Daten von Kindern unter 16 Jahren.

## 12. Änderungen dieser Datenschutzerklärung

Wir behalten uns vor, diese Datenschutzerklärung bei Bedarf anzupassen, um sie an geänderte Rechtslage oder bei Änderungen der App anzupassen. Die aktuelle Version ist immer in der App bzw. im App Store einsehbar.

## 13. Kontakt

Bei Fragen zum Datenschutz oder zur Ausübung Ihrer Rechte können Sie uns kontaktieren:

**E-Mail:** app-patrick@web.de

## 14. Technische Informationen

- **App-Name:** Dortler
- **Entwickler:** Patrick Pfüller
- **Plattform:** Android
- **Mindest-Android-Version:** Android 7.0 (API Level 24)
- **Datenbank:** SQLite (lokale Speicherung)
- **Framework:** React Native / Expo

## 15. Haftungsausschluss für Drittanbieter-Dienste

Diese App nutzt Dienste von Drittanbietern (insbesondere Expo/650 Industries, Inc.). Obwohl wir sorgfältig Drittanbieter auswählen, die angemessene Datenschutzstandards einhalten, haben wir keine direkte Kontrolle über deren Datenverarbeitungspraktiken.

**Wir übernehmen keine Haftung für:**

- Datenverarbeitung durch Drittanbieter, die über das in dieser Datenschutzerklärung Beschriebene hinausgeht
- Änderungen an den Datenschutzpraktiken der Drittanbieter
- Sicherheitsvorfälle bei Drittanbietern

**Ihre Verantwortung:**

Durch die Nutzung dieser App erklären Sie sich mit der Datenverarbeitung gemäß dieser Datenschutzerklärung sowie den Datenschutzrichtlinien der verwendeten Drittanbieter-Dienste einverstanden. Wir empfehlen Ihnen, die Datenschutzerklärungen der Drittanbieter zu lesen:

- **Expo:** [https://expo.dev/privacy](https://expo.dev/privacy)
- **Google (für Feedback-Funktion):** [https://policies.google.com/privacy](https://policies.google.com/privacy)

## 16. Rechtsgrundlagen der Verarbeitung (DSGVO)

Die Verarbeitung Ihrer Daten erfolgt auf folgenden Rechtsgrundlagen:

| Verarbeitung                          | Rechtsgrundlage                                                                          |
| ------------------------------------- | ---------------------------------------------------------------------------------------- |
| Lokale Speicherung von Trainingsdaten | Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung)                                           |
| Feedback-Funktion                     | Art. 6 Abs. 1 lit. a DSGVO (Einwilligung durch freiwillige Nutzung)                      |
| App-Updates über Expo                 | Art. 6 Abs. 1 lit. f DSGVO (Berechtigtes Interesse an Bereitstellung aktueller Software) |

---

**Zusammenfassung:**  
Dortler ist eine datenschutzfreundliche Trainings-App. Alle Ihre Trainingsdaten werden ausschließlich lokal auf Ihrem Gerät gespeichert. Es erfolgt kein Tracking, keine Werbung und keine automatische Datenübertragung. Nur bei Nutzung der optionalen Feedback-Funktion werden anonyme Daten übermittelt.

---

_Letzte Aktualisierung: Februar 2026_

---

---

---

<a name="english"></a>

# 🇬🇧 Privacy Policy for Dortler

**Last updated: February 2026**

## 1. Introduction

This privacy policy informs you about the nature, scope, and purpose of the processing of personal data within the mobile application "Dortler" (hereinafter "App"). We take the protection of your personal data very seriously and treat your personal data confidentially and in accordance with statutory data protection regulations and this privacy policy.

**Data Controller:**  
Patrick Pfüller  
Email: app-patrick@web.de

## 2. Overview of App Functions

Dortler is a fitness training app for tracking strength training. The app allows you to:

- Create and manage training plans
- Add and configure training exercises
- Perform and document training sessions
- Analyze training progress and statistics
- View training history

## 3. What Data is Collected?

### 3.1 Locally Stored Data (on your device)

The app stores the following data **exclusively locally on your device** in a SQLite database:

- **Training plans:** Name and icon of the training plan
- **Training exercises:** Name, notes, equipment settings, weight, weight unit, repetitions, order, icon
- **Training sessions:** Exercise ID, performed weight, completed repetitions, status (completed/skipped), timestamp

This data does not leave your device and is not transmitted to servers or third parties.

### 3.2 Feedback Function (optional)

If you use the optional feedback function, the following data is transmitted **anonymously**:

- Your star rating (1-5 stars)
- Your optional feedback text

**Important:** **No personal data** is collected. The feedback is transmitted via Google Apps Script to a Google Spreadsheet. No identifying information such as device ID, IP address, or username is stored.

### 3.3 App Updates and Third-Party Services (Expo)

The app was developed using the **Expo** framework (650 Industries, Inc., USA). When using the app, the following technical data may be processed by Expo:

#### Expo Updates

The app uses the "Expo Updates" service to provide app updates. When checking for updates, the following **non-personal** technical data is transmitted:

- Device operating system
- Developer's project ID
- A randomly generated token to determine if an update has already been downloaded

**No unique device identifiers or personal data are transmitted.**

#### Data Processing by Expo

Expo acts as a data processor and processes the aforementioned technical data solely for providing update functionality. Expo is GDPR, CCPA, and Data Privacy Framework compliant. For more information, see Expo's privacy policy: [https://expo.dev/privacy](https://expo.dev/privacy)

#### No Push Notifications

The app does **not use push notifications**, therefore no push tokens are collected or transmitted to Expo.

## 4. What Permissions Does the App Require?

The app requires the following permissions:

| Permission                                 | Purpose                                                                       |
| ------------------------------------------ | ----------------------------------------------------------------------------- |
| **Storage Access (READ_EXTERNAL_STORAGE)** | Allows importing and exporting database backups to restore your training data |

## 5. Data Storage and Security

### 5.1 Local Storage

All your training data is stored **exclusively locally** on your device in a SQLite database (`workout_dortler.db`). The app does not have its own servers or cloud services for data storage.

### 5.2 Export and Import

The app offers the ability to export and import your data:

- **Export:** You can export your database file and save it to a location of your choice (e.g., for backups)
- **Import:** You can import previously exported databases to restore your data

These functions are for data backup and transfer between devices. The responsibility for the secure storage of exported data lies with you.

## 6. Data Sharing with Third Parties

### 6.1 Principle

We do **not** share your personal data with third parties unless:

- You have given your explicit consent
- There is a legal obligation

### 6.2 Feedback Transmission

If you use the feedback function, the anonymous feedback data is processed via Google Apps Script and stored in a Google Spreadsheet. This is done based on your voluntary use of the feedback function.

## 7. No Advertising, No Tracking

The app contains:

- **No advertising**
- **No analytics or tracking tools** (such as Google Analytics, Firebase Analytics, etc.)
- **No social media plugins**
- **No cookies**

## 8. Your Rights

You have the following rights regarding your data:

### 8.1 Right to Access

You can view your data stored in the app at any time (training history, statistics).

### 8.2 Right to Deletion

You can:

- Delete individual training exercises
- Delete individual training sessions from the history
- Delete the entire database by uninstalling the app

### 8.3 Right to Data Portability

You can export your data via the export function in the settings.

### 8.4 Control Over Your Data

Since all data is stored locally on your device, you have full control over your training data at all times.

## 9. Data Security

We recommend the following measures to protect your data:

- Use your device's screen lock
- Create regular backups via the export function
- Store exported backups securely

## 10. Retention Period

- **Local data:** Your training data remains stored on your device until you manually delete it or uninstall the app
- **Feedback data:** Submitted feedback data is stored indefinitely in the developer's Google Spreadsheet

## 11. Children

The app is not specifically designed for children under 16 years of age. We do not knowingly collect personal data from children under 16 years of age.

## 12. Changes to This Privacy Policy

We reserve the right to adapt this privacy policy as necessary to comply with changed legal requirements or when changes are made to the app. The current version is always available in the app or in the app store.

## 13. Contact

For questions about data protection or to exercise your rights, you can contact us:

**Email:** app-patrick@web.de

## 14. Technical Information

- **App Name:** Dortler
- **Developer:** Patrick Pfüller
- **Platform:** Android
- **Minimum Android Version:** Android 7.0 (API Level 24)
- **Database:** SQLite (local storage)
- **Framework:** React Native / Expo

## 15. Disclaimer for Third-Party Services

This app uses services from third-party providers (in particular Expo/650 Industries, Inc.). Although we carefully select third-party providers that maintain appropriate privacy standards, we have no direct control over their data processing practices.

**We assume no liability for:**

- Data processing by third parties beyond what is described in this privacy policy
- Changes to the privacy practices of third-party providers
- Security incidents at third-party providers

**Your Responsibility:**

By using this app, you agree to the data processing in accordance with this privacy policy and the privacy policies of the third-party services used. We recommend that you read the privacy policies of third-party providers:

- **Expo:** [https://expo.dev/privacy](https://expo.dev/privacy)
- **Google (for feedback function):** [https://policies.google.com/privacy](https://policies.google.com/privacy)

## 16. Legal Basis for Processing (GDPR)

The processing of your data is based on the following legal grounds:

| Processing                     | Legal Basis                                                              |
| ------------------------------ | ------------------------------------------------------------------------ |
| Local storage of training data | Art. 6(1)(b) GDPR (Contract performance)                                 |
| Feedback function              | Art. 6(1)(a) GDPR (Consent through voluntary use)                        |
| App updates via Expo           | Art. 6(1)(f) GDPR (Legitimate interest in providing up-to-date software) |

---

**Summary:**  
Dortler is a privacy-friendly fitness training app. All your training data is stored exclusively locally on your device. There is no tracking, no advertising, and no automatic data transmission. Only when using the optional feedback function is anonymous data transmitted.

---

_Last updated: February 2026_

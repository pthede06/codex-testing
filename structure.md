# Website-Struktur – `structure.md`
Technische Übersicht über die Seitenarchitektur und Inhaltsstruktur der Agentur-Website.  
Die Datei dient Entwicklern als Referenz für Aufbau, Inhalte und logische Beziehungen zwischen den Seiten.

---

## 1. Hauptkategorien (Main Navigation)

Die Website besteht aus vier zentralen Hauptkategorien:

1. **Startseite**
2. **Themse**
3. **Kontakt**
4. **Rechtliches**

> Die Reihenfolge ist nicht fest definiert und kann je nach Layout, UX oder Priorisierung variieren.

Zusätzliche sinnvolle globale Elemente:
- Header (mit Navigation)
- Footer (mit zentralen rechtlichen Informationen)
- Globale rechtliche Hinweise (z. B. in jeder Fußzeile)
- Globale Suchleiste (optional)

---

## 2. Startseite

Die Startseite dient als zentrale Einstiegsseite und Übersicht über alle Kernfunktionen der Website.

### Mindestinhalte:

#### 2.1 Banner / Slider
- Rotierender Banner mit verschiedenen **Themse-Kategorien**
- Jede Banner-Szene enthält:
  - Kurztitel der Kategorie
  - Themenbeschreibung
  - **Link zur zugehörigen Themse-Kategorie**

#### 2.2 Argumente („Warum bei uns kaufen?“)
Beispiele:
- Schnell
- Günstig
- Professionell
- Personalisierte Anpassung
- Keine technischen Kenntnisse erforderlich  
(Argumente erweiterbar)

#### 2.3 „Wie es funktioniert“-Erklärung
- Auswahl eines Themse
- Personalisierung durch uns:
  - Kunde sendet Daten/Wünsche über das Kontaktformular
  - Anpassung erfolgt durch unser Team
- Alternative: Individuelle Website ohne Vorlage

#### 2.4 Rezensionen
- Kundenbewertungen
- Sterne-Bewertungen
- Optional: Filterbar nach Kategorie

#### 2.5 Rechtliches
- Kurze Hinweise
- Links auf die rechtlichen Unterseiten

---

## 3. Themse – Hauptseite

Die Themse-Hauptseite listet **alle Kategorien** und bietet Orientierung.

### Mindestinhalte:

#### 3.1 Suchfunktion
- Freitextsuche
- Filter nach Kategorien möglich  
  Beispiele:
  - Friseur
  - Café
  - Restaurant
  - Bauunternehmen  
  (weitere Kategorien möglich)

#### 3.2 Vorgestellte Kategorien
- Vorschau-Kacheln beliebter Themse-Bereiche
- Bild + Kurzbeschreibung + Link zur Kategorie

#### 3.3 Rechtliches
- Kurze Hinweise
- Link zu vollständigen rechtlichen Seiten

---

## 4. Themse-Kategorie (z. B. „Friseur“, „Restaurant“)

Diese Seite zeigt alle verfügbaren Themse innerhalb einer Kategorie.

### Mindestinhalte:

#### 4.1 Themse-Übersicht
- Mehrere Website-Themse mit:
  - Titel
  - Beschreibung
  - Preis
  - Vorschau-Bild
  - Details-Button (führt zur Themse-Detailseite)

#### 4.2 Rezensionen
- Bewertungen für Themse in dieser Kategorie
- Optional: Filter nach Thema

#### 4.3 Argumente („Warum dieses Themse wählen?“)
- Vorteile dieser Kategorie (z. B. optimiert für Restaurants, Fokus auf Buchung usw.)

#### 4.4 Häufige Fragen (FAQ)
- Typische Fragen und passende Antworten  
  Beispiele:
  - „Kann ich das Design anpassen lassen?“  
  - „Wie lange dauert die Umsetzung?“  
  - „Was kostet die Personalisierung?“

#### 4.5 „Kein passendes Themse gefunden?“
- Kontaktformular oder Link dorthin  
- Möglichkeit, eine individuelle Website erstellen zu lassen

---

## 5. Einzelnes Themse (Detailseite)

Seite für ein spezifisches Website-Template.

### Mindestinhalte:

#### 5.1 Interaktive Vorschau
- Live-Demo oder simulierte Vorschau
- Nutzer kann durch das Themse scrollen und navigieren

#### 5.2 Preis und Details
- Preisübersicht
- Beschreibung des Funktionsumfangs
- Technische Merkmale
- Ziel-Use-Cases

#### 5.3 Ablauf „Was muss ich tun?“
- Kontaktaufnahme
- Bereitstellung benötigter Daten:
  - Texte
  - Bilder
  - Öffnungszeiten
  - Farben/Branding-Wünsche
- Personalisierungsprozess

#### 5.4 Link zum Kontakt
- Button/CTA zum Kontaktformular

#### 5.5 Argumente
- Vorteile des ausgewählten Themse

#### 5.6 Rezensionen
- Bewertungen spezifisch zu diesem Themse

#### 5.7 Rechtliches
- Kurze Hinweise + Link zu vollständigem Rechtstext

---

## 6. Kontaktseite

Die Kontaktseite dient sowohl der Anfrage für Themse als auch der Übermittlung von personalisierten Daten.

### Mindestinhalte:

#### 6.1 Kontaktformular
- Name
- E-Mail
- Kategorie / Themse-Auswahl
- Nachricht / Anforderungen / Wünsche
- Datei-Upload (optional für Bilder, Logos)  

#### 6.2 Häufige Fragen (FAQ)
- Wiederholung relevanter Fragen (global oder themsebezogen)

#### 6.3 Rechtliches
- Datenschutz-Hinweis
- Einverständnis-Checkbox (DSGVO)
- Links zu Impressum & Datenschutz

---

## 7. Rechtliches (Hauptbereich)

Umfasst mindestens:

- Impressum
- Datenschutz
- AGB (falls vorhanden)
- Widerrufsbelehrung (optional)
- Cookie-Hinweise

Diese Unterseiten werden global im Footer verlinkt.

---

## 8. Erweiterbare Elemente (optional sinnvoll)

Folgende Inhalte können später ergänzt werden:

- Blog / News
- Preisrechner
- Angebots-Konfigurator
- Tutorials / Hilfe-Bereich
- Kundenportal (Datei-Upload, Projektstatus)
- Newsletter-Opt-In
- Statistiken (Verkaufszahlen, meist gewählte Themse)
- Mehrsprachigkeit

---

## 9. Technische Hinweise

- Alle Seiten müssen vollständige Navigation + Footer enthalten
- Keine toten Links (`href="#"`)
- Jede Kategorie- und Themse-Seite ist modular aufgebaut
- Einheitliche UI-Komponenten verwenden (Cards, Buttons, Banner)
- Dateistruktur (Empfehlung):


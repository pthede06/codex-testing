# Agentur-Website – Technisches Grundgerüst  
Modulare Website-Struktur für eine professionelle Webdesign-Agentur

Dieses Repository enthält die technische Basis der **Webdesign-Agentur-Homepage** (`AGENTUR_NAME`).  
Die Seite dient als Präsentationsplattform für das Geschäftsmodell: Erstellung einfacher, verständlicher Websites für Cafés und lokale Betriebe.  
Der Fokus liegt auf klar strukturiertem, gut dokumentiertem Code, der technisch wartbar bleibt und professionell wirkt.

Die README richtet sich an Entwickler und beschreibt Aufbau, Struktur und technische Leitlinien der Agentur-Website.

---

## 1. Zielsetzung der Website

Die Website ist **nicht** für Kunden, sondern stellt die **eigene Agentur** vor.  
Sie dient dazu:

- Leistungen für Cafés & lokale Businesses klar zu kommunizieren  
- das Geschäftsmodell verständlich zu präsentieren  
- Module, Preise & Prozessablauf übersichtlich darzustellen  
- ein professionelles technisches Fundament zu zeigen  
- Kontakt- und Angebotsanfragen zu ermöglichen  

Die Seite ist **mehrseitig und modular**, nicht als Onepager angelegt.

---

## 2. Technische Anforderungen

Die Agentur-Website folgt folgenden technischen Prinzipien:

- **modulare Seitenstruktur** (jede Unterseite ist separat aufgebaut)
- **klare, nachvollziehbare Codeorganisation**
- **HTML/CSS/JS ohne Frameworks**
- **mobile Optimierung**
- **voll funktionierende Navigation (keine toten Links)**
- **leicht erweiterbare Module (z. B. Preise, Portfolio, Team)**

Die Architektur muss repräsentieren, wie Kundenprojekte aufgebaut werden.

---

## 3. Seitenarchitektur

Die Website besteht aus mehreren klar getrennten Seiten:


Jede Seite ist semantisch korrekt aufgebaut und kann unabhängig erweitert werden.

---

## 4. Code-Struktur

```text
root/
├─ index.html
├─ leistungen.html
├─ portfolio.html
├─ prozess.html
├─ ueber-uns.html
├─ kontakt.html
├─ impressum.html
├─ datenschutz.html
├─ css/
│  └─ styles.css      → Haupt-CSS
├─ js/
│  └─ main.js         → Navigation, mobile Menülogik
└─ assets/
   ├─ img/
   └─ icons/
## 5. Verlinkungsrichtlinien (keine toten Links)

Die Navigation der Agentur-Website muss vollständig funktionieren.  
Folgende Regeln gelten verbindlich:

### ✔ Erlaubt:
- Links zu existierenden HTML-Seiten  
- Gültige externe Links  
- Interne Anker **nur**, wenn sie tatsächlich existieren  

### ✖ Nicht erlaubt:
- `href="#"`
- `href=""`
- Links zu nicht vorhandenen Dateien  
- Platzhalter ohne Ziel  

Diese Richtlinie ist zentral, da die Agentur-Website Professionalität demonstrieren soll.

---

## 6. Features der Agentur-Website

- Responsives Layout (Mobile-first)  
- Klare modulare Seitenstruktur  
- Mobile Navigation (Hamburger-Menü)  
- Leistungsdarstellung in flexiblen Komponenten  
- Prozessbeschreibung (Workflow der Agentur)  
- Portfolio-Ansicht (Bilder, Referenzen, Case Studies)  
- Kontaktformular (Frontend; Backend optional)  
- Konsistentes Designsystem (Farben, Abstände, Typografie)

---

## 7. Technischer Stack

- **HTML5** (semantisch korrekt)  
- **CSS3** mit Flexbox & Grid  
- **Vanilla JavaScript** (Navigation, UI-Interaktionen)  
- Keine Frameworks in der Basisversion  
- Optional erweiterbar mit Backend oder CMS

---

## 8. Weiterentwicklungsmöglichkeiten

- Dynamischer Preisrechner / Angebotsformular  
- Blog-/News- oder Case-Study-System  
- Automatisierte Build-Pipeline (z. B. minify, image optimization)  
- Templating oder Komponentenstruktur (z. B. via Include-Mechanismen)  
- Backend-Anbindung für Formulare oder CMS  
- SEO-Optimierungen  
- Dark-Mode-Unterstützung  
- Mehrsprachigkeit (DE/EN)

---


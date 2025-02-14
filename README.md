# **Dokumentation: Planung, Gestaltung und Programmierung der Landingpage**

Diese Dokumentation beschreibt den Prozess der Erstellung einer **Landingpage für ein Immobilienunternehmen** von Grund auf (from scratch) ohne die Verwendung von Frameworks oder Bibliotheken. Die Seite wurde mit **HTML5**, **CSS3** und **JavaScript** entwickelt und ist vollständig responsiv.

---

## **1. Planung**

### **1.1 Zielsetzung**
Die Landingpage soll:
- Potenzielle Kunden über die Dienstleistungen des Unternehmens informieren.
- Vertrauen durch Erfolgszahlen, Kundenbewertungen und professionelles Design aufbauen.
- Interessenten dazu animieren, Kontakt aufzunehmen oder Immobilienangebote zu erkunden.
- Eine benutzerfreundliche und visuell ansprechende Erfahrung bieten.

### **1.2 Zielgruppe**
- **Käufer**: Personen, die eine Immobilie kaufen möchten.
- **Verkäufer**: Personen, die eine Immobilie verkaufen möchten.
- **Investoren**: Personen, die in Immobilien investieren möchten.

### **1.3 Funktionale Anforderungen**
- **Navigation**: Einfache Navigation zwischen den Abschnitten der Seite.
- **Responsive Design**: Optimierte Darstellung auf allen Geräten (Desktop, Tablet, Mobile).
- **Interaktionen**: Animierte Statistiken, FAQs, Kundenbewertungen und ein Kontaktformular.
- **Visuelle Effekte**: Parallax-Effekt, Hover-Animationen und sanfte Scroll-Effekte.

### **1.4 Nicht-funktionale Anforderungen**
- **Performance**: Schnelle Ladezeiten durch optimierte Bilder und Code.
- **Barrierefreiheit**: Zugänglichkeit für alle Nutzer (z. B. durch semantisches HTML).
- **Cross-Browser-Kompatibilität**: Funktionieren auf allen gängigen Browsern (Chrome, Firefox, Safari, Edge).

---

## **2. Gestaltung**

### **2.1 Design-Prinzipien**
- **Farbpalette**: Naturgrün (#2E8B57) als Hauptfarbe, kombiniert mit Weiß und Grautönen für ein professionelles und vertrauenswürdiges Erscheinungsbild.
- **Typografie**: Klare, gut lesbare Schriftarten (Arial, sans-serif) für eine moderne und zugängliche Optik.
- **Bilder**: Hochwertige Bilder von Immobilien und Kundenbewertungen, um Vertrauen zu schaffen.
- **Leerzeichen**: Ausreichend Whitespace, um die Seite nicht zu überladen.

### **2.2 Struktur der Seite**
1. **Header**: Logo und Navigation.
2. **Hero-Section**: Einprägsamer Titel, Untertitel und Call-to-Action-Button.
3. **Über Uns**: Kurze Vorstellung des Unternehmens.
4. **Verkaufen-Section**: Informationen zum Verkaufsprozess.
5. **Immobilienangebote**: Liste von Immobilien mit Details.
6. **Erfolgszahlen**: Statistische Erfolge des Unternehmens.
7. **Parallax-Section**: Inspirierendes Zitat mit Parallax-Effekt.
8. **FAQs**: Häufig gestellte Fragen.
9. **Kundenbewertungen**: Scrollbare Kundenbewertungen.
10. **Social Media**: Links zu Social-Media-Profilen.
11. **Kontaktformular**: Formular für Anfragen.
12. **Footer**: Copyright-Informationen.

### **2.3 Wireframes**
- **Desktop**: Mehrspaltiges Layout mit großen Bildern und klaren Abschnitten.
- **Mobile**: Einspaltiges Layout mit reduzierten Elementen für bessere Lesbarkeit.

---

## **3. Programmierung**

### **3.1 Technologien**
- **HTML5**: Struktur der Seite.
- **CSS3**: Styling und Animationen.
- **JavaScript**: Interaktionen und dynamische Effekte.

### **3.2 HTML-Struktur**
- **Semantische Elemente**: `<header>`, `<section>`, `<footer>`, `<article>`, `<nav>`.
- **Formulare**: `<form>` für das Kontaktformular.
- **Bilder**: `<img>` mit `alt`-Attributen für Barrierefreiheit.

### **3.3 CSS-Stil**
- **Flexbox und Grid**: Für das Layout der Immobilienkarten und Statistiken.
- **Media Queries**: Für die Anpassung an verschiedene Bildschirmgrößen.
- **Animationen**: Hover-Effekte, sanfte Übergänge und Parallax-Effekte.
- **Blur-Effekt**: Überlagerung des Hero-Bildes mit einem weißen Blur.

### **3.4 JavaScript-Interaktionen**
- **Smooth Scroll**: Sanftes Scrollen zu Abschnitten bei Klick auf Navigationslinks.
- **Animierte Zahlen**: Statistische Zahlen werden beim Scrollen animiert.
- **FAQs**: Aufklappbare Antworten auf Fragen.
- **Kundenbewertungen**: Automatisches Scrollen der Bewertungen.
- **Kontaktformular**: Einfache Validierung und Bestätigungsnachricht.

### **3.5 Responsive Design**
- **Breakpoints**: Anpassungen für Bildschirme unter 768px (Mobile) und 1200px (Desktop).
- **Flexible Bilder**: Bilder passen sich der Bildschirmgröße an.
- **Hamburger-Menü**: Navigation wird auf mobilen Geräten kompakt dargestellt.

### **3.6 Barrierefreiheit**
- **ARIA-Labels**: Verbesserte Zugänglichkeit für Screenreader.
- **Kontrast**: Ausreichender Kontrast zwischen Text und Hintergrund.
- **Tastatur-Navigation**: Alle interaktiven Elemente sind per Tastatur bedienbar.

---

## **4. Testing**

### **4.1 Funktionale Tests**
- **Navigation**: Alle Links und Buttons funktionieren korrekt.
- **Formulare**: Das Kontaktformular validiert Eingaben und zeigt eine Bestätigungsnachricht an.
- **Animationen**: Alle Animationen (Zahlen, FAQs, Bewertungen) funktionieren wie erwartet.

### **4.2 Cross-Browser-Tests**
- Getestet auf: Chrome, Firefox, Safari, Edge.
- **Konsistenz**: Das Design und die Funktionalität sind auf allen Browsern konsistent.

### **4.3 Performance-Tests**
- **Ladezeiten**: Bilder wurden optimiert, um die Ladezeit zu minimieren.
- **Lighthouse-Score**: Hohe Bewertung in den Kategorien Performance, Barrierefreiheit und SEO.

---

## **5. Deployment**

### **5.1 Hosting**
- Die Seite wird auf einem **Webserver** gehostet (z. B. Apache, Nginx).
- **Domain**: `https://test.twisted-style.de/landingpage`.

### **5.2 SEO-Optimierung**
- **Meta-Tags**: Titel, Beschreibung und Keywords für Suchmaschinen.
- **Canonical-Tag**: Vermeidung von Duplicate Content.
- **Strukturierte Daten**: Verbesserte Sichtbarkeit in Suchmaschinenergebnissen.

---

## **6. Fazit**

Die Landingpage wurde **from scratch** entwickelt und erfüllt alle Anforderungen an Funktionalität, Design und Performance. Durch die Verwendung von modernen Webtechnologien und die Einhaltung von Best Practices bietet sie eine **benutzerfreundliche und ansprechende Erfahrung** für potenzielle Kunden.

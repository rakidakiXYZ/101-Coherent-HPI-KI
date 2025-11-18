# Tutorial: Dein KI-Assistent für durchdachte Entscheidungen

Herzlich willkommen! In diesem Tutorial lernst du, wie du die KI dazu bringst, **nicht sofort zu antworten**, sondern erst ihren Denkprozess zu erklären. Das führt zu besseren, durchdachteren Ergebnissen. Du musst kein KI-Experte sein – wir zeigen dir Schritt für Schritt, wie es funktioniert.

---

## Was ist ein Reflexions-Prompt?

Stell dir vor, du fragst einen Kollegen um Rat. Anstatt sofort eine Antwort zu geben, erklärt er dir erst:
- Welche Annahmen er trifft
- Wie er zu seiner Empfehlung kommt
- Welche Risiken er sieht
- Was seine Meinung ändern würde

Genau das macht ein **Reflexions-Prompt** mit der KI. Er zwingt sie, **erst zu denken, dann zu antworten**.

---

## Der Reflexions-Prompt

Hier ist der Prompt, den du am Ende deiner Frage hinzufügst:

```
Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**So einfach ist das!** Du stellst deine Frage und fügst diesen Satz am Ende hinzu.

---

## Warum ist das wichtig?

**Ohne Reflexions-Prompt:**
> Frage: "Sollen wir Faserlaser oder Festkörperlaser für die Automobilindustrie empfehlen?"
> 
> KI-Antwort: "Faserlaser, weil sie effizienter sind."

❌ **Problem:** Oberflächlich, keine Begründung, keine Berücksichtigung spezifischer Anforderungen.

**Mit Reflexions-Prompt:**
> Frage: "Sollen wir Faserlaser oder Festkörperlaser für die Automobilindustrie empfehlen?
> 
> Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit einer Einschätzung deines Vertrauensniveaus."

✅ **Ergebnis:** Die KI erklärt ihre Annahmen (z.B. Anwendungsfall, Materialien), ihren Denkprozess, Risiken (z.B. Kosten, Wartung) und gibt eine fundierte Empfehlung mit Vertrauensniveau.

---

## Wann solltest du den Reflexions-Prompt nutzen?

✅ **Nutze ihn, wenn:**
- Die Entscheidung **Budget, Ressourcen oder Reputation** betrifft
- Du eine **Management-Vorlage** oder **Entscheidungsgrundlage** vorbereitest
- Du **mehrere Optionen** abwägen musst
- Du **Risiken** identifizieren und minimieren willst
- Du **Transparenz** und **Nachvollziehbarkeit** brauchst
- Die Antwort **compliance-relevant** ist (Datenschutz, Sicherheit, regulatorische Anforderungen)
- Es um **Kundenberatung** oder **Lösungsdesign** geht
- **Investitionsentscheidungen** anstehen

❌ **Nutze ihn NICHT, wenn:**
- Du eine schnelle, einfache Antwort brauchst (z.B. "Was bedeutet Photonik?")
- Du kreative Texte ohne strategische Komponente benötigst
- Die Aufgabe rein operativ ist (z.B. "Formatiere diese Tabelle")

---

## Wie funktioniert der Reflexions-Prompt?

Der Prompt besteht aus **5 Elementen**, die nacheinander abgefragt werden:

| **Element** | **Was es bewirkt** | **Nutzen für dich** |
|-------------|-------------------|---------------------|
| **Annahmen** | KI legt zugrunde liegende Annahmen offen | Du erkennst, ob die KI realistische oder falsche Annahmen trifft |
| **Denkprozess** | KI erklärt ihre Überlegungen Schritt für Schritt | Du verstehst die Logik und kannst sie nachvollziehen oder korrigieren |
| **Risiken** | KI identifiziert mögliche Probleme | Du erkennst blinde Flecken und kannst präventiv gegensteuern |
| **Was die Empfehlung ändern würde** | KI nennt Faktoren, die ihre Meinung kippen würden | Du verstehst Sensitivitäten und kannst Szenarien durchspielen |
| **Empfehlung + Vertrauensniveau** | KI gibt klare Handlungsempfehlung mit Unsicherheitsangabe | Du weißt, wie belastbar die Empfehlung ist (z.B. "85 % sicher" vs. "50 % sicher") |

---

## Wie nutzt du den Reflexions-Prompt?

**Standard-Struktur:**

```
[Deine konkrete Frage oder Aufgabe]

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

💡 **Tipp:** Stelle deine Frage möglichst konkret und kontextreich. Gib der KI Informationen über:
- Zielmarkt (Industrial, Communications, Electronics, Instrumentation)
- Budget-Rahmen
- Zeitliche Anforderungen
- Technische Anforderungen
- Compliance-Anforderungen

---

## Praxisbeispiele: 12 Rollen bei Coherent

Hier sind zwölf Beispiele, wie verschiedene Rollen bei Coherent den Reflexions-Prompt nutzen können.

### 1. HR Talent Acquisition Specialist – Recruiting-Strategie

**Deine Anfrage:**

```
Wir möchten unsere Recruiting-Strategie für Photonics Engineers optimieren. 
Zwei Ansätze:
A) Fokus auf Universitäten und Forschungseinrichtungen (Hochschul-Recruiting)
B) Fokus auf Abwerbung von Wettbewerbern (Active Sourcing)

Welchen Ansatz empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Arbeitsmarkt für Photonics Engineers ist eng, Gehaltsniveau, Standorte
- **Denkprozess:** Verfügbarkeit, Kosten, Time-to-Hire, Qualität der Kandidaten
- **Risiken:** Hochschul-Recruiting = lange Einarbeitungszeit; Active Sourcing = höhere Gehälter
- **Was die Empfehlung ändern würde:** Budget, Dringlichkeit, Standort
- **Empfehlung:** Mix aus beiden mit Schwerpunkt auf Hochschul-Recruiting
- **Vertrauensniveau:** 75 %

---

### 2. Marketing Content Specialist – Kampagnenstrategie

**Deine Anfrage:**

```
Wir planen eine Marketing-Kampagne für Lasersysteme in der Halbleiterfertigung. 
Budget: 50.000 €. Zwei Strategien:
A) Fokus auf Fachmedien und Whitepapers (Thought Leadership)
B) Fokus auf Messen und Events (Direktkontakt)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Zielgruppe sind Entscheider in Halbleiter-Unternehmen, Budget ist begrenzt
- **Denkprozess:** Reichweite, Kosten pro Lead, Conversion-Rate, Markenbildung
- **Risiken:** Thought Leadership = langfristig; Messen = teuer, kurze Wirkung
- **Was die Empfehlung ändern würde:** Zeitrahmen, Lead-Ziele, bestehende Kontakte
- **Empfehlung:** 60/40-Mix (60 % Thought Leadership, 40 % Messen)
- **Vertrauensniveau:** 70 %

---

### 3. Sales Account Manager – Produktempfehlung

**Deine Anfrage:**

```
Ein Kunde aus der Automobilindustrie fragt nach Lasersystemen für die Schweißtechnik. 
Zwei Optionen:
A) Faserlaser (höhere Effizienz, höherer Preis)
B) Festkörperlaser (bewährte Technologie, günstiger)

Welche Lösung empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Kunde hat hohe Produktionsvolumen, Budget ist vorhanden, Energiekosten relevant
- **Denkprozess:** TCO, Energieeffizienz, Wartung, Produktionsgeschwindigkeit
- **Risiken:** Faserlaser = höhere Initialkosten; Festkörperlaser = höhere Betriebskosten
- **Was die Empfehlung ändern würde:** Budget, Produktionsvolumen, Energiepreise
- **Empfehlung:** Faserlaser wegen langfristig niedrigerer TCO
- **Vertrauensniveau:** 80 %

---

### 4. Executive Assistant – Strategische Entscheidung

**Deine Anfrage:**

```
Das Management überlegt, ob wir in den Markt für medizinische Lasersysteme einsteigen sollen. 
Zwei Optionen:
A) Fokus auf bestehende Märkte (Industrial, Communications) ausbauen
B) Diversifikation in medizinische Anwendungen

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Medizinmarkt hat hohe Eintrittsbarrieren, regulatorische Anforderungen
- **Denkprozess:** Marktpotenzial, Wettbewerb, erforderliche Investitionen, Risiken
- **Risiken:** Diversifikation = hohe Kosten, lange Time-to-Market; Fokus = begrenzte Wachstumschancen
- **Was die Empfehlung ändern würde:** Verfügbare Ressourcen, strategische Prioritäten
- **Empfehlung:** Fokus auf bestehende Märkte mit selektiven Pilotprojekten in Medizin
- **Vertrauensniveau:** 65 %

---

### 5. Customer Success Manager – Kundenzufriedenheit

**Deine Anfrage:**

```
Ein wichtiger Kunde ist unzufrieden mit der Reaktionszeit unseres Supports. 
Zwei Verbesserungsansätze:
A) Dedizierter Account Manager für diesen Kunden (Kosten: 80.000 €/Jahr)
B) Verbesserung des allgemeinen Support-Prozesses (Kosten: 30.000 € einmalig)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Kunde ist strategisch wichtig, Umsatz >500.000 €/Jahr, Churn-Risiko hoch
- **Denkprozess:** Kundenwert, Churn-Kosten, Skalierbarkeit, andere Kunden
- **Risiken:** Dedizierter Manager = teuer, nicht skalierbar; Prozessverbesserung = wirkt verzögert
- **Was die Empfehlung ändern würde:** Kundenwert, Anzahl unzufriedener Kunden
- **Empfehlung:** Option A kurzfristig, Option B parallel für langfristige Lösung
- **Vertrauensniveau:** 75 %

---

### 6. Finance Controller – Investitionsentscheidung

**Deine Anfrage:**

```
Wir überlegen, in neue Produktionsanlagen für optische Komponenten zu investieren. 
Zwei Optionen:
A) Kauf neuer Anlagen (Kosten: 2 Mio. €, Abschreibung 10 Jahre)
B) Outsourcing an Zulieferer (Kosten: 300.000 €/Jahr)

Was ist finanziell sinnvoller?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Produktionsvolumen, Qualitätsanforderungen, Verfügbarkeit von Zulieferern
- **Denkprozess:** NPV, ROI, Flexibilität, Qualitätskontrolle, strategische Unabhängigkeit
- **Risiken:** Kauf = hohe Initialkosten, Auslastungsrisiko; Outsourcing = Qualitätsrisiko, Abhängigkeit
- **Was die Empfehlung ändern würde:** Produktionsvolumen, Qualitätsanforderungen, strategische Prioritäten
- **Empfehlung:** Kauf bei Volumen >X Einheiten/Jahr, sonst Outsourcing
- **Vertrauensniveau:** 70 %

---

### 7. Training & Development Coordinator – Schulungsprogramm

**Deine Anfrage:**

```
Wir möchten ein Schulungsprogramm für Laser-Sicherheit entwickeln. 
Zwei Ansätze:
A) Externe Schulungsanbieter (Kosten: 50.000 €, professionell)
B) Interne Schulungen durch erfahrene Mitarbeitende (Kosten: 20.000 €, individuell)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Laser-Sicherheit ist compliance-relevant, Mitarbeitende haben unterschiedliche Vorkenntnisse
- **Denkprozess:** Qualität, Kosten, Compliance-Anforderungen, Skalierbarkeit
- **Risiken:** Extern = teuer, generisch; Intern = Qualitätsschwankungen, Zeitaufwand
- **Was die Empfehlung ändern würde:** Budget, Anzahl Mitarbeitende, Compliance-Druck
- **Empfehlung:** Extern für Grundlagen, intern für spezifische Anwendungen
- **Vertrauensniveau:** 75 %

---

### 8. Compliance Officer – Regulatorische Anforderungen

**Deine Anfrage:**

```
Wir exportieren Lasersysteme in verschiedene Länder. 
Zwei Ansätze für Compliance-Management:
A) Externe Compliance-Beratung (Kosten: 100.000 €/Jahr)
B) Aufbau internes Compliance-Team (Kosten: 150.000 €/Jahr)

Was ist langfristig sinnvoller?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Export-Volumen steigt, regulatorische Anforderungen werden komplexer
- **Denkprozess:** Kosten, Expertise, Flexibilität, strategische Kontrolle
- **Risiken:** Extern = Abhängigkeit, Wissensabfluss; Intern = höhere Kosten, Rekrutierung schwierig
- **Was die Empfehlung ändern würde:** Export-Volumen, Anzahl Zielmärkte, Komplexität
- **Empfehlung:** Start mit extern, Aufbau intern ab bestimmtem Export-Volumen
- **Vertrauensniveau:** 70 %

---

### 9. Photonics Application Engineer – Technologieauswahl

**Deine Anfrage:**

```
Ein Kunde fragt nach Lasersystemen für die Mikrobearbeitung. 
Zwei Technologien:
A) Pikosekunden-Laser (höchste Präzision, teuer)
B) Nanosekunden-Laser (gute Präzision, günstiger)

Welche Technologie empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Anwendung erfordert hohe Präzision, Kunde hat Budget, Materialien sind empfindlich
- **Denkprozess:** Präzisionsanforderungen, Materialien, Kosten, Produktionsgeschwindigkeit
- **Risiken:** Pikosekunden = Überqualifikation, teuer; Nanosekunden = möglicherweise unzureichend
- **Was die Empfehlung ändern würde:** Materialtyp, Präzisionsanforderungen, Budget
- **Empfehlung:** Pikosekunden für empfindliche Materialien, Nanosekunden für robuste
- **Vertrauensniveau:** 85 %

---

### 10. R&D Documentation Specialist – Forschungsprojekt

**Deine Anfrage:**

```
Wir planen ein Forschungsprojekt zu neuen optischen Beschichtungen. 
Zwei Ansätze:
A) Interne Forschung (Kosten: 500.000 €, volle Kontrolle)
B) Kooperation mit Universität (Kosten: 200.000 €, geteilte IP)

Was empfehlen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Technologie ist strategisch wichtig, Zeitrahmen ist flexibel
- **Denkprozess:** Kosten, IP-Kontrolle, Expertise, Time-to-Market
- **Risiken:** Intern = teuer, Expertise fehlt; Kooperation = IP-Teilung, langsamere Entscheidungen
- **Was die Empfehlung ändern würde:** Strategische Bedeutung, Budget, Zeitdruck
- **Empfehlung:** Kooperation für Grundlagenforschung, intern für Produktentwicklung
- **Vertrauensniveau:** 75 %

---

### 11. Quality Assurance Engineer – Qualitätsprozess

**Deine Anfrage:**

```
Wir möchten unsere Qualitätsprüfung für optische Komponenten verbessern. 
Zwei Ansätze:
A) Automatisierte Prüfsysteme (Kosten: 300.000 €, schnell)
B) Erweiterte manuelle Prüfung (Kosten: 100.000 €/Jahr, flexibel)

Was ist langfristig besser?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Produktionsvolumen steigt, Qualitätsanforderungen sind hoch
- **Denkprozess:** Kosten, Geschwindigkeit, Genauigkeit, Skalierbarkeit
- **Risiken:** Automatisiert = hohe Initialkosten, Inflexibilität; Manuell = langsamer, fehleranfällig
- **Was die Empfehlung ändern würde:** Produktionsvolumen, Komplexität der Komponenten
- **Empfehlung:** Automatisiert ab Volumen >X Einheiten/Jahr
- **Vertrauensniveau:** 80 %

---

### 12. Purchasing Specialist – Lieferantenauswahl

**Deine Anfrage:**

```
Wir suchen einen Lieferanten für optische Rohmaterialien. 
Zwei Finalisten:
A) Etablierter Anbieter (höhere Preise, zuverlässig)
B) Neuer Anbieter (20 % günstiger, weniger Referenzen)

Welchen Partner wählen wir?

Bevor du mir deine Antwort gibst, erkläre mir bitte zuerst deine Annahmen, 
deinen vollständigen Denkprozess, mögliche Risiken und was deine Empfehlung 
ändern würde. Gib mir danach deine abschließende Empfehlung zusammen mit 
einer Einschätzung deines Vertrauensniveaus.
```

**Erwartete KI-Ausgabe:**
- **Annahmen:** Materialqualität ist kritisch, Lieferketten-Stabilität wichtig
- **Denkprozess:** Kosten, Qualität, Zuverlässigkeit, Risiko
- **Risiken:** Etabliert = höhere Kosten; Neu = Qualitätsrisiko, Lieferrisiko
- **Was die Empfehlung ändern würde:** Volumen, Kritikalität der Materialien, Budget-Druck
- **Empfehlung:** Dual-Sourcing (80 % etabliert, 20 % neu für Test)
- **Vertrauensniveau:** 75 %

---

## 🔒 Wichtige Sicherheitshinweise für Coherent

Die Nutzung des Reflexions-Prompts ist sehr hilfreich, aber die Sicherheit unserer Daten hat oberste Priorität.

### Datenschutz & Compliance

Gib **niemals** vertrauliche oder geschützte Informationen in ein KI-Tool ein. Dazu gehören:

-   **Proprietäre Produktdaten:** Keine Patentinformationen, Forschungsergebnisse oder unveröffentlichte technische Spezifikationen
-   **Kundendaten:** Keine Namen von Kunden, Kontaktdaten, Projektinformationen oder Angebotsdetails
-   **Fertigungsprozesse:** Keine Details zu Herstellungsverfahren oder Materialzusammensetzungen
-   **Mitarbeiterdaten:** Keine persönlichen Informationen über Kolleginnen und Kollegen
-   **Finanzdaten:** Keine echten Budgets, Gehälter, Umsatzzahlen oder Kostenstrukturen
-   **Strategische Informationen:** Keine Geschäftsstrategien, Marktanalysen oder Wettbewerbsinformationen

➡️ **Regel:** Verwende für Beispiele immer **anonymisierte oder fiktive Daten**.

### ✅ Qualitätssicherung: Der Mensch bleibt verantwortlich

Der Reflexions-Prompt liefert durchdachte Analysen, aber du triffst die finalen Entscheidungen.

> **Das Human-in-the-Loop-Prinzip:** Die KI ist ein Werkzeug zur Unterstützung, kein Ersatz für deine Expertise. Prüfe alle Empfehlungen kritisch, ergänze dein Fachwissen und verifiziere wichtige Fakten.

---

## Tipps für den Alltag

### 1. Gib der KI Kontext

Je mehr Informationen du gibst (Zielmarkt, Budget, Anforderungen), desto besser die Analyse.

### 2. Nutze die Ausgabe als Diskussionsbasis

Überarbeite die KI-Empfehlung mit deinem Fachwissen und deiner Erfahrung.

### 3. Dokumentiere Annahmen

Halte fest, welche Annahmen du übernimmst oder änderst – wichtig für Kundendokumentation.

### 4. Hole Feedback ein

Teile die Analyse mit Kollegen zur Validierung, besonders bei komplexen Entscheidungen.

### 5. Prüfe das Vertrauensniveau

Wenn die KI nur 50 % Vertrauen hat, brauchst du mehr Informationen oder Expertenrat.

### 6. Verwende neutrale Begriffe

Nutze "Sprachmodell" oder "KI-Assistent" statt Produktnamen.

---

## Zusammenfassung: Die goldenen Regeln für Coherent

1.  **Strukturierte Prompts nutzen** – Verwende den Reflexions-Prompt für wichtige Entscheidungen.
2.  **Quellen einfordern** – Prüfe die Annahmen der KI und ergänze echte Daten.
3.  **Kreativität bewusst steuern** – Nutze niedrige Kreativitätseinstellungen für faktenbasierte Analysen.
4.  **Perspektiven wechseln** – Lass die KI verschiedene Optionen aufzeigen und bewerten.
5.  **Neutralität wahren** – Hinterfrage, ob die KI bestimmte Lösungen ohne Grund bevorzugt.
6.  **Menschliche Validierung ist Pflicht** – Jede Empfehlung muss von einem Menschen geprüft und freigegeben werden.
7.  **Datenschutz geht vor** – Gib **niemals** proprietäre Daten, Kundenprojekte oder NDA-Informationen ein.
8.  **Compliance beachten** – Halte dich immer an die gesetzlichen und unternehmensinternen Richtlinien.
9.  **Wissen teilen** – Dokumentiere erfolgreiche Anwendungsfälle und teile sie mit deinem Team.

---

**@ 2025 - HPI KI Workshops | Tutorials**


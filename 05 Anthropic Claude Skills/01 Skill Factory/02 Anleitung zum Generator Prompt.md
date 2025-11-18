# Claude Skills Factory Generator – Anleitung für Anfänger

## Was ist das überhaupt?

Stell dir vor, du möchtest Claude beibringen, **spezialisierte Aufgaben** für dein Unternehmen zu erledigen – zum Beispiel:
- Finanzberichte automatisch erstellen
- Kundenpräsentationen im Corporate Design generieren
- Daten aus Excel-Tabellen analysieren und visualisieren

Der **Skills Factory Generator** ist wie eine **Fabrik für maßgeschneiderte Claude-Fähigkeiten** (sogenannte "Skills"). Du gibst an, was du brauchst, und der Generator erstellt komplette, sofort einsetzbare Pakete, die Claude neue Spezialwissen verleihen.

---

## 🎯 Was macht dieser Prompt genau?

Der Prompt ist eine **detaillierte Bauanleitung** für Claude, um automatisch professionelle Skills zu erstellen. Er funktioniert wie ein **intelligenter Assistent**, der:

1. **Deine Geschäftsanforderungen versteht** (z.B. "Ich arbeite in der Finanzberatung")
2. **Passende Skills entwirft** (z.B. "Finanzanalyse-Rechner", "Investitionsbericht-Generator")
3. **Vollständige Pakete erstellt**, die sofort funktionieren

---

## 📦 Was bekommst du am Ende?

Für jeden Skill erhältst du ein **komplettes Paket** mit:

### 1. **SKILL.md** – Die Bedienungsanleitung
Eine Datei, die beschreibt:
- Was der Skill kann
- Wie man ihn benutzt
- Beispiele für typische Anwendungsfälle
- Grenzen und Best Practices

**Analogie:** Wie eine Gebrauchsanweisung für ein neues Werkzeug.

### 2. **Python-Skripte** (optional)
Programmcode für komplexe Berechnungen oder Datenverarbeitung.

**Wann werden Skripte erstellt?**
- Wenn präzise Berechnungen nötig sind (z.B. Finanzanalysen)
- Wenn Dateien umgewandelt werden müssen (z.B. CSV zu PowerPoint)
- Wenn externe Dienste eingebunden werden

**Wann NICHT?**
- Für einfache Textaufgaben (z.B. E-Mail-Vorlagen schreiben)
- Für kreative Inhalte (z.B. Marketingtexte)

### 3. **Testdaten** (optional)
Beispieldateien (CSV, JSON, Excel), mit denen du den Skill sofort ausprobieren kannst.

**Beispiel:** Ein "Umsatzanalyse-Skill" könnte eine Beispiel-CSV mit Verkaufsdaten enthalten.

### 4. **sample_prompt.md** – Fertige Beispiel-Prompts
Sofort kopierbare Prompts, die du einfach in Claude einfügen kannst.

**Beispiel:**
```
"Analysiere bitte die Datei 'verkaufsdaten.csv' und erstelle einen 
Monatsbericht mit den Top 5 Produkten und Umsatztrend."
```

### 5. **ZIP-Datei** – Für einfaches Importieren
Eine komprimierte Datei, die du direkt in Claude.ai hochladen kannst, um den Skill zu aktivieren.

---

## 🚀 Wie benutzt du den Generator?

### Schritt 1: Bereite deine Informationen vor

Beantworte diese Fragen:

**1. Was ist dein Geschäftsbereich?**
- Beispiel: "Ich arbeite im Marketing bei Coherent Corp."

**2. Was sind deine konkreten Anwendungsfälle?**
- Beispiel: 
  - "Produktbeschreibungen erstellen"
  - "Social-Media-Posts generieren"
  - "Kundenanfragen beantworten"

**3. Wie viele Skills brauchst du?**
- Empfehlung für Anfänger: 3-5 Skills

**4. Sollen die Skills sich überschneiden?**
- **"mutually_exclusive"** = Jeder Skill macht etwas völlig anderes
- **"overlapping"** = Skills können sich ergänzen und überlappen

**5. Wie komplex sollen die Skills sein?**
- **"beginner"** = Einfach, für Einsteiger
- **"intermediate"** = Mittel, etwas fortgeschritten
- **"advanced"** = Komplex, für Experten

**6. Wie viel Programmierung soll enthalten sein?**
- **"minimal"** = Fast keine Python-Skripte
- **"balanced"** = Einige Skripte für Berechnungen
- **"extensive"** = Viele Skripte für komplexe Aufgaben

---

### Schritt 2: Füttere den Generator

Gib Claude deine Antworten in diesem Format:

```markdown
BUSINESS_TYPE: Ich arbeite im Marketing bei Coherent Corp.

BUSINESS_CONTEXT: Wir erstellen Inhalte für Photonik-Produkte und 
technische Zielgruppen.

USE_CASES:
- Produktbeschreibungen für Laser-Systeme
- LinkedIn-Posts für Thought Leadership
- Kundenanfragen zu technischen Spezifikationen

NUMBER_OF_SKILLS: 3

OVERLAP_PREFERENCE: mutually_exclusive

COMPLEXITY_LEVEL: beginner

PYTHON_PREFERENCE: minimal
```

---

### Schritt 3: Erhalte deine Skills

Claude erstellt jetzt für jeden Use Case einen kompletten Skill mit:
- ✅ Detaillierter Dokumentation
- ✅ Beispiel-Prompts
- ✅ (Optional) Python-Skripten
- ✅ (Optional) Testdaten
- ✅ ZIP-Datei zum Importieren

---

## 💡 Praktisches Beispiel

### Deine Eingabe:
```
BUSINESS_TYPE: HR-Manager bei Coherent Corp.
USE_CASES:
- Stellenausschreibungen schreiben
- Onboarding-Dokumente erstellen
- Interview-Fragen vorbereiten
NUMBER_OF_SKILLS: 3
OVERLAP_PREFERENCE: mutually_exclusive
COMPLEXITY_LEVEL: beginner
PYTHON_PREFERENCE: minimal
```

### Was du bekommst:

**Skill 1: "job-posting-writer"**
- Erstellt Stellenausschreibungen im Coherent-Stil
- Berücksichtigt Brand Voice und Tonalität
- Beispiele für verschiedene Positionen

**Skill 2: "onboarding-doc-generator"**
- Generiert Onboarding-Checklisten
- Erstellt Willkommens-E-Mails
- Anpassbar an verschiedene Abteilungen

**Skill 3: "interview-question-builder"**
- Erstellt strukturierte Interview-Leitfäden
- Berücksichtigt Jobanforderungen
- Inkludiert Bewertungskriterien

---

## ✅ Vorteile dieses Systems

1. **Zeitersparnis:** Statt jeden Prompt neu zu formulieren, hast du vorgefertigte Skills
2. **Konsistenz:** Skills folgen immer den gleichen Qualitätsstandards
3. **Wiederverwendbarkeit:** Einmal erstellt, immer wieder nutzbar
4. **Professionell:** Jeder Skill ist vollständig dokumentiert
5. **Flexibel:** Anpassbar an deine spezifischen Bedürfnisse

---

## ⚠️ Was du wissen solltest

### Limitierungen:
- Skills sind **nicht magisch** – sie machen Claude nicht allwissend
- Du musst trotzdem **klare Anweisungen** geben
- **Qualitätskontrolle** bleibt deine Aufgabe (Human-in-the-Loop!)

### Datenschutz:
- Füge **keine vertraulichen Coherent-Daten** in die Skills ein
- Nutze **fiktive Beispiele** für Testdaten
- Beachte die **Coherent-Compliance-Richtlinien**

---

## 🎓 Für wen ist das geeignet?

### ✅ Perfekt für:
- **HR & Marketing:** Automatisierung von Texterstellung
- **Sales:** Angebotserstellung und Kundenkommunikation
- **Administration:** Dokumentenerstellung und -formatierung
- **Engineering:** Technische Dokumentation (mit Python-Skills)

### ⚠️ Weniger geeignet für:
- Aufgaben, die **hochspezialisiertes Fachwissen** erfordern
- Prozesse mit **strikten rechtlichen Vorgaben** (ohne Review)
- **Echtzeit-Entscheidungen** (z.B. Produktionssteuerung)

---

## 🚦 Schnellstart für Eilige

**In 3 Schritten zu deinem ersten Skill:**

1. **Definiere:** "Ich brauche einen Skill, der mir hilft, [konkrete Aufgabe] zu erledigen."
2. **Füttere:** Gib dem Generator deine Infos (siehe Beispiel oben)
3. **Nutze:** Importiere den ZIP-File in Claude.ai und probiere die Beispiel-Prompts aus

---

## 📚 Weiterführende Tipps

### Skill-Pflege:
- **Teste regelmäßig:** Prüfe, ob die Skills noch deinen Anforderungen entsprechen
- **Aktualisiere:** Passe Skills an neue Prozesse oder Richtlinien an
- **Teile:** Erfolgreiche Skills mit Kollegen teilen (nach Freigabe!)

### Kombination von Skills:
Skills können **gestapelt** werden. Beispiel:
1. **Skill A:** Erstellt Produktbeschreibung
2. **Skill B:** Formatiert als LinkedIn-Post
3. **Skill C:** Übersetzt in mehrere Sprachen

---

## Zusammenfassung: Was ist der Skills Factory Generator?

Der **Claude Skills Factory Generator** ist ein **intelligentes Template**, das Claude beibringt, wie man **maßgeschneiderte Fähigkeiten (Skills)** für deine spezifischen Geschäftsanforderungen erstellt. 

**Metapher:** Stell dir vor, du hast einen **Werkzeugkasten-Baumeister**, der genau die Werkzeuge anfertigt, die du für deine tägliche Arbeit brauchst – mit Bedienungsanleitung, Beispielen und allem, was du zum sofortigen Loslegen benötigst.

**Kernnutzen:**
- ✅ Spart Zeit bei wiederkehrenden Aufgaben
- ✅ Sorgt für konsistente Qualität
- ✅ Macht KI-Nutzung strukturierter und effizienter
- ✅ Keine Programmierkenntnisse erforderlich (bei "minimal"-Einstellung)

---



---

**@ 2025 - Coherent Corp. | KI-Enablement**

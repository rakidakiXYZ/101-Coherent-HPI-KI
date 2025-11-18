# 🤖 Anleitung: PowerPoint-Skill für Coherent mit Claude erstellen

## 📚 Für wen ist diese Anleitung?

Diese Anleitung zeigt dir, wie du **gemeinsam mit Claude** einen Custom Skill erstellst. Du gibst Claude Schritt für Schritt Anweisungen, und Claude erstellt die Dateien für dich.

**Ziel**: Am Ende hast du eine **ZIP-Datei** mit einem funktionsfähigen PowerPoint-Generator-Skill für Coherent.

---

## ⏱️ Zeitaufwand

- **Gesamt**: ca. 30-45 Minuten
- **Vorbereitung** (Dateien hochladen): 5 Minuten
- **Interaktive Skill-Erstellung mit Claude**: 20-30 Minuten
- **Download & Test**: 5 Minuten

---

## 🎯 Was du brauchst

### Dateien vorbereiten

Bevor du startest, sammle diese Dateien:

1. ✅ **Coherent-Logo** (z.B. `logo-Coherent_800x300.png`)
2. ✅ **Corporate Identity Dokument** (z.B. `Coherent_Corporate_Identity.md`)
3. ✅ **Sprache & Tonalität Dokument** (z.B. `Coherent_Sprache_Tonalitaet.md`)
4. ⭕ **Optional**: Beispielbilder (z.B. `solutions-*.webp`)

---

## 🚀 Schritt-für-Schritt-Anleitung

### 📍 Schritt 1: Neues Claude-Projekt erstellen (2 Minuten)

**Warum?** Skills werden in Projekten gespeichert. So bleiben alle Dateien organisiert.

1. **Öffne** claude.ai
2. **Klicke** auf "Projects" (linke Seitenleiste)
3. **Klicke** auf "+ New Project"
4. **Gib** einen Namen ein:
   ```
   Name: Coherent PowerPoint Skill Creator
   ```
5. **Klicke** auf "Create Project"

✅ **Ergebnis**: Du bist jetzt in einem neuen, leeren Projekt.

---

### 📍 Schritt 2: Dateien hochladen (3 Minuten)

**Warum?** Claude braucht die Brand Guidelines und das Logo, um den Skill zu erstellen.

1. **Klicke** auf das **Büroklammer-Symbol** (📎) im Chat
2. **Wähle** "Upload from Computer"
3. **Lade hoch**:
   - `logo-Coherent_800x300.png`
   - `Coherent_Corporate_Identity.md`
   - `Coherent_Sprache_Tonalitaet.md`
   - Optional: Beispielbilder (`solutions-*.webp`)

✅ **Ergebnis**: Die Dateien erscheinen im Chat-Eingabefeld.

---

### 📍 Schritt 3: Skill-Erstellung starten (1 Minute)

**Jetzt geht's los!** Kopiere diesen Prompt und füge ihn in Claude ein:

```
Ich möchte einen Custom Skill für Claude erstellen, der PowerPoint-Präsentationen im Coherent Corporate Design generiert.

Ziel: Marketing-Mitarbeiter bei Coherent sollen einfach sagen können "Erstelle mir eine Präsentation über [Thema]" und Claude erstellt dann automatisch eine professionelle PowerPoint-Datei mit:
- Coherent-Logo (korrekt platziert)
- Neptune Blue (#2E5D9D) als Hauptfarbe
- Brand Guidelines (aus den hochgeladenen Dokumenten)
- Verschiedenen Folientypen (Titel, Content, Charts, etc.)
- Der Tagline "INNOVATIONS THAT RESONATE"

Bitte erstelle diesen Skill Schritt für Schritt mit mir zusammen. Beginne mit der Erklärung, welche Dateien der Skill braucht.
```

✅ **Was passiert**: Claude erklärt dir die Skill-Struktur und beginnt mit der Planung.

---

### 📍 Schritt 4: Skill-Struktur bestätigen (2 Minuten)

Claude wird dir eine **Ordnerstruktur** vorschlagen, die ungefähr so aussieht:

```
coherent-powerpoint-generator/
├── SKILL.md                  (Hauptdatei)
├── assets/                    (Logo, CSS, Bilder)
├── references/                (Brand Guidelines)
└── scripts/                   (Hilfsskripte)
```

**Deine Antwort**: Bestätige einfach mit:

```
Ja, diese Struktur sieht gut aus. Bitte erstelle jetzt die SKILL.md Datei.
```

✅ **Was passiert**: Claude erstellt die erste Datei.

---

### 📍 Schritt 5: SKILL.md erstellen lassen (5 Minuten)

Claude wird jetzt die **SKILL.md** erstellen. Das ist die Hauptdatei mit allen Anweisungen für den Skill.

**Was du tust**: Warte, bis Claude fertig ist. Die Datei wird automatisch erstellt.

**Wenn du Anpassungen möchtest**, sage z.B.:

```
Die SKILL.md sieht gut aus. Kannst du bitte noch einen Abschnitt hinzufügen, der erklärt, wie man verschiedene Akzentfarben für die drei Geschäftsbereiche (Networking, Materials, Lasers) verwendet?
```

✅ **Ergebnis**: Die SKILL.md ist fertig und enthält alle Anweisungen.

---

### 📍 Schritt 6: Assets hinzufügen lassen (5 Minuten)

**Jetzt kopiert Claude die hochgeladenen Dateien in den richtigen Ordner.**

**Dein Prompt**:

```
Bitte kopiere jetzt:
1. Das Coherent-Logo in den assets/ Ordner
2. Die Brand Guidelines in den references/ Ordner
3. Die Beispielbilder (falls vorhanden) in den assets/ Ordner

Erstelle außerdem eine CSS-Datei (coherent-styles.css) mit dem kompletten Coherent Design System (Farben, Typografie, Layout).
```

✅ **Was passiert**: Claude erstellt die CSS-Datei und organisiert alle Assets.

---

### 📍 Schritt 7: Zusätzliche Dokumentation erstellen (10 Minuten)

**Gute Skills brauchen Dokumentation!** Lass Claude hilfreiche Anleitungen erstellen.

**Dein Prompt**:

```
Erstelle bitte noch folgende Dateien:

1. README.md - Eine vollständige Anleitung für Marketing-Mitarbeiter
   - Wie installiert man den Skill?
   - Wie benutzt man ihn?
   - Beispiel-Anfragen
   - Troubleshooting

2. QUICKSTART.md - Eine 3-Schritte-Schnellstart-Anleitung

3. Ein Beispiel-Script (scripts/example-generator.js) - Das zeigt, wie Claude intern eine Präsentation erstellt

Bitte erstelle diese Dateien nacheinander und zeige mir jeweils eine kurze Zusammenfassung.
```

✅ **Was passiert**: Claude erstellt die Dokumentationsdateien.

**Hinweis**: Du kannst bei jeder Datei Feedback geben, z.B.:

```
Die README.md ist super! Kannst du noch einen Abschnitt über häufige Fehler hinzufügen?
```

---

### 📍 Schritt 8: Skill testen (Optional, 5 Minuten)

**Bevor du den Skill verpackst, teste ihn kurz.**

**Dein Prompt**:

```
Lass uns den Skill kurz testen. Erstelle eine Mini-Beispiel-Präsentation mit 2 Folien:
1. Titelfolie: "Test"
2. Content-Folie: "Das ist ein Test"

Verwende das Coherent-Design und zeige mir, ob alles funktioniert.
```

✅ **Was passiert**: Claude erstellt eine Test-Präsentation. Du siehst, ob der Skill korrekt funktioniert.

---

### 📍 Schritt 9: Skill als ZIP-Datei verpacken (5 Minuten)

**Jetzt wird's spannend!** Claude verpackt alles in eine ZIP-Datei.

**Dein Prompt**:

```
Perfekt! Bitte erstelle jetzt eine ZIP-Datei mit allen Skill-Dateien:
- SKILL.md
- README.md
- QUICKSTART.md
- assets/ (mit Logo, CSS, Bildern)
- references/ (mit Brand Guidelines)
- scripts/ (mit Beispiel-Script)

Die ZIP-Datei soll "coherent-powerpoint-generator.zip" heißen und zum Download bereit sein.
```

✅ **Was passiert**: Claude erstellt die ZIP-Datei und gibt dir einen **Download-Link**.

---

### 📍 Schritt 10: Download & Installation (3 Minuten)

**Fast geschafft!** Jetzt lädst du den Skill herunter und installierst ihn.

1. **Klicke** auf den Download-Link, den Claude dir gibt
2. **Speichere** die ZIP-Datei auf deinem Computer
3. **Entpacke** die ZIP-Datei

**Zur Installation:**

```
1. Gehe zu claude.ai
2. Öffne ein Projekt (oder erstelle ein neues)
3. Klicke auf "Skills"
4. Klicke auf "+ Add Skill"
5. Wähle "Upload Custom Skill"
6. Ziehe den Ordner "coherent-powerpoint-generator/" hinein
7. Fertig! ✅
```

---

## 🎯 Beispiel-Dialoge (Was du Claude sagen kannst)

### Anpassungen vornehmen

**Wenn du etwas ändern möchtest:**

```
Die SKILL.md ist gut, aber kannst du noch einen Abschnitt hinzufügen, der erklärt, wie man Diagramme in die Präsentation einfügt?
```

**Oder:**

```
Die Farben in der CSS-Datei sind perfekt. Kannst du noch eine zusätzliche Akzentfarbe für "Medical/Healthcare"-Themen hinzufügen? (z.B. ein helles Grün)
```

### Mehr Beispiele hinzufügen

```
Kannst du noch 3 weitere Beispiel-Anfragen in die README.md einfügen? Zum Beispiel:
- Eine Präsentation für Investoren
- Eine technische Präsentation für Ingenieure
- Eine Marketing-Präsentation für Kunden
```

### Fehler beheben

**Wenn etwas nicht funktioniert:**

```
Der Download-Link funktioniert nicht. Kannst du die ZIP-Datei nochmal erstellen?
```

**Oder:**

```
Das Logo wird nicht angezeigt. Kannst du überprüfen, ob der Pfad in der SKILL.md korrekt ist?
```

---

## 💡 Tipps für die Zusammenarbeit mit Claude

### ✅ DO (Mach das):

1. **Sei spezifisch**
   ```
   ✅ "Füge eine Akzentfarbe für Medical-Themen hinzu (hellgrün, #4CAF50)"
   ❌ "Füge eine Farbe hinzu"
   ```

2. **Gib klare Anweisungen**
   ```
   ✅ "Erstelle eine README.md mit 5 Abschnitten: Installation, Nutzung, Beispiele, Troubleshooting, FAQ"
   ❌ "Mach eine README"
   ```

3. **Teste zwischendurch**
   ```
   ✅ "Lass uns testen, ob das Logo richtig platziert wird"
   ❌ "Erstelle alles und dann testen wir"
   ```

4. **Gib Feedback**
   ```
   ✅ "Die SKILL.md ist super! Aber der Abschnitt über Farben könnte noch detaillierter sein"
   ❌ "Ist okay"
   ```

### ❌ DON'T (Vermeide das):

1. **Zu vage Anfragen**
   ```
   ❌ "Mach mir einen Skill"
   ✅ "Erstelle einen Skill für PowerPoint-Präsentationen im Coherent-Design"
   ```

2. **Alles auf einmal verlangen**
   ```
   ❌ "Erstelle den kompletten Skill mit allen Dateien sofort"
   ✅ "Lass uns Schritt für Schritt vorgehen. Beginne mit der SKILL.md"
   ```

3. **Keine Rückmeldung geben**
   ```
   ❌ [Claude erstellt etwas] → [Du sagst nichts]
   ✅ [Claude erstellt etwas] → "Das sieht gut aus! Weiter mit dem nächsten Schritt"
   ```

---

## 🔧 Troubleshooting (Häufige Probleme)

### Problem 1: "Claude versteht nicht, was ich möchte"

**Lösung**: Sei spezifischer. Zeige Claude Beispiele.

**Vorher**:
```
❌ "Erstelle eine schöne Präsentation"
```

**Nachher**:
```
✅ "Erstelle eine Präsentation mit:
- Titelfolie mit Neptune Blue Hintergrund (#2E5D9D)
- Logo oben rechts (100px breit)
- Weiße Schrift für den Titel
- Tagline 'INNOVATIONS THAT RESONATE' unten"
```

### Problem 2: "Die ZIP-Datei ist zu groß"

**Lösung**: Entferne unnötige Beispielbilder.

```
Claude, bitte erstelle die ZIP-Datei nochmal, aber ohne die Beispielbilder im assets/-Ordner. Lass nur das Logo und die CSS-Datei drin.
```

### Problem 3: "Der Skill funktioniert nicht nach der Installation"

**Lösung**: Überprüfe die Skill-Aktivierung.

1. Gehe zu deinem Claude-Projekt
2. Klicke auf "Skills"
3. Stelle sicher, dass "coherent-powerpoint-generator" **aktiviert** ist (Toggle-Switch)

**Oder sage Claude**:

```
Der Skill wird nicht ausgelöst. Kannst du die "description" in der SKILL.md überprüfen? Sie sollte deutlich machen, dass der Skill für "PowerPoint", "Präsentation" und "Coherent" zuständig ist.
```

### Problem 4: "Ich möchte nachträglich etwas ändern"

**Lösung**: Lade den Skill erneut hoch und sage Claude:

```
Ich habe den Skill bereits erstellt, aber ich möchte die SKILL.md ändern. Kannst du mir helfen, den Abschnitt über [THEMA] zu verbessern?
```

Claude wird die Datei für dich anpassen, und du kannst sie dann erneut als ZIP herunterladen.

---

## 📋 Checkliste: Ist dein Skill komplett?

Bevor du die ZIP-Datei herunterlädst, überprüfe:

### Dateien vorhanden?

- ✅ `SKILL.md` (mit YAML Frontmatter)
- ✅ `README.md` (Vollständige Anleitung)
- ✅ `QUICKSTART.md` (Schnellstart)
- ✅ `assets/logo-coherent.png` (Coherent-Logo)
- ✅ `assets/coherent-styles.css` (Design System)
- ✅ `references/Coherent_Corporate_Identity.md`
- ✅ `references/Coherent_Sprache_Tonalitaet.md`
- ✅ `scripts/example-generator.js` (optional, aber empfohlen)

### Inhalt korrekt?

- ✅ Neptune Blue (#2E5D9D) ist in der CSS-Datei definiert
- ✅ Logo-Pfad ist korrekt (`assets/logo-coherent.png`)
- ✅ SKILL.md erklärt alle Schritte zur Präsentationserstellung
- ✅ README.md enthält Installations- und Nutzungsanleitung
- ✅ Brand Guidelines sind im `references/` Ordner

### Test bestanden?

- ✅ Hast du eine Test-Präsentation erstellen lassen?
- ✅ Wurde das Logo angezeigt?
- ✅ War die Farbe Neptune Blue korrekt?

**Wenn alles ✅ ist**: Download starten! 🎉

---

## 🎓 Was du gelernt hast

Nach dieser Anleitung weißt du:

1. ✅ Wie man ein Claude-Projekt für Skill-Entwicklung erstellt
2. ✅ Wie man Claude Schritt für Schritt durch die Skill-Erstellung führt
3. ✅ Welche Dateien ein Skill braucht (SKILL.md, assets, references, scripts)
4. ✅ Wie man Brand Guidelines in einen Skill integriert
5. ✅ Wie man den fertigen Skill als ZIP-Datei herunterlädt und installiert

**Du kannst jetzt:**
- 🚀 Eigene Skills für andere Zwecke erstellen (z.B. Word-Dokumente, E-Mails, Reports)
- 🔧 Bestehende Skills anpassen und verbessern
- 📚 Skills für dein Team erstellen und teilen

---

## 🚀 Nächste Schritte

### Nach der Skill-Erstellung:

1. **Skill testen**
   ```
   Erstelle mir eine 3-Folien-Präsentation über VCSEL-Technologie im Coherent-Design.
   ```

2. **Mit Team teilen**
   - ZIP-Datei an Marketing-Kollegen senden
   - Anleitung zur Installation mitschicken (README.md)

3. **Weitere Skills erstellen**
   - Word-Dokument-Generator
   - E-Mail-Vorlagen
   - Social-Media-Posts

---

## 💬 Beispiel: Kompletter Dialog mit Claude

**So könnte dein kompletter Dialog aussehen:**

```
🧑 Du: Ich möchte einen PowerPoint-Generator-Skill für Coherent erstellen. Kannst du mir dabei helfen?

🤖 Claude: Natürlich! Ich helfe dir gerne. Lass uns Schritt für Schritt vorgehen...

🧑 Du: [Lädst Logo und Brand Guidelines hoch] Hier sind die Dateien.

🤖 Claude: Perfekt! Ich sehe das Logo und die Brand Guidelines. Ich erstelle jetzt die Skill-Struktur...

🧑 Du: Das sieht gut aus. Bitte erstelle die SKILL.md.

🤖 Claude: [Erstellt SKILL.md] Fertig! Die SKILL.md enthält jetzt...

🧑 Du: Super! Kannst du noch einen Abschnitt über Diagramme hinzufügen?

🤖 Claude: [Passt SKILL.md an] Ich habe den Abschnitt hinzugefügt...

🧑 Du: Perfekt! Erstelle jetzt bitte die README.md und QUICKSTART.md.

🤖 Claude: [Erstellt Dokumentation] Fertig! Die README erklärt...

🧑 Du: Alles sieht toll aus! Bitte erstelle die ZIP-Datei zum Download.

🤖 Claude: [Erstellt ZIP] Fertig! Hier ist dein Download-Link: [LINK]

🧑 Du: Danke! 🎉
```

---

## 📧 Hilfe & Support

**Bei Fragen während der Skill-Erstellung:**

1. **Claude fragen**
   ```
   Ich bin bei Schritt [X] und nicht sicher, was ich tun soll. Kannst du es nochmal erklären?
   ```

2. **Dokumentation prüfen**
   - Nach der Erstellung: Lies die README.md
   - Claude kann auch Teile davon vorlesen/erklären

3. **Neu starten** (Falls etwas schief geht)
   ```
   Lass uns nochmal von vorne beginnen. Ich möchte die SKILL.md neu erstellen.
   ```

---

## 🎉 Fazit

**Mit dieser Anleitung kannst du:**
- ✅ Gemeinsam mit Claude einen professionellen Skill erstellen
- ✅ Jeden Schritt verstehen (kein "Blackbox"-Prozess)
- ✅ Den Skill an deine Bedürfnisse anpassen
- ✅ Eine fertige ZIP-Datei zum Teilen erhalten

**Zeitaufwand**: 30-45 Minuten
**Schwierigkeit**: Leicht (keine Programmier-Kenntnisse nötig)
**Ergebnis**: Funktionsfähiger PowerPoint-Generator-Skill für Coherent

---

**Viel Erfolg bei der Skill-Erstellung! 🚀**



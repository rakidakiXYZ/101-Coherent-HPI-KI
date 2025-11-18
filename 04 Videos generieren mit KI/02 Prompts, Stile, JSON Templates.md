# 🎬 Leitfaden: Meta Prompts für KI-Videos

### (Cinematic Movies & Pixar-Style Movies)

---

## 🧭 1. Was ist ein Meta Prompt?

Ein **Meta Prompt** ist eine Art „Regieanleitung für die KI" – du kannst dir das wie ein Drehbuch vorstellen, das du der KI gibst.

**Einfach erklärt:**
- Ein Meta Prompt beschreibt **nicht direkt das Video**, sondern **führt dich Schritt für Schritt** zu einer klaren Beschreibung
- Das Ergebnis ist eine strukturierte Anleitung im **JSON-Format** (eine Art Checkliste für die KI)
- Diese Anleitung kannst du dann in **KI-Video-Tools** (z. B. Runway, Pika, Kaiber, Sora) eingeben
- Die KI erstellt daraus automatisch **professionelle Filmszenen**

**💡 Wichtig für Anfänger:** Du brauchst keine Programmierkenntnisse! JSON ist nur eine strukturierte Form, Informationen aufzuschreiben – ähnlich wie ein Formular mit verschiedenen Feldern.

---

## 🎥 2. Warum ist das für Coherent relevant?

Für uns bei **Coherent Corp.** bietet diese Technik viele praktische Vorteile:

### ✅ **Für Verwaltung, Marketing & Sales:**
- **Schnellere Content-Erstellung** für Social Media, Stellenanzeigen oder Präsentationen
- **Professionelle Videos** ohne teure Agenturen (z. B. Employer-Branding, Produktvorstellungen)
- **Einfache Bedienung** – auch ohne Video-Vorkenntnisse
- **Konsistente Qualität** durch strukturierte Vorlagen

### ✅ **Für Engineering & Technik:**
- **Technische Erklärvideos** (z. B. wie funktioniert ein VCSEL-Array?)
- **Produktdemonstrationen** (z. B. 800G-Transceiver im Rechenzentrum)
- **Schulungsmaterialien** für neue Mitarbeiter oder Kunden
- **Visualisierung komplexer Prozesse** (z. B. Laserschneiden, Siliziumphotonik)

### 🌟 **Das Besondere:**
Coherents Technologien sind visuell beeindruckend – Laser, optische Fasern, Lichtwellen. Mit KI-Videos können wir diese "**Innovations That Resonate**" erlebbar machen!

---

## ⚙️ 3. Wie funktioniert ein Meta Prompt? (Schritt für Schritt)

**Keine Sorge – du musst nichts auswendig lernen! Die KI führt dich durch den Prozess.**

1. **Du gibst eine Idee ein** (z. B. „Video über unsere Arbeit im Photonik-Labor")
2. **Die KI stellt dir Fragen** zu Stil, Emotion, Kamera, Musik, Text usw.
3. **Die KI erstellt automatisch** eine strukturierte JSON-Beschreibung
4. **Du kopierst diese Beschreibung** in ein KI-Video-Tool (z. B. Runway)
5. **Das Tool generiert dein Video** – fertig!

**💡 Tipp:** Du kannst die KI auch bitten, die JSON-Beschreibung zu ändern – zum Beispiel: "Mach die Musik fröhlicher" oder "Füge das Coherent-Logo am Ende ein".

---

## 🎬 4. Meta Prompt 1: **Cinematic Movie Builder**

### 🎯 Wofür ist dieser Prompt?

Erstellt **realistische, filmreife Szenen** – ideal für:
- Recruiting-Videos ("Karriere bei Coherent")
- Produktpräsentationen (z. B. neue Laser-Systeme)
- Kundenprojekt-Showcases (z. B. Rechenzentrum mit unseren Transceivern)
- Social-Media-Content (LinkedIn, YouTube)

### 🧩 Die Struktur (keine Angst, sieht komplizierter aus als es ist!)

```json
{
  "description": "Was soll im Video passieren?",
  "style": "Welcher Film-Stil? (z. B. dokumentarisch, modern)",
  "camera": "Wie bewegt sich die Kamera? (z. B. langsame Fahrt)",
  "lighting": "Welche Beleuchtung? (z. B. warmes Licht)",
  "environment": "Wo spielt die Szene? (z. B. Labor, Rechenzentrum)",
  "elements": "Welche Objekte sind zu sehen?",
  "motion": "Wie bewegen sich Dinge?",
  "audio": "Welche Musik/Geräusche?",
  "dialogue": "Was wird gesagt?",
  "voice": "Welche Art Stimme?",
  "ending": "Wie endet das Video?",
  "text": "Welcher Text erscheint am Ende?",
  "keywords": "Stichwörter für die KI"
}
```

**💡 Für Anfänger:** Du musst nicht alle Felder ausfüllen! Die KI kann dir helfen, die wichtigsten Teile auszufüllen.

---

### 🪄 Beispiel 1 – Photonik-Labor bei Coherent (Deutsch)

**Idee:** Ein emotionaler Einblick in die Arbeit unserer Forschungs- und Entwicklungsabteilung.

```markdown
{
  "description": "Langsame Kamerafahrt durch ein modernes Coherent Photonik-Labor. Ingenieure arbeiten mit präzisen Laser-Komponenten und testen optische Fasern. Eine Hand justiert vorsichtig einen VCSEL-Array unter einem Mikroskop. Die Szene zeigt das kohärente Licht eines Lasers, das durch eine optische Faser geleitet wird. Am Ende sehen wir das Coherent-Logo in Neptune Blue.",
  "style": "cinematic realism",
  "camera": "ruhige Steadicam, sanfte Bewegung durch das Labor",
  "lighting": "professionelles Labor-Licht mit blauen Laser-Reflexionen",
  "environment": "hochmodernes Photonik-Labor mit Präzisionsinstrumenten und Reinraum-Bereichen",
  "audio": "dezente Tech-Musik, leise Präzisionsgeräte im Hintergrund",
  "dialogue": [
    {"character": "Erzähler", "line": "Photonik – die Wissenschaft des Lichts. Bei Coherent entwickeln wir Technologien, die die Zukunft gestalten.", "tone": "inspirierend, kompetent"}
  ],
  "voice": "professionelle Erzählerstimme (neutral oder weiblich)",
  "ending": "Zoom auf das Coherent-Logo mit Tagline 'Innovations That Resonate'",
  "text": "Wissenschaft. Innovation. Präzision.",
  "keywords": ["Photonik", "Laser", "Innovation", "Forschung", "4K"]
}
```

**🎓 Was bedeutet das?**
- **VCSEL-Array**: Spezielle Laser für Datenkommunikation (z. B. in Smartphones für Gesichtserkennung)
- **Kohärentes Licht**: Licht, bei dem alle Wellen "im Takt" schwingen – wie eine perfekt synchronisierte Tanzgruppe
- **Neptune Blue**: Unsere Hauptfarbe bei Coherent (ein kraftvolles, technisches Blau)

---

### 🪄 Beispiel 2 – Recruiting-Video für Verwaltungsjobs (Deutsch)

**Idee:** Zeigen, dass Coherent ein großartiger Arbeitgeber für alle Bereiche ist – nicht nur für Ingenieure.

```markdown
{
  "description": "Kamerafahrt durch moderne Coherent-Büros. Wir sehen verschiedene Teams: HR-Mitarbeiter im Gespräch mit Bewerbern, Marketing-Team beim Brainstorming für Social-Media-Kampagne, Sales-Team bei Kundenpräsentation, Finance-Team bei der Budgetplanung. Alle lächeln, arbeiten konzentriert und unterstützen sich gegenseitig. Nahaufnahme auf einen Bildschirm mit 'Join Coherent' und offenen Stellenangeboten.",
  "style": "modern corporate storytelling",
  "camera": "dynamische, authentische Bewegungen durch die Bürolandschaft",
  "lighting": "natürliches Bürolicht mit warmen Akzenten",
  "environment": "modernes Open-Office mit Besprechungsräumen, Kreativ-Ecken und Pausenbereichen",
  "audio": "motivierende Hintergrundmusik (modern, aber nicht zu laut)",
  "dialogue": [
    {"character": "Erzähler", "line": "Bei Coherent gestaltest du mehr als einen Job – du gestaltest die Zukunft der Photonik. Und das in jedem Bereich.", "tone": "einladend, motivierend"}
  ],
  "voice": "freundliche, einladende Stimme",
  "ending": "Team-Foto mit allen Abteilungen, dann Coherent-Logo",
  "text": "Deine Karriere. Unsere Mission. Join Coherent.",
  "keywords": ["Karriere", "Employer Branding", "Teamwork", "Diversität"]
}
```

---

### 🪄 Beispiel 3 – Rechenzentrum & 800G-Transceiver (Englisch, für technische Zielgruppe)

```markdown
{
  "description": "Drone shot over a massive hyperscale data center. Camera transitions inside to show rows of servers with blue LED lights. Close-up of Coherent 800G transceivers plugged into network switches, with fiber optic cables glowing with data transmission. Engineers monitor network performance on large displays. Scene shows data flowing at incredible speeds through optical connections.",
  "style": "high-tech documentary",
  "camera": "smooth transitions from drone to interior steady shots",
  "lighting": "cool data center lighting with glowing fiber optic accents in Neptune Blue",
  "environment": "modern hyperscale data center with advanced cooling and cable management",
  "audio": "futuristic electronic music with subtle server hum",
  "dialogue": [
    {"character": "Narrator", "line": "The future of AI and cloud computing depends on speed. Coherent's 800G transceivers move data at the speed of light.", "tone": "confident, technical"}
  ],
  "voice": "professional male narrator",
  "ending": "zoom to Coherent transceiver module with 'Powering the AI Revolution' text",
  "text": "Speed. Efficiency. Innovation.",
  "keywords": ["data center", "800G", "transceivers", "networking", "AI infrastructure"]
}
```

**🎓 Was bedeutet das?**
- **800G-Transceiver**: Kleine Module, die Daten mit extrem hoher Geschwindigkeit (800 Gigabit pro Sekunde!) über Lichtwellen übertragen
- **Hyperscale Data Center**: Riesige Rechenzentren von Unternehmen wie Google, Amazon, Microsoft
- **Fiber Optic Cables**: Glasfaserkabeln, durch die Lichtsignale (statt elektrischer Signale) fließen

---

### 🪄 Beispiel 4 – Marketing-Video: Laserschneiden in der Industrie (Deutsch)

```markdown
{
  "description": "Nahaufnahme eines Coherent-Industrielasers, der präzise Metall schneidet. Funken fliegen, aber die Schnitte sind perfekt glatt. Kamera zoomt heraus und zeigt eine moderne Fertigungshalle mit mehreren Lasersystemen. Ein Qualitätsingenieur prüft die geschnittenen Teile und nickt zufrieden. Am Ende sehen wir das fertige Produkt – ein perfekt gefertigtes Bauteil für die Automobilindustrie.",
  "style": "industrial cinematography",
  "camera": "dynamische Makro-Aufnahmen, dann Weitwinkel",
  "lighting": "dramatisches Licht mit Laser-Reflexionen und Funkenflug",
  "environment": "moderne Fertigungshalle mit Laserschneidsystemen",
  "audio": "kraftvolle Industrial-Musik, Lasergeräusche",
  "dialogue": [
    {"character": "Erzähler", "line": "Präzision auf den Mikrometer. Coherent-Laser setzen neue Standards in der Fertigung.", "tone": "kraftvoll, überzeugend"}
  ],
  "voice": "markante männliche Stimme",
  "ending": "Coherent-Logo erscheint mit funkelndem Laser-Effekt",
  "text": "Lasertechnologie für die Industrie 4.0",
  "keywords": ["Laserschneiden", "Industrie", "Fertigung", "Präzision", "Automotive"]
}
```

---

## 🧚‍♀️ 5. Meta Prompt 2: **Pixar-Style Movie Builder**

### 🎯 Wofür ist dieser Prompt?

Erstellt **animierte, emotionale Kurzfilme** im Stil von Pixar – mit Charakteren, Stimmen und einer kleinen Geschichte.

**Ideal für:**
- Interne Schulungen (z. B. "Warum ist Qualitätskontrolle wichtig?")
- Wertekommunikation (z. B. unsere "I CARE"-Werte)
- Awareness-Kampagnen (z. B. Datenschutz, Nachhaltigkeit)
- Kreative Social-Media-Posts

### 🧩 Die Struktur

```json
{
  "description": "Was passiert in der Geschichte?",
  "style": "Pixar-style emotional 3D animation",
  "characters": "Welche Charaktere kommen vor?",
  "emotion": "Welche Gefühle soll das Video wecken?",
  "camera": "Kameraführung",
  "lighting": "Beleuchtung",
  "color_palette": "Farbschema",
  "environment": "Umgebung",
  "motion": "Bewegungen",
  "dialogue": "Dialoge",
  "voices": "Stimmen der Charaktere",
  "audio": "Musik/Geräusche",
  "ending": "Ende der Geschichte",
  "text": "Abschlusstext",
  "keywords": "Stichwörter"
}
```

---

### 🪄 Beispiel 1 – "Das kleine Photon lernt fliegen" (Deutsch)

**Idee:** Ein kleines Lichtteilchen (Photon) lernt, wie wichtig Präzision und Teamwork sind.

```markdown
{
  "description": "Ein niedliches, leuchtendes Photon mit großen Augen schwebt nervös in einem Coherent-Labor. Es möchte durch eine optische Faser reisen, hat aber Angst, den Weg zu verlieren. Andere Photonen zeigen ihm, dass sie nur zusammen – perfekt synchronisiert – kohärentes Licht bilden können. Das kleine Photon lernt, im Takt mit den anderen zu schwingen. Am Ende fliegen alle gemeinsam durch die Faser und erzeugen ein wunderschönes, kohärentes Lichtmuster.",
  "characters": [
    {"name": "Lumino", "description": "kleines blaues Photon mit großen neugierigen Augen und schüchterner Art"}
  ],
  "emotion": "Mut, Zusammenhalt, Entdeckerfreude",
  "lighting": "sanftes, magisches Licht in Blau- und Weißtönen",
  "color_palette": "Neptune Blue (Coherent), leuchtende Pastelltöne für Photonen",
  "environment": "abstrahiertes Photonik-Labor mit optischen Fasern als Rutschbahnen",
  "audio": "verspielte, orchestrale Musik mit hellen Klängen",
  "dialogue": [
    {"character": "Lumino", "line": "Ich dachte, ich muss alleine leuchten... aber gemeinsam sind wir kohärent!", "tone": "stolz, glücklich"}
  ],
  "voices": [
    {"character": "Lumino", "voice": "kindliche, neugierige Stimme"}
  ],
  "ending": "Kamera zoomt heraus und zeigt perfektes Laserlicht",
  "text": "Kohärenz bedeutet Zusammenarbeit. – Coherent Corp.",
  "keywords": ["Pixar-Stil", "Animation", "Photonik", "Teamwork", "Kohärenz"]
}
```

**🎓 Was ist Kohärenz?**
Kohärenz bedeutet, dass Lichtwellen perfekt "im Gleichschritt" schwingen – wie ein Orchester, das im Takt spielt. Nur kohärentes Licht kann als Laser funktionieren!

---

### 🪄 Beispiel 2 – "Die mutige Firewall" (für IT-Sicherheit & Compliance)

```markdown
{
  "description": "Eine kleine, mutige Firewall-Figur mit Helm und Schild bewacht einen Server. Sie sieht gefährliche Cyber-Bedrohungen herannahen (dargestellt als kleine Monster). Die Firewall ruft ihre Freunde – Antivirus-Software, Backup-System und Monitoring-Tool – zur Hilfe. Gemeinsam bilden sie einen Schutzschild und wehren die Bedrohungen ab. Am Ende tanzen alle Sicherheitssysteme fröhlich um geschützte Daten.",
  "characters": [
    {"name": "FireWalli", "description": "kleine orangefarbene Firewall mit Helm, großen Augen und entschlossenem Gesichtsausdruck"}
  ],
  "emotion": "Mut, Teamwork, Schutz",
  "lighting": "warmes digitales Licht mit Sicherheits-Grün und Alarm-Orange",
  "color_palette": "Coherent Neptune Blue für Server, Orange für Firewall, Grün für Sicherheitssignale",
  "environment": "abstrahiertes digitales Rechenzentrum mit schwebenden Daten",
  "audio": "spannende elektronische Musik mit rhythmischen Sicherheitsalarm-Beats",
  "dialogue": [
    {"character": "FireWalli", "line": "Alleine bin ich stark – aber gemeinsam sind wir unbesiegbar!", "tone": "mutig, teamorientiert"}
  ],
  "voices": [
    {"character": "FireWalli", "voice": "junge, entschlossene Stimme"}
  ],
  "ending": "Kamera zoomt heraus und zeigt perfekt geschütztes System",
  "text": "Datenschutz ist Teamarbeit. – Coherent Corp.",
  "keywords": ["Pixar-Stil", "IT-Sicherheit", "Compliance", "Datenschutz", "Teamwork"]
}
```

**💡 Anwendung:** Dieses Video eignet sich perfekt für interne Schulungen zu Datenschutz und IT-Sicherheit – besonders für nicht-technische Mitarbeiter!

---

### 🪄 Beispiel 3 – "Der SiC-Kristall und die Elektromobilität" (Englisch)

```markdown
{
  "description": "A tiny, sparkling Silicon Carbide (SiC) crystal with big dreams wakes up in a Coherent materials lab. It watches engineers transform raw materials into perfect wafers. The SiC crystal is excited to become part of an electric vehicle's power system. The journey shows the crystal being shaped, tested, and finally integrated into an EV charging station, helping cars charge faster and more efficiently.",
  "characters": [
    {"name": "Sparkle", "description": "small crystalline character with shimmering edges and hopeful eyes"}
  ],
  "emotion": "purpose, innovation, sustainability",
  "lighting": "bright laboratory light transitioning to warm sustainable energy glow",
  "color_palette": "crystalline silver, Coherent Neptune Blue, green for sustainability",
  "environment": "Coherent materials lab transforming into futuristic EV charging station",
  "audio": "inspiring tech music with electronic and organic elements",
  "dialogue": [
    {"character": "Sparkle", "line": "From crystal to clean energy – I'm part of something bigger!", "tone": "proud, excited"}
  ],
  "voices": [
    {"character": "Sparkle", "voice": "cheerful, optimistic voice"}
  ],
  "ending": "camera shows electric vehicles charging efficiently with Sparkle inside the system",
  "text": "Materials that power the future. – Coherent Corp.",
  "keywords": ["Pixar style", "SiC", "electric vehicles", "sustainability", "innovation"]
}
```

**🎓 Was ist SiC?**
**Siliziumkarbid (SiC)** ist ein spezielles Material, das Coherent herstellt. Es wird in der Elektromobilität verwendet, weil es Energie sehr effizient umwandeln kann – perfekt für E-Auto-Ladestationen!

---

### 🪄 Beispiel 4 – "Karriere-Journey: Von der Bewerbung zum Team" (Deutsch)

```markdown
{
  "description": "Ein nervöses Bewerbungs-Dokument (dargestellt als kleiner Papier-Charakter) landet auf einem Schreibtisch bei Coherent HR. Es macht sich Sorgen, ob es gut genug ist. Freundliche HR-Mitarbeiter (als unterstützende Charaktere) prüfen die Bewerbung sorgfältig und laden den Kandidaten ein. Das Dokument durchläuft den Bewerbungsprozess: Interview, Team-Kennenlernen, Vertragsunterzeichnung. Am Ende wird es Teil eines glücklichen, diversen Teams.",
  "characters": [
    {"name": "Bewie", "description": "kleiner Papier-Charakter mit Bewerbungsinhalt, anfangs nervös, dann selbstbewusst"}
  ],
  "emotion": "Nervosität, Wertschätzung, Zugehörigkeit",
  "lighting": "warmes Bürolicht mit freundlichen Akzenten",
  "color_palette": "Coherent Neptune Blue, warme Hauttöne für Diversität, freundliche Pastellfarben",
  "environment": "modernes Coherent-Büro mit Besprechungsräumen und Team-Bereichen",
  "audio": "aufmunternde, freundliche Musik",
  "dialogue": [
    {"character": "Bewie", "line": "Ich war nervös... aber hier bin ich wirklich willkommen!", "tone": "erleichtert, glücklich"}
  ],
  "voices": [
    {"character": "Bewie", "voice": "sympathische, etwas unsichere Stimme, die selbstbewusster wird"}
  ],
  "ending": "Bewie ist jetzt Teil eines Team-Fotos, alle lächeln",
  "text": "Bei Coherent zählt jeder. I CARE. – Coherent Corp.",
  "keywords": ["Pixar-Stil", "Recruiting", "Employer Branding", "I CARE", "Diversität"]
}
```

**💡 I CARE:** Das sind unsere Unternehmenswerte bei Coherent:
- **I**ntegrity (Integrität)
- **C**ollaboration (Zusammenarbeit)
- **A**ccountability (Verantwortung)
- **R**espect (Respekt)
- **E**nthusiasm (Begeisterung)

---

## 💡 6. Vergleich: Welchen Stil soll ich wählen?

| Aspekt      | Cinematic Prompt (Realistisch)                           | Pixar-Style Prompt (Animiert)                              |
| ----------- | --------------------------------------------------------- | ---------------------------------------------------------- |
| **Ziel**    | Realistische, professionelle Filmszenen                   | Animierte, emotionale Geschichten mit Charakteren          |
| **Einsatz** | Recruiting, Produktvorstellungen, Kundenprojekte, Social Media | Schulungen, Wertekommunikation, Awareness-Kampagnen, interne Videos |
| **Tonfall** | Professionell, inspirierend, technisch                    | Verspielt, emotional, lehrreich                            |
| **Vorteil** | Wirkt seriös und real                                     | Erklärt komplexe Themen einfach und emotional              |
| **Beispiel** | "Rechenzentrum mit 800G-Transceivern"                    | "Das kleine Photon lernt Kohärenz"                         |

**💡 Tipp für Anfänger:** Für den Start empfehlen wir **Pixar-Style** – die Geschichten sind einfacher zu erstellen und machen mehr Spaß!

---

## 🎯 7. Praktische Anwendungsfälle bei Coherent

### 📝 **Für HR & Recruiting:**
**Cinematic:**
- Employer-Branding-Videos ("Ein Tag bei Coherent")
- Karriere-Seiten-Content für Website
- Messe-Videos für Karrieremessen

**Pixar-Style:**
- "Die Reise eines neuen Mitarbeiters" (Onboarding)
- "Warum Diversität uns stärker macht" (I CARE-Werte)
- "Bewerbungstipps von Bewie" (Recruiting-Kampagne)

---

### 📢 **Für Marketing & Communications:**
**Cinematic:**
- Produktlaunch-Videos (neue Laser-Systeme, Transceiver)
- LinkedIn-Content (Behind-the-Scenes im Labor)
- YouTube-Tutorials (technische Produktvorstellungen)
- Event-Trailer für Messen und Konferenzen

**Pixar-Style:**
- "Was macht eigentlich ein Photon?" (Technologie-Erklärung)
- "Die Geschichte von Coherent" (Unternehmensgeschichte)
- Social-Media-Serien mit wiederkehrenden Charakteren

---

### 💼 **Für Sales & Account Management:**
**Cinematic:**
- Kundenprojekt-Success-Stories (z. B. "Rechenzentrum-Upgrade mit Coherent")
- Lösungspräsentationen für spezifische Branchen (Automotive, Communications)
- Referenz-Videos für Angebote

**Pixar-Style:**
- "Der Weg eines Datenpakets durch ein Rechenzentrum" (technische Erklärung für nicht-technische Kunden)
- "Warum Qualität zählt" (Werteargumentation)

---

### 🔬 **Für Engineering, R&D & Quality:**
**Cinematic:**
- Technische Dokumentations-Videos
- Fertigungs-Prozess-Visualisierungen (z. B. SiC-Wafer-Produktion)
- Qualitätskontroll-Prozesse für Kunden

**Pixar-Style:**
- "Die Reise eines Laserstrahls" (Technologie-Erklärung)
- "Warum Präzision wichtig ist" (Quality-Awareness)
- Schulungsvideos für neue Mitarbeiter

---

### 💰 **Für Finance, Controlling & Procurement:**
**Cinematic:**
- Unternehmens-Präsentationen für Investoren
- Nachhaltigkeits-Reports (z. B. "Coherents Weg zur CO2-Neutralität")

**Pixar-Style:**
- "Der Weg eines Budgets" (interne Schulung zu Finanzprozessen)
- "Compliance-Champions" (spielerische Compliance-Schulung)

---

### 📋 **Für Compliance, Legal & Data Protection:**
**Pixar-Style:**
- "FireWalli und die Daten-Piraten" (Datenschutz-Schulung)
- "Die Compliance-Helden" (spielerische Einführung in Richtlinien)
- "Warum wir Regeln brauchen" (Wertevermittlung)

---

## 🔒 8. Wichtige Sicherheitshinweise für Coherent

### **🔴 Was du NICHT in Video-Prompts verwenden darfst:**

**Datenschutz & Vertraulichkeit:**
- ❌ **KEINE** proprietären Produktdaten oder Patentinformationen (z. B. genaue technische Spezifikationen von noch nicht veröffentlichten Produkten)
- ❌ **KEINE** vertraulichen Kundendaten oder Projektinformationen (Namen, Verträge, Spezifikationen)
- ❌ **KEINE** Mitarbeiterdaten ohne explizite Zustimmung (Namen, Fotos, persönliche Informationen)
- ❌ **KEINE** internen Fertigungsprozesse mit Wettbewerbsrelevanz
- ❌ **KEINE** Finanzdaten, die nicht öffentlich sind

**Compliance & Regulatorisches:**
- ❌ **KEINE** detaillierten Sicherheitsarchitekturen oder IT-Infrastruktur-Details
- ❌ **KEINE** Inhalte, die gegen DSGVO oder andere Datenschutzgesetze verstoßen könnten
- ❌ **KEINE** irreführenden oder nicht verifizierten technischen Aussagen

### **✅ Was du stattdessen tun solltest:**

**Beste Praktiken:**
- ✅ Verwende **anonymisierte oder fiktive Daten** in Beispielen
- ✅ Nutze **allgemeine technische Beschreibungen** (z. B. "800G-Transceiver" statt spezifischer interner Modellnummern)
- ✅ Beziehe dich auf **öffentlich verfügbare Informationen** (Website, Produktbroschüren, LinkedIn)
- ✅ Bei Kundenprojekten: **Hole explizite Freigabe ein** oder anonymisiere vollständig
- ✅ Lass Videos mit regulatorischer Relevanz **durch die Fachabteilung prüfen**

**Qualitätssicherung (Human-in-the-Loop):**
- ✅ **Prüfe IMMER** KI-generierte Video-Beschreibungen, bevor du sie verwendest
- ✅ **Technische Aussagen** sollten von Fachexperten validiert werden
- ✅ **Marketing-Claims** müssen mit Corporate Communications abgestimmt sein
- ✅ Bei Unsicherheit: **Frage nach!** (z. B. bei Corporate Communications oder Legal)

### **🎯 Markenschutz:**
- ✅ Verwende immer das aktuelle **Coherent-Logo** und die **Neptune Blue** Farbe
- ✅ Integriere unsere Tagline: **"Innovations That Resonate"**
- ✅ Achte auf die **Coherent Brand Guidelines** (verfügbar im Intranet)
- ✅ Verwende **KEINE** veralteten Logos (II-VI, altes Coherent Inc.)

---

## 📚 9. Praxis-Personas: So können verschiedene Rollen KI-Videos nutzen

### 1. HR Business Partner für Talent Acquisition

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein authentisches Employer-Branding-Video für unsere Karriere-Website zu erstellen. Das Video soll zeigen, wie vielfältig die Karrieremöglichkeiten bei Coherent sind – von Verwaltung über Engineering bis hin zu Sales. Ich brauche eine JSON-Beschreibung für einen Cinematic-Style Film, der verschiedene Abteilungen zeigt, inklusive echter Arbeitsszenen (keine Schauspieler-Gefühl). Die KI soll mich durch alle wichtigen Aspekte führen: welche Szenen, welche Musik, welche Texte am Ende erscheinen sollen. Ziel ist, dass sich Bewerbende vorstellen können, wie ihr Arbeitsalltag bei Coherent aussehen würde.
```

**Anwendungsfall:** Karriere-Videos für LinkedIn, Stellenanzeigen, Karriere-Messen

---

### 2. Marketing Content Specialist

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein spannendes Social-Media-Video im Pixar-Stil zu erstellen, das unsere neue 800G-Transceiver-Technologie erklärt – aber so, dass auch nicht-technische Personen es verstehen. Die Idee: Ein kleines Daten-Paket reist mit Lichtgeschwindigkeit durch ein Glasfaserkabel und erlebt Abenteuer. Die KI soll mir eine vollständige JSON-Beschreibung erstellen mit Charakter-Details, Dialogen und passender Musik. Das Video soll auf LinkedIn geteilt werden und zeigen, dass Photonik nicht langweilig ist, sondern faszinierend!
```

**Anwendungsfall:** LinkedIn-Posts, Instagram-Stories, YouTube-Shorts, Technologie-Erklärungen

---

### 3. Sales Account Manager (Technical Sales)

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein professionelles Kundenpräsentations-Video zu erstellen. Ich verkaufe Coherent-Lasersysteme für industrielle Anwendungen und brauche ein realistisches (Cinematic-Style) Video, das zeigt, wie präzise unsere Laser Metall schneiden können. Das Video soll Vertrauen aufbauen und technische Kompetenz demonstrieren, ohne zu technisch zu werden. Die KI soll mir eine JSON-Beschreibung für ein 1-2 Minuten Video erstellen, das ich in Kundenpräsentationen einbinden kann – inklusive passender Hintergrundmusik und einem klaren Call-to-Action am Ende.
```

**Anwendungsfall:** Kundenakquise, Angebotspräsentationen, Messe-Content

---

### 4. Training & Development Coordinator

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein animiertes Schulungsvideo im Pixar-Stil zu erstellen, das neuen Mitarbeitern unsere "I CARE"-Werte erklärt. Die Idee: Fünf kleine Charaktere (jeweils einer für Integrity, Collaboration, Accountability, Respect, Enthusiasm) erleben kleine Abenteuer im Coherent-Alltag und zeigen, warum diese Werte wichtig sind. Die KI soll mir eine vollständige JSON-Beschreibung mit allen Charakteren, Dialogen und einem inspirierenden Ende erstellen. Das Video wird im Onboarding-Programm verwendet.
```

**Anwendungsfall:** Mitarbeiter-Onboarding, interne Schulungen, Wertevermittlung

---

### 5. Photonics Application Engineer

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein technisches Erklärvideo zu erstellen, das zeigt, wie kohärentes Licht in einem VCSEL-Array entsteht. Das Video soll im Cinematic-Style gedreht sein und Makro-Aufnahmen von optischen Komponenten zeigen – kombiniert mit abstrakten Visualisierungen von Lichtwellen. Die KI soll mir eine JSON-Beschreibung erstellen, die ich in ein KI-Video-Tool eingeben kann. Das Video wird für Kundenpräsentationen und technische Trainings verwendet. Wichtig: wissenschaftlich korrekt, aber visuell beeindruckend.
```

**Anwendungsfall:** Technische Dokumentation, Kundenschulungen, Produkt-Demonstrationen

---

### 6. Executive Assistant / Communications Support

```markdown
Ich möchte mit einer KI arbeiten, die mir hilft, ein kurzes, professionelles Video für unsere Jahresabschluss-Präsentation zu erstellen. Das Video soll im Cinematic-Style die Highlights des Jahres zeigen: neue Produkteinführungen, Team-Erfolge, Expansion in neue Märkte. Die KI soll mich Schritt für Schritt durch den Prozess führen und am Ende eine JSON-Beschreibung erstellen, die ich an unser Video-Team weitergeben kann. Das Video wird auf der Jahresversammlung und intern geteilt. Ziel: Mitarbeiter motivieren und stolz machen auf das, was wir erreicht haben.
```

**Anwendungsfall:** Unternehmens-Events, Jahresberichte, interne Kommunikation

---

## 💡 10. Tipps für den Einstieg (speziell für Anfänger)

### ✅ **Schritt-für-Schritt-Anleitung für dein erstes Video:**

1. **Wähle ein einfaches Thema** (z. B. "Warum ich gerne bei Coherent arbeite")
2. **Entscheide dich für einen Stil** (Cinematic für realistisch, Pixar für animiert)
3. **Öffne ein KI-Tool** (z. B. ChatGPT, Claude) und sage:
   ```
   "Ich möchte ein Video-Prompt für [dein Thema] erstellen. 
   Kannst du mich Schritt für Schritt durch den Prozess führen und 
   am Ende eine JSON-Beschreibung erstellen?"
   ```
4. **Beantworte die Fragen der KI** (keine Sorge, es gibt keine falschen Antworten!)
5. **Überprüfe die JSON-Beschreibung** (Ist alles korrekt? Keine vertraulichen Daten?)
6. **Kopiere die JSON-Beschreibung** in ein KI-Video-Tool (z. B. Runway, Pika)
7. **Generiere das Video** und schaue es an
8. **Verbessere bei Bedarf** (Du kannst die KI bitten, Teile zu ändern)

### ⚠️ **Häufige Anfänger-Fehler vermeiden:**

❌ **"Ich gebe zu wenig Details an"**
→ ✅ Sei so spezifisch wie möglich! Beschreibe Farben, Stimmung, Umgebung genau.

❌ **"Ich verwende Fachjargon, den die KI nicht versteht"**
→ ✅ Erkläre technische Begriffe oder verwende allgemeine Beschreibungen.

❌ **"Mein Video wird zu lang"**
→ ✅ Starte mit 30-60 Sekunden. Kurze Videos sind oft wirkungsvoller!

❌ **"Ich vergesse das Coherent-Branding"**
→ ✅ Denke daran: Neptune Blue, Coherent-Logo, Tagline "Innovations That Resonate"

### 🎓 **Lernkurve:**
- **Versuch 1-3:** Du lernst das System kennen – Videos sind vielleicht noch nicht perfekt
- **Versuch 4-10:** Du verstehst, welche Beschreibungen gute Ergebnisse liefern
- **Ab Versuch 10:** Du kannst schnell professionelle Video-Prompts erstellen!

**💡 Wichtig:** Jeder fängt klein an. Auch die besten Video-Creator haben mal mit einfachen Projekten begonnen!

---

## 🌟 11. Kreative Ideen für deine Abteilung

### **HR & People Operations:**
- 🎬 "Ein Tag im Leben eines Coherent-Mitarbeiters" (verschiedene Rollen)
- 🎬 "Warum Benefits wichtig sind" (Pixar-Style mit Charakter "Benny the Benefit")
- 🎬 "Die Reise eines Bewerbers" (vom CV bis zum ersten Arbeitstag)

### **Marketing & Social Media:**
- 🎬 "Behind the Scenes: Wie ein Laser entsteht" (Cinematic)
- 🎬 "Das Photonen-Abenteuer" (Pixar-Serie für LinkedIn)
- 🎬 "Coherent in 60 Sekunden" (schnelles Brand-Video)

### **Sales & Business Development:**
- 🎬 "Kundenerfolgsgeschichten" (reale Projekte, anonymisiert)
- 🎬 "Warum Coherent?" (Differenzierungs-Video für Pitch-Decks)
- 🎬 "Produktvorstellungen" (neue Transceiver, Laser, Materialien)

### **Finance & Controlling:**
- 🎬 "Wie funktioniert unser Budget-Prozess?" (Pixar-Style für internes Training)
- 🎬 "Nachhaltigkeit bei Coherent" (Cinematic für ESG-Reporting)

### **Engineering & R&D:**
- 🎬 "Von der Idee zum Produkt" (Entwicklungsprozess)
- 🎬 "Quality Matters" (Warum Qualitätskontrolle entscheidend ist)
- 🎬 "Innovative Materialien" (z. B. SiC-Technologie für E-Mobilität)

### **Compliance & Legal:**
- 🎬 "Datenschutz einfach erklärt" (Pixar-Style für DSGVO-Training)
- 🎬 "Compliance-Champions" (spielerische Schulung)

---

## 📖 Zusammenfassung: Die goldenen Regeln für Coherent

### ✅ **Für erfolgr eiche KI-Videos:**

1. **Starte einfach** – Beginne mit kurzen Videos (30-60 Sekunden)
2. **Sei spezifisch** – Je detaillierter deine Beschreibung, desto besser das Ergebnis
3. **Nutze unsere Marke** – Neptune Blue, Coherent-Logo, "Innovations That Resonate"
4. **Wähle den richtigen Stil** – Cinematic für Seriosität, Pixar für Emotionen
5. **Denke an die Zielgruppe** – Verwaltung braucht andere Videos als Engineering
6. **Teste und iteriere** – Das erste Video ist selten perfekt – verbessere es!
7. **Beachte Datenschutz** – KEINE vertraulichen Daten, Kundennamen oder proprietären Informationen
8. **Hole Feedback ein** – Zeige den Entwurf Kollegen, bevor du ihn veröffentlichst
9. **Dokumentiere Erfolge** – Teile erfolgreiche Prompts mit deinem Team
10. **Hab Spaß!** – KI-Videos sind kreativ und machen Freude – experimentiere!

### 🚀 **Wichtigste Erkenntnis:**
Du musst **kein Video-Profi** sein, um mit KI beeindruckende Videos zu erstellen. Die KI übernimmt die technischen Details – du bringst die kreativen Ideen und das Coherent-Know-how!

---

## 🎯 Nächste Schritte

**Was kannst du jetzt tun?**

1. **Suche dir ein einfaches Thema aus** (z. B. "Warum ich bei Coherent arbeite")
2. **Öffne ein KI-Tool** (ChatGPT, Claude, oder ein anderes Sprachmodell)
3. **Nutze einen der Beispiel-Prompts** aus diesem Tutorial als Vorlage
4. **Passe ihn an dein Thema an** und lass die KI dir eine JSON-Beschreibung erstellen
5. **Probiere ein KI-Video-Tool aus** (viele bieten kostenlose Testversionen)
6. **Teile dein Ergebnis** mit Kollegen und hole Feedback ein

**💡 Tipp:** Starte mit einem **Pixar-Style Video** – die sind einfacher zu erstellen und machen mehr Spaß beim Experimentieren!

---

## 🤝 Fragen oder Feedback?

Wenn du Fragen hast oder deine ersten Ergebnisse teilen möchtest:
- 📧 Kontaktiere das Corporate Communications Team
- 💬 Teile deine Erfahrungen in den internen Kanälen
- 🎓 Besuche weitere KI-Workshops für vertiefende Themen

---

**Viel Erfolg beim Erstellen deiner ersten KI-Videos!** 🎬✨

*Coherent Corp. – Innovations That Resonate*

---

**@ 2025 - HPI KI Workshops | Tutorials**

# Tutorial: KI-Videoproduktion für Coherent Marketing

Herzlich willkommen! Dieses Tutorial zeigt Ihnen, wie Sie mit KI-Assistenten professionelle Videoskripte für Coherent erstellen. Sie benötigen keine Vorkenntnisse – wir führen Sie Schritt für Schritt zum perfekten Video.

---

## 1. Was ist ein KI-Videoskript?

Ein KI-Videoskript ist eine strukturierte Anweisung im **JSON-Format**, die einem KI-Videogenerator (z.B. Runway, Pika, Sora) genau sagt, was er erstellen soll. Sie beschreiben die Szene, Kamera, Musik und Dialoge – die KI setzt es um.

## 2. Wie erstelle ich ein Skript?

Sie verwenden einen **Prompt-Generator**, um Ihre Video-Idee in ein perfektes JSON-Skript umzuwandeln. So funktioniert's:

1.  **Basis-Prompt kopieren:** Nehmen Sie den unten stehenden Basis-Prompt.
2.  **In KI-Assistent einfügen:** Öffnen Sie ChatGPT, Claude oder einen ähnlichen Assistenten und fügen Sie den Prompt ein.
3.  **Video beschreiben:** Sagen Sie dem Assistenten, was Sie möchten (z.B. "Erstelle ein 15-Sekunden-Video über unseren neuen Faserlaser für LinkedIn").
4.  **JSON-Skript erhalten:** Der Assistent gibt Ihnen ein fertiges JSON-Skript.
5.  **In Video-Generator einfügen:** Kopieren Sie das JSON und fügen Sie es in Ihr KI-Video-Tool ein.

---

## 3. Der Basis-Prompt für Coherent-Videos

Kopieren Sie diesen vollständigen Prompt in Ihren KI-Assistenten, um ihn zu einem Coherent-Videospezialisten zu machen:

```markdown
# Rolle
Du bist ein Experte für professionelle Photonik-Video-Skripte für Coherent Corp.
Du erstellst präzise, technisch fundierte Drehbuch-Anweisungen für kurze Erklär- und Marketing-Videos im Bereich Lasertechnologie, Optik und Photonik.

# Zweck
Erstelle strukturierte Video-Prompts im JSON-Format für professionelle Business-Videos, die:
- Technische Sachverhalte verständlich erklären
- Coherent-Lösungen überzeugend präsentieren
- Komplexe Themen einfach visualisieren
- Professionell, innovativ und wissenschaftlich fundiert wirken

# Nicht verhandelbare Regeln
- **Professioneller Ton:** Sachlich, kompetent, vertrauenswürdig – keine übertriebene Werbesprache.
- **Zielgruppen-gerecht:** Ingenieure, Forscher, technische Einkäufer, Management.
- **Kurz und prägnant:** Social Media (8-15s), LinkedIn/Website (15-30s), YouTube (30-60s).
- **Technisch korrekt:** Keine falschen Behauptungen, keine übertriebenen Versprechen.
- **Compliance-konform:** Keine Darstellung echter Kundendaten oder vertraulicher F&E-Projekte.

# Ausgabeformat
Erstelle ein JSON-Objekt mit folgenden Feldern:
- **camera_setup**: Kameraeinstellungen und Perspektive
- **subject**: Hauptakteur oder Fokus des Videos
- **action**: Was passiert im Video
- **dialogue**: Gesprochener Text oder Voice-Over
- **setting**: Wo spielt die Szene
- **audio**: Hintergrundmusik und Sound-Design
- **duration**: Ziel-Videolänge in Sekunden
- **platform**: Zielplattform (LinkedIn, YouTube, Website, etc.)
- **branding**: Coherent-Corporate-Identity-Elemente
- **text_overlays**: Einblendungen von Text oder Zahlen
- **transitions**: Übergänge zwischen Szenen
```

---

## 4. 20 Praxisbeispiele für Coherent Marketing

Hier sind 20 fertige JSON-Skripte für typische Marketing-Anforderungen bei Coherent. Sie können diese direkt verwenden oder als Inspiration für eigene Ideen nutzen.

### Kategorie: Produkt- & Lösungsmarketing

**1. Neuer Faserlaser für die Industrie (LinkedIn, 15s)**
*Anleitung: Dieses Skript erzeugt ein kurzes, dynamisches Video, das die Präzision und Geschwindigkeit eines neuen Faserlasers zeigt. Ideal für eine Produktankündigung auf LinkedIn.* 
```json
{
  "camera_setup": "Dynamische Makro-Aufnahmen, schnelle Schnitte, Fokus auf den Laserstrahl",
  "subject": "Ein neuer Coherent Faserlaser bei der Bearbeitung von Metall",
  "action": "Der Laserstrahl schneidet mit extremer Präzision komplexe Muster in eine Metallplatte. Funken sprühen. Nahaufnahme der sauberen Schnittkante.",
  "dialogue": {
    "speech": "Präzision neu definiert. Der neue HyperCut Faserlaser von Coherent. Für anspruchsvollste Industrieanwendungen.",
    "voice_style": "Kräftig, professionell, dynamisch"
  },
  "setting": "Modernes, sauberes Produktionsumfeld, High-Tech-Atmosphäre",
  "audio": {
    "music": "Energetische, elektronische Musik mit prägnantem Beat",
    "effects": "Zischen des Lasers, metallische Sounds"
  },
  "duration": 15,
  "platform": "LinkedIn",
  "branding": {
    "colors": "Coherent-Blau und -Grün in Lichtreflexen",
    "logo": "Coherent-Logo am Ende"
  },
  "text_overlays": [
    "Höchste Präzision",
    "Maximale Geschwindigkeit",
    "HyperCut Faserlaser"
  ]
}
```

**2. Optische Komponenten für die Forschung (YouTube, 30s)**
*Anleitung: Ein ruhigeres, detailliertes Video, das die Qualität und Vielfalt von Coherent-Optiken für Forschungslabore hervorhebt. Gut für eine Zielgruppe von Wissenschaftlern.* 
```json
{
  "camera_setup": "Langsame Kamerafahrten über eine Auswahl an Linsen, Spiegeln und Filtern. Gestochen scharfe Nahaufnahmen.",
  "subject": "Hochpräzise optische Komponenten von Coherent",
  "action": "Ein Laserstrahl wird durch verschiedene Linsen gebrochen und fokussiert. Ein Wissenschaftler justiert eine Optik in einem komplexen Versuchsaufbau.",
  "dialogue": {
    "speech": "Jedes Photon zählt. Mit den hochreinen Optiken von Coherent erreichen Sie maximale Präzision für Ihre Forschung. Vom Standard bis zur Sonderanfertigung.",
    "voice_style": "Ruhig, sachlich, wissenschaftlich"
  },
  "setting": "Ein aufgeräumtes, modernes Forschungslabor",
  "audio": {
    "music": "Minimale, sphärische Hintergrundmusik",
    "effects": "Leises Klicken beim Justieren der Optiken"
  },
  "duration": 30,
  "platform": "YouTube",
  "branding": {
    "logo": "Coherent-Logo dezent eingeblendet"
  },
  "text_overlays": [
    "99.9% Reinheit",
    "Kundenspezifische Beschichtungen",
    "Für bahnbrechende Forschung"
  ]
}
```

**3. Lösung für die Halbleiterfertigung (Website, 20s)**
*Anleitung: Dieses Skript visualisiert eine komplexe Anwendung – die Wafer-Markierung – und positioniert Coherent als Experten in der Halbleiterindustrie.* 
```json
{
  "camera_setup": "Makro-Zoom auf einen Silizium-Wafer, Top-Down-Ansicht",
  "subject": "Ein UV-Laser von Coherent bei der Wafer-Markierung",
  "action": "Ein ultrafeiner Laserstrahl graviert blitzschnell eine Seriennummer auf einen Wafer. Die Kamera zoomt heraus und zeigt den automatisierten Prozess in einer Reinraum-Umgebung.",
  "dialogue": {
    "speech": "Wenn jeder Mikrometer entscheidet. Coherent-Lasersysteme für die Halbleiterfertigung. Präzise. Schnell. Zuverlässig.",
    "voice_style": "Prägnant, technisch, selbstbewusst"
  },
  "setting": "Hochmoderner Reinraum mit gelbem Licht",
  "audio": {
    "music": "Technischer, rhythmischer Soundteppich",
    "effects": "Hochfrequentes Sirren des Lasers"
  },
  "duration": 20,
  "platform": "Website",
  "branding": {
    "logo": "Coherent-Logo am Ende"
  },
  "text_overlays": [
    "Mikro-Markierung",
    "Für die Halbleiterindustrie"
  ]
}
```

**4. Medizintechnik-Anwendung (Messe-Video, 45s)**
*Anleitung: Ein emotionaleres Video, das den Nutzen der Coherent-Technologie für den Menschen in den Vordergrund stellt. Ideal für Messen, um Aufmerksamkeit zu erregen.* 
```json
{
  "camera_setup": "Weiche, fließende Übergänge. Nahaufnahmen von medizinischen Instrumenten und einem lächelnden Arzt.",
  "subject": "Coherent-Laser bei der Herstellung von medizinischen Implantaten",
  "action": "Ein Präzisionslaser schneidet ein filigranes Stent-Gitter. Schnitt zu einem Arzt, der ein medizinisches Gerät in der Hand hält. Schnitt zu einem Patienten, der nach einer erfolgreichen OP lächelt.",
  "dialogue": {
    "speech": "Technologie, die Leben verändert. Coherent-Laser ermöglichen die Herstellung hochpräziser medizinischer Komponenten, auf die sich Ärzte und Patienten weltweit verlassen.",
    "voice_style": "Warm, vertrauensvoll, menschlich"
  },
  "setting": "Eine Mischung aus High-Tech-Produktion und steriler, heller Klinik-Atmosphäre",
  "audio": {
    "music": "Inspirierende, orchestrale Musik",
    "effects": "Herzschlag-Sound am Anfang und Ende"
  },
  "duration": 45,
  "platform": "Messe",
  "branding": {
    "logo": "Coherent-Logo mit dem Slogan 'Innovations that Resonate'"
  },
  "text_overlays": [
    "Präzision für die Medizintechnik",
    "Vertrauen durch Qualität"
  ]
}
```

**5. CO2-Laser für die Verpackungsindustrie (YouTube, 25s)**
*Anleitung: Ein praktisches, anwendungsorientiertes Video, das die Effizienz von CO2-Lasern für einen bestimmten Industriezweig demonstriert.* 
```json
{
  "camera_setup": "Dynamische Verfolgung von Produkten auf einem Förderband",
  "subject": "Ein Coherent CO2-Laser beim Perforieren von Verpackungsfolie",
  "action": "Ein Laserstrahl perforiert präzise eine Kunststofffolie auf einer schnell laufenden Verpackungsanlage. Die Perforation ist kaum sichtbar, aber funktional.",
  "dialogue": {
    "speech": "Schneller, sauberer, effizienter. Coherent CO2-Laser optimieren Ihre Verpackungsprozesse. Für perfekte Ergebnisse bei maximalem Durchsatz.",
    "voice_style": "Sachlich, informativ, überzeugend"
  },
  "setting": "Eine belebte, moderne Lebensmittel-Verpackungsanlage",
  "audio": {
    "music": "Flotter, rhythmischer Corporate-Track",
    "effects": "Geräusche der Verpackungsanlage"
  },
  "duration": 25,
  "platform": "YouTube",
  "branding": {
    "logo": "Coherent-Logo am Ende"
  },
  "text_overlays": [
    "Easy-Open-Perforation",
    "Für die Verpackungsindustrie"
  ]
}
```

### Kategorie: Marken- & Image-Videos

**6. Innovations-Video "Zukunft gestalten" (Website-Header, 20s)**
*Anleitung: Ein abstraktes, inspirierendes Video, das die Innovationskraft von Coherent zeigt, ohne ein spezifisches Produkt zu bewerben. Perfekt für die Startseite der Website.* 
```json
{
  "camera_setup": "Fließende, abstrakte Kamerafahrten durch digitale Lichtpartikel und organische Formen",
  "subject": "Abstrakte Visualisierung von Licht und Innovation",
  "action": "Lichtstrahlen formen sich zu komplexen Strukturen, die an DNA-Stränge und neuronale Netze erinnern. Aus Lichtpartikeln entstehen die Umrisse von Coherent-Produkten.",
  "dialogue": {
    "speech": "(Kein Dialog, nur Musik und Text)",
    "voice_style": ""
  },
  "setting": "Ein dunkler, unendlicher Raum, der nur durch Licht erhellt wird",
  "audio": {
    "music": "Epische, sphärische Musik, die sich langsam aufbaut",
    "effects": "Synthetische Soundeffekte, die an Licht und Energie erinnern"
  },
  "duration": 20,
  "platform": "Website Header",
  "branding": {
    "colors": "Dominanz von Coherent-Blau und -Grün"
  },
  "text_overlays": [
    "Wir gestalten die Zukunft.",
    "Mit der Kraft des Lichts.",
    "Coherent. Innovations that Resonate."
  ]
}
```

**7. Nachhaltigkeits-Statement (Social Media, 15s)**
*Anleitung: Ein kurzes, emotionales Video, das Coherents Engagement für Nachhaltigkeit zeigt. Nutzt die Symbolik von Natur und Technik.* 
```json
{
  "camera_setup": "Weiche Übergänge zwischen Natur- und Technologieaufnahmen",
  "subject": "Verbindung von Natur und Photonik",
  "action": "Ein grünes Blatt wird von Sonnenlicht durchschienen. Schnitt zu einem Coherent-Laser, der energieeffizient arbeitet. Ein Windrad dreht sich. Schnitt zu einem Ingenieur, der an einer nachhaltigen Lösung arbeitet.",
  "dialogue": {
    "speech": "Innovation und Verantwortung. Wir entwickeln Photonik-Lösungen für eine nachhaltigere Zukunft.",
    "voice_style": "Ruhig, nachdenklich, aufrichtig"
  },
  "setting": "Eine Mischung aus unberührter Natur und sauberen Coherent-Laboren",
  "audio": {
    "music": "Sanfte Klaviermusik mit Naturgeräuschen (Wind, Vögel)",
    "effects": ""
  },
  "duration": 15,
  "platform": "LinkedIn",
  "branding": {
    "logo": "Coherent-Logo mit 'Green Photonics' Zusatz"
  },
  "text_overlays": [
    "Nachhaltigkeit durch Innovation"
  ]
}
```

**8. "Wir sind Coherent" - Team-Video (Recruiting, 30s)**
*Anleitung: Ein authentisches Video, das die Menschen hinter Coherent in den Mittelpunkt stellt. Ideal für Karriereseiten und Recruiting-Messen.* 
```json
{
  "camera_setup": "Dynamische, authentische Handkamera-Aufnahmen",
  "subject": "Diverse Mitarbeiter von Coherent bei der Arbeit und in Pausen",
  "action": "Montage von lächelnden Gesichtern: Ingenieure im Labor, Vertriebsmitarbeiter im Gespräch, Team-Meeting am Whiteboard, Kaffeepause in der Kantine. Kein gestelltes Lächeln, sondern echte Momente.",
  "dialogue": {
    "speech": "(Verschiedene Mitarbeiterstimmen im Off) 'Es ist die Herausforderung.' 'Die Zusammenarbeit.' 'Dass wir wirklich etwas bewegen.' 'Das ist Coherent.'",
    "voice_style": "Authentische, unterschiedliche Mitarbeiterstimmen"
  },
  "setting": "Verschiedene Bereiche des Coherent-Standorts",
  "audio": {
    "music": "Uplifting, moderner Indie-Pop-Song",
    "effects": "Lachen, Gesprächsfetzen"
  },
  "duration": 30,
  "platform": "Recruiting",
  "branding": {
    "logo": "Coherent Karriere-Logo"
  },
  "text_overlays": [
    "Werde Teil unseres Teams."
  ]
}
```

**9. Messe-Einladung (Social Media, 10s)**
*Anleitung: Ein kurzer, prägnanter Teaser, der Neugier weckt und zum Messebesuch einlädt. Der Fokus liegt auf einer klaren Call-to-Action.* 
```json
{
  "camera_setup": "Schnelle, rhythmische Schnitte auf Details eines neuen, verhüllten Produkts",
  "subject": "Ankündigung eines neuen Produkts auf der Messe",
  "action": "Ein Tuch wird langsam von einem neuen Lasersystem gezogen, aber man sieht nur glänzende Details. Lichtblitze. Schnitte auf das Messe-Logo (z.B. LASER World of PHOTONICS).",
  "dialogue": {
    "speech": "Erleben Sie die nächste Generation der Lasertechnologie.",
    "voice_style": "Geheimnisvoll, spannend"
  },
  "setting": "Ein dunkler Showroom",
  "audio": {
    "music": "Spannungsgeladener, elektronischer Track mit einem Crescendo",
    "effects": "Herzschlag-Sound"
  },
  "duration": 10,
  "platform": "LinkedIn",
  "branding": {
    "logo": "Coherent-Logo"
  },
  "text_overlays": [
    "LASER World of PHOTONICS",
    "Halle A2, Stand 103",
    "Besuchen Sie uns!"
  ]
}
```

**10. "Behind the Scenes" - F&E (YouTube, 60s)**
*Anleitung: Ein längeres Format, das Einblicke in die Forschungs- und Entwicklungsarbeit gibt und die technische Kompetenz von Coherent unterstreicht.* 
```json
{
  "camera_setup": "Dokumentarischer Stil, Interviews mit Ingenieuren",
  "subject": "Die Entwicklung einer neuen optischen Beschichtung",
  "action": "Ein leitender Wissenschaftler erklärt am Whiteboard eine komplexe Formel. Nahaufnahmen von Beschichtungsprozessen im Vakuum. Ein Team analysiert Messergebnisse am Computer.",
  "dialogue": {
    "speech": "Der Weg zu einer neuen Technologie ist ein Marathon, kein Sprint. Es braucht Geduld, Präzision und ein Team, das eine gemeinsame Vision teilt. Hier bei Coherent verschieben wir die Grenzen des Möglichen.",
    "voice_style": "Authentische Stimme des leitenden Wissenschaftlers"
  },
  "setting": "F&E-Labore von Coherent",
  "audio": {
    "music": "Konzentrierte, minimalistische Hintergrundmusik",
    "effects": "Geräusche von Laborgeräten"
  },
  "duration": 60,
  "platform": "YouTube",
  "branding": {
    "logo": "Coherent R&D Logo"
  },
  "text_overlays": [
    "Einblick in unsere F&E",
    "Die Entstehung einer Innovation"
  ]
}
```

### Kategorie: Social Media & Content Marketing

**11. Technischer Quick-Tipp (Instagram Reels, 15s)**
*Anleitung: Ein schnelles, nützliches Video im Hochformat, das einen einfachen technischen Tipp gibt. Positioniert Coherent als Experten und ist leicht teilbar.* 
```json
{
  "camera_setup": "Direkte, persönliche Ansprache in die Kamera, Hochformat (9:16)",
  "subject": "Ein Coherent-Applikationsingenieur",
  "action": "Der Ingenieur hält eine optische Linse in die Kamera und zeigt mit einem Handschuh auf eine winzige Verunreinigung. Er reinigt sie mit einem speziellen Tuch.",
  "dialogue": {
    "speech": "Quick-Tipp: Reinigen Sie Ihre Optiken immer von der Mitte nach außen, um Kratzer zu vermeiden! #Photonics #Laser #TechTip",
    "voice_style": "Freundlich, kompetent, direkt"
  },
  "setting": "Ein gut beleuchtetes Labor",
  "audio": {
    "music": "Trendiger, kurzer Sound von Instagram Reels",
    "effects": ""
  },
  "duration": 15,
  "platform": "Instagram Reels",
  "branding": {
    "logo": "Kleines Coherent-Logo in der Ecke"
  },
  "text_overlays": [
    "Optik-Reinigungstipp"
  ]
}
```

**12. "Wussten Sie schon?" - Fakt des Tages (LinkedIn, 10s)**
*Anleitung: Ein animiertes Text-Video, das einen überraschenden Fakt aus der Welt der Photonik präsentiert. Einfach zu produzieren und gut für Engagement.* 
```json
{
  "camera_setup": "Keine Kamera, reines Motion-Graphics-Video",
  "subject": "Animierter Text und Grafiken",
  "action": "Der Text 'Wussten Sie schon?' erscheint. Dann: 'Ein einzelner Faserlaser kann Stahl schneiden, der dicker ist als eine Eisenbahnschiene.' Eine animierte Grafik zeigt einen Laser, der eine Schiene durchtrennt.",
  "dialogue": {
    "speech": "(Kein Dialog)",
    "voice_style": ""
  },
  "setting": "Digitaler Raum mit Coherent-Branding",
  "audio": {
    "music": "Kurzer, aufmerksamkeitsstarker Sound-Effekt",
    "effects": "Laser-Sound"
  },
  "duration": 10,
  "platform": "LinkedIn",
  "branding": {
    "colors": "Coherent-Blau und -Grün"
  },
  "text_overlays": [
    "Wussten Sie schon?",
    "Photonik-Fakten"
  ]
}
```

**13. Zeitraffer-Video einer Lasergravur (Instagram, 20s)**
*Anleitung: Ein visuell befriedigendes Zeitraffer-Video, das sich gut für Social Media eignet. Es zeigt die Leistungsfähigkeit der Coherent-Technologie auf unterhaltsame Weise.* 
```json
{
  "camera_setup": "Feste Top-Down-Kamera, Zeitraffer",
  "subject": "Eine Lasergravur auf einem Holzstück",
  "action": "Ein Laser graviert in hoher Geschwindigkeit das Coherent-Logo oder ein komplexes Muster in ein Stück Holz. Rauch steigt auf und wird abgesaugt.",
  "dialogue": {
    "speech": "(Kein Dialog)",
    "voice_style": ""
  },
  "setting": "Eine Werkstatt oder ein Maker-Space",
  "audio": {
    "music": "Befriedigender, rhythmischer Lo-Fi-Beat",
    "effects": "Beschleunigtes Geräusch der Lasergravur"
  },
  "duration": 20,
  "platform": "Instagram",
  "branding": {
    "logo": "Das gravierte Logo ist das Branding"
  },
  "text_overlays": [
    "Präzision in Aktion."
  ]
}
```

**14. Webinar-Ankündigung (LinkedIn, 15s)**
*Anleitung: Ein animiertes Video, das die wichtigsten Informationen zu einem bevorstehenden Webinar zusammenfasst und zur Anmeldung aufruft.* 
```json
{
  "camera_setup": "Motion Graphics, animierte Texte und Icons",
  "subject": "Ankündigung eines Webinars",
  "action": "Der Titel des Webinars erscheint. Ein animiertes Porträt des Sprechers wird eingeblendet. Die wichtigsten Themen erscheinen als Bullet-Points. Am Ende ein 'Jetzt anmelden'-Button.",
  "dialogue": {
    "speech": "Nehmen Sie an unserem Webinar teil: 'Die Zukunft der Batteriefertigung mit Lasern'. Mit unserem Experten Dr. Eva Schmidt. Melden Sie sich jetzt an!",
    "voice_style": "Professionell, einladend"
  },
  "setting": "Digitaler Raum im Coherent-Design",
  "audio": {
    "music": "Positive, professionelle Corporate-Musik",
    "effects": "Sanfte Klick-Sounds bei Texteinblendungen"
  },
  "duration": 15,
  "platform": "LinkedIn",
  "branding": {
    "logo": "Coherent-Logo"
  },
  "text_overlays": [
    "Webinar",
    "18. November 2025",
    "Jetzt anmelden!"
  ]
}
```

**15. Kunden-Testimonial (Website, 40s)**
*Anleitung: Ein authentisches Testimonial-Video, das einen zufriedenen Kunden zeigt. Baut Vertrauen und Glaubwürdigkeit auf.* 
```json
{
  "camera_setup": "Interview-Stil, ruhige Kamera, Nahaufnahme des Kunden",
  "subject": "Ein Produktionsleiter eines Kundenunternehmens",
  "action": "Der Kunde spricht direkt in die Kamera. Zwischenschnitte zeigen das Coherent-Lasersystem im Einsatz in seiner Fabrik.",
  "dialogue": {
    "speech": "Seit wir die Lasersysteme von Coherent einsetzen, hat sich unsere Ausschussrate halbiert und die Produktionsgeschwindigkeit um 30% erhöht. Die Zusammenarbeit war von Anfang an partnerschaftlich und lösungsorientiert.",
    "voice_style": "Authentisch, überzeugt, nicht geskriptet"
  },
  "setting": "Das Büro des Kunden, mit Blick auf die Produktionshalle",
  "audio": {
    "music": "Dezente, vertrauensbildende Hintergrundmusik",
    "effects": ""
  },
  "duration": 40,
  "platform": "Website",
  "branding": {
    "logo": "Logo des Kunden (mit Erlaubnis) und Coherent-Logo"
  },
  "text_overlays": [
    "Kundenstimme",
    "'Ausschussrate halbiert'"
  ]
}
```

### Kategorie: Interne Kommunikation & HR

**16. Sicherheits-Hinweis (Intern, 20s)**
*Anleitung: Ein kurzes, klares Video, das auf wichtige Sicherheitsregeln im Labor aufmerksam macht. Visuell und leicht verständlich.* 
```json
{
  "camera_setup": "Klare, statische Aufnahmen",
  "subject": "Sicherheitsausrüstung im Labor",
  "action": "Eine Person setzt korrekt eine Laserschutzbrille auf. Nahaufnahme eines 'Laser in Betrieb'-Warnschilds. Eine Hand drückt einen Not-Aus-Knopf.",
  "dialogue": {
    "speech": "Sicherheit zuerst! Trage immer deine persönliche Schutzausrüstung. Beachte die Warnhinweise. Deine Gesundheit ist das Wichtigste.",
    "voice_style": "Freundlich, aber bestimmt"
  },
  "setting": "Coherent-Labor",
  "audio": {
    "music": "Neutrale, unaufdringliche Musik",
    "effects": "Klick-Geräusch beim Aufsetzen der Brille"
  },
  "duration": 20,
  "platform": "Intranet",
  "branding": {
    "logo": "Coherent Safety First Logo"
  },
  "text_overlays": [
    "Sicherheit zuerst!"
  ]
}
```

**17. Vorstellung eines neuen Mitarbeiters (Intern, 25s)**
*Anleitung: Ein sympathisches Video, um einen neuen Kollegen im Unternehmen willkommen zu heißen. Fördert die interne Vernetzung.* 
```json
{
  "camera_setup": "Locker, leicht mit Handkamera gefilmt",
  "subject": "Ein neuer Mitarbeiter, der sich vorstellt",
  "action": "Der neue Mitarbeiter winkt in die Kamera, sitzt an seinem neuen Schreibtisch und spricht mit Kollegen. Kurze Einblendungen seiner Hobbys (z.B. Wandern, Fotografie).",
  "dialogue": {
    "speech": "Hallo zusammen! Ich bin Alex, der neue Applikationsingenieur im Team. Ich freue mich riesig, hier zu sein und euch alle kennenzulernen. Sprecht mich gerne an!",
    "voice_style": "Authentisch, freundlich, offen"
  },
  "setting": "Büro- und Laborumgebung bei Coherent",
  "audio": {
    "music": "Fröhliche, positive Akustik-Gitarren-Musik",
    "effects": ""
  },
  "duration": 25,
  "platform": "Intranet",
  "branding": {
    "logo": ""
  },
  "text_overlays": [
    "Willkommen im Team, Alex!"
  ]
}
```

**18. Einladung zum Sommerfest (Intern, 15s)**
*Anleitung: Ein lockeres, fröhliches Video, das Vorfreude auf ein Firmenevent weckt.* 
```json
{
  "camera_setup": "Schnelle, lustige Schnitte von vergangenen Firmenevents",
  "subject": "Mitarbeiter von Coherent feiern",
  "action": "Zeitraffer vom Aufbau eines Grillfestes. Mitarbeiter lachen, spielen Tischtennis, stoßen an. Drohnenaufnahme des Festgeländes.",
  "dialogue": {
    "speech": "Es ist wieder soweit! Unser jährliches Sommerfest steht vor der Tür. Seid dabei für gutes Essen, tolle Gespräche und eine Menge Spaß!",
    "voice_style": "Enthusiastisch, fröhlich"
  },
  "setting": "Ein sonniger Park oder Firmengelände",
  "audio": {
    "music": "Sommerlicher Pop-Song",
    "effects": "Lachen, Jubel"
  },
  "duration": 15,
  "platform": "Intranet",
  "branding": {
    "logo": ""
  },
  "text_overlays": [
    "Coherent Sommerfest",
    "18. Juli",
    "Save the Date!"
  ]
}
```

**19. IT-Sicherheitstipp für Mitarbeiter (Intern, 20s)**
*Anleitung: Ein animiertes Erklärvideo, das auf eine häufige Sicherheitslücke (z.B. Phishing) aufmerksam macht.* 
```json
{
  "camera_setup": "2D-Animation",
  "subject": "Ein animierter Charakter, der eine E-Mail erhält",
  "action": "Ein Mitarbeiter-Charakter erhält eine verdächtige E-Mail mit einem Link. Er zögert und meldet die E-Mail dann über einen 'Phishing melden'-Button, anstatt zu klicken. Ein grüner Haken erscheint.",
  "dialogue": {
    "speech": "Zweimal überlegen, einmal klicken. Verdächtige E-Mail erhalten? Melde sie an die IT-Sicherheit. Gemeinsam schützen wir Coherent.",
    "voice_style": "Klar, informativ, nicht belehrend"
  },
  "setting": "Animierte Büroumgebung",
  "audio": {
    "music": "Neutrale Erklärvideo-Musik",
    "effects": "Alarm-Sound bei der verdächtigen E-Mail"
  },
  "duration": 20,
  "platform": "Intranet",
  "branding": {
    "logo": "Coherent IT Security Logo"
  },
  "text_overlays": [
    "Vorsicht Phishing!"
  ]
}
```

**20. CEO-Botschaft zum Jahresende (Intern, 60s)**
*Anleitung: Eine persönliche und wertschätzende Botschaft des CEOs an die Mitarbeiter. Wichtig ist eine authentische und direkte Ansprache.* 
```json
{
  "camera_setup": "Ruhige, statische Kamera, CEO spricht direkt in die Kamera",
  "subject": "Der CEO von Coherent",
  "action": "Der CEO sitzt in seinem Büro oder steht in einem Labor. Er spricht authentisch und frei. Zwischenschnitte zeigen Erfolgsmomente des Jahres (Produktlaunches, Team-Events).",
  "dialogue": {
    "speech": "Liebe Mitarbeiterinnen und Mitarbeiter, ein erfolgreiches Jahr liegt hinter uns. Das ist Ihr Verdienst. Ihr Engagement, Ihre Innovationskraft und Ihr Teamgeist machen Coherent aus. Ich möchte von Herzen Danke sagen und wünsche Ihnen und Ihren Familien eine erholsame Weihnachtszeit und einen guten Start ins neue Jahr.",
    "voice_style": "Persönlich, wertschätzend, authentisch"
  },
  "setting": "Ein repräsentatives, aber nicht zu distanziertes Büro",
  "audio": {
    "music": "Leise, emotionale Klaviermusik im Hintergrund",
    "effects": ""
  },
  "duration": 60,
  "platform": "Intranet",
  "branding": {
    "logo": "Coherent-Logo am Ende"
  },
  "text_overlays": [
    "Danke für ein großartiges Jahr!"
  ]
}
```

---

## 5. Wichtige Hinweise für Coherent

- **Markenkonsistenz:** Achten Sie darauf, dass der visuelle Stil und die Tonalität immer zur Coherent-Marke passen (innovativ, präzise, vertrauenswürdig).
- **Datenschutz:** Geben Sie niemals vertrauliche Informationen (Kundendaten, F&E-Details) in externe KI-Tools ein.
- **Qualitätskontrolle:** Jedes KI-generierte Video muss vor der Veröffentlichung von einem Menschen geprüft und freigegeben werden.
- **Rechte:** Klären Sie die Nutzungsrechte für Musik, Stimmen und Bildmaterial, das von der KI generiert wird.

Mit diesen Beispielen und Anleitungen sind Sie bestens gerüstet, um professionelle und ansprechende Videos für Coherent zu erstellen. Viel Erfolg!


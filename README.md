
# 🛡️ Anti-Grooming-System für Minecraft-Netzwerke
![wakatime](https://wakatime.com/badge/user/21ab4ec4-0bff-4728-8b18-7e38dfe33309/project/410a70a4-7497-4c0c-a4ec-8bb12bef69b6.svg)

Ein intelligentes, datenschutzkonformes Sicherheitssystem für Minecraft-Server, das Grooming und unangemessene Kommunikation erkennt – mit Unterstützung durch Künstliche Intelligenz und menschliche Moderation.

---

## 📌 Inhaltsverzeichnis

1. [Überblick](#überblick)
2. [Warum ein Anti-Grooming-System?](#warum-ein-anti-grooming-system)
3. [Funktionsweise](#funktionsweise)
4. [Datenschutz & DSGVO](#datenschutz--dsgvo)
5. [Ablauf der Analyse](#ablauf-der-analyse)
6. [Integration in bestehende Systeme](#integration-in-bestehende-systeme)
7. [GlobalTeam – kollektive Moderation](#globalteam--kollektive-moderation)
8. [Unterstützung weiterer Spiele](#unterstützung-weiterer-spiele)
9. [Preismodell](#preismodell)
10. [Langfristiges Ziel](#langfristiges-ziel)

---

## 🧠 Überblick

Dieses Anti-Grooming-System schützt Minecraft-Spieler – insbesondere Kinder – vor gefährlichen, manipulativen Kontakten. Es kombiniert automatische Sprachanalyse mit menschlicher Nachkontrolle und wahrt dabei die Privatsphäre der Spieler.

---

## ❗ Warum ein Anti-Grooming-System?

- **Grooming ist eine reale Gefahr** in Online-Games – insbesondere für Minderjährige.
- **Private Nachrichten** sind oft unkontrolliert – genau dort setzt das System an.
- **Minecraft** ist eines der meistgenutzten Spiele von Kindern weltweit – Schutz ist essenziell.

---

## ⚙️ Funktionsweise

### 1. KI-gestützte Analyse

- Erkennung kontextueller Risiken durch ein Sprachmodell (LLM)
- Keine simplen Keyword-Filter – echtes Sprachverständnis
- Laufendes Training zur Erkennung neuer Muster

### 2. Datenschutzkonform

- Keine Namen, IPs oder personenbezogenen Daten werden übertragen
- Nur der Nachrichtentext wird anonym analysiert
- Vollständig DSGVO-konform

### 3. Menschliche Nachkontrolle

- **Kein Auto-Bann-System**
- Auffällige Nachrichten werden **manuell von Moderatoren geprüft**
- Falschmeldungen werden vermieden

### 4. Nahtloser Spielverlauf

- Analyse im Hintergrund in Echtzeit (nur wenige Millisekunden)
- Kein Lag, keine Störung des Chatflusses
- Eingriff nur bei tatsächlicher Gefahr

---

## 🔐 Datenschutz & DSGVO

- Analyse erfolgt **ausschließlich anonymisiert**
- Spieler erhalten **Transparenz beim Serverbeitritt**
- **Volle Datenhoheit** bleibt beim Serverbetreiber
- Keine dauerhafte Speicherung von Nachrichten

---

## 🔄 Ablauf der Analyse

```text
1. Spieler sendet Nachricht (nicht sofort öffentlich sichtbar)
2. Nachricht wird an KI weitergeleitet
3. KI analysiert anonymisiert auf potenziell gefährliche Inhalte
4. Ergebnis:
   - Unbedenklich → Nachricht wird angezeigt
   - Verdächtig → Moderation prüft, ggf. blockiert oder warnt
5. Feedback der Moderation fließt zurück ins Modell
```

---

## 🧩 Integration in bestehende Systeme

- Kompatibel mit:
  - Rangsystemen
  - Chatformattern
  - Bann-/Warnsystemen
- Geringe Serverbelastung (nur wenige kB Daten pro Nachricht)
- Extrem einfache Integration via Plugin (Bukkit/Spigot/BungeeCord)

---

## 🌍 GlobalTeam – kollektive Moderation

- Freiwilliger Zusammenschluss mehrerer Server
- Gemeinsame Bewertung anonymisierter Chatbeispiele
- Verbesserte Modellausbildung durch **Schwarmintelligenz**
- Stärkeres, robusteres Modell – für alle Teilnehmer

---

## 🎮 Unterstützung weiterer Spiele

- System ist modular aufgebaut – nicht nur auf Minecraft beschränkt
- Entwickler können das System in eigene Spiele integrieren
- API & SDK für flexible Anpassung verfügbar

---

## 💸 Preismodell

| Version        | Funktionen                                             | Preis         |
|----------------|--------------------------------------------------------|---------------|
| **Free**       | Basis-Schutz, KI-Analyse, DSGVO-konform, ein Teamchannel, 5.000 Nachrichten frei, 150 Abfragen pro Minute, Logfile anlegen, nur volle Updates               | Kostenlos     |
| **Tier I**    | Basis-Schutz, KI-Analyse, DSGVO-konform, 3 Teamchannel, 25.000 Nachrichten frei, 200 Abfragen pro Minute, Logfile anlegen, DEV BETA und SNAPSHOT Updates  | ,- €       |
| **Tier II**    |  Basis-Schutz, KI-Analyse, DSGVO-konform, 5 Teamchannel, 60.000 Nachrichten frei, 500 Abfragen pro Minute, Logfile anlegen, DEV BETA und SNAPSHOT Updates  | ,- €        |
| **Tier III**    |  Basis-Schutz, KI-Analyse, DSGVO-konform, unbegrenzte Teamchannel, unlimeted Nachrichten frei, 1000 Abfragen pro Minute, Logfile anlegen, DEV BETA und SNAPSHOT Updates  | ,- €        |

> Ziel: Auch kleine Server sollen sich bestmöglichen Schutz leisten können.

---

## 🎯 Langfristiges Ziel

Ein sich selbst verbesserndes Sicherheitssystem, das:

- Grooming frühzeitig erkennt
- Falschmeldungen reduziert
- Auch zukünftige Bedrohungen adaptiv erkennt

---

## 📣 Fazit

Dieses System schützt junge Spieler zuverlässig – ohne sie zu überwachen oder den Spielspaß zu stören.  
**Sicherheit durch KI – mit Respekt für Privatsphäre.**

---

## 📞 Kontakt & Mitwirkung

Interessiert an einer Integration oder Partnerschaft?  
Melde dich per [E-Mail/Discord/Website] – wir unterstützen dich gern!

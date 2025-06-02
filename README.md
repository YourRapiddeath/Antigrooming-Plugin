# 🛡️ Anti-Grooming-System für Minecraft-Netzwerke

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

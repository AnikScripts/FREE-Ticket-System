# 🎫 Discord Ticket System by Anik Bothosting

Ein leistungsstarkes Discord Ticket-System mit verschiedenen Ticket-Kategorien und umfangreichen Funktionen.

## ✨ Features

- 📝 Verschiedene Ticket-Kategorien:
  - Support Tickets
  - Team-Bewerbungen
  - Team-Beschwerden
  - Fraktions-Tickets
  - Event-Tickets
  - Content-Tickets
  - Projektleitungs-Tickets

- 🛠️ Funktionen:
  - Ticket-Erstellung per Dropdown-Menü
  - Ticket-Verwaltung (Beanspruchen, Schließen, Löschen)
  - Transcript-Erstellung
  - Ticket-Logs
  - Benutzer hinzufügen/entfernen
  - Ticket umbenennen
  - Administrator-Befehle

## 📋 Voraussetzungen

- Node.js (Version 16.x oder höher)
- Discord Bot Token
- Discord Server mit entsprechenden Berechtigungen

## 🚀 Installation

1. Repository klonen oder herunterladen
2. Erforderliche Pakete installieren:
```bash
npm install
```

## ⚙️ Konfiguration

1. Öffne die `config.js` Datei
2. Fülle folgende Informationen aus:
   - Bot Token
   - Client ID
   - Guild ID
   - Webhook URLs
   - Kategorie IDs
   - Rollen IDs

Beispiel:
```javascript
Config.General = {
    ['Token']: 'DEIN_BOT_TOKEN',
    ['ClientId']: 'DEINE_CLIENT_ID',
    ['GuildId']: 'DEINE_GUILD_ID',
    ['JSON']: './jsons/ticket-data.json',
};
```

## 🎨 Anpassung

- Passe die Embed-Farben in der `config.js` an
- Ändere die Nachrichten und Beschreibungen
- Füge eigene Bilder und Icons hinzu
- Passe die Ticket-Kategorien nach Bedarf an

## 🚀 Start des Bots

1. Starte den Bot mit der start.bat oder:
```bash
node index.js
```

## 📜 Befehle

- `/ticketpanel` - Erstellt das Ticket-Panel
- `/add` - Fügt einen Benutzer zum Ticket hinzu
- `/rename` - Benennt ein Ticket um
- `/closealltickets` - Schließt alle offenen Tickets
- `/deletetickets` - Löscht geschlossene Tickets

## 🔐 Berechtigungen

Folgende Berechtigungen werden für die verschiedenen Befehle benötigt:
- `Administrator` - Für Systembefehle
- `ManageMessages` - Für Ticket-Verwaltung

## 📞 Support

Bei Fragen oder Problemen können Sie:
- Ein Issue erstellen
- Den Support kontaktieren

## 📝 Lizenz

Dieser Bot wurde von Anik Bothosting entwickelt.
Alle Rechte vorbehalten.

---
Erstellt mit ❤️ von Anik Bothosting 

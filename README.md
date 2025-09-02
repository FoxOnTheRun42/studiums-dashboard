# studiums-dashboard

## Push-Leitfaden für main Branch

### 1. Repository klonen
```bash
git clone https://github.com/FoxOnTheRun42/studiums-dashboard.git
cd studiums-dashboard
```

### 2. Änderungen vornehmen
- Bearbeiten Sie Dateien nach Bedarf
- Fügen Sie neue Dateien hinzu

### 3. Änderungen zu Git hinzufügen
```bash
# Alle Änderungen hinzufügen
git add .

# Oder spezifische Dateien hinzufügen
git add dateiname.txt
```

### 4. Commit erstellen
```bash
git commit -m "Ihre Commit-Nachricht hier"
```

### 5. Zum main Branch pushen
```bash
git push origin main
```

### Zusätzliche nützliche Befehle

#### Status prüfen
```bash
git status
```

#### Änderungen anzeigen
```bash
git diff
```

#### Remote-Repository-Information anzeigen
```bash
git remote -v
```

#### Branch-Information anzeigen
```bash
git branch -a
```

### Fehlerbehebung

Wenn Sie Probleme beim Pushen haben:

1. **Prüfen Sie die Remote-URL:**
   ```bash
   git remote get-url origin
   ```

2. **Pull vor dem Push (falls erforderlich):**
   ```bash
   git pull origin main
   ```

3. **Authentifizierung prüfen:**
   - Stellen Sie sicher, dass Sie berechtigt sind, zu diesem Repository zu pushen
   - Verwenden Sie Personal Access Token für HTTPS

### Repository-Information
- **Owner:** FoxOnTheRun42
- **Repository:** studiums-dashboard
- **Main Branch:** main
- **Clone URL (HTTPS):** https://github.com/FoxOnTheRun42/studiums-dashboard.git
- **Clone URL (SSH):** git@github.com:FoxOnTheRun42/studiums-dashboard.git

---

*Dieser Leitfaden hilft Ihnen beim erfolgreichen Pushen zum main Branch dieses Repositories.*

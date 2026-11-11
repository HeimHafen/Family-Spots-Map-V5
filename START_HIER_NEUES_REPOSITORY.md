# 1× neu aufsetzen – Family Spots Map V5

**Repository:** `HeimHafen/Family-Spots-Map-V5`  
**Live-Adresse:** https://heimhafen.github.io/Family-Spots-Map-V5/  
**Quelle:** gesamtes ZIP, nicht acht oder dreizehn Austauschdateien  
**Änderungen am bisherigen Repository:** keine

1. In der alten App bei Bedarf zuerst „Mein Tag“ / persönliche Bilder und Favoriten exportieren.
2. GitHub → **New repository** → Name exakt `Family-Spots-Map-V5` → **Public** → ohne vorgeschlagene Startdateien erstellen.
3. ZIP auf dem iPhone öffnen → **Teilen → Working Copy** → **als neues Repository importieren** (die App unterstützt das ausdrücklich). Alternativ ZIP über die Dateien-App per Drag & Drop in die Repository-Übersicht von Working Copy ziehen. Alle Dateien müssen **auf der Root-Ebene**, ohne zusätzlichen Projektordner, liegen. Vor dem Push `index.html`, `.github/workflows/deploy.yml` und `data/spots.json` prüfen.
4. Working Copy: **neuen** Remote `git@github.com:HeimHafen/Family-Spots-Map-V5.git` verbinden, aktiver Branch `main`, Push `refs/heads/main` → `refs/heads/main`, **Force Push: Aus**. Nicht versehentlich auf `Family-Spots-Map-V4-Neu` pushen.
5. GitHub → neues Repository → Settings → Pages → Source **GitHub Actions**.
6. Bei noch nicht ausgelöstem Deployment: Actions → Family Spots Map V5 → Run workflow → main. Beim grünen Haken URL `https://heimhafen.github.io/Family-Spots-Map-V5/release-info.json` öffnen und die Commit-Version kontrollieren.
7. In Safari nur die **neue vollständige Adresse** öffnen. Alte Home-Screen-Verknüpfung nicht zur Versionsprüfung verwenden. Kein Browser-Speicher wird gelöscht.

**Commit-Zusammenfassung:** `FSM V5: vollständiger geprüfter Neustart mit automatischen Releases`  
**Detaillierte Informationen:** `173 Spots; DE/EN/DA; Filter, Tourenwelt, Mein Tag, Treffen & Spielen, Spots Plus; freigegebenes Premium-Design; neues scope-isoliertes Update-/Offline-System; GitHub Pages Actions mit automatischen SHA256-Prüfsummen und Live-Release-Nachweis.`  
**Source-Referenz:** `refs/heads/main`  
**Vorhandene oder neue Remote-Referenz:** `refs/heads/main`  
**Force Push:** `Aus`

**Achtung:** GitHub selbst übernimmt ein ZIP nicht automatisch als Repo. **Working Copy kann es als neues Repository importieren** (Herstellerdokumentation). Wenn das Teilen-Menü nicht funktioniert: ZIP in „Dateien“ speichern und über Drag & Drop in Working Copy importieren. Es ist **kein** Austausch im alten Repository.

## A–Z-Zusatzabnahme (11.11.2026)

**Für den neuen Import ausschließlich das ZIP `FSM_V5_AZ_REPOSITORY_20261111.zip` verwenden.** Keine vorherigen Zwischenstände kombinieren. Vor dem ersten Push den Bericht `00_A_BIS_Z_PRUEFBERICHT.md` und die verbindlichen Design-/Funktionsfreigaben lesen. Die App-Store-Einreichung bleibt ausdrücklich **nicht** freigegeben; dazu siehe `APP_STORE_FREIGABEMATRIX_20261111.md`. Alle vorherigen Repositories bleiben erhalten.

**Commit-Zusammenfassung:** `FSM V5: geprüfter A–Z-Neuaufbau mit Versions- und Assetprüfung`  
**Detaillierte Informationen:** `173 Spotdatensätze (172 eigenständige Orte), DE/EN/DA, Premium-Design unverändert, Tourenwelt, Mein Tag, Treffen & Spielen Pilot, Plus-Demo; geprüfte Bildmetadaten und Leaflet-Ressourcen; GitHub Actions mit synchronisiertem Release-Beleg; native iOS-Vorbereitung separat, App-Store-Freigabe offen.`  
**Source-Referenz:** `refs/heads/main`  
**Vorhandene oder neue Remote-Referenz:** `refs/heads/main`  
**Force Push:** `Aus`

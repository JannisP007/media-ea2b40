# Audio-Block (unlisted) — Forschungs-Pilot HTW Berlin

Statisch gehostete Entspannungs-Audios für eine EEG-Pilotstudie (Bachelorarbeit).
Zwei Bedingungen für ein Between-Subject-Design:

- `eg.html` → **EG** (`audio_eg.mp3`): hypnotherapeutisch fundierte Meditation mit
  4-7-8-Atmung (inhaltlich bereitgestellt von Dr. Frank Buckler), KI-Stimme (ElevenLabs).
- `kg.html` → **KG** (`audio_kg.mp3`): standardisierte, nicht-personalisierte Entspannung.
- `index.html` → neutrale Gruppenauswahl für die Versuchsleitung.

Jede Player-Seite protokolliert Audio-Onset/-Offset in `epoch_ms` (Wall-Clock) und lädt
am Ende eine Marker-CSV herunter → 1:1-Synchronisation mit dem EEG-Roh-Export.

**Hinweis:** „unlisted" = mit `robots.txt`/`noindex` von Suchmaschinen ausgenommen und
unter zufälligem Repo-Namen, aber technisch über die exakte URL erreichbar. **Nicht
weiterverbreiten.** Kein echter Zugriffsschutz (dafür wäre eine andere Hosting-Variante nötig).
Keine personenbezogenen Daten; die Marker-CSV entsteht lokal im Browser.

# Team-Building-Tag · IT-Abteilung Ärztekammer Wien

Eine eigenständige HTML-Seite für den Team-Building-Tag (17.09.2026): Ablauf, Live-Wetter,
Team-Auslosung, interaktive Karte, geteilte Foto-Cloud (Supabase) und ein paar Easter Eggs.

## Hosting via GitHub Pages
Diese `index.html` liegt in der Wurzel des Repos. In den Repo-Einstellungen unter
**Settings → Pages → Build and deployment → Source: „Deploy from a branch"**,
Branch `main` / Ordner `/root` auswählen. Die Seite ist danach unter
`https://<dein-user>.github.io/<repo-name>/` erreichbar.

## Foto-Cloud einrichten
Im `<script>`-Block `window.TBT_CLOUD` in der `index.html` die Supabase-Werte
(`url`, `anonKey`, `bucket`) eintragen. Ohne diese Werte läuft die Galerie im lokalen Modus.

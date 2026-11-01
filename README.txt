OPPSTILLINGSAPP – PWA (norsk)

1. Last opp hele mappen til en HTTPS-nettside (for eksempel GitHub Pages eller Netlify).
2. Åpne HTTPS-adressen på telefonen.
3. Android: Chrome > meny > Installer app.
4. iPhone: Safari > Del > Legg til på Hjem-skjerm.
5. Åpne appen én gang med internett for å lagre offline-filer.

Lokal testing: python3 -m http.server 8000 i denne mappen, deretter http://localhost:8000 på samme datamaskin.

Data lagres lokalt på hver enhet, ikke synkronisert mellom telefoner. Ta sikkerhetskopi via Logg og data.
Spilletid baseres på faktisk tid mellom hendelser, også ved skjermlås. Hvis appen lukkes mens settet går, fortsetter tiden å løpe fram til den åpnes igjen og stoppes.

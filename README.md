# Publika webbsidor

Integritetspolicy och supportsida som App Store kräver. Publiceras med GitHub Pages från det publika repot
`harochdar-web` (bara den här mappen, inte resten av koden).

| Fil | Innehåll |
| --- | --- |
| `index.html` | Startsida |
| `integritet.html` / `privacy.html` | Integritetspolicy sv/en – **länkas i App Store Connect och i appen** |
| `support.html` / `support-en.html` | Support sv/en – **länkas i App Store Connect** |

**Före lansering:**

- Ersätt `[FÖRETAGSNAMN]`, `[E-POST]`, `[DATUM]` (och engelska `[COMPANY NAME]`, `[EMAIL]`, `[DATE]`).
- Läs igenom policyn mot vad appen faktiskt gör (t.ex. om statistik med PostHog införs måste den läggas till).
- Låt någon i teamet eller UF-rådgivaren granska texten.

Publicera ändringar: `git subtree push --prefix web web main` från projektroten (se docs/drift.md).

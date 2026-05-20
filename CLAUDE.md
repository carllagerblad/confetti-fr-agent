# confetti-fr-agent

## Om projektet
Ett verktyg för Carl Lagerblad, Technical Support på Confetti (en eventplattform för att skapa eventsidor).

Verktyget analyserar feedback från användare — i första hand från Intercom, men även från andra kanaler — och identifierar feature requests automatiskt.

## Vad appen gör
1. Ta emot feedback (inklistrad text eller framtida Intercom-integration)
2. Analysera med Claude AI: sammanfatta feedbacken, identifiera vad som efterfrågas och vilket problem det löser
3. Jämföra med befintliga feature requests i databasen och slå ihop om det är ett duplikat
4. Skapa eller uppdatera ett ärende i appen
5. Visa nya ärenden i en nyhetsvy och alla ärenden i en listvy

## Planerat framöver (inte byggt än)
- Notion-integration för ärendehantering
- Slack-notiser när nya feature requests skapas
- Direktkoppling till Intercom via webhook

## Tech-stack
- Frontend: HTML, CSS och JavaScript (ingen React, inget byggsteg)
- Backend: Vercel serverless functions (i /api-mappen)
- Databas: Supabase
- AI: Claude API (Anthropic)
- Publicering: Vercel

## Design
- Stil: Proffsig och stram med inslag av retro-känsla
- Färger: #135029 (skogsgrönt), #e7d1ff (lavendel), mörk bakgrund #0a130d
- Typsnitt: Playfair Display (rubriker), EB Garamond (brödtext) — klassiska serifer
- Känsla: editorial, mörkt, strukturerat

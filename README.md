# binaural.reset

En liten binaural beat-generator som körs helt i webbläsaren. Ingen server, inget konto, ingen data skickas någonstans — allt ljud genereras lokalt med Web Audio API.

## Användning

Öppna sidan, välj ett band (Delta/Theta/Alpha/Beta/Gamma) i Enkelt läge, eller ställ in bärvåg och beat-frekvens manuellt i Avancerat läge. Lägg på vitt eller rosa brus om du vill, med valfri chorus/flanger-effekt. Ställ in en timer om du vill att sessionen ska fasa ut automatiskt.

**Kräver hörlurar.** Binaural beats bygger på att vänster och höger öra hör en något olika ton — via högtalare uppstår inte effekten på samma sätt.

## Tekniskt

Enda-fil HTML/CSS/JS, inga externa beroenden eller typsnitt. Ljudgrafen (oscillatorer, brusgenerering, filter, reverb, effekter) byggs och körs helt klientsidan med Web Audio API. Ingen `fetch`, ingen `localStorage`, inga cookies, ingen tracking.

## Licens

Fri att använda och ändra.

---

Byggd i samarbete med Claude (Anthropic) — kod granskad och justerad iterativt.

# Classic Snake

Ett minimalt Snake-spel byggt utan externa beroenden.

## Krav

- Node.js 24+ (eller annan modern Node-version med `node --test`)

## Kom igång

1. Öppna terminal i projektmappen.
2. Starta utvecklingsservern:
   - `npm run dev`
3. Öppna i webbläsaren:
   - `http://localhost:5173`

## Tester

- Kör logiktesterna:
  - `npm test`

## Kontroller

- Tangentbord: pil-tangenter eller `W/A/S/D`
- `Space`: pausa/fortsätt
- Knappar på sidan: Up/Left/Down/Right
- `Restart`: starta om spelet

## Manuell verifiering

- Snake rör sig ett steg per tick i vald riktning.
- Snake växer och poängen ökar när mat äts.
- Kollision med vägg ger game over.
- Kollision med egen kropp ger game over.
- Pause/Resume stoppar och återupptar spel-loopen.
- Restart nollställer spelstatus och poäng.

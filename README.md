# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.


# Mini-Projekt

## Beschreibung
Dies ist ein kleines Svelte-Projekt mit einer einfachen Navigationsleiste, einem Eingabefeld und einer dynamischen Anzeige des Benutzereingangs.

## Features
- Responsive Navigation mit Links
- Eingabefeld mit Live-Anzeige der Benutzereingabe
- Stilvolle und minimalistische Gestaltung mit `app.css`
- Barrierefreiheit durch Labels für das Eingabefeld

## Installation und Nutzung
1. Stelle sicher, dass Node.js und npm installiert sind.
2. Klone das Repository oder speichere die Dateien:

3. Installiere die Abhängigkeiten:
4. Starte das Projekt:
5. Öffne `http://localhost:5173/` in deinem Browser.

## Projektstruktur

## Anpassungen
Falls du das Styling anpassen möchtest, ändere einfach `app.css`. Für neue Funktionen bearbeite `App.svelte`.

## Lizenz
Dieses Projekt steht unter der MIT-Lizenz.

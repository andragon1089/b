# Brick — Laura Dannon Flashcards

A source-data pack containing all **47** flashcards for the *Brick* (2005) Laura Dannon exam essay.

## Files

- `data/flashcards.json` — portable JSON data, suitable for websites, apps, or databases.
- `src/flashcards.ts` — typed TypeScript export for a TypeScript/JavaScript project.

## Data shape

Each card has:
- `id`: stable numeric identifier within this deck
- `front`: question or recall prompt
- `back`: answer

## Use in a TypeScript project

```ts
import { flashcards } from "./src/flashcards";

console.log(flashcards[0].front);
console.log(flashcards[0].back);
```

## Add this folder to GitHub

1. Create a new repository on GitHub.
2. Unzip this folder.
3. Upload the `brick-laura-flashcards` folder contents to the repository, or run:

```bash
git init
git add .
git commit -m "Add Brick Laura Dannon flashcards"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with your own repository URL. These files are ready to commit; they have not been pushed to GitHub from this chat.

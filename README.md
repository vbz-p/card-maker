# Card Maker

Flashcards made from anything you read, built for studying for school tests.

## What's here

| File | What it is |
|---|---|
| `index.html` | **Study app.** No login. Flip cards, take multiple-choice quizzes, study by test topic, track progress. Decks and progress are saved on the device. Add it to a phone's home screen to use it like an app. |
| `card-maker.html` | **Card maker.** Turns pasted text, text files or photos of book pages into flashcards. It recognizes test overviews ("Inför provet", learning goals, practice questions) and builds the deck around those topics. Runs as a Claude artifact: making cards, saving to an account and the Shared tab need it to be opened inside Claude while signed in. |

## Getting a deck to the study app

- **Link:** in the card maker, open a deck and tap **Send as link**. The whole deck is inside the link (after `#d=`), so nothing is stored on a server. Opening it adds the deck to the study app. If tapping doesn't work, paste the link into the **Got a deck link?** box.
- **File:** tap **Save as file** and use **Import deck** in the study app.

Links point to `https://brittsjo.com/cards/` by default. Change it under "Study app address" in the card maker, or edit `DEFAULT_STUDY_URL` in the code.

## Hosting the study app

Upload `index.html` to any static host, for example a `cards/` folder on your website or GitHub Pages.

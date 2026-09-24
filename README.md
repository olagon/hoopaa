# Hoʻopaʻa

**Learn 1,000 Hawaiian words with stories you won't forget.**

Hoʻopaʻa (to memorize, to fasten, to study) is a free web app for learning 500 Hawaiian verbs and 500 Hawaiian nouns. Every word comes with a sound hook and a ridiculous story that acts out the meaning, so the word sticks. Each word you master lights a star on your own night sky.

**Try it:** https://olagon.github.io/hoopaa/

## How it works

- **Meet the word.** You see the word, how to say it, the meaning, the sound hook, the story and a "say it" action.
- **Get tested right away.** New words come back twice in the same session.
- **Spaced review.** Each right answer moves a word up a level and waits longer before asking again (10 minutes, 1 day, 3 days, 7 days, 16 days). Reach level 6 and the word is mastered. A miss drops it back and shows the story again.
- **Harder questions as you improve.** Pick the meaning, match the sound hook, pick the word from its meaning or its scene, then type it from memory. Buttons for ʻ ā ē ī ō ū are built in.
- **Your sky.** 1,000 stars laid out like a star compass. Stars brighten as you learn and turn gold when mastered. Tap any star to read its story.
- **Streaks, daily points goal, combos and milestones** to keep you coming back.

No signup and no server. Progress is saved in your browser. Use "Copy progress code" on the Progress screen to back it up or move it to another device.

## Files

- `index.html` is the whole app in one file, with the word list built in. Open it in any browser, or host it anywhere.
- `AUDIT.md` lists every correction made in the word audit.
- `hawaiian_1000_words.json` is the full word list as structured data: Hawaiian word, pronunciation, meaning, sound hook, story paragraphs, say-it action, bonus facts and a short scene summary for each word.

## A note on the words

There is no official frequency ranking of Hawaiian words, so the list is built from the everyday words beginners hear and use most. In September 2026 every word was audited against Pukui-Elbert (1986) and Māmaka Kaiao on Wehewehe Wikiwiki, with an independent second check. See `AUDIT.md` for every change. Hawaiian treats describing words (to be big, to be red) as verbs, so many of those sit in the verb list. The sound hooks are memory tricks, not perfect pronunciation. Check words against [wehewehe.org](https://wehewehe.org) and learn from native speakers. Corrections are welcome as issues or pull requests.

## License

The app code is released under the MIT License. The word list and stories are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See `LICENSE`.

## Credits

Made by [Olin Kealoha Lagon](https://olagon.github.io/), with [Claude](https://claude.ai) by Anthropic as a contributor. Olin set the direction and the style of the stories. Claude wrote the memory stories, built the app and ran the word audit against Pukui-Elbert and Māmaka Kaiao.

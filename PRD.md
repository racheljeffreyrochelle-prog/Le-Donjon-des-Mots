# PRD: Le Donjon des Mots (first release)

Oct 28, 2026 · @Rachel

## Summary

**Status: agreed on 28 October 2026. The changes below are built and live at racheljeffreyrochelle-prog.github.io/Le-Donjon-des-Mots.**

A short Undertale-style phone game. A 10-year-old falls from the garden into the Donjon des Mots and gets home by helping four monsters remember their words. The first release teaches the numbers 21–100 and keeps the phrases for home, places and weather fresh. All characters, names, art and music are original.

## User, situation and problem

**Primary user:** one 10-year-old with a French lesson once a week. They know 1–20 and the tens (20, 30 … 100), and can say where they live: town or village, near the sea, in the mountains, in the countryside.

**Situation:** plays alone, in 5–10 minute sittings, on their own phone or a parent's, at home or in the car. Siblings don't play.

**Problem:** they get almost no French practice between lessons, and drills feel like homework. Games are fun for them, so the game is what gets them practising.

**Topics:** numbers 21–100 (new), where I live, weather.

## Goals and success measures

The game succeeds if the child chooses to play it during the week and learns new numbers. The bar for "worth continuing" is a proposal you can still adjust.

| Measure | Bar for "worth continuing" | How we'd know |
| --- | --- | --- |
| Plays unprompted | At least twice in the trial week | You note each time they open it without a reminder |
| Learns new numbers | After score at least 3 higher than before, out of 8 | The same 8-number check before and after the week |
| Finishes alone | Reaches home without adult help | Saved progress, and asking them |
| Speaks aloud | Observed, no bar: this decides whether a microphone is worth adding | You watch one session for the "Répète !" lines |

## Main user journey

The whole game takes 1–2 sittings of 5–10 minutes, and progress is saved between them.

1. They fall from the garden into the Donjon des Mots.
2. They meet four monsters in turn. Every question is read aloud in French, with the French on screen and English in brackets.
3. Each right answer fills a ♥. When all are full, ⭐ ÉPARGNER spares the monster and gives a pie.
4. A wrong answer brings a silly "attack" and a stronger hint. The child can never lose.
5. After a right answer, the monster says "Répète !" and invites the child to say it aloud. Nothing checks this.
6. The door opens, they say goodbye to the monsters, and they're home.

💬 PARLER does funny things in French, and 🎒 OBJET holds pies (+10 HP) and a word book to tap and hear.

## Scope of first release

The smallest useful release is the existing four-room game, changed so that it teaches the new numbers. It stays a web page played on a phone.

| Room | Monster | Content |
| --- | --- | --- |
| La Grotte | Brumette, a ghost | Where I live: town, village, countryside, sea, mountains |
| Le Pont | Croquette, a dog | Warm-up with 1–20, then 21–69 (vingt et un, trente-deux …) |
| La Mare | Rainette, a frog | Weather and places, plus reading numbers from 21–69 |
| La Grande Porte | Monsieur Cent, a stone giant | 70–100 (soixante-dix, quatre-vingts, quatre-vingt-dix, cent) |

**Changes from the current version**

- **New numbers:** add the compound numbers and 70–100. Today the game only asks 1–20 and the tens.
- **Fresh questions:** draw the numbers from each room's range at random, so a replay isn't identical.
- **Harder to guess:** 3 choices per question, in a shuffled position each time. Today there are 2, and the right answer alternates sides.
- **Better wrong-answer help:** replay the audio and show a stronger hint, for example "70 = soixante + dix".
- **Complete home answers:** "Où habites-tu ?" offers village, sea and mountains too.
- **Readable text:** the pixel font throughout, as you chose after trying a plainer font, set a step larger than in the original game.
- **Saved progress:** save which monsters have been spared.

## Accessibility and privacy

- Audio plus on-screen text, so it works with sound off
- A 🔊 replay button on every question
- No time pressure, and no way to lose
- Large tap targets
- Reduced motion is respected
- Readable text at phone size

**Privacy, by design:** no accounts, no ads, no tracking, no microphone. Progress is saved only on the phone.

## Out of scope for the first release

- Microphone or speech recognition (decided after watching whether the child speaks aloud)
- Playing with siblings or multiplayer
- Accounts, logins and a parent dashboard
- New topics beyond places, weather and numbers
- Custom art or audio: we keep emoji and the phone's French voice
- App Store release
- Any Undertale characters, names, art or music

## Assumptions we cannot yet prove

| Assumption | Why it matters | How we'll find out |
| --- | --- | --- |
| The game is fun enough that the child returns to it during the week without a reminder | The reason the game exists | Count unprompted plays in the trial week |
| The child actually says the "Répète !" lines aloud | Speaking is on trust; this decides whether to add a microphone | Watch one session |
| The phone has a working French voice, including in the car or offline | Every question is spoken | Try it on the phones they'll use, with and without signal |
| The child knows il fait beau and il pleut, or picks them up from the English | Weather stays in the game | Watch the Rainette room |
| Recognising a number by tapping carries over to understanding it spoken in class | Tapping is the main way to answer | Ask the child, or their teacher, after the trial |
| Testing with one child shows whether to continue, not whether it works for other children | Limits what we can claim | Accepted; a wider trial would come later |

## How we will test

One child, your own, over one week.

1. **Before:** a 2-minute check. They hear 8 new numbers (24, 37, 51, 68, 71, 79, 84, 96) and tap the digits.
2. **During:** free play with no reminders. Note whether they finish without help and how often they come back on their own. Watch one session for whether they say the "Répète !" lines aloud.
3. **After:** the same 8-number check.
4. **Decide:** compare with the bars under Goals. Then fix problems, add content, or stop. If they rarely speak aloud, that shapes the microphone decision.

## Open questions

- [ ] Are the bars for "worth continuing" right for you?
- [ ] Add microphone checking in a later release? Decide after the trial.

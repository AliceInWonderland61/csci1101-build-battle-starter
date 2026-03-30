# 🏆 Build-Battle — CSCI 1101

> Two tracks. Four devs. One hour to build. Demo on Wednesday. May the best team win.

---

## 📅 Timeline

| When | What |
|---|---|
| **Monday class** | Build — this is your main work time |
| **Monday last 10 min** | 30-second team checkpoint with the class |
| **Tuesday 11:59 PM** | ⛔ Feature freeze — no new features after this |
| **Wednesday class** | 5-minute live demo + class vote |

---

## 🎮 Pick Your Track

Every team chooses **one** track at the start of Monday and sticks with it.

---

# 🕹️ Track A — One-Button Game

> Build a browser game that uses only one interaction.

### The Goal
Build a fun, playable game in HTML, CSS, and JavaScript where the only control is **one click or one key** (spacebar or mouse click). Think flappy bird, a timing game, dodge the obstacles, a clicker — anything goes as long as it's one button.

### How It Works
1. Player lands on a start screen
2. They press the one button to begin
3. The game runs — something moves, something happens
4. It ends with a game over screen and a score

### Requirements
Your finished game must have all of these:

- [ ] A start screen with instructions
- [ ] Exactly **one** interaction (click or spacebar — pick one)
- [ ] Something that moves or changes on screen
- [ ] A visible score that updates as you play
- [ ] A game over state that shows your final score
- [ ] A way to restart without refreshing the page
- [ ] Styled UI — it should look good, not just work

### 🏆 Bonus Challenges
- [ ] High score that persists during the session
- [ ] Increasing difficulty over time
- [ ] Sound effects
- [ ] Smooth animations using `requestAnimationFrame()`
- [ ] A leaderboard for the class to compete on

### 💡 Tips
- Start with the game loop first — get something moving before you style anything
- Use `setInterval()` or `requestAnimationFrame()` to animate
- Keep the rules simple — the best one-button games are easy to learn, hard to master
- Use `console.log()` to debug — open DevTools with `F12`
- Commit often so teammates can see your changes

---

# 🐸 Track B — What Do You Meme?

> Type a sentence. Get a meme.

### The Goal
Build a webpage where a user types something like:

> *"When your professor says the final is cumulative"*

...and a relevant meme appears with caption text on it.

### How It Works
1. User types a sentence
2. Your code scans it for keywords (e.g. "quiz", "fail", "sleep", "professor")
3. A matching meme image appears with the caption overlaid on it

**What you need to build:**
- A keyword → meme image mapping (at least 5 memes)
- Logic that scans the input and picks the right meme
- Text overlaid on top of the image
- A fallback meme for when no keywords match

---

### Requirements
Your finished meme generator must have all of these:

- [ ] A text input where the user types their caption
- [ ] A Generate button
- [ ] At least **8 different meme templates**
- [ ] Caption text visibly overlaid on the meme image
- [ ] A download button so the user can save their meme
- [ ] Styled UI — it should look good, not just work

### 🏆 Bonus Challenges
- [ ] Download button that saves the meme as a real image file (hint: look up HTML `<canvas>`)
- [ ] Let the user edit the top/bottom text after it generates
- [ ] Add a meme history so users can scroll back through what they made
- [ ] Animate the meme appearing on screen

### 💡 Tips
- Find free meme image URLs at [imgflip.com](https://imgflip.com) — right-click any meme → Copy Image Address
- Start simple — a working ugly meme generator beats a beautiful broken one
- Use `console.log()` to debug — open DevTools with `F12`
- Commit often so teammates can see your changes

---

## 📋 Rules (Both Tracks)

1. **Teams of 4** — everyone must contribute commits to the repo
2. **HTML, CSS, and JavaScript only** — no frameworks (no React, no Vue)
3. **AI tools are allowed** — vibecoding is fair game, but every team member must be able to explain any part of the code during the Wednesday demo
4. **One repo per team** — all work goes through GitHub, no emailing files
5. **Feature freeze at Tuesday 11:59 PM** — commits after that won't count toward judging
6. **5-minute demo on Wednesday** — show it live, explain what you built, what broke, and what you'd do next

---

## ⚖️ How You'll Be Judged

The class votes. Instructor breaks ties.

| Category | Game Track | Meme Track |
|---|---|---|
| 🏅 Most Fun | ✅ | |
| 🎨 Best UI / Design | ✅ | ✅ |
| 😂 Most Creative | ✅ | ✅ |
| ⚡ Most Feature-Complete | ✅ | ✅ |

---

## 📁 File Structure

Keep your repo organized like this:

```
build-battle-[your-team-name]/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🤝 Team Expectations

- **Everyone codes.** Each team member must have at least 2 commits.
- **Communicate.** Use your repo's Issues or a group chat to stay in sync.
- **Don't ghost your team.** If you're stuck, say something — Monday class time is your chance to get help.
- **Be ready to present.** All four members should be ready to speak during the demo.

---

## 🚀 Getting Started

1. Accept the GitHub Classroom invite link shared by your instructor
2. One person creates the team name — make it memorable 👀
3. Teammates join that team by searching the name
4. Clone your repo and start building!

```bash
git clone https://github.com/[your-org]/build-battle-[your-team-name]
cd build-battle-[your-team-name]
```

5. Pick your track, pick your path, and start vibing. Good luck. 🎯

---

*CSCI 1101 — Spring 2026*

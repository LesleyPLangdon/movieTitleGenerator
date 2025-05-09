# 🎬 Ridiculous Movie Title & Summary Generator

Create a PHP program that builds a completely ridiculous movie title and summary using a series of mini-challenges! Each part of your program will use logic, randomness, and user input to generate something unique every time it runs.

---

## 📁 File Setup

- All code should go in a single PHP file: `movie_generator.php`
- You must define and call **all functions** from within this one file.
- Use **procedural programming**. No classes yet!
- All data should be stored in a single associative array called `$movie`.

---

## 🧠 Step-by-Step Challenges

Each step should be completed as its own **function**, and your main code should call each one in order.

### 1. `getHeroName()`
- Prompt the user to enter the hero’s name.
- Store the result in `$movie['hero']`.

### 2. `getTone()`
- Ask the user to choose a tone: `serious`, `funny`, `dramatic`, or `weird`.
- Store their response in `$movie['tone']`.

### 3. `rollTraits()`
- Roll three "trait" values: `action`, `romance`, and `weirdness`. Each should be a random number between 60 and 180.
- Store in `$movie['action']`, `$movie['romance']`, and `$movie['weirdness']`.

### 4. `assignGenre()`
- Use the trait values to decide the movie’s genre.
- Example logic:
  - If action is the highest, it's an **Action** movie.
  - If romance is highest, it’s a **Romantic Comedy**.
  - If weirdness is highest, it’s a **Sci-Fi Oddity**.
- Store the genre in `$movie['genre']`.

### 5. `chooseSetting()`
- Show the user 5 or more setting options using a **numbered list**.
- Use a loop to display them.
- Let the user choose one by typing a number.
- Store the selected setting in `$movie['setting']`.

### 6. `getPlotTwist()`
- Randomly select one plot twist from at least 5 fun options.
- Store in `$movie['twist']`.

### 7. `getSidekick()`
- Use a **switch statement** based on the genre to assign a sidekick.
- Include a default case.
- Store in `$movie['sidekick']`.

### 8. `generateTitle()`
- Combine a random adjective, noun, and the setting/genre to create the title.
- Example: “The Explosive Burrito of Space”
- Store in `$movie['title']`.

### 9. `printSummary()`
- Echo out a short paragraph that includes:
  - The hero’s name
  - The movie title
  - The genre and setting
  - The tone and sidekick
  - The twist
- Format it like a short movie trailer summary.
- Bonus: Change the summary style based on tone.

---

## 📝 Final Notes

- **All functions should `return` a value and store it in the `$movie` array.**
- Use good spacing and comments to organize your code.
- Use `fgets(STDIN)` for user input.
- Creativity counts! Have fun with your genres, sidekicks, settings, and twists.

---

## ✅ Submission Checklist

- [ ] All 9 required functions are written and working
- [ ] `$movie` array is used to store all data
- [ ] The program runs start-to-finish with no crashes
- [ ] Inputs are accepted and output is clear
- [ ] Final summary is readable and fun

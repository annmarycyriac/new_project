<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# [Pazhamkanji Prime] 🎯

## Basic Details

### Team Name: [individual]

### Team Members
- Member 1: [Annmary Cyriac] - [VJCET]


### Hosted Project Link
[project hosted link ](https://new-project-gilt-six.vercel.app/)

### Project Description
[Pazhamkanji Prime is an AI-powered historical recipe oracle that transforms kitchen leftovers into "mass" Kerala masterpieces. Users choose a historical era, and the AI generates a cookable recipe that follows the strict dietary constraints of that time period (Ancient, Medieval, or Modern).]

### The Problem statement
[Food waste is a global issue, yet many people find "leftover cooking" boring or repetitive. Additionally, there is a lack of interactive ways to explore Kerala's rich culinary evolution and the impact of the spice trade on our diet.]

### The Solution
[We solve this by gamifying leftover cooking through an AI "Thug" persona. The app uses the Google Gemini 1.5 Flash API to analyze ingredients and apply historical filters (like removing chilies/tomatoes for Ancient recipes), making waste reduction both educational and culturally "Mass."]

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: [HTML5, CSS3 (Modern Glassmorphism), JavaScript (ES6+), PHP (Backend Bridge)]
- Frameworks used: [CSS]
- Libraries used: [Google Generative AI (Gemini API), html2canvas (for recipe sharing)]
- Tools used: [VS Code, Google AI Studio, Git]



## Features

List the key features of your project:
- Era-Strict Filtering: [ Automatically adjusts ingredients based on history (e.g., Ancient mode uses only Pepper/Tamarind; no Chilies allowed).]
- Thug Persona (Manglish): [DescriptionA witty, bossy AI voice that speaks in a mix of Malayalam and English for a "Mass" user experience.]
- Visual Uploads: [Supports drag-and-drop or camera uploads for food photos to identify ingredients.]
- Recipe History: [Saves your "Pazhamkanji Prime" creations to LocalStorage for offline viewing]
-Theme Engine: [Fully responsive Dark/Light mode inspired by Kerala's rustic aesthetics.]
---

## Implementation

### For Software:

#### Installation
1.Clone the repository.

2.Create a config.php file in the root directory.

3.Add your Gemini API Key:
<?php define('GEMINI_API_KEY', 'YOUR_KEY_HERE'); ?>

Run
Since the project uses PHP for the API bridge, run it using a local server:
```bash
<?php define('GEMINI_API_KEY', 'YOUR_KEY_HERE'); ?>
```

#### Run
```bash
# Using PHP built-in server
php -S localhost:8000
```
Open http://localhost:8000 in your browser.



## Project Documentation

### For Software:

#### Screenshots (Add at least 3)
1.
![Screenshot1](https://github.com/user-attachments/assets/e96a51e1-bf37-49f4-9fbd-83793eddcd74)


2.
![Screenshot2](https://github.com/user-attachments/assets/516b2b8d-3864-4dea-b7e2-79376f2aeb95)

3.
![Screenshot_3_](https://github.com/user-attachments/assets/6f22b621-da89-4469-8a64-4d2a5dcdd5c0)





#### Diagrams

**System Architecture:**
<img width="1536" height="1024" alt="architecture" src="https://github.com/user-attachments/assets/f8bf43ea-2f12-4cb4-8bfe-d351f43ddd35" />


*Architecture Type: Client-side SPA (Single Page Application)






*Pazhamkanji Prime is an AI-powered historical recipe oracle that transforms kitchen leftovers into "mass" Kerala masterpieces. Users choose a historical era, and the AI generates a cookable recipe that follows the strict dietary constraints of that time period (Ancient, Medieval, or Modern*




## Project Demo


https://github.com/user-attachments/assets/ef04c583-2ef0-4649-93a0-a0d246b9514f


### Video
***Key Features**

AI-powered recipe generator

Era selection: Ancient / Medieval / Modern

Dark & Light theme toggle

API key connection status indicator

Image upload (drag & drop)

Ingredient tag system

Gibberish input detection

AI insights (nutrition + pairing suggestions)

Recipe history storage

Copy/share actions

**User Flow**

User selects AI mode.

Adds ingredients (text or images).

Chooses cooking era.

Sets extra options (style, servings, etc.).

Clicks Generate.

Loading animation plays.

AI-generated recipe appears:

Title + era badge

Backstory

Step-by-step method

Special tip

Nutrition insights

Pairing suggestions

Recipe is saved in history.

 **Technical Highlights**

CSS variables for dynamic theming

Smooth animations (keyframes, transitions)

Local state handling for tags & history

Validation logic for incorrect input

Drag-and-drop file handling

Dynamic UI rendering for recipe output

Modal system for API key management

Responsive grid layouts

Interactive visual effects (glow, shimmer, gradients)
*



## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [ChatGPT (primary), Gemini AI (runtime), Claude]

**Purpose:** []
- UI copy & micro-interactions

-Prompt engineering for recipe generation

-Logic validation & edge-case handling

-Code optimization suggestions

**Key Prompts Used:**
- “Generate a structured recipe from ingredients with constraints”

-“Detect gibberish or invalid food inputs”

-“Format AI output into steps, tips, and insights

**Percentage of AI-generated code:** [~40–50%]

**Human Contributions:**
- Full system architecture & flow design

-Era rules, business logic & constraints

-UI/UX styling, animations & responsiveness

-Integration, testing & performance tuning

---

## Team Contributions

- [Annmary Cyriac]: [ Frontend development, API integration,Logic & Integration, etc.]


---

## License

This project is licensed under the MIT License, allowing free use, modification, and distribution with attribution.

---

Made with ❤️ at TinkerHub

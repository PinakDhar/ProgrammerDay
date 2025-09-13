# Programmers' Day - An Interactive Tribute

This is a responsive, single-page web application created to celebrate International Programmers' Day (September 13th). It features a futuristic, Matrix-style aesthetic and provides an immersive experience dedicated to programmers and the technologies they have built.

The project was originally inspired by a poster and brought to life with dynamic animations and interactive elements.

## ✨ Features

- **Animated Matrix Background**: A classic "digital rain" effect runs in the background for a fully immersive feel.
- **Hacker-Themed UI**: The entire interface uses a dark theme with glowing green text, scanline effects, and monospace fonts to simulate a retro computer terminal.
- **"Access Granted" Preloader**: The page begins with a terminal-style loading animation, cycling through messages before granting access to the main site.
- **Interactive Technology Pages**: Clickable icons for major technologies (C, Java, Python, JavaScript, AI/ML) navigate to dedicated detail pages.
- **Dynamic Content with Typewriter Effect**: Historical information on each technology page is "typed out" live, enhancing the retro terminal experience.
- **AI-Powered "Code Oracle"**: Each technology page includes an integrated Q&A feature powered by the Google Gemini API, allowing users to ask questions and receive real-time, AI-generated answers.
- **Fully Responsive**: The layout is designed to work seamlessly on all devices, from desktops to mobile phones.

## 🚀 Technologies Used

- **HTML5**: For the core structure of the application.
- **Tailwind CSS**: For rapid, utility-first styling.
- **Vanilla JavaScript (ES6+)**: To handle all interactivity, page navigation, animations, and API calls.
- **Google Fonts**: For the specific Share Tech Mono and VT323 fonts that define the theme.
- **Google Gemini API**: To power the "Code Oracle" interactive Q&A feature.

## 🛠️ How to Use

This project is self-contained in a single HTML file and requires no complex setup or build process.

1. Clone or download this repository.
2. Open the `programmers_day.html` file in any modern web browser (like Chrome, Firefox, or Edge).
3. That's it! The application will run locally.

**Note**: For the "Code Oracle" feature to work, an active internet connection is required.

## 🎨 Customization

It's easy to add your own content or modify the existing setup:

### Add More Technologies
Simply add a new entry to the `techData` JavaScript object. Follow the existing structure for the title, icon, and content. The application will automatically generate the new icon and page.

### Change the Theme
All core colors are defined as CSS variables in the `<style>` block at the top of the file under the `:root` selector. You can change the `--primary-color` and `--glow-color` to easily re-theme the entire site.

### Modify Preloader Text
The intro animation messages can be changed by editing the `introMessages` array in the JavaScript section.

## 👤 Author & Credits

This project was envisioned and created by **Pinak Dhar (CICADA)**.

- **GitHub**: [@PinakDhar](https://github.com/PinakDhar)
- **Instagram**: [@pirated.me](https://instagram.com/pirated.me)

## 📄 License

This project is open-source and available under the MIT License.

# Aleksandr Bykovskiy
 
## Contact
- Email: aleksandr.bykovskiy.dev@gmail.com
- Location: [Belgrade, Serbia](https://www.google.com/maps/place/%D0%91%D0%B5%D0%BB%D0%B3%D1%80%D0%B0%D0%B4/@44.8099216,20.3789573,12.25z/data=!4m6!3m5!1s0x475a7aa3d7b53fbd:0x1db8645cf2177ee4!8m2!3d44.8125449!4d20.4612299!16zL20vMGZoemY?entry=ttu&g_ep=EgoyMDI2MDkwMi4wIKXMDSoASAFQAw%3D%3D)
- GitHub: [github.com/bykovskiy-dev](https://github.com/bykovskiy-dev)
- Discord: bykovskiydev
## About me
 
Fullstack developer with a strong focus on React and TypeScript, building
scalable web applications using Next.js and Feature-Sliced Design (FSD)
architecture. Also experienced in cross-platform mobile development with
Flutter. Currently expanding into fullstack engineering through RS School,
with a particular interest in backend architecture, authentication systems,
and building well-structured, maintainable applications end to end.
 
Working independently as a registered sole proprietor in Serbia, I value
clean code, thoughtful architecture decisions, and continuous learning.
 
## Skills
 
- **Languages:** JavaScript, TypeScript, Dart, PHP, Rust
- **Frontend:** React, Next.js, Feature-Sliced Design (FSD)
- **Mobile:** Flutter
- **Tools:** Git, GitHub, VS Code
- **Other:** REST API integration, responsive/adaptive UI, basic backend (Node.js)
## Code example
 
Example of the Singleton pattern in TypeScript:
 
```javascript
// Singleton
class Logger {
  private static instance: Logger;
  private logs: string[] = [];

  private constructor() {}

  public static getInstance(): Logger {
    if (!Logger.instance) {
      Logger.instance = new Logger();
    }
    return Logger.instance;
  }

  public log(message: string): void {
    this.logs.push(message);
    console.log(message);
  }

  public getLogs(): string[] {
    return this.logs;
  }
}

// usage
const logger1 = Logger.getInstance();
const logger2 = Logger.getInstance();

logger1.log('App started');
console.log(logger1 === logger2); // true — same instance
```
 
## Experience / Projects
 
- **Receipt Tracker** — Flutter app using the Gemini API and ML Kit OCR to
  automatically parse and categorize receipts.
- **Next.js Auth Architecture** — designed an authentication flow addressing
  refresh-token race conditions across stateless server instances.
- **RS School CV project** — this very CV, built with Markdown, HTML, and CSS,
  deployed via GitHub Pages. [Source code](https://github.com/bykovskiy-dev/rsschool-cv)

## Education
 
- **RS School** — Fullstack Engineering course (in progress), 2026
- **Yandex.Praktikum** — HTML, CSS, JavaScript, TypeScript, SOLID, GIT courses, 2025 — 2026

## Languages
 
- **Russian** — native
- **English** — B2 (Upper-Intermediate). Comfortable reading technical
  documentation, following tutorials, and communicating in written form.

# Accessible Web Design — Scrimba Course

> Learn how to write accessible HTML by solving interactive coding challenges and fixing a real-world website.

This repository holds my notes, solutions, and project files from Scrimba's **Accessible Web Design** course. Everything here is written as I work through the course, so expect it to grow challenge by challenge.

## About the course

The course teaches accessibility from the ground up: instead of memorizing rules, you solve interactive coding challenges and then apply what you've learned by fixing the accessibility problems on a real-world website.

🔗 [Take the course on Scrimba](https://scrimba.com/)

## What I'm learning

- Semantic HTML and why `<div>` isn't always the answer
- Landmark elements (`<header>`, `<nav>`, `<main>`, `<footer>`) and page structure
- A logical heading hierarchy
- Meaningful `alt` text — and when to leave it empty
- Accessible forms: labels, grouping, and error messages
- Links vs. buttons, and picking the right one
- Keyboard navigation and visible focus states
- Color contrast and not relying on color alone
- ARIA basics — and the first rule of ARIA
- Testing with a screen reader and automated tools

## Repository structure

```
.
├── challenges/       # Solutions to the interactive coding challenges
├── project/          # The real-world website being fixed
│   ├── before/       # Original, inaccessible version
│   └── after/        # Refactored, accessible version
├── notes/            # Notes and takeaways per section
└── README.md
```

## Progress

- [ ] Introduction to web accessibility
- [ ] Semantic HTML
- [ ] Page structure and landmarks
- [ ] Headings
- [ ] Images and alt text
- [ ] Links and buttons
- [ ] Forms
- [ ] Keyboard navigation and focus
- [ ] Color and contrast
- [ ] Intro to ARIA
- [ ] Fixing the real-world website
- [ ] Course completed 🎉

## Running the project locally

```bash
git clone https://github.com/lessandsass/Accessible-Web-Design.git
cd <repo-name>
```

Open any `index.html` file in your browser, or serve the folder with a live server:

```bash
npx serve project/after
```

## Tools I'm using

| Tool | Purpose |
| --- | --- |
| [WAVE](https://wave.webaim.org/) | In-browser accessibility evaluation |
| [axe DevTools](https://www.deque.com/axe/devtools/) | Automated issue detection |
| [Lighthouse](https://developer.chrome.com/docs/lighthouse/) | Accessibility scoring |
| [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) | Color contrast ratios |
| NVDA / VoiceOver | Screen reader testing |

## Useful references

- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
- [MDN — Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
- [The A11y Project Checklist](https://www.a11yproject.com/checklist/)
- [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/)

## License

[MIT](LICENSE) — feel free to use anything here for your own learning.

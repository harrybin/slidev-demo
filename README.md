# Slidev Presentation Project

This project is a presentation built using [Slidev](https://sli.dev), a tool for creating interactive and customizable slides using Markdown. The presentation content is written in Markdown files, and custom Vue.js components can be used to enhance the slides.

## Project Structure

- **`slides.md`**: The entry point of the presentation. It links to other Markdown files containing the slide content.
- **`components/`**: Contains custom Vue.js components that can be used in the Markdown slides.
- **`public/`**: Static assets (e.g., images) used in the presentation.
- **`package.json`**: Project dependencies and scripts.

## Writing Slides

Slides are written in Markdown and separated by `---` lines. You can also use headmatter for slide metadata:

```markdown
---
title: Slide Title
---

Slide content here.
```

### Notes

Add presenter notes as Markdown comments. Only the last comment in a slide is treated as the note:

```markdown
<!-- This is a presenter note -->
```

## Running the Presentation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open the presentation in your browser at `http://localhost:3030`.

## Building for Production

To build the presentation for production:

```bash
npm run build
```

The output will be in the `dist/` directory.

## Learn More

- [Slidev Documentation](https://sli.dev)
- [Markdown Syntax](https://www.markdownguide.org)
- [Vue.js Documentation](https://vuejs.org)

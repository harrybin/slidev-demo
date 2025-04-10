This project is no web-app project. The web-app techstack (vite & vue) which may be usedis only the platform for the content.
This is a project for presentation slides using the [slidev technology](https://sli.dev).
Generell Syntax hints can be found in the [slidev documentation](https://sli.dev/guide/syntax).
A description of the per slide frontmatter configuration can be found in the [slidev documentation](https://sli.dev/custom/#frontmatter). the typedefinition of the frontmatter can be found in the soure code on [github](https://raw.githubusercontent.com/slidevjs/slidev/refs/heads/main/packages/types/src/config.ts).
Supported layouts can be found [here](https://sli.dev/builtin/layouts).

The main work is done within mardown files. The content is written in markdown and the presentation is generated from it.
The entrypoint of the presentation is the `slides.md` in the root directory.
From there on the content is linked to other markdown files.

Each slide within a markdown file is separated by a `---` line or a `---` line with frontmatter and a further `---` line. Both must be followed by a blank line.

Custom components can be defined and used in the markdown files to enhance the presentation.
These components are defined in the `components` directory using Vue.js.

Notes for the presentation are written in markdown as comments. But only the last comment in a slide is taken as note.
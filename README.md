# 🎙️MicMasterFlex
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

**MicMasterFlex** is a web app that allows users to configure the positions of a microphone array on an interactive grid. 

Designed for audio engineers and researchers, this tool offers an intuitive interface for precise microphone placement, enabling users to simulate and optimize array setups for various acoustic applications.

## 📸 Demo
https://github.com/user-attachments/assets/419bda8b-d6a5-4f54-87b8-acef9d752226

## 💡 Project Motivation
**MicMasterFlex** was born out of challenges encountered during the [*Robots as Furniture*](https://github.com/robotsasfurniture/passive-sound-localization) project at Brown University, where configuring a microphone array for sound localization required precise positioning of multiple microphones. 

Given the complex arrangement, writing down positions manually without a visual guide proved inefficient and error-prone. 

MicMasterFlex addresses this by offering an interactive, visual interface to configure microphone positions on a grid, making it easier to plan and visualize the array layout. 

Additionally, the tool generates the necessary `numpy` code for these positions, streamlining the setup process for audio processing and sound localization tasks.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun run dev`             | Starts local dev server at `localhost:4321`      |
| `bun run build`           | Build your production site to `./dist/`          |
| `bun run preview`         | Preview your build locally, before deploying     |
| `bun run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun run astro -- --help` | Get help using the Astro CLI                     |

## 📝 Citation

If you'd like to cite this project, please use this BibTex:

```
@article{perez2024micmasterflex,
  title={MicMasterFlex},
  author={Nicolas Perez},
  journal={https://example.com/},
  year={2024}
}
```

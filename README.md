# Bricks

Bricks is an open source tool for converting Figma designs into high-quality frontend code.

## Try Bricks

### Prerequisites

Install the [VS Code extension](https://marketplace.visualstudio.com/items?itemName=Bricks.d2c-vscode) and the [Figma plugin](https://www.figma.com/community/plugin/1178847414663679049/Bricks---Copilot-for-UI-Engineering).

### How to use

1. In VS Code, open the command palette (Command + Shift + P) and type "Activate Bricks" to start up Bricks.
2. In Figma, select a component to convert to code
3. Click “Generate”
4. Done! The generated code shows up in VS Code, along with a live preview
5. You can tinker with the generated code, and see changes instantly in the preview
6. When you’re happy with the code, just drop it into your codebase 👏

## Project Structure

Bricks is composed of a number of components. We are working to open-source as many of them as possible. Below is a description of each component:

- `core`: code that converts Figma nodes into `StyledBricksNode`s, which are meant as an input for other plugins to generate the final code.

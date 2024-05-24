## Project Requirements

Before running the project, ensure your system meets the following requirements:

- Node.js 20.10+
- MongoDB Community Server Download 7.0.4+ or MongoDB Atlas
- **Backend Installation:**
  - The Bestiary Frontend relies on the Bestiary Backend for seamless functionality.
  - Follow the instructions in the [Backend Repository](https://github.com/itsrusty/) to set up and configure the backend before initiating the frontend.
- Internet access

## Installation

Follow these steps to install and configure the project:

1. Clone the repository: `git clone https://github.com/itsrusty/pokedex-prueba-fullstack.git`
2. Enter the project directory: `cd pokedex-prueba-fullstack`
3. Install dependencies: `pnpm install`
4. Modify the file with the IP and port of the backend: `src/globalVariables.tsx`

## Project Structure

- `/`
  - `src/`: Contains the source code.
  - `src/pages`: Contains references to the pages.
  - `src/components`: Contains page components.
  - `src/globalVariables.tsx`: Contains configuration variables.
  - `public/`: Contains public files.

## Usage

To test in dev mode:

```bash
pnpm start
```
Build the project:
```bash
pnpm run build
```

# License

MIT License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

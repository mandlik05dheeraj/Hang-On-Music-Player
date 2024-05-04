
# React + TypeScript + Vite	# Random Quote Generator with Speech (React + TypeScript)


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.	This is a simple web application built using React and TypeScript that fetches random quotes from an API and allows users to hear the quote spoken aloud.


Currently, two official plugins are available:	## Features


- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh	- **Random Quotes**: Fetches quotes from [API_NAME] to display on the app.
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh	- **Text-to-Speech**: Provides a button to hear the quote read aloud using browser text-to-speech functionality.
- **React and TypeScript**: Built with React framework using TypeScript for strict typing.


## Expanding the ESLint configuration	## Installation


If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:	1. Clone the repository:


- Configure the top-level `parserOptions` property like this:	   ```bash
   git clone https://github.com/your-username/quote-generator.git
   ```


```js	2. Navigate to the project directory:
export default {	
  // other rules...	
  parserOptions: {	
    ecmaVersion: 'latest',	
    sourceType: 'module',	
    project: ['./tsconfig.json', './tsconfig.node.json'],	
    tsconfigRootDir: __dirname,	
  },	
}	
```	


- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`	   ```bash
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`	   cd quote-generator
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list	   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

1. Obtain an API key from [API_PROVIDER] and replace `[YOUR_API_KEY]` in `src/api.ts` with your actual API key.

2. Start the development server:

   ```bash
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the app.

4. Click the "Generate Quote" button to fetch a random quote. Press the "Listen" button to hear the quote spoken aloud.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **TypeScript**: Typed superset of JavaScript for enhanced code quality.

## API Reference

This app uses the (https://api.adviceslip.com/advice) API to fetch random quotes. For more information.

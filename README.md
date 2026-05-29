# react-carbon-exercise

steps:
create boilerplate for react and carbon
configure scss
carbon + react setup

🚀 1. Create a React App

Use Vite (recommended for speed):

npm create vite@latest my-carbon-app
cd my-carbon-app
npm install

Choose:

Framework: React

Variant: JavaScript 

📦 2. Install Carbon Packages

Install the core Carbon dependencies:

npm install @carbon/react @carbon/styles

Optional icons package:

npm install @carbon/icons-react
🎨 3. Import Carbon Styles

In your main.jsx or main.tsx:

import '@carbon/styles/css/styles.css';
🧱 4. Basic App Structure

Update App.jsx:

import { Button } from '@carbon/react';

function App() {
  return (
    <div style={{ padding: '2rem' }}>
      <h1>Carbon + React</h1>
      <Button kind="primary">Click me</Button>
    </div>
  );
}

export default App;
🌗 5. (Optional) Add Theme Support

Carbon supports themes like white, g10, g90, g100:

import { Theme } from '@carbon/react';

function App() {
  return (
    <Theme theme="g100">
      <div style={{ padding: '2rem' }}>
        <h1>Dark Theme</h1>
      </div>
    </Theme>
  );
}
🧭 6. Use Carbon Layout Components

Example with layout:

import {
  Header,
  HeaderName,
  Content
} from '@carbon/react';

function App() {
  return (
    <>
      <Header aria-label="App">
        <HeaderName href="#" prefix="My">
          App
        </HeaderName>
      </Header>
      <Content>
        <h2>Welcome</h2>
      </Content>
    </>
  );
}
⚡ 7. Run the App
npm run dev
🧠 Tips for Production Setup
setup carbon mcp 

Use SCSS tokens if you want deeper customization

Follow Carbon’s grid (@carbon/grid) for layout - understand carbon grid and flex layout in detail

Use their accessibility-first components (built-in 👍)

Consider integrating with:

React Router for navigation

carbon MCP setups

Follow these steps to configure your AI application or AI agent to use Carbon MCP.

Step 1: Using your w3id or functional ID
Step 2: Getting access credentials
Step 3: Connecting to IBM Bob and other MCP clients
Step 4: Adding the carbon-builder skill


## please follow the steps mentined here

npm init
npm install -D parcel 
npm install
npx parcel index.html 
npm install react
npm install react-dom

#parcel
- Dev Build
- many more advantages

import React from "react";
import ReactDOM from "react-dom/client";
import Body from "./components/body";
import { Header } from "./components/header";

const App = () => {
  return (
    <main>
      <Header />
      <Body />
    </main>
  );
};

//This syntax is not a problem for obvious reasons
const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);
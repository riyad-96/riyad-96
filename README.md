# It's Riyad

🌱 Self-taught web developer from Bangladesh, learning every day and building cool things.
💻 I love working with **JavaScript, React, TailwindCSS** to create clean, minimal, and useful apps.

* ✅ Improving React skills
---

### Gained some control over

<p align="start">
  <img title="HTML" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5"/>&nbsp;&nbsp;
  <img title="CSS" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3"/>&nbsp;&nbsp;
  <img title="JavaScript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript"/>&nbsp;&nbsp;
  <img title="Tailwindcss" src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" height="40" alt="TailwindCSS"/>&nbsp;&nbsp;
  <img title="NPM" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" height="40" alt="NPM"/>&nbsp;&nbsp;
  <img title="Firebase" src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" height="40" alt="Firebase"/>&nbsp;&nbsp;
</p>

### Learing

<P>
  <img title="ReactJS" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="ReactJS"/>&nbsp;&nbsp;
  <img title="NodeJS" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="NodeJS"/>&nbsp;&nbsp;
  <img title="ExpressJS" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" alt="ExpressJS"/>&nbsp;&nbsp;
  <img title="MongoDB" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="MongoDB"/>
</p>

### Targets

<p>
  <img title="TypeScript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript"/>
  <!-- <img title="NextJS" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="NextJS"/> -->
</p>

---

### ⚡ Current Experiments

* ✅ Built <a title="ZeroIDE" href="https://zero-ide.vercel.app" target="_blank">ZeroIDE</a>, a minimal in-browser code editor.
* ✅ Published small npm utility called <a title="kitzo, light-weight usefull utility" href="https://www.npmjs.com/package/kitzo" target="_blank">kitzo</a>.
* ✅ Built <a title="KitzoBazar" href="https://kitzobazar.vercel.app" target="_blank">KitzoBazar</a>, bazar list calculator and session history can be saved in database.

---
```jsx
import { useEffect, useContext } from 'react';
import { goalContext } from './contexts';

function LevelUp() {
  const { goal, setGoal } = useContext(goalContext);

  useEffect(() => {
    setGoal('Acquire React 👑');
  }, []);

  return <p>Today's goal: {goal}</p>;
}

export default LevelUp;
```
> “Consistency over perfection.” – Let’s keep building!

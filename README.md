<h1 align="center">Hi there, I'm Pavlo 👋</h1>

<p align="center">
  <a href="https://github.com/your-username">
    <img src="https://img.shields.io/github/followers/your-username?label=Follow&style=social" alt="GitHub followers"/>
  </a>
  <a href="https://www.npmjs.com/package/react-url-query-params">
    <img src="https://img.shields.io/npm/v/react-url-query-params?color=blue&label=npm%20package" alt="npm package"/>
  </a>
  <a href="https://twitter.com/your-twitter">
    <img src="https://img.shields.io/twitter/follow/your-twitter?style=social" alt="Twitter Follow"/>
  </a>
</p>

---

### 🚀 About Me
- 💻 **Frontend Developer** focused on React & TypeScript
- 🛠 Building useful **React hooks & npm packages**
- ✍ Writing about code and sharing open-source projects

---

### 📦 My Latest npm Package
**[react-url-query-params](https://www.npmjs.com/package/react-url-query-params)**  
A tiny React hook to simplify working with URL query parameters in `react-router-dom`.

```ts
import useUrlParams from 'react-url-query-params';

function MyComponent() {
  const { view, setView, toggleView, isViewGrid, isViewTable } = useUrlParams({
    keyName: 'view',
    options: ['grid', 'table'] as const,
  });

  return (
    <>
      <p>View: {view}</p>
      <button onClick={() => setView('grid')}>Grid</button>
      <button onClick={() => setView('table')}>Table</button>
      <button onClick={toggleView}>Toggle</button>
    </>
  );
}

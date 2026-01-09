<h1 align="center">Hi there, I'm Pavlo 👋</h1> 

<p align="center">
  <a href="https://github.com/PashaSchool">
    <img src="https://img.shields.io/github/followers/PashaSchool?label=Follow&style=social" alt="GitHub followers"/>
  </a>
  <a href="https://www.npmjs.com/package/react-url-query-params">
    <img src="https://img.shields.io/npm/v/react-url-query-params?color=blue&label=react-url-query-params" alt="npm package"/>
  </a>
  <a href="https://www.npmjs.com/package/react-csv-autopilot">
    <img src="https://img.shields.io/npm/v/react-csv-autopilot?color=green&label=react-csv-autopilot" alt="npm package"/>
  </a>
</p>

---

## About Me
- **Frontend Developer** focused on React & TypeScript
- Building useful **React hooks & npm packages**
- Writing about code and sharing open-source projects

---

## 📦 My npm Packages

### [react-csv-autopilot](https://www.npmjs.com/package/react-csv-autopilot)
React hooks for CSV export with automatic pagination - drop the function, we handle the rest.

```ts
import { useCSVAutopilot } from 'react-csv-autopilot';

function ExportButton() {
  const { download, isExporting, progress } = useCSVAutopilot({
    fetchData: async (page) => {
      const response = await fetch(`/api/data?page=${page}`);
      return response.json();
    },
    filename: 'export.csv',
  });

  return (
    <button onClick={download} disabled={isExporting}>
      {isExporting ? `Exporting... ${progress}%` : 'Export CSV'}
    </button>
  );
}
```

### [react-url-query-params](https://www.npmjs.com/package/react-url-query-params)
A tiny React hook to simplify working with URL query parameters in `react-router-dom`.

```ts
import { useUrlParams } from 'react-url-query-params';

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
```

## 🌟 Support
If you find my projects useful, consider giving them a ⭐️ on [GitHub](https://github.com/PashaSchool/utils-kit)!

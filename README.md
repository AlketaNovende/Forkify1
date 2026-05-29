# forkify Project

Recipe application with custom recipe uploads.

**What this is:**
- **Description:** A small recipe web app that lets users search for recipes, bookmark favorites, and upload new recipes to the API.

**Features:**
- **Search:** use the search bar to find recipes by keyword.
- **Bookmarks:** save recipes to your local bookmarks for quick access.
- **Add recipe:** upload a recipe via the upload form (API key required for uploads).

**Prerequisites:**
- **Node.js** (v14+ recommended) and `npm` installed on your machine.

**Install:**
1. Clone the repository and change into the project folder.
2. Install dependencies:

```
npm install
```

**Run (development):**
```
npm start
```
Open `index.html` in the browser (Parcel should open a dev server).

**Build (production):**
```
npm run build
```

**API key (uploads):**
If you want to upload recipes you must set your API key in [src/js/config.js](src/js/config.js#L1). Replace the `KEY` value with your own Forkify API key or remove key checks if you don't need upload functionality.

**Usage notes:**
- Type a query into the search bar and press Enter to load results.
- Click the bookmark icon to add/remove a recipe from bookmarks (stored in Local Storage).
- Use the upload form to add a custom recipe; ingredients must use the format `quantity,unit,description` (e.g. `1,kg,flour`).

**License & Credits:**
- MIT License — see the `LICENSE` file.

Thank you for checking out the project — feel free to open issues or PRs with improvements.

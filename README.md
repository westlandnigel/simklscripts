# Simkl and Letterboxd Tools

This repository contains scripts and tools for working with **Letterboxd** and **Simkl**, including exporting data, importing histories, and enhancing the Simkl experience with Letterboxd reviews.

## Files and Descriptions

### 1. `exportLetterboxdHistory.py`
This script exports all watched data from **Letterboxd**, including:
- Watched movies and shows
- Ratings
- Watchlist items

### 2. `importLetterboxdintoSimkl.py`
This script imports the exported **Letterboxd history** into **Simkl**.
- Ensure you edit the `client_id` from Simkl and include your own **TMDB API key** in the script before running.
- Supports importing movies and shows seamlessly into Simkl.

### 3. `exportLetterboxdList.py`
This script exports all items from a specific **Letterboxd list**.
- Future updates will enable importing these lists into **Simkl**, enhancing integration and syncing capabilities.

### 4. `Letterboxd reviews on Simkl (Userscript).js`
A user script designed to enhance **Simkl** by displaying **Letterboxd reviews** on Simkl pages.
- Works with **Tampermonkey** or similar browser extensions.
- Adds a section on Simkl to show relevant reviews from Letterboxd for movies. Shows don't yet until Letterboxd implements TV

## Usage Instructions

### 1. Export Letterboxd Data
Run `exportLetterboxdHistory.py` to generate a csv file containing all your Letterboxd data.

### 2. Import Data into Simkl
- Edit `importLetterboxdintoSimkl.py` with your Simkl `client_id` and TMDB API key.
- Run the script to import your history into Simkl.

### 3. Export a Letterboxd List
Use `exportLetterboxdList.py` to extract all items from a specific Letterboxd list in a .csv file

### 4. Enhance Simkl with Letterboxd Reviews
- Install **Tampermonkey** or a similar userscript manager.
- Add the `Letterboxd reviews on Simkl (Userscript).js` script.
- Visit Simkl pages to see Letterboxd reviews seamlessly integrated.

## Notes
- **Ensure all API keys and client IDs are correctly configured before running the scripts.**
- Future updates will add more functionalities, including importing custom Letterboxd lists into Simkl.

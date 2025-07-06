# Trip-list-maker

A simple and intuitive React app to help you create, manage, and track your packing list for any trip. Add items, set quantities, mark items as packed, sort your list, and see your packing progress at a glance.

🌐 **Live Demo:** [https://nikhil2004nk.github.io/Trip-list-maker](https://nikhil2004nk.github.io/Trip-list-maker)

## Features
- Add items with quantity to your packing list
- Mark items as packed/unpacked
- Delete individual items
- Sort items by input order, description, or packed status
- Clear the entire list
- View packing statistics (total items, packed items, percentage)

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nikhil2004nk/Trip-list-maker.git
   cd Trip-list-maker
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the App
Start the development server:
```bash
npm start
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Technologies Used
- React (Create React App)
- JavaScript (ES6+)
- CSS

## File Structure
```
Trip-list-maker/
  ├── public/
  │   └── ... (static assets)
  ├── src/
  │   ├── App.js         # Root component, manages state
  │   ├── form.js        # Form for adding new items
  │   ├── Item.js        # Single item component
  │   ├── PackingList.js # List and sorting logic
  │   ├── Stats.js       # Packing statistics
  │   ├── logo.js        # Logo component
  │   ├── index.js       # Entry point
  │   └── index.css      # Global styles
  ├── package.json
  └── README.md
```

## Scripts
- `npm start` – Run the app in development mode
- `npm run build` – Build the app for production
- `npm test` – Run tests (if any)
- `npm run deploy` – Deploy to GitHub Pages

---

Feel free to contribute or suggest improvements!

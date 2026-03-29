On app refresh from ai studio to Xcode. Open terminal move into the project directory using cd, ls pwd cd.. cd ..
In terminal run
npm install
npm run build
npx cap sync

On a new project run these
npm install
npm run build
npx cap add ios
npx cap open ios

this is to list new games, file look like this. [
  {
    "id": "piano-kids",
    "title": "Nate's Magic Piano",
    "description": "Learn and play your favorite nursery rhymes!",
    "url": "https://your-piano-game-link.com",
    "icon": "🎹",
    "category": "Music"
  },
  {
    "id": "new-game",
    "title": "My New Awesome Game",
    "description": "Check out my latest creation!",
    "url": "https://your-new-game-link.com",
    "icon": "🚀",
    "category": "Action"
  },
  {
    "id": "new-game2",
    "title": "My New Awesome Game 2",
    "description": "Check out my latest creation!",
    "url": "https://your-new-game-link.com",
    "icon": "🚀",
    "category": "Action",
    "isNew": true
  }]

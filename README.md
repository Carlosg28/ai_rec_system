# AI Media Recommender

This project is a React application that uses the [TMDb API](https://www.themoviedb.org/) to recommend movies based on user-selected genres and previously selected items. It allows users to browse movie genres, add items to a list, and receive movie recommendations.

## Features

- Browse movies by genre (e.g., Action, Comedy, Drama, etc.).
- Select movies to add to a list.
- Get personalized movie recommendations based on the selected list.
- Show movie posters and titles.
- Toggle movie selections and remove items from the list.
- Display movie recommendations with posters.

## Technologies Used

- **React**: Frontend framework for building the user interface.
- **Vite**: Next-generation build tool and development server for fast builds and HMR (Hot Module Replacement).
- **TMDb API**: Provides access to movie data, including details and recommendations.
- **CSS-in-JS**: Used inline styles in JSX to define the layout and appearance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai_media_recommender.git
   cd ai_media_recommender
2. Install the dependencies:
```bash
   npm install
```
3. Create a .env file in the root directory and add your TMDb API key:
```bash
VITE_TMDB_API_KEY=your-api-key-here
```
4. Start the development server:
```bash
npm run dev
```
## Usage
1. Type a movie into the input field.
2. Hit "Enter" to add the item to your list.
3. Select movies from the genre sections to add them to your list.
4. Click the "Recommend Movies" button to get personalized recommendations based on your list.
5. Click on a movie in the list to remove it.
## License
This project is open-source and available under the MIT Lisence.
### Key Things to Customize:
- Replace `your-username` with your actual GitHub username in the clone URL (`git clone https://github.com/your-username/ai_media_recommender.git`).
- Replace the placeholder `your-api-key-here` in the `.env` file section with your actual TMDb API key.

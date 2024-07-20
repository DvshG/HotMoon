# HotMoon: Movie Search App

HotMoon is a responsive React application that allows users to search for movies using the OMDb API. This app displays movie information including the title, release year, and type. It's a great example of how to integrate a third-party API with a modern front-end framework.

## Working with Image
![Screenshot 2024-07-20 215726](https://github.com/user-attachments/assets/ce5afe18-7512-43ef-809f-00b6eb65f73b)

The application uses the OMDb API to fetch movie data. The fetched data is then displayed in a grid of movie cards, each showing the movie's poster, title, year of release, and type.

## Features

- **Responsive Design**: Adjusts seamlessly to different screen sizes.
- **Movie Search**: Search for movies by title.
- **Dynamic Content**: Displays movie results in a visually appealing format.

## Tech Stack

- **Frontend**: React.js
- **Styling**: CSS, Google Fonts
- **API**: OMDb API

## Installation

### Requirements

- Node.js (v14.x or later)
- npm

### Steps

1. Clone the repository:

 ```bash
 git clone https://github.com/yourusername/hotmoon.git
 cd hotmoon
 ```
2. Install dependencies:

```bash
npm install
```
## Usage
1. Start the development server:

```bash
npm start
```
2. Open your browser and go to **http://localhost:3000** to use the application.

## Project Structure
### Source Files
- **App.js**: Main component file containing the app's structure and logic.
- **App.css**: Styling specific to the App component.
- **index.js**: Entry point for React application rendering.
- **index.css**: Global styling for the application.
- **MovieCard.jsx**: Component for rendering individual movie cards.
### Public
- **index.html**: Main HTML file.
- **search.svg**: Search icon used in the search bar.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch ```git checkout -b feature/your-feature```
3. Commit your changes ```git commit -m 'Add some feature'```
4. Push to the branch ```git push origin feature/your-feature```
5. Open a pull request.
## Requirements
- Node.js (v14.x or later)
- npm
## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

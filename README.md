# NASA APOD React Website

## Project Description

The NASA Astronomy Picture of the Day (APOD) React Website showcases daily astronomical images from NASA. It features a full-screen 4K image in the background, a title in the footer, and a sidebar that provides additional details about the image. The website is built using React and effectively uses React Hooks to manage state and side effects. Font Awesome icons are utilized for enhanced visual appeal.

## Technologies Used

- React
- React Hooks
- Font Awesome Icons
- NASA APOD API

## Setup and Run Instructions

### Prerequisites

- Node.js (version 18.0.0 or later)
- npm (Node Package Manager)

### Setup Instructions

1. Clone the project repository from the source, or download it as a ZIP archive and extract it to your local machine.
    ```bash
    git clone https://github.com/yourusername/nasa-apod-react-website.git
    ```
2. Navigate to the project directory.
    ```bash
    cd nasa-apod-react-website
    ```
3. Install the necessary dependencies using npm.
    ```bash
    npm install
    ```
4. Create a `.env` file in the root directory of the project and add your NASA API key.
    ```env
    VITE_NASA_API_KEY=your_api_key_here
    ```

### Running the Project

1. Start the development server.
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000` to view the application.

## Key Features and Functionalities Implemented

1. **Full-Screen Background Image**:
    - Displays a high-resolution image from NASA's Astronomy Picture of the Day (APOD) API.
    

2. **Title in Footer**:
    - Shows the title of the APOD image in the footer section.
    

3. **Sidebar with Image Details**:
    - Provides additional details about the image, including explanation and date.


7. **React Hooks**:
    - Utilizes hooks such as `useState` and `useEffect` to manage API data and component states.
    

8. **API Integration**:
    - Fetches data from the NASA APOD API using a secure API key.
    

9. **Font Awesome Icons**:
    - Uses Font Awesome icons for better visual representation.

    
## Authors

- [Muhammad Wasif Shakeel](https://github.com/mwasifshkeel)

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [React](https://reactjs.org/docs/getting-started.html)
- [Font Awesome](https://fontawesome.com/)
- [NASA APOD API](https://api.nasa.gov/)
- [Create React App](https://create-react-app.dev/docs/getting-started/)
- [Font Awesome Icons](https://fontawesome.com/icons)

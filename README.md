
# News Display Front-End

This repository contains a React-based front-end for displaying processed news articles. It reads data from a `processed_news.json` file and renders a list of articles on a homepage.

## Features

- **Responsive News Display**: Dynamically renders news articles with titles, categories, publication dates, and summaries.
- **External Links**: Each article includes a clickable title that redirects to the full article.
- **Stylized UI**: Clean and simple UI using CSS for better user experience.

## Project Structure

```bash
.
├── src/
│   ├── App.js                # Main app component that handles rendering the homepage and articles.
│   ├── HomePage.js           # Component that renders the homepage content.
│   ├── Article.js            # Component responsible for rendering individual articles.
│   ├── processed_news.json   # JSON file containing the processed news data.
│   ├── App.css               # Global styling for the app.
│   └── HomePage.css          # Styling specific to the homepage and article cards.
├── public/
│   └── index.html            # Main HTML template for React.
├── package.json              # Project dependencies and scripts.
└── README.md                 # This file.
```

## Setup Instructions

### Prerequisites

1. **Node.js**: Ensure you have Node.js installed on your machine.
2. **React**: This project uses React, so make sure you are familiar with basic React concepts.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Ensure you have a `processed_news.json` file in the `src/` directory. This file contains the news data to be displayed. Here is an example format:

   ```json
   [
     {
       "title": "Sample News Title",
       "url": "https://example.com/news/1",
       "published_at": "2024-10-01",
       "category": "Technology",
       "news": "Generated summary of the news article."
     },
     ...
   ]
   ```

### Running the Project

To start the development server, run:

```bash
npm start
```

The app will run on `http://localhost:3000`. Visit the URL in your browser to see the rendered news articles.

### Screenshots

[Include screenshots of the homepage and article components here.]

## Contributions

Feel free to fork this repository, submit issues, or open pull requests for any improvements or new features.

## License

This project is licensed under the MIT License.

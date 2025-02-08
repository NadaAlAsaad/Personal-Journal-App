# Personal Journal

This is a simple web-based personal journal application that allows users to write daily journal entries, analyze their mood through sentiment analysis, and store their entries locally in the browser. The journal entries are saved using localStorage, allowing them to persist even after refreshing the page.

## Features

- **Write Journal Entries**: Users can write and save their journal entries.
- **Sentiment Analysis**: Each entry's mood is analyzed using the Sentim API and categorized as "positive", "neutral", or "negative".
- **LocalStorage**: Journal entries are saved in the browser's local storage, so they remain even after a page refresh.
- **Responsive Design**: The journal application is responsive and looks good on mobile, tablet, and desktop screens.
- **Edit and Delete Entries**: Users can edit or delete their journal entries.
  
## Installation

To use this journal application locally, follow these steps:

1. Clone the repository or download the project files.
2. Open the `index.html` file in any web browser.

No server-side setup is required as this project runs entirely on the client side.

## Usage

1. Open the journal application in a browser.
2. Write your journal entry in the provided text box.
3. Click the "Save Entry" button to save your entry.
4. The application will analyze the mood of your entry using the Sentim API and display the result.
5. You can edit or delete any entry by clicking the respective buttons.

## API Used

- **Sentim API**: This API is used for sentiment analysis. It analyzes the mood of the journal entries and categorizes them into "positive", "neutral", or "negative".

API URL: `https://sentim-api.herokuapp.com/api/v1/`

## Technologies Used

- HTML
- CSS
- JavaScript
- Sentim API (for sentiment analysis)

## License

This project is open-source and free to use. You can modify it as per your needs.

# word_counter
This is a simple web app built in React that counts the number of words in text.

## Features

- Counts the words from text pasted or typed into a textbox 
- Displays total number of words
- Removes punctuation before counting words 
- Accepts multiple paragraphs 
- Responsive design
- Calculate approx time to read by human 

## Usage

The app is hosted at this URL:

```
https://wordcounter.example.com
```

Users can simply paste or type text into the text box and the word count will automatically update. The page works well on all screen sizes.

## Implementation 

The frontend is implemented in:

- React 
- HTML 
- CSS
- JavaScript

Some key aspects:

-Created reusable TextInput React component to handle text input and counting
- Use Hooks including useState for managing state
- Removes punctuation and counts words after each text change
- Responsive design using CSS media queries and Flexbox

The backend connects to a simple Node/Express REST API to save count history in a MongoDB database.

## Development

To run the app locally:

1. Clone this repo
2. Run `npm install`  
3. Run `npm start`
4. Access the app at http://localhost:3000

## Future Improvements

Looking to add:

- Highlight words as they're typed
- Save/export files with word counts  
- Visualizations of word data
- Support for additional file types

Please let me know if you have any other questions or ideas for enhancing this app!

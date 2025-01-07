Crossword Generator
A single-page application (SPA) that generates a random 10x10 crossword puzzle with clues, offering a fun and interactive puzzle-solving experience. The crossword grid is dynamically created with symmetrical black spaces, and the words are populated using the Datamuse API.

Features
Random Grid Generation: A 10x10 grid is generated with symmetrical black spaces, creating a challenging puzzle layout.
API-Driven Word Population: Words are fetched from the Datamuse API to populate the grid, ensuring a diverse set of clues.
Automatic Clue Generation: Definitions are automatically generated using the Datamuse API, providing clues for each word in the puzzle.
Automatic Page Reload: In case of a build failure, the page reloads automatically, generating a fresh crossword puzzle.
How It Works
The application generates a 10x10 grid with symmetrical black spaces.
The Datamuse API is called to populate the grid with words.
The API responses provide definitions, which are used as clues for the words.
The puzzle grid and clues are rendered on the page for the user to solve.
Visit the App
You can visit the crossword generator app here:
vincor1986.github.io/crossword-generator
Technical Details
Grid Generation: The grid is generated using a combination of algorithms and random number generation to ensure the symmetry and challenge.
API Integration: The app uses the Datamuse API to fetch words and their definitions, which are used to populate the crossword and provide clues.
Page Reload Mechanism: The app includes an automatic reload feature to regenerate the crossword puzzle if the build fails.
Contributing
We welcome contributions! If you'd like to improve the crossword generator app, please fork the repository and submit a pull request. We're happy to accept bug fixes, feature enhancements, and other improvements.


# Mindcode Zero — Build 2 Testing Prototype

## Run it
1. Extract the ZIP.
2. Keep `index.html` and `study-content.js` in the same folder.
3. Open `index.html` in a modern browser (Chrome recommended).
4. No API key, AI subscription, or installation is required.

## What's new in Build 2
- Fixed canvas coordinate scaling so strokes track the pointer position more accurately on high-DPI screens.
- Added direct on-canvas text objects: select **Text**, click the page, and type in place. Text is editable and can be moved with its small handle.
- Added fullscreen writing workspace and a floating corner tool panel. The panel includes drawing tools, colour/size/background, undo, clear, save, PNG export and page controls.
- Added a **Solve in Free Writing** action during a test. Written work is saved against the current test question, and the test timer pauses while writing.
- Added textbook chapter indexes for 9 uploaded Maharashtra Board Class 10 textbooks covering 10 subject sections: Mathematics Part 1, Mathematics Part 2, Science & Technology Parts 1 and 2, Geography, History, Political Science, English, Hindi and Marathi.
- Added original chapter-focus study guides and starter flashcard, MCQ, write-and-memorize and reading activities.
- Added a starter chapter practice generator. Selected Mathematics chapters include original worked numerical practice. Objective questions are checked; descriptive answers are flagged for manual review.
- Added automatic question marks and per-question marks in results.

## Study content scope and accuracy
The uploaded textbooks are copyrighted works. The Library contained nine textbook PDFs; History and Political Science are two sections of the same book. This app does not reproduce entire textbook chapters or long passages. It uses chapter titles and original concise study guides/practice prompts based on the uploaded book topics. The current build indexes 124 chapter/lesson entries and includes starter study aids; it is **not yet a complete set of detailed notes and exercise-by-exercise question banks for every chapter**. Some older Marathi/Hindi/Geography pages use legacy fonts or scanned layouts and need further OCR/review before reliable detailed notes can be generated. Unverified content should not be treated as a textbook answer.

## Still not included
- Google OAuth, secure cloud accounts, cross-device sync or online backup. Profile data remains local to this browser.
- Infinite canvas, pressure-sensitive stylus support, image insertion, equation keyboard, PDF export and complete folder/notebook organization.
- Full chapter-by-chapter notes and comprehensive question banks for every subject.

## Data and backup
Writing pages, profile details, learning activity and test history are stored in this browser's localStorage. Export a JSON backup from Settings before clearing browser data. This prototype is local-first and does not send your notes to a server.

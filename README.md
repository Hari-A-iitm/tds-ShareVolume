# Bio-Techne Share Tracker
## Summary
This project fetches and displays the outstanding common stock shares of Bio-Techne (CIK 0000842023) from the SEC API. The data is filtered to include only fiscal years after 2020 and is then used to calculate the maximum and minimum share values. The results are displayed in a visually appealing HTML page.

## Setup
To view the project, simply open the `index.html` file in a web browser.

## Usage
The application can be used to track the outstanding common stock shares of Bio-Techne. If a different CIK is provided as a query parameter (e.g., `index.html?CIK=0001018724`), the application will fetch the data for the specified CIK and update the display without requiring a page reload.

## Code Explanation
The project uses JavaScript to fetch data from the SEC API, parse the JSON response, and calculate the maximum and minimum share values. The results are then used to update the HTML page, which includes dynamic elements for the entity name, maximum share value, maximum fiscal year, minimum share value, and minimum fiscal year. The application uses a proxy (e.g., AIPipe) to handle requests for different CIKs.

## License
This project is licensed under the MIT License.
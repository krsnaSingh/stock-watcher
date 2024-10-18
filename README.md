
# StockWatcher

StockWatcher is a web-based application that allows users to track the latest stock prices and visualize real-time changes. It is built using GWT (Google Web Toolkit) and leverages Java for the backend functionality while using CSS for styling.


## Features

- Dynamically update stock prices at regular intervals.
- Add or remove stocks from your watchlist.
- Highlight stock price changes with color coding:
  - **Green** for positive changes.
  - **Red** for negative changes.
  - **Black** for no change.
- Responsive design with a simple and intuitive interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/StockWatcher.git
    ```

2. Navigate to the project directory:
    ```bash
    cd StockWatcher
    ```

3. Ensure you have [GWT](http://www.gwtproject.org/download.html) installed.

4. Compile the GWT project:
    ```bash
    ant build
    ```

5. Run the project:
    ```bash
    ant devmode
    ```


### Key Files

- `MyStockWatcher.java`: The main entry point for the GWT app, handling the user interface and business logic for the stock list.
- `StockPrice.java`: Defines the stock object, including symbol, price, and price changes.
- `StockWatcher.html`: The main HTML file for rendering the web app.
- `MyStockWatcher.css`: CSS file for styling the web app.

## Usage

   1. Open the app in a browser after running the `ant devmode` command.
   2. Enter a stock symbol in the input field and click **Add** or press **Enter**.
   3. Watch the stock prices update in real-time every 5 seconds.
   4. Click the "x" button next to a stock to remove it from the list.


## Screenshots
![Screenshot from 2024-10-18 12-14-52](https://github.com/user-attachments/assets/31ee2d14-5a81-47f7-94a5-2b29fb6b6708)



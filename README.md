# influenza

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application for visualizing reported seasonal influenza patient numbers in Japan. It uses open data from Japan's Ministry of Health, Labour and Welfare to generate interactive charts.

## Demo

This project provides two different visualizations of the influenza data:

1.  **Continuous Timeline View:** Shows a single, continuous chart of weekly influenza reports across all available years.
    -   https://code4fukui.github.io/influenza/

    
![Screenshot of the continuous timeline view, showing a single line graph of influenza cases over several years.](https://user-images.githubusercontent.com/1595839/213852899-8884976f-319a-41d1-9257-2796113800e8.png)


2.  **Yearly Comparison View:** Overlays data from multiple years onto a single weekly axis to compare seasonal trends.
    -   https://code4fukui.github.io/influenza/year.html

    
![Screenshot of the yearly comparison view, showing multiple colored lines on a single graph, each representing a different year's influenza trend.](https://user-images.githubusercontent.com/1595839/213852906-89849226-c56a-4933-9118-293677b1029c.png)


## Features

-   **Continuous Timeline:** Track weekly patient reports sequentially over multiple years.
-   **Yearly Comparison:** Compare influenza seasons by overlaying yearly data on a single chart.
-   **Interactive Charts:** Hover over data points to see specific weekly report numbers.
-   **Lightweight:** Runs entirely in the browser with no server-side dependencies.

## Usage / Development

This is a static web application that can be run locally without a web server.

1.  Clone the repository:
    ```bash
    git clone https://github.com/code4fukui/influenza.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd influenza
    ```
3.  Open `index.html` or `year.html` directly in your web browser.

## Data Source

The data is from the following open data source provided by the Japanese government:

-   [Influenza-related press release materials | Ministry of Health, Labour and Welfare](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/kenkou_iryou/kenkou/kekkaku-kansenshou01/houdou.html)

## License

MIT License — see [LICENSE](LICENSE).
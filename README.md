# Covered Call Profit Calculator

A simple, single-page web application to calculate potential profits from covered call options.


## Features

-   **Stock Details**: Input your stock's ticker, buy price, lot size, and the number of lots you hold. The total invested amount is calculated automatically.
-   **Dynamic Option Chain**: Configure the option chain display by setting the current strike price, the interval between strikes, and the number of strike prices to show above and below the current strike.
-   **Profit Calculation**: For each strike price in the option chain, you can input the premium. The calculator will then automatically compute:
    -   **On Expiry Profit**: The profit you make if the option expires out-of-the-money (i.e., the stock price is below the strike price at expiry).
    -   **On Assignment Profit**: The total profit if the option is exercised (assigned), including the profit from the stock's appreciation and the premium received.
    -   **Percentage Returns**: Both "On Expiry" and "On Assignment" profits are also shown as a percentage of your total investment.

---

MIT License © 2025 Vishnu Haridas. See [LICENSE](LICENSE) for full details.
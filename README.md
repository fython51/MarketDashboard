# Market Dashboard
## What is it?
A composite plot of the trailing-six-month performance of the most relevant government bonds, equity indexes, commodities, and currency pairs.

<br>

## Why would anybody need this?
To get a general overview of the performance of various markets over the last six months. 

<br>

## How does it work?
Run the whole thing, the last cell concatenates a bunch of plots and subplots that is the dashboard itself. You can see in the outputs folder of this repo, or lower down in this ReadMe file, an example of the output in its current state.

<br>

## Which assets are covered?

| Class        | Asset                             | Source                   |
| ------------ | --------------------------------- | ------------------------ |
| Fixed Income | Gov't bonds – United States       | worldgovernmentbonds.com |
| Fixed Income | Gov't bonds – China               | worldgovernmentbonds.com |
| Fixed Income | Gov't bonds – United Kingdom      | worldgovernmentbonds.com |
| Fixed Income | Gov't bonds – Japan               | worldgovernmentbonds.com |
| Fixed Income | Gov't bonds – Germany             | worldgovernmentbonds.com |
| Fixed Income | Gov't bonds – Italy               | worldgovernmentbonds.com |
| Curve        | Italy - Germany gov't bond spread | Internal calculation     |
| Equity       | MIB (Italy)                       | Yahoo Finance            |
| Equity       | China large-cap ETF               | Yahoo Finance            |
| Equity       | FTSE100 (U.K.)                    | Yahoo Finance            |
| Equity       | DE40 (Germany)                    | Yahoo Finance            |
| Equity       | S&P500 (U.S.)                     | Yahoo Finance            |
| Equity       | Hang Seng (H.K.)                  | Yahoo Finance            |
| Equity       | Nasdaq (U.S.)                     | Yahoo Finance            |
| Equity       | Nikkei (Japan)                    | Yahoo Finance            |
| Commodities  | Month-ahead future: Gold          | Yahoo Finance            |
| Commodities  | Month-ahead future: Platinum      | Yahoo Finance            |
| Commodities  | Month-ahead future: Brent crude   | Yahoo Finance            |
| Commodities  | Month-ahead future: Natural gas   | Yahoo Finance            |
| Commodities  | Month-ahead future: Wheat         | Yahoo Finance            |
| Commodities  | Month-ahead future: Corn          | Yahoo Finance            |
| FX           | EUR/USD                           | Yahoo Finance            |
| FX           | EUR/CHF                           | Yahoo Finance            |
| FX           | EUR/JPY                           | Yahoo Finance            |
| FX           | EUR/GBP                           | Yahoo Finance            |
| FX           | GBP/USD                           | Yahoo Finance            |
| FX           | USD/JPY                           | Yahoo Finance            |
| FX           | USD/CHF                           | Yahoo Finance            |
| FX           | USD/AUD                           | Yahoo Finance            |
| FX           | USD/CAD                           | Yahoo Finance            |

<br>

## Example of the output (as of 2023-03-10 11.45)
Keep in mind that the actual charts are interactive, while these are simply screenshots.
<br>
![Example output 1](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_1.png "Example output 1")
![Example output 2](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_2.png "Example output 2")
![Example output 3](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_3.png "Example output 3")
![Example output 4](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_4.png "Example output 4")
![Example output 5](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_5.png "Example output 5")
![Example output 6](https://github.com/fython51/MarketDashboard/blob/main/Outputs/Plot_6.png "Example output 6")


<br>

## To Do's
- [X] Fix outputs
- [X] Add yield curves.
- [X] Add example outputs.
- [X] Add further commodities.
- [X] Add FX.
- [X] Convert to dark mode, so it doesn't feel like you're staring at a lightbulb.
- [X] Format code to the correct python standards.
- [ ] Add further macro indicators.
- [ ] Make this script into its own webpage.
- [ ] **Maybe:** add an _Asset Inputs_ section to add/remove assets.

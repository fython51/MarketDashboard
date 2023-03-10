# Market Dashboard
## What is it?
A composite TSM plot of the most relevant government bonds, equity indexes, and commodity futures.

<br>

## Why would anybody need this?
To get a general overview of market performance over the last six months. 

<br>

## How does it work?
Run the whole thing, the last cell concatenates a bunch of plots and subplots that is the dashboard itself. You can see in the outputs folder of this repo, or lower down in this ReadMe file, an example of the output in its current state.

<br>

## Which assets are covered?

| Class        | Asset                             |
| ------------ | --------------------------------- |
| Fixed Income | Gov't bonds – United States       |
| Fixed Income | Gov't bonds – China               |
| Fixed Income | Gov't bonds – United Kingdom      |
| Fixed Income | Gov't bonds – Japan               |
| Fixed Income | Gov't bonds – Germany             |
| Fixed Income | Gov't bonds – Italy               |
| Curve        | Italy - Germany gov't bond spread |
| Equity       | MIB (Italy)                       |
| Equity       | China large-cap ETF               |
| Equity       | FTSE100 (U.K.)                    |
| Equity       | DE40 (Germany)                    |
| Equity       | S&P500 (U.S.)                     |
| Equity       | Hang Seng (H.K.)                  |
| Equity       | Nasdaq (U.S.)                     |
| Equity       | Nikkei (Japan)                    |
| Commodities  | Gold                              |
| Commodities  | Brent crude                       |
| Commodities  | Natural gas                       |
| Commodities  | Wheat                             |

<br>

_See the script for the sources of each._ 

<br>

## Example of the output (as of 2023-03-10 11.45)
![Example output 1](https://github.com/fython51/MarketDashboard/blob/main/Outputs/explot1.png "Example output 1")
![Example output 2](https://github.com/fython51/MarketDashboard/blob/main/Outputs/explot2.png "Example output 2")
![Example output 3](https://github.com/fython51/MarketDashboard/blob/main/Outputs/explot3.png "Example output 3")
![Example output 4](https://github.com/fython51/MarketDashboard/blob/main/Outputs/explot4.png "Example output 4")
![Example output 5](https://github.com/fython51/MarketDashboard/blob/main/Outputs/explot5.png "Example output 5")


<br>

## To Do's
- [X] Fix outputs
- [X] Add yield curves.
- [X] Add example outputs.
- [ ] Add requirements.txt
- [ ] Add further commodities.
- [ ] Add further macro indicators.
- [ ] Make this baby into its own webpage.
- [ ] **Maybe:** add an _Asset Inputs_ section to add/remove assets.

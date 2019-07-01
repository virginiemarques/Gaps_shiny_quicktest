# Gaps_shiny_quicktest

This repo allows sharing and testing of our shiny-app investigating database gaps in eDNA.

## Display the app 

1) On your local computer

You first need to download the repo, then lauchn R

```bash
git clone https://github.com/virginiemarques/Gaps_shiny_quicktest
cd Gaps_shiny_quicktest/
R
```
After, you need to load 'shiny' to run the app in local inside a R session

```R
library(shiny)
RunApp()
```
2) Using GitHub

You can load the app just by calling the GitHub repo in a local R session
At the moment, the solution is not stable and takes a very long time to load (>10 min)

```R
library(shiny)
runGitHub("Gaps_shiny_quicktest", "virginiemarques")
```



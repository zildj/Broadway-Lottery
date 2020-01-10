# Broadway Lottery
Selenim IDE test suite that automates Broadway lotteries.
## Supported Websites
* [Broadway Direct](https://broadwaydirect.com/)
    * *Must fill out information in script*
* [Lucky Seat](https://www.luckyseat.com/)
    * *Must have an account signed in*
## Instructions
1. Download Selenium IDE addon for [Chrome](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/).
1. Open the *.side* file from this repo in Selenium IDE.
1. Navigate to the script you want to run in the left sidebar.
1. Depending on the script you choose, you may have to fill out your information. Replace the text in the *Target* fields at the top of the script. Save the file so you don't have to do this again.  
    * Ex: Replace ```FIRST NAME HERE``` with ```John```
1. Add a breakpoint at the line that says ```"BREAKPOINT HERE (SELECT + B) - COMPLETE CAPTCHA"```. You must do this everytime you open the script. Breakpoints do not save.  
    * Do this by right-clicking the line and selecting *Toggle Breakpoint* or left-clicking on the line and pressing *B*.
    * You will see a blue marker on the line number.
1. Run the script by clicking the play button or *Ctrl-R*.
1. The script will pause at the breakpoints to allow you to complete captchas. Resume the script after completing a captcha.
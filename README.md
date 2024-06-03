## README - Citations of Contributions/Code Sources

### Starter Code

- Some starter code in provided GitHub repositories had been given by our AP Computer Science Principles teacher for lessons and work to be built off of in order to develop our own fully original code/projects. Below are links to said GitHub repositories.
  - [Original Teacher-Provided Repository (Backend - Base/Template)](https://github.com/nighthawkcoders/flask_portfolio)
  - [Original Teacher-Provided Repository (Frontend - Base/Template)](https://github.com/nighthawkcoders/teacher_portfolio)
- We used the templates of and cloned the provided repositories to have a base on which to build our projects/code. Below are links to said modified repositories in which we developed our original code for the College Board CPT Project (2023-2024).
  - [Modified Backend Repository](https://github.com/tuckergol/backgang)
  - [Modified Frontend Repository](https://github.com/tuckergol/frontgang)
### Stock Project
---
- Created  by Varun Manoj Pillai ( varunm532)
- files concerning this feature: _posts/2024-04-04-stocks.md, _posts/2024-04-04-stockportfolio.md, _posts/2024-04-04-stocktransactionlog.md, _posts/2024-05-20-bucketstockstort.md, _posts/2024-05-21-stocksortdisplay.md
    - _posts/2024-04-04-stocks.md:
        - display top 25 stocks(get request) , shows account balance( post request ), option to buy sell (post request )
        - updates price of all stocks each time page is reloaded
        - requires uid stored in local storage
        - uses JavaScript and HTML
    -  _posts/2024-04-04-stocktransactionlog.md:
        - requires uid stored in local storage 
        - display transaction log of user  ( post request)
        - uses JavaScript and HTML
    -  _posts/2024-04-04-stockportfolio.md:
        - requires uid stored in local storage
        - displays stocks currently owned (post request), uses AnyChart to dynamically create interactive graph (post request), has feature to sell owned stocks (post request)
        - uses JavaScript and HTML
    -  _posts/2024-05-20-bucketstockstort.md:
        - interactive pie chart with differnt sectors of S&P 500
        - works in tandem with _posts/2024-05-21-stocksortdisplay.md to display storted stocks
        - saves selected sector to localStorage
        - redirects to _posts/2024-05-21-stocksortdisplay.md
        - uses JavaScript and HTML
    - _posts/2024-05-21-stocksortdisplay.md:
        - displays sorted stocks based on sectors
        - has buy feature that shows current price of single stock
        - uses stored sector from localStorage
        - displays account balance
        - uses JavaScript and HTML

# Stock Alert Repository
This repository contains the shared files of the Stocks Alert Formula App from Milhomens Apps.

You can get the app from  Google Play at:
https://play.google.com/store/apps/details?id=cat.obiols.milhomens.BorsaValors

From this App you can access to the Stock prices of every stock in the main markets of the World.

If you find out that your market is not in the list, you can add a market to the list at the **markets.xml** file.
You have to name the market as its main Index in Yahoo, for example  Oslo Exchange is ^OSEAX because OSLO EXCH ALL SHARE Index it is accessed from https://finance.yahoo.com/q?s=^OSEAX  and its components can be taken from https://finance.yahoo.com/q/cp?s=^OSEAX


Some markets  need no additional files becaouse Yahoo Finance alrady have already the components of a market, as in our last case or like in  ^IBEX or ^NDX the App gets the symbols automaticatly, in this way:
        https://finance.yahoo.com/q/cp?s=^IBEX

Otherwise, you can add or update the stocks from a market that can not be accessed automatically updating / creating a file on the repository. Once done, make me a pull request and if everything is all right, I will include it.

For example:  
  To update a stock in the Mercado Continuo we should change MC.xml file
  Grifols Symbol at the Mercado Continuo is  GRF.MC , 
  The URL to get Grifols information would be  http://finance.yahoo.com/q?s=GRF.MC

Remeber that the  **Symbols** contained in every file, **have to match with** the symbols that uses **Yahoo Finance**.

I you have any doubt, do not hesitate to contact me at  milhomens.apps@gmail.com

Thanks for using the app !
        

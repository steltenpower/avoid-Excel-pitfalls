Well-meaning people using Excel, are without realizing it, too often making analysts and coders cry for inefficiency reasons.
This is very costly, both financially and emotionally, and must be improved:
<img src="https://repository-images.githubusercontent.com/244763599/c07ee780-7893-11eb-92b4-f02910371f4e">
- I suggest to have everybody invest a few hours in ["Data Organization in Spreadsheets ..."](https://datacarpentry.org/spreadsheet-ecology-lesson/), from the awesome carpentries.org, for which I am a certified instructor. "We teach foundational coding and data science skills to researchers worldwide."
- Advertise that course, this page, or your own, widely in contexts, including in the default 'new Excel sheet'.
- Try a pre-structured spreadsheet, like what I made a rough sketch for in the Excel file in this repo.
- When the 'damage' is already done, and you have to figure out the (implicit and hidden?) structure of an already existing Excel spreadsheet, look at https://mobile.twitter.com/steltenpower/status/1330290665322934278
- Questions will arise and Digital Competence Centers and the like should be great at answering them
- It is not uncommon that finding and cleaning of data takes way more time than everything else in a project. Put that in your planning and make sure managers read it, to make sure they think about investing in data quality.
- (Mental note: Excel's comma-delimited .csv is actually semi-colon (;) delimited. See if there are carpentries.org courses to explain this and maybe mention how to roundtrip from Python/R with Excel on CSV)
- [Why electronic notebooks make you work together faster and fewer errors](https://github.com/steltenpower/PowerGists/blob/main/animation.md)
- If datacarpentry and softwarecarpentry sound scary, try [Library Carpentry](https://librarycarpentry.org/)

If you actually want or need further structuring of data:
- [oversimplified ultra-summary of FAIR data principles](https://srs.saxion.nl/wp-content/uploads/2019/01/SRS_poster_2019_FAIR-724x1024.jpg), from there go to [GO_FAIR](https://go-fair.org) for the real deal.
- [Data-centric Manifesto](http://datacentricmanifesto.org/) Data 1st!, applications should be 'mere visitors'.
- [an example of a research Data Management Plan template](https://srs.saxion.nl/dmp_template/)
- Some of my related brainstorm-[ideas on getting&using data FAIR&early in happy cooperation workflows](https://github.com/search?q=user%3Asteltenpower+fair-early)

Excel is not all bad if you know how to use it, plus there are nice extensions:
- [E2D3](https://e2d3.org) (Excel to D3, where D3 stands for Data Driven Documents; aka the most used library for defining your own visualisations)
- [Excel querying Linked Open Data cloud](https://mobile.twitter.com/kidehen/status/1248711829070774274)
- [Perfect XL](https://www.perfectxl.com/) helps some

Spreadsheets can show the output of many cells, but the formula of only 1. That's like looking through a peephole, instead of proper coding. I propose to no longer show formulas exclusively 1-on-1 per cell, but in some sort of code view besides the sheet. And why stick to only 1 source view; pick whatever you like: cells, linear text, graph

Actually, the problem seems less bad: https://www.bilibili.com/video/BV1734y187KS/?share_source=copy_web "You suck at Excel", 1 highlight: Ctrl-backtick switches between values and formulas. https://www.ablebits.com/office-addins-blog/show-formulas-excel/#:~:text=In%20your%20Excel%20worksheet%2C%20go,again%20to%20toggle%20it%20off.

How to implement: Seems done: https://towardsdatascience.com/interactive-spreadsheets-in-jupyter-32ab6ec0f4ff and https://github.com/mito-ds/monorepo#-mito-monorepo

otherwise:

Make it inside of E2D3 (has JavaScript references to cells in Excel-embedded web browser), or as an Excel extension like E2D3 is.
If the above doesn't work, try this route through R: https://mobile.twitter.com/steltenpower/status/1330290665322934278
Also to name columns: select all of them, then Enter key moves you right

Also look at:

Excel doing Lambda, or User Defined Functions nowadays.
Deep Spreadsheets
https://blockpad.net/
https://observablehq.com
See how far you can get with Jupyter
Microsoft must have something like this. Can you tell me? VBA? Though I strongly prefer open source.

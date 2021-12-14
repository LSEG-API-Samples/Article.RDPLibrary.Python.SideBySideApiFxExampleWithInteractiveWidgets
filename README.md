# Article.RDPLibrary.Python.SideBySideApiFxExampleWithInteractiveWidgets
# Side by Side API In Python: An FX Example With Interactive Widgets

In this article, I exemplify how one may use pre-existing articles (such as [Umer's](https://developers.refinitiv.com/en/article-catalog/article/instrument-pricing-analytics-volatility-surfaces-and-curves)) together to form Jupyter Python Apps working anlongside your Workspace Tiles environment using the [Refinitiv Side by Side API](https://developers.refinitiv.com/en/api-catalog/eikon/workspace-web-side-by-side-api).

1st, we will use Python functions created by Umer in his [Instrument Pricing Analytics - Volatility Surfaces and Curves](https://developers.refinitiv.com/en/article-catalog/article/instrument-pricing-analytics-volatility-surfaces-and-curves) article to create [FX Volatility Surfaces](https://www.investopedia.com/articles/stock-analysis/081916/volatility-surface-explained.asp).

2nd, we will inbed such graphs in a widget, using techniques shown in CodeBook examles (in '__ Examples __/04. Advanced UseCases/04.01. Python Apps/EX_04_01_02__WFCH_Company_Income_Statement_Waterfall.ipynb') and online (shout out to [ac24](https://stackoverflow.com/questions/50842160/how-to-display-matplotlib-plots-in-a-jupyter-tab-widget)).

3rd, we will finally incorporate this workflow with the [Refinitiv Side by Side API](https://developers.refinitiv.com/en/api-catalog/eikon/workspace-web-side-by-side-api) so that Tiles become linked with our notebook, reacting to them live (shout out to [Evgeny Kovalyov](https://github.com/zhenyakovalyov)).

In this article, we look at a simple example with an FX Quote Tile and Volatility Surfaces; but you are encouraged to use this code and work to create your own applications that work ergonomically with your workflow, whatever it may be. The techniques used bellow are very maleable, and do not have to be used specifically for Volatility Surface creation. If you have an idea in mind and would like some help to code them up, don't hesitate to submit your idea on the [Article Competition](https://docs.google.com/forms/d/e/1FAIpQLSdUk6inKvZD50MHA7qAqRC5vanlGf88oIixVePiQ1eXw5PiZw/viewform) and contact me.

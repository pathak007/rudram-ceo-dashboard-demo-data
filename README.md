# CEO Dashboard demo data (synthetic)

Daily-updated example data for the CEO Dashboard demo of **Demo Cleaning Co Pty Ltd**, a fictional Perth cleaning business. Every client, person and figure here is made up by a simulation. None of it is real business data.

- `data/cleaning/*.csv`: the star-schema tables the Power BI model reads (fact tables, dimensions, configuration, narrative)
- `data/metrics.json`: headline figures for the current window, used as the Power BI test sheet and by the narrative engine
- `data/reconciliation_report.txt`: every dashboard figure and the consistency checks it passed

Updated once a day. History is append-only: past days never change, only new days are added. The narrative is refreshed weekly.

Built by [Rudram Data Solutions](https://rudramdata.com).

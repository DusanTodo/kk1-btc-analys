# Bitcoin: En tillgång som mognar (av Dusan Todorovic, ai-python-hai25ha/kunskapskontroll/KK1/)

## Vad datasetet är och varifrån det kommer

- Datasetet innehåller historisk marknadsdata för Bitcoin (BTC) i par med USD. Det består av kolumner som datum "Day", stängningspris "Close" och handelsvolym "Volume" aggregerat på daglig basis för att analysera finansiella trender och marknadsmognad mellan 2012 och 2026.
- Ursprungsdatan är hämtad från **Kaggle (Bitcoin Historical Data)** och baseras på historiska transaktioner från kryptobörser (t.ex. Bitstamp/Coinbase). Den ursprungliga tidsupplösta filen btcusd_1-min_data.csv har aggregerats till en mer lätthanterlig daglig fil btcusd-daily.csv.  
  https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data

## Projektets innehåll

Jupyter-notebooken notebook.ipynb utforskar datan genom fyra obligatoriska visualiseringar enligt "Kartografens beslutsprocess" och Anscombes lärdom:

- Linjediagram: Långsiktig exponentiell pristrend över tid.
- Histogram: Distribution av dagliga priser och visuelt dolda mönster.
- Scatter plot: Samband och korrelation mellan volym och stängningspris.
- Boxplot: Årlig prisdistribution som visar hur tillgången mognar och stabiliseras med tiden.

## Hur notebooken körs

Följ dessa steg för att köra analysen lokalt:

1. Installera nödvändiga Python-bibliotek:

- bash/terminal/powershell
- pip install pandas matplotlib seaborn numpy

2. Öppna projektet: Starta VS Code eller Jupyter Notebook och öppna filen notebook.ipynb.

3. Kör cellerna: Kör kodcellerna sekventiellt (uppifrån och ned) för att läsa in den aggregerade datan från folder /data och generera graferna.

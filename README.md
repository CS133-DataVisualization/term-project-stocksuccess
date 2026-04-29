# CS133 Stock Success Project
Lexinejazly Asuncion, Pranavi Immanni, Anika Manjesh

Datasets sourced from Nasdaq and Kaggle:
Tech
Apple: 2005-2025
https://www.kaggle.com/datasets/pranavlakhotiakaggle/apple-stock-price-history-2005-2025/data
Nvidia: 2000-2025
https://www.kaggle.com/datasets/abdulmoiz12/nvidia-stock-dataset-2025 
Microsoft: 1986-2025
https://www.kaggle.com/datasets/muhammadatiflatif/complete-microsoft-stock-dataset-19862025 
Defense
Lockheed Martin: 2000-2024
https://www.kaggle.com/datasets/middlehigh/lockheed-martin-stocks
Northrop Grumman: 2016-2026
https://www.nasdaq.com/market-activity/stocks/noc/historical 
Boeing: 1962-2024
https://www.kaggle.com/datasets/ahmadwaleed1/boeing-company-ba-stock-prices-1962-2024 

Waste Management
Waste Management, Inc: 2016-2026
https://www.nasdaq.com/market-activity/stocks/wm/historical
Republic Services, Inc: 2016-2026
https://www.nasdaq.com/market-activity/stocks/rsg/historical
Waste Connections, Inc: 2016-2026
https://www.nasdaq.com/market-activity/stocks/wcn/historical 

## Project Setup

Follow these steps to set up the project locally and start working with the Jupyter Notebook.

### First-Time Setup

**1. Clone the repository**
```bash
git clone https://github.com/CS133-DataVisualization/term-project-stocksuccess.git
cd term-project-stocksuccess
```

**2. Create a virtual environment**
```bash
python3 -m venv venv
```

**3. Activate the virtual environment**
```bash
source venv/bin/activate
```
*Note: You should now see `(venv)` in your terminal.*

**4. Install dependencies**
```bash
pip install -r requirements.txt
```

**6. Run Jupyter Notebook**
```bash
jupyter notebook
```
*Note: Open the link shown in your terminal (usually http://localhost:8888).*

---

## Subsequent Usage

After completing the initial setup, you only need to run these commands:

```bash
cd path/to/term-project-stocksuccess
source venv/bin/activate
jupyter notebook
```

---

## Saving Changes

To save and upload your work:

In jupyter: File -> Save All

In your terminal:

```bash
git status
git add .
git commit -m "Update project files"
git push
```


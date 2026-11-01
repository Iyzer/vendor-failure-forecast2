# Vendor Failure Forecast (Weeks 10 and 11)

MS Analytics, Saint Louis University. Team: Mirza Ali and Debra Senteu.

A weekly forecast of which suppliers are likely to fail a delivery, and a review list for the Purchasing & Receiving Manager of a seasonal independent resort. All data is synthetic: it shows how the method behaves, not how a real property would perform.

## Live app

*(Streamlit link to be added here after deployment.)*

The app opens on the Week 11 version. Add `?version=week10` to the address to see the Week 10 version, which is kept unchanged.

## What is in this repository

| File | What it is |
|---|---|
| `streamlit_app.py` | The Streamlit app. One self-contained file: the forecast model, charts and what-if controls run in the browser, and both app versions are embedded in it. |
| `Week11_Evaluation_Report.pdf` | The Week 11 evaluation report (test design, leakage check, KPIs and baselines, error analysis, improvements, limits, decision support, outside test, package). |
| `Vendor_Failure_Forecast_Week11_Full_Package.zip` | Everything else, in folders: the Week 11 app source and offline copy, code (`run_all.sh` rebuilds all results), data and source tables, browser tests, usability test kit, video script, contributions draft, and the unchanged Week 10 submission (`Week10_frozen/`). |

## Where to start inside the zip

1. Unzip it. Open `Vendor_Failure_Forecast_Week11/README.md`, then `Week11_Vendor_Risk_Forecast/README.md`. The second one lists every file, the setup and dependencies, how requirements 1 to 5 are covered, and the items the team still has to finish.
2. To see the app offline, open `Week11_Vendor_Risk_Forecast/app/index.html` in any browser.
3. The Week 10 version is in `Week10_frozen/`.

## Not stored here

The two silent screen recordings that accompany the video script (about 24 MB) and regenerable screenshots are left out because of their size. The finished narrated video will be linked here.

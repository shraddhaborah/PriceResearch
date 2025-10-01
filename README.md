# PriceResearch

Overview

This project compiles current prices for four requested items across multiple reputable U.S. retailers. The data was collected manually from sites such as Amazon, Staples, Office Depot, Best Buy, and Walmart, then organized into an Excel file and summarized in a Word report with visualizations.

The goal was to demonstrate research ability, attention to detail, and organizational skills.

Files Included

price_research_template.xlsx

Data sheet: raw quotes (each row = one item from one retailer).

Summary sheet: automatically calculates lowest price, retailer of lowest, average price, and last update.

ReadMe sheet: usage notes.

Price_Research_Summary.docx

One-page report with summary charts and key findings.

README.md (this file)

Methodology

Identified product specifications:

Laptop: Acer Swift Go, Intel Evo, i7, 14", 1920×1200 Touch, 100% sRGB.

Printer: Brother MFC-L6700DW All-in-One Monochrome Laser Printer.

Notebooks: 3 × standard spiral notebooks (college-ruled, ~70–100 pages).

Stapler + Staples: Standard full-strip stapler with ¼-inch staples.

Collected 3–5 quotes per item from reputable online retailers.

Recorded price, shipping, tax rate, stock status, and URL in the Data sheet.

Calculated Total Price = Item Price + Shipping + (Item Price × Tax%).

Used Excel formulas and Python (in Google Colab) to generate summaries and visualizations.

Assumptions

Prices reflect current listings on the day of collection; they may fluctuate over time.

Shipping was included where available; otherwise assumed free.

Taxes used a standard 8.875% example (NYC rate) if not explicitly provided.

Lowest and average prices exclude out-of-stock items.

Visuals Generated (in Word report)

Bar chart: Lowest total price by item.

Bar chart: Average total price by item.

Horizontal bar: Lowest price with retailer labels.

(Optional) Box plot: Distribution of prices by item.

How to Use the Excel File

Open price_research_template.xlsx.

Go to the Summary sheet to quickly see:

Lowest total price and retailer (with URL).

Average total price.

Number of quotes collected per item.

Date of last update.

Check the Data sheet if you want to verify individual quotes.

Next Steps

This document and spreadsheet can be emailed along with the completed task.

For reproducibility, Python scripts (Colab) can re-generate visuals if needed.

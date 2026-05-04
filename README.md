# 📊 Auto-Quant - Improve trading strategies using artificial intelligence

[![](https://img.shields.io/badge/Download_Auto-Quant-blue.svg)](https://github.com/gabrielsmonteiro87-web/Auto-Quant)

Auto-Quant automates the process of testing and refining trading strategies. It uses artificial intelligence to update strategy code, run tests, and save the best results. The software focuses on crypto assets like Bitcoin, Ethereum, Solana, Binance Coin, and Avalanche. It tests these across different timeframes to find patterns.

## ⚙️ Minimum System Requirements

Your computer needs the following to run this software:

*   Operating System: Windows 10 or Windows 11 (64-bit).
*   Processor: Intel Core i5 or AMD Ryzen 5 or better.
*   Memory: 8 GB RAM minimum, 16 GB recommended.
*   Storage: 2 GB of free disk space.
*   Internet: Stable connection for downloading updates and external data.

## 📥 Downloading the Software

You must download the repository to your computer to begin.

1. Go to this link: [https://github.com/gabrielsmonteiro87-web/Auto-Quant](https://github.com/gabrielsmonteiro87-web/Auto-Quant).
2. Look for the green button labeled "Code" near the top right of the page.
3. Click the button and select "Download ZIP".
4. Choose a folder on your computer to save the file.

## 🛠️ Setting Up Your Computer

The software requires a few extra tools to function correctly. 

1. Install Python from the official Microsoft Store or the Python website. Ensure you check the box that says "Add Python to PATH" during installation.
2. Open your Windows Start menu and type "Powershell".
3. Right-click "Windows PowerShell" and select "Run as Administrator".
4. Type `pip install freqtrade` and press Enter to install the testing engine.
5. Wait for the process to finish.

## 🚀 Running the Automated Loop

Once your setup is complete, you can start the research loop.

1. Navigate to the folder where you saved the files.
2. Find the file named `program.md`. This file contains the instructions for the agent.
3. Open your terminal in the main folder of the project.
4. Execute the command provided in your setup instructions to start the loop.
5. The agent will begin testing strategy modifications. 
6. Watch the terminal output as the agent performs backtests.
7. The software generates a file named `results.tsv` in your folder. This file contains the performance data of every test the agent completed.

## 🔍 Understanding the Results

The software generates data based on historical price movements. It does not look at future markets. The goal of this tool is to help you see how different strategy logic impacts outcomes.

Pay attention to:
*   Indicator changes: Did the agent add or remove trading indicators?
*   Win rate: Does the strategy succeed more often with the changes?
*   Drawdown: How much capital did the strategy lose during the worst periods?

You can open `results.tsv` in any spreadsheet program like Excel or Google Sheets to sort and filter your findings.

## 🛡️ Important Safety Notes

Auto-Quant serves as a research prototype. It helps you understand how an agent finds useful patterns. It does not provide financial advice. Never use this tool to manage real money without deep knowledge of how the strategies function. The automated loop generates many ideas, but not all of them work well in a live environment. Test all findings in a simulated environment before taking any action with your own capital.

## ❓ Frequently Asked Questions

**Does this software connect to my exchange?**
No. This software runs on your local machine using static data for testing. It does not place live trades.

**How do I stop the loop?** 
Press `Ctrl + C` in the terminal window where the process is running. This will halt the ongoing task immediately.

**Can I use other cryptocurrencies?** 
Yes. You can edit the configuration files to include different trading pairs. Ensure your data sources provide historical information for those specific coins.

**What happens if the software crashes?**
Check your internet connection and verify that Python is installed correctly. Use the terminal to check for error messages that explain why the process stopped.

**Is my data private?**
Yes. Everything stays on your local machine. No external service accesses your results or strategy logic.
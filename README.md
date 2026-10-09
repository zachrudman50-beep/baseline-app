# Baseline

Your food, weight, bloodwork and body scans in one Windows app, with an AI coach that remembers all of it.

## Download

**[Download Baseline for Windows (zip, 330 KB)](https://github.com/zachrudman50-beep/baseline-app/releases/latest/download/Baseline-2.2-Windows.zip)**

Every version is listed on the [Releases page](https://github.com/zachrudman50-beep/baseline-app/releases).

## Install

1. Open the zip, choose **Extract all**, and move `Baseline.exe` somewhere permanent, like Documents.
2. Open `Baseline.exe`. Windows may say "Windows protected your PC" because the app isn't signed by a known publisher. Click **More info**, then **Run anyway**.
3. While it's open, right-click its icon in the taskbar and choose **Pin to taskbar**.

Runs on Windows 10 and 11 (64-bit). It uses Microsoft Edge WebView2, which is built into Windows 11 and most Windows 10 PCs. If it's missing, the app offers the download.

## What it does

- **Today:** log food by describing it, snapping a photo or entering numbers. Track calories, protein, carbs, fat, water, steps and sleep.
- **Progress:** a smoothed weight trend, your target line, this week compared with last, and a projected goal date.
- **Bloodwork:** read lab results in from a photo, flag anything out of range, and get a plain-English explanation.
- **Body scan:** photos are analysed for where you carry fat, with a body-fat estimate and comparisons over time.
- **Coach:** an AI coach that uses your own numbers, remembers what you tell it, and can log food and weight from chat.
- **Plan:** calorie and protein targets from your goal and pace that adjust as your weight changes, plus over 50 settings.

## Your data

Everything is saved to one file on your PC (`%LOCALAPPDATA%\Baseline\data\baseline-data.json`), with 90 days of history kept. Nothing is uploaded anywhere except the requests the AI features send to Claude. The only way to erase it is **Settings → Data → Delete all my data**.

## AI features

The coach, food estimates, bloodwork reading and body scans run on Claude Haiku 5.5 through the Claude API. Add your own API key from [console.anthropic.com](https://console.anthropic.com) in **Settings → AI connection**. API use is billed by Anthropic separately from a Claude subscription. Setting a monthly spend limit in the Console is a good idea.

Baseline gives general fitness guidance, not medical advice.

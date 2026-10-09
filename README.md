# Baseline

Your food, workouts, weight, bloodwork and body scans in one Windows app, with **Miccah**, an AI health assistant who remembers all of it.

## Download

**[Download Baseline for Windows (zip, 355 KB)](https://github.com/zachrudman50-beep/baseline-app/releases/latest/download/Baseline-Windows.zip)**

This link always gets the newest version. Older versions are on the [Releases page](https://github.com/zachrudman50-beep/baseline-app/releases).

## Install

1. Open the zip, choose **Extract all**, and move `Baseline.exe` somewhere permanent, like Documents.
2. Open `Baseline.exe`. Windows may say "Windows protected your PC" because the app isn't signed by a known publisher. Click **More info**, then **Run anyway**.
3. While it's open, right-click its icon in the taskbar and choose **Pin to taskbar**.

Runs on Windows 10 and 11 (64-bit). It uses Microsoft Edge WebView2, which is built into Windows 11 and most Windows 10 PCs. If it's missing, the app offers the download.

## What it does

- **Miccah:** an AI assistant in the corner of every screen. Ask any health question, or tell him what you ate, drank or did and he logs it. He nudges you when something needs attention.
- **Today:** a daily Baseline Score from 0 to 100, a calorie ring with macros, quick actions, and trackers for water, steps and sleep.
- **Food:** describe a meal, snap a photo, enter numbers, or re-log recent and favourite foods in one tap.
- **Workouts:** 12 activity types with estimated calories burned, optionally added to your daily budget.
- **Body:** weigh-ins with a smoothed trend, body measurements, and a US Navy body-fat estimate.
- **Progress:** weight trend and goal date, week-over-week comparison, score and activity charts, and a weekly report from Miccah.
- **Bloodwork:** read lab results in from a photo, flag anything out of range, and get a plain-English explanation.
- **Body scan:** photos are analysed for where you carry fat, with comparisons over time.
- **Apple Health import:** steps, sleep, weight, workouts, resting heart rate and food from the iPhone Health app export.
- **20 achievements**, a command palette (Ctrl+K), keyboard shortcuts, light and dark mode, and over 50 settings.

## Your data

Everything is saved to one file on your PC (`%LOCALAPPDATA%\Baseline\data\baseline-data.json`), with 90 days of history kept. Nothing is uploaded anywhere except the requests the AI features send to Claude. The only way to erase it is **Settings → Data → Delete all my data**.

## AI features

Miccah, food estimates, bloodwork reading and body scans run on Claude Haiku 5.5 through the Claude API. Add your own API key from [console.anthropic.com](https://console.anthropic.com) in **Settings → AI connection**. API use is billed by Anthropic separately from a Claude subscription. Setting a monthly spend limit in the Console is a good idea.

Baseline gives general fitness guidance, not medical advice.

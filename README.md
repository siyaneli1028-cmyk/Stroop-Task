# Stroop Color-Word Test — Social Facilitation & Observation Study

Standardized 50-item web-based Stroop Color-Word Test built for psychology research on:
**"The Effect of Being Observed on Task Performance Among Psychology Students"**

## Quick Start (Run Locally on Any Computer)

### Requirements
- Node.js (version 18 or higher): [https://nodejs.org](https://nodejs.org)

### Installation & Execution
1. Unzip this project directory.
2. Open a terminal / command prompt in this folder:
   ```bash
   npm install
   ```
3. Start the local offline server:
   ```bash
   npm run dev
   ```
4. Open your browser at `http://localhost:5173` or the URL printed in terminal.

### Production Build (For offline lab machines or campus hosting)
```bash
npm run build
```
The resulting static files in `dist/` can be served by any static web server (Apache, Nginx, or directly opened).

## Features
- **50 Scored Items**: 25 Congruent and 25 Incongruent trials, randomized.
- **Silent Background RT Recording**: Monotonic high-resolution timing via `performance.now()` without distracting visible countdowns.
- **Observed vs. Unobserved Condition**: Standardized protocol with checklist.
- **Privacy Compliance**: Uses participant codes (e.g. P001); no full names gathered.
- **Local Storage**: Data stays on the testing machine; zero external server transmission.
- **CSV Exports**: Trial-level (all 50 items) and summary CSVs.

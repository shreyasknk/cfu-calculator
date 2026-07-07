# CFU Calculator Pro

A colony forming unit (CFU) calculator for microbiology lab work — built for spread/pour-plate dilution series.

## Features
- Multi-sample support (run several dilution series in one session, compare side by side)
- Liquid (CFU/mL) and solid (CFU/g) unit modes
- Automatic 30–300 countable-range validation
- Statistical outlier detection (median-deviation check)
- CSV export of sample comparisons
- Print-friendly report view

## Usage
Open `index.html` in any browser — no build step, no dependencies. All calculations run client-side in JavaScript.

## Formula
```
CFU/mL = colonies counted ÷ (dilution factor × volume plated)
CFU/g  = colonies counted ÷ (dilution factor × sample weight plated)
```

Built by Shreyas — M.Sc. Microbiology, Davangere University.

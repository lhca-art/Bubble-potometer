# Bubble Potometer Documentation

## Project Overview
The Bubble Potometer is a scientific tool used to measure the rate of water uptake in plants, enabling researchers to draw conclusions about plant physiology and water transport mechanisms.

## Features
- **Real-time measurement** of water uptake.
- **Data logging** for further analysis.
- **User-friendly interface** for ease of operation.
- **Portability**, allowing usage in various environments.

## Physics Model
The Bubble Potometer works on the principle of measuring the air bubbles produced by aquatic plants submerged in water, as they absorb water for photosynthesis. The rate at which these bubbles are produced gives an indication of the plant’s water uptake.

## File Structure
```plaintext
/Bubble-potometer
├── src          # Source code files
│   ├── main.py  # Main execution file
│   └── utils.py  # Utility functions
├── data         # Data files
│   └── measurements.csv  # Collected data
└── tests        # Test files
    └── test_main.py  # Unit tests for main script
```

## Usage Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/lhca-art/Bubble-potometer.git
   cd Bubble-potometer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python src/main.py
   ```

## Teaching Activities
- **Lab Experiment:** Setting up a bubble potometer and measuring plant water uptake.
- **Data Analysis:** Analyzing collected data to draw conclusions about plant behavior.
- **Discussion:** Discussing the implications of water uptake on plant health and growth.

## Scientific Background
Understanding how plants absorb water is crucial for studying their physiology. The Bubble Potometer provides practical insights into this process by directly observing water uptake rates.

## Technical Details
- **Programming Language:** Python
- **Dependencies:** `numpy`, `pandas` for data manipulation; `matplotlib` for data visualization.
- **Data Format:** Measurements are stored in CSV format for compatibility with various data analysis tools.

---
This documentation will help users understand the workings of the Bubble Potometer and how to utilize it effectively for scientific research.
# Unit Converter

A flexible and extensible unit conversion library with a graphical user interface. This project provides a framework for converting between different units of measurement, with support for temperature, length, weight, and volume conversions.

## Features
- **Modular Design**: Base converter class that can be extended for any unit type.
- **Temperature Conversion**: Convert between multiple temperature scales (Celsius, Fahrenheit, Kelvin, Rankine, Réaumur etc...)
- **Length Conversion**: Convert between multiple length scales (meters, feet, miles, kilometers, inches, yards, nautical miles etc...)
- **Weight Conversion**: Convert between multiple weight scales (grams, kilograms, pounds, ounces, stones, metric tons etc...)
- **Volume Conversion**: Convert between multiple volume scales (liters, gallons, cups, pints, quarts, fluid ounces, cubic meters, cubic feet etc...)
- **Area Conversion**: Convert between multiple area scales (square meters, square feet, square miles, square kilometers, acres, hectares etc...)
- **Speed Conversion**: Convert between multiple speed units (meters per second, kilometers per hour, miles per hour, knots, mach, speed of light etc...)

- **User-friendly GUI**: Tkinter-based interface with:
  - Input validation
  - Unit swapping
  - Support for both absolute values and intervals (delta)
  - Error handling
- **Extensible**: Easy to add new unit converters

### Requirements

- Python 3.6 or higher
- Tkinter (usually included with Python, but may require separate installation on certain Linux distributions)

### Test Environment

## 🧪 Testing Environment

### Manual Testing
The project was manually tested in the following environment:

- **Operating System:** Windows 11  
- **Python Version:** 3.13.7  
- **Python Libraries:**  
  - `Tkinter` (included with Python)  
  - `pytest` (for automated testing)  
- **Notes:**  
  No additional external libraries were required for testing.

---

### Automated Testing (GitHub Actions)
Continuous Integration (CI) was configured using **GitHub Workflows** to ensure cross-platform and multi-version compatibility.  
The test matrix used was:

```yaml
matrix:
  os: [ubuntu-latest, windows-latest, macos-latest]
  python-version: ["3.8", "3.9", "3.10", "3.11", "3.12", "3.13", "3.14"]
  include:
    # Add Python 3.6 and 3.7 only for Windows
    - os: windows-latest
      python-version: "3.6"
    - os: windows-latest
      python-version: "3.7"

### Installation

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Ivexx4/unit-converter-whit-gui.git
   cd converter


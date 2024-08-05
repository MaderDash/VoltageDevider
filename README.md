# VoltageDevider

# VoltageDevider Project Summary

## Current Status
We've implemented a basic voltage divider calculator with a PySimpleGUI interface. The app currently:
- Uses E-series resistor values (E3, E6, E12, E24, E48, E96)
- Calculates and displays multiple resistor combinations
- Shows voltage, current, and power for each combination
- Avoids redundant resistor combinations
- Uses a Discord-inspired theme for the GUI

## Next Steps
1. Implement tolerance calculations
   - Add tolerance values for each E-series
   - Calculate and display the effect of tolerance on output voltage

2. Add filtering options
   - Total resistance (min/max)
   - Power limits
   - Current limits

3. Implement circuit load input
   - Allow user to specify load resistance
   - Recalculate voltage divider considering load effect

4. Create info popup
   - Display formulas for voltage divider calculations
   - Show base E-series values
   - Provide brief usage instructions

## Implementation Details
- Use PySimpleGUI for all GUI elements
- Maintain Discord theme for consistency
- Ensure all new features are integrated into the existing calculate_voltage_divider and find_best_resistor_combinations functions
- Update the layout to include new input fields for filters and load
- Consider adding a separate tab or window for the info popup

## Goals
- Create a comprehensive, user-friendly voltage divider calculator
- Provide practical results for real-world applications
- Educate users about voltage divider principles and E-series resistors

Remember to update the VoltageDevider.py file with each new feature implementation.


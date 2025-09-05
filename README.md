# WaveRider Trading Technologies

Welcome to the WaveRider Trading Technologies repository. This project contains trading indicators and analysis tools built with Pine Script v5.

## Project Structure

```
WTT_Vlm/
├── src/                    # Source code directory
│   └── indicators/         # Pine Script indicators
│       └── VolumeSpikeSignals_v1.1.pine
├── docs/                   # Documentation
│   └── user_guides/        # User guides for indicators
│       └── VolumeSpikeSignals_UserGuide.md
├── examples/               # Example usage and templates
│   └── IndicatorTemplate_v1.1.pine
├── tests/                  # Test files
└── README.md              # This file
```

## Current Indicators

### Volume Spike Signals (v1.1)
- **File**: `src/indicators/VolumeSpikeSignals_v1.1.pine`
- **Description**: Generates long and short signals based on unusual spikes in volume
- **Features**:
  - Volume spike detection with customizable thresholds
  - Price confirmation using ATR or fixed percentage
  - Configurable alert system
  - Orange/purple color scheme for signals
- **User Guide**: `docs/user_guides/VolumeSpikeSignals_UserGuide.md`

## Getting Started

1. **Installation**: Copy any `.pine` file to your TradingView Pine Script editor
2. **Configuration**: Adjust parameters based on your trading style and market conditions
3. **Documentation**: Refer to the user guides in the `docs/` folder for detailed instructions

## Features

- **Pine Script v5**: All indicators use the latest Pine Script version
- **Conservative Defaults**: Settings optimized for reliability over signal frequency
- **Comprehensive Alerts**: Built-in alert system with dynamic messages
- **User Guides**: Detailed documentation for each indicator
- **Template System**: Reusable templates for creating new indicators

## Coding Standards

- **Version Control**: Each indicator includes revision history in comments
- **Naming Convention**: `IndicatorName_vVersion.pine`
- **Color Scheme**: Orange for long signals, purple for short signals
- **Alert System**: Uses `alert()` function with `alert.freq_once_per_bar`
- **Conservative Settings**: Default parameters prioritize signal quality

## Contributing

When creating or modifying indicators:
1. Follow the established coding conventions
2. Update revision history in file comments
3. Create comprehensive user guides
4. Test thoroughly before deployment
5. Use conservative default settings

## License

This project is proprietary to WaveRider Trading Technologies.

---

**Note**: These indicators are designed as tools to assist in trading decisions. Always use proper risk management and consider multiple factors when making trading decisions. Past performance does not guarantee future results.

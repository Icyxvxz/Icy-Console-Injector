# Icy Console Injector

A Roblox FFlag injector for modifying game settings and flags.

## Features

- Inject custom FFlags into Roblox
- Support for string, integer, and boolean flag types
- Automatic process attachment
- LRU caching for improved performance
- UTF-8 console support

## Usage

1. Run the injector:
   ```bash
   python main.py
   ```

2. Place your `fflags.json` file in the same directory as the script

3. The injector will automatically attach to Roblox and apply the flags

## FFlags.json Format

```json
{
    "FFlagSomeFlag": true,
    "FIntSomeInt": 100,
    "FStringSomeString": "value"
}
```

## Requirements

- Python 3.8+
- Windows OS
- RobloxPlayerBeta.exe running

## Disclaimer

This tool is for educational purposes only. Use at your own risk.

# Kinesis - Location Spoofing for iOS 17

Built with `pymobiledevice3` and `leaflet`.

## Requirements

- Python version 3.11.X
- iOS Device in [developer mode](https://developer.apple.com/documentation/xcode/enabling-developer-mode-on-a-device)

## Run

This project uses poetry. It's a modern dependency management
tool.

To run the project use this set of commands:

```bash
poetry install
poetry run sudo python -m cv_copilot
```

This will start the project on the configured host.

You can read more about poetry here: <https://python-poetry.org/>

Browse [http://localhost:3000](http://localhost:3000)

## TODO

- [x] Run with one-command
- [ ] Better UI
- [x] Randomized location
- [x] Adjustable speed -> Choose between 3 speeds
- [x] Randomized speed
- [x] Closed path -> Use "loop" mode
- [x] Persist zoom and center
- [ ] OSRM Routing (?)
- [ ] Saved route
- [ ] ~~Electron~~ (why bother)
- [ ] ~~Get out of vanilla js before it's too late~~  (why bother)

# Home Occupancy Console Voice Control

Build a smart home prototype that uses BME280, light sensor to accept local voice commands. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 93 |
| Category | Smart Home |
| Platform | ESP32 |
| Difficulty | Intermediate |
| Estimated build time | 32 hours |
| Connectivity | Matter |
| Core components | BME280, light sensor |
| Control mode | closed loop control |

## Repository layout

- `firmware/home-occupancy-console-voice-control/home-occupancy-console-voice-control.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/home-occupancy-console-voice-control/home-occupancy-console-voice-control.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **ESP32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Voice Control demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT

# SnowBot-2025: Autonomous Snow-Blower Beast

## Overview
Raspberry Pi 4-powered snow-plower with AI Camera (IMX500), NEO-6M GPS, ICM-20948 IMU, ultrasonic bumper, and Sabertooth 2x12 drive. Phase 1: Safe GPS-guided plowing with obstacle avoidance.

## Quick Start
1. Flash Pi with 64-bit Bookworm (see setup/raspberry_pi_setup.sh).
2. Wire sensors per docs/wiring_diagram.pdf.
3. Run `source ~/snowbot_env/bin/activate && python src/test_vision_gps.py` for first smoke test.

## Structure
- `setup/`: OS installs, pip reqs.
- `src/`: Core Python nodes (sensors, control).
- `docs/`: Fritzing diagrams, BOM.
- `config/`: Systemd services, YAML configs.

Budget: ~$450. Target: Plow a 10x10m driveway autonomously by Dec 2025.

Built with Grok @ xAI. Let's melt some snow! ❄️🤖

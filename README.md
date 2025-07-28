# LeRobot + teleop Integration

Brings a simple integration with [LeRobot](https://github.com/huggingface/lerobot) and [teleop](https://github.com/SpesRobotics/teleop).

## Getting Started

```bash
pip install lerobot-teleop

python -m lerobot.teleoperate \
    --robot.type=lerobot_xarm \
    --robot.id=black \
    --teleop.type=lerobot_teleop \
    --fps=60
```

## Development

Install the package in editable mode:
```bash
git clone https://github.com/SpesRobotics/lerobot-teleop.git
cd lerobot-teleop
pip install -e .
```

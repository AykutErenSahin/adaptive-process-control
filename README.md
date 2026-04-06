# Adaptive Industrial Process Control via SAC with RLHF

> Replacing traditional PID controllers with Soft Actor-Critic (SAC)
> enhanced by human preference learning (RLHF) on a physical Arduino
> thermal testbed.

## Project Status: 🚧 In Development

## Vision
This project demonstrates an end-to-end pipeline where a Deep RL agent
(SAC) learns to control a physical thermal process more effectively than
a tuned PID controller, with reward functions learned from human operator
preferences using the Bradley-Terry model (RLHF).

## Architecture
See [docs/architecture.md](docs/architecture.md)

## Hardware
- Arduino Uno R3
- LM35 temperature sensor (process variable)
- DHT-11 temperature/humidity sensor (ambient)
- DC motor + transistor + relay (actuator)
- 16x2 LCD, 7-segment displays, LEDs (feedback)
- Potentiometer (setpoint control)

## Roadmap
- [ ] Phase 1: Physical testbed & PID baseline
- [ ] Phase 2: Python-Arduino communication
- [ ] Phase 3: SAC implementation & training
- [ ] Phase 4: RLHF reward model
- [ ] Phase 5: Evaluation & documentation

## License
MIT
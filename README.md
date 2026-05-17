# MAX1954 Buck Converter Practice

Personal power supply design practice using MAX1954 synchronous buck controller.

Main goals:
- Practice synchronous buck converter design
- Learn power stage PCB layout
- Evaluate DH/LX switching behavior
- Test snubber effectiveness
- Observe switching noise and ringing

---

## Current Status

- [x] Schematic
- [ ] PCB layout
- [ ] ERC/DRC cleanup
- [ ] Prototype
- [ ] Oscilloscope validation

---

## Basic Specs

| Item | Value |
|---|---|
| VIN | 12V |
| VOUT | TBD |
| Controller | MAX1954 |
| MOSFET | FDS6690A |
| Topology | Synchronous Buck |

---

## Things To Learn

- Bootstrap circuit behavior
- DH/LX waveform
- MOSFET switching loss
- Snubber tuning
- Ground return path
- Switching loop minimization

---

## Notes

### Snubber

Current value:
- 1500pF capacitor
- resistor TBD

Need waveform validation later.

---

## TODO

- [ ] Add input bulk capacitor
- [ ] Check compensation network
- [ ] Measure LX ringing
- [ ] Optimize MOSFET placement
- [ ] Thermal estimation

---

## Git Commit Style

```bash
PCB: move MOSFET closer to controller
SCH: update bootstrap capacitor
TEST: measure LX overshoot
```

---

## References

- MAX1954 Datasheet
- TI Power Layout Guidelines
- Analog Devices Buck Converter Layout Notes

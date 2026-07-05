# Triaksha Singh

ECE student at the University of Washington building systems at the intersection of embedded hardware, applied ML, and low-latency infrastructure.

🌐 [Website](https://triakshasingh.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/triakshasingh/)

---

## Projects

### [TPS54331 Buck Converter PCB](https://github.com/triakshasingh/TPS54331_Buck_Converter)
12V to 5V step-down switching regulator, simulated in LTspice and laid out in KiCad.
- TI TPS54331, 3A output, non-synchronous buck, 0.8V reference feedback
- Verified in simulation: switch node confirmed switching, output settles at 4.9V (4.96V target)

### [DRV8833 Motor Driver PCB](https://github.com/triakshasingh/MotorDriver_DRV8833)
Dual H-bridge motor driver PCB for brushed DC motor control.
- TI DRV8833, 1.5A per channel, PWM input, SLEEP/FAULT broken out
- DRC clean · 0 violations · 0 unconnected

### [AC-DC Bridge Rectifier PCB](https://github.com/triakshasingh/AC_DC_Converter)
Full-wave bridge rectifier designed in KiCad 10.
- 1N4007 diode bridge, 1mF filter cap, LED indicator, GND copper pour
- DRC clean · 0 violations · 0 unconnected

### [Limit Order Book & Matching Engine](https://github.com/triakshasingh/limitOrderBook)
High-performance exchange simulation with deterministic order matching.
- O(log P) price level updates, O(1) cancellation via hash index
- 1M synthetic events at ~102k events/sec · p50 5.29µs, p99 20.33µs

### [Persistent Key-Value Store](https://github.com/triakshasingh/kvStore)
Crash-safe in-memory KV store with durability and concurrent client support.
- WAL with fsync for crash recovery, multithreaded TCP server
- 306,961 ops/sec · p50 1.97µs, p99 11.46µs

### [Volatility Estimator Toolkit](https://github.com/triakshasingh/volatility-estimator-)
Quantitative finance toolkit for statistical volatility modeling.
- Rolling-window and EWMA estimators, vectorized NumPy pipelines


---

## Stack

`Python` `Java` `C` `KiCad` `ROS2` `PyTorch` `NumPy` `Linux` `Git`

---

## Connect
 
- Email: triakshasingh@gmail.com
- School Email: tsingh05@uw.edu
- Contact: +1 206-605-6394

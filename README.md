											

										-- Model 101X — Integrated Vacuum Tube Amplifier -- 


-------------------------------------------------------------------------------------------------------

* Overview:
 
	The Model 101X is a custom-built, single-ended Class A vacuum tube integrated amplifier designed for high-fidelity audio reproduction and archival playback systems. The design prioritizes linear signal behaviour, minimal global feedback (none used), and direct RC-coupled stage progression.

The amplifier is constructed as a low-volume, built-to-order system with emphasis on serviceability, electrical clarity, and period-inspired analog design practices.

-------------------------------------------------------------------------------------------------------

* Variants:

-101R / 101L (Monoblock Units) → Electrically identical monaural amplifiers with mirrored physical layouts. Designed for stereo systems using separate left and right chassis units.

-101M (Integrated Stereo-to-Mono Unit) → Stereo input is summed into mono at the initial 6K8 stage. Signal processing proceeds through a unified amplification path to a single output stage.

-------------------------------------------------------------------------------------------------------

* Signal Path Architecture:

The amplifier uses a strictly RC-coupled, zero-feedback architecture with a linear stage progression:
Primary Audio Chain:
Input (Dual RCA)
→ 6K8 (Triode) — Input gain stage, RIAA equalization / mixing (101M only)
→ 6K5G — Second voltage amplification stage
→ 6SN7 — Driver stage and tone shaping network
→ 6L6G — Single-ended Class A power output stage
→ Output Transformer → Speaker Output
All coupling between stages is performed via RC networks. No global negative feedback is employed.

-------------------------------------------------------------------------------------------------------

* Eye Tube / Monitoring Circuit:

A secondary signal path derived from the 6SN7 stage drives a visual indicator subsystem:
6SN7 tap
→ 6K8 (hexode section)
→ Potentiometer + capacitor network
→ 6H6 rectifier
→ 6U5 eye tube display
The 6U5 functions as a real-time visual indicator of signal presence and relative amplitude.

-------------------------------------------------------------------------------------------------------

* Tube Complement (tube count per chassis): 

6K8 x1 — Input gain stage (triode) + eye tube driver (hexode)
6K5G x1 — Voltage amplification stage
6SN7 x1 — Driver stage and tone shaping
6L6G x1 — Single-ended Class A output stage
5Y4G x1 — Full-wave rectifier
6H6 x1 — Eye tube rectification
6U5 x1 — Visual signal indicator

-------------------------------------------------------------------------------------------------------

* Power Supply:

The power supply is based on a high-capacity transformer and dual-choke filtering architecture.
Power Transformer: 275–0–275V @ 175mA, 6.3V heater supply @ 4A, 5V rectifier supply @ 3A

Rectification: 5Y4G full-wave rectifier (center-tapped configuration)

Filtering: Dual-stage choke filtering using two chokes for improved ripple suppression and stage isolation.

B+ Distribution:
Main filter: ~250V
6K8 stage: ~240V
6K5G stage: ~235V
6SN7 stage: ~245V
6L6G plate: ~220V
6L6G screen: ~240V

-------------------------------------------------------------------------------------------------------

* Output Stage:

Tube: 6L6G
Configuration: Single-ended Class A
Output Power: ~5W nominal, up to ~7W maximum drive
Output Transformer: 2.5kΩ primary, 8Ω secondary (custom impedance options available)

-------------------------------------------------------------------------------------------------------

* Performance Specifications:

Output Power: ~5W continuous, ~7W peak
THD: ~1% at 5W output

Frequency Response:
15 Hz – 60 kHz (unfiltered mode)
10 Hz – 30 kHz (RIAA mode)

Designed for 5 mV (MM cartridge) or 0.5 V (ceramic cartridge)
Usable down to ~1 mV (noise-limited operation)

Signal-to-Noise Ratio:
~90 dB at sub-watt output levels
Transformer hum exceeds circuit noise floor at idle

-------------------------------------------------------------------------------------------------------

* Mechanical Design:

Chassis: Steel, painted grey finish
Dimensions: 43 × 25.5 × 17 cm
Weight: ~10 kg
Layout: Signal-path-aligned tube placement with symmetrical visual structure

Transformer placement optimized for short high-current runs and physical isolation between power and signal sections

-------------------------------------------------------------------------------------------------------

* Wiring & Construction:

Point-to-point wiring throughout
Shielded signal wiring used where appropriate
Twisted heater pairs (floating configuration)
B+ and heater lines routed along chassis edges to minimize coupling
Signal wiring routed above socket plane; power wiring routed beneath
Stage isolation achieved through physical spacing and lead dress discipline
Optional shielding for high-gain stages (6K5G) via auxiliary shielding hardware

-------------------------------------------------------------------------------------------------------

* Controls & I/O:

Inputs: Dual RCA (expandable per build)
Outputs: Banana plug speaker terminals (custom impedance options available)
Controls:
Volume potentiometer
Tone control potentiometer
RIAA / Unfiltered mode switch
Power switch: Front-mounted, isolated from signal path
Indicator: 6U5 eye tube (configurable function)

-------------------------------------------------------------------------------------------------------

* Safety Architecture:

Bleeder resistors across main filter capacitors
Three-prong grounded mains connection
High-voltage isolation practices in chassis design
Heater wiring is implemented as a floating twisted pair system with per-stage capacitive referencing based on grid-adjacent stabilization techniques derived from classical vacuum tube design literature.

-------------------------------------------------------------------------------------------------------

* Design Philosophy:

The Model 101X is designed as a linear, feedback-free vacuum tube amplification system emphasizing electrical simplicity, controlled harmonic behaviour, and long-term serviceability. The architecture favours predictable stage behaviour, physical layout discipline, and modular service access over circuit complexity or corrective feedback systems.


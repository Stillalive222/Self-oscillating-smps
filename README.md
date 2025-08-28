# Halogen Lamp–Based Self-Oscillating SMPS

## Description
A **self-oscillating switched-mode power supply (SMPS)** adapted from commercial halogen lamp electronic transformers ([Elliott Sound Products – Electronic Transformers](https://sound-au.com/lamps/elect-trans.html)).  
Redesigned with an **AC input filter**, **rectifier + low-pass output stage**, and **custom-wound transformers**, it provides a stable **DC output** suitable for medium-power loads.  

- **No-load output:** ~20 V DC  
- **Loaded output:** ~17.5 V @ 3.78 A (~66 W tested, higher load capability expected)  

## Features
- Self-oscillating half-bridge topology (no feedback loop)  
- Input stage: AC line filter for EMI reduction  
- Output stage: full-wave rectifier + low-pass filter for DC conversion  
- Custom-wound drive transformer: 2×3-turn + 1×10-turn windings  
- Power transformer: salvaged **EI-33 core**, 80T primary, ~20T CT secondary  

## Technical Stack
- **Design Tools:** KiCad (schematic available)  
- **Hardware:** salvaged EI-33 core transformer, discrete components, wound drive transformer  

## Media
### Schematic
![SMPS Schematic](selfsmpsschematic.pdf)

### Build Reference
📺 [YouTube – Electronic Halogen Transformer SMPS](https://www.youtube.com/watch?v=6ko4plGJTkY)  

## Skills Demonstrated
- Power electronics design & transformer winding  
- EMI filtering and rectification techniques  
- Practical testing of SMPS under resistive load  
- Documentation using KiCad & schematic export  

## Future Work
- Test at higher continuous load for thermal limits  
- Add over-current/short-circuit protection  
- Optimize transformer winding for efficiency  

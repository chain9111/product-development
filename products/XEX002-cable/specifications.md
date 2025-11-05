# XEX002 Cable Assembly - Technical Specifications

## Product Overview
**Product Code:** XEX002
**Product Name:** Industrial Control Cable Assembly
**Status:** In Development
**Revision:** 1.0
**Date:** 2025-11-06

## General Specifications

### Electrical Characteristics
- **Voltage Rating:** 300V AC/DC
- **Current Rating:** 10A per conductor
- **Number of Conductors:** 4 + Ground
- **Conductor Material:** Stranded tinned copper
- **Wire Gauge:** 18 AWG (0.82mm²)
- **Resistance:** ≤ 21 Ω/km @ 20°C
- **Insulation Resistance:** ≥ 100 MΩ @ 500V DC

### Physical Characteristics
- **Cable Length:** 3 meters (standard) / Custom lengths available
- **Overall Diameter:** 10.5mm ± 0.5mm
- **Jacket Material:** PVC, flame retardant
- **Jacket Color:** Black (standard) / Gray (optional)
- **Bend Radius:** Min. 42mm (4× cable diameter)
- **Weight:** ~150g per meter

### Connector Specifications

#### End A: Industrial Connector (Male)
- **Type:** M12, 5-pin, A-coded
- **Housing:** Nickel-plated brass
- **Contacts:** Gold-plated pins
- **Coupling:** Threaded locking
- **IP Rating:** IP67 when mated
- **Operating Temperature:** -40°C to +85°C

#### End B: Panel Mount Connector (Female)
- **Type:** 5-pin circular connector
- **Housing:** Plastic, UL94-V0
- **Contacts:** Gold-plated sockets
- **Mounting:** Panel mount with nut
- **IP Rating:** IP54 (front), IP20 (rear)
- **Operating Temperature:** -25°C to +70°C

### Cable Construction

#### Conductor Configuration
1. **Pin 1 (Brown):** Power + / Signal A
2. **Pin 2 (White):** Power - / Signal B
3. **Pin 3 (Blue):** Control Signal / Data +
4. **Pin 4 (Black):** Control Signal / Data -
5. **Pin 5 (Green/Yellow):** Ground / Shield

#### Insulation & Shielding
- **Conductor Insulation:** PVC, 0.6mm wall thickness
- **Shield:** Aluminum-mylar foil + tinned copper braid (85% coverage)
- **Shield Drain Wire:** 24 AWG tinned copper
- **Outer Jacket:** PVC, 1.2mm wall thickness
- **Color Code:** IEC 60757 standard

## Performance Specifications

### Mechanical Properties
- **Tensile Strength:** ≥ 50N per conductor
- **Flex Life:** > 1,000,000 cycles @ 10× diameter bend
- **Pull Force:** ≥ 80N (connector retention)
- **Insertion/Extraction Force:** 10-40N
- **Durability:** > 10,000 mating cycles

### Environmental Specifications
- **Operating Temperature:** -25°C to +80°C
- **Storage Temperature:** -40°C to +85°C
- **Humidity:** 5% to 95% RH (non-condensing)
- **Vibration:** IEC 60068-2-6 (10-500 Hz, 10g)
- **Shock:** IEC 60068-2-27 (50g, 11ms)
- **Salt Spray:** 48 hours (ASTM B117)

### Electrical Performance
- **Contact Resistance:** ≤ 10 mΩ initial
- **Dielectric Withstanding:** 1500V AC (1 minute)
- **Insulation Resistance:** ≥ 100 MΩ
- **Capacitance:** ≤ 150 pF/m (conductor to conductor)
- **Impedance:** 120Ω ± 10% (differential pairs)

## Safety & Compliance

### Standards Compliance
- **Cable:** UL 2464, CSA C22.2
- **Connectors:** IEC 61076-2-101 (M12)
- **Flammability:** UL 94-V0
- **RoHS:** Compliant (2015/863/EU)
- **REACH:** Compliant

### Safety Features
- Double insulation system
- Strain relief at both ends
- Shielding for EMI/RFI protection
- Color-coded for easy identification
- Pull tab for easy connector removal

## Applications
- Industrial automation systems
- Sensor connections
- Actuator control
- PLC I/O connections
- Machine-to-machine communication
- Building automation
- HVAC control systems

## Quality Requirements

### Testing Requirements
- [ ] Continuity test (100% production)
- [ ] Hi-pot test (1500V AC, 1 minute)
- [ ] Insulation resistance test
- [ ] Pull force test (sample)
- [ ] Mating cycle test (qualification)
- [ ] Environmental testing (qualification)
- [ ] EMC testing (pre-production)

### Quality Standards
- Manufactured per IPC/WHMA-A-620 Class 2
- Visual inspection per MIL-STD-883
- 100% electrical testing
- AQL 1.5 sampling plan
- Traceability by lot number

## Documentation References
- Cable specification sheet: `technical-drawings/XEX002-cable-spec.pdf`
- Connector pinout diagram: `technical-drawings/XEX002-pinout.pdf`
- Assembly drawing: `technical-drawings/XEX002-assembly.pdf`
- Bill of Materials: `BOM.md`
- Test procedures: `testing/test-plan.md`

## Product Variants

### Length Options
- **XEX002-1M:** 1 meter
- **XEX002-3M:** 3 meters (standard)
- **XEX002-5M:** 5 meters
- **XEX002-10M:** 10 meters
- **XEX002-CUSTOM:** Custom length (MOQ applies)

### Connector Options
- **Standard:** M12 male to panel mount female
- **Option A:** M12 male to M12 male
- **Option B:** M12 female to panel mount female
- **Option C:** Open-ended (pigtail) one or both ends

### Cable Options
- **Standard:** Black PVC jacket
- **Option A:** Gray PVC jacket
- **Option B:** TPU jacket (enhanced flexibility)
- **Option C:** PUR jacket (oil resistant)

## Development Notes

### Current Status
- Design phase: 90% complete
- Prototype: Not started
- Testing: Not started
- Certification: Pending

### Key Design Decisions
1. M12 connector for industrial standard compatibility
2. 18 AWG for 10A current capacity with safety margin
3. Shielded construction for noise immunity
4. PVC jacket for cost-effectiveness
5. IEC color coding for international use

### Open Issues
- Final strain relief design pending prototype
- Cable marking/labeling specification
- Packaging design for different lengths
- Cost optimization for volume production
- Qualification test plan approval

## Packaging & Labeling

### Product Marking
- Product code (XEX002-XX)
- Length marking every 500mm
- Manufacturer logo
- Voltage rating (300V)
- Temperature rating
- Compliance marks (CE, RoHS)

### Packaging
- Individual polybag with desiccant
- Cable coiled and secured with velcro strap
- Product label on bag
- 10 units per master carton
- ESD protection not required

## Revision History

| Version | Date | Author | Description |
|---------|------|--------|-------------|
| 1.0 | 2025-11-06 | Development Team | Initial specification |

## Notes
- Custom lengths available with 10-piece MOQ
- Volume discounts available at 100+ units
- Lead time: 4-6 weeks for standard versions
- Lead time: 6-8 weeks for custom configurations
- Consult engineering for special requirements

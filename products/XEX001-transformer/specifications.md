# XEX001 Transformer - Technical Specifications

## Product Overview
**Product Code:** XEX001
**Product Name:** Industrial Power Transformer
**Status:** In Development
**Revision:** 1.0
**Date:** 2025-11-06

## General Specifications

### Electrical Characteristics
- **Primary Voltage:** 230V AC ± 10%
- **Secondary Voltage:** 24V AC / 12V AC (dual output)
- **Frequency:** 50/60 Hz
- **Power Rating:** 100VA
- **Efficiency:** ≥ 92%
- **Insulation Class:** Class II (Double Insulation)
- **Dielectric Strength:** 3000V AC (1 minute)

### Physical Characteristics
- **Dimensions:** 85mm (L) × 75mm (W) × 60mm (H)
- **Weight:** 850g ± 50g
- **Mounting:** PCB mount or chassis mount options
- **Terminals:** Screw terminals (M3)
- **Core Type:** EI laminated silicon steel
- **Winding Type:** Copper wire, Class H insulation

### Environmental Specifications
- **Operating Temperature:** -20°C to +70°C
- **Storage Temperature:** -40°C to +85°C
- **Humidity:** 5% to 95% RH (non-condensing)
- **Protection Rating:** IP20 (standard) / IP54 (optional with enclosure)
- **Cooling:** Natural convection

## Design Features

### Safety Features
- Thermal fuse protection (130°C)
- Overcurrent protection capability
- UL94-V0 flame retardant materials
- Meets IEC 61558-1 & IEC 61558-2-6 standards

### Quality Standards
- CE certified (pending)
- RoHS compliant
- REACH compliant
- ISO 9001 manufacturing

## Performance Specifications

### Regulation
- **Load Regulation:** ≤ 5% (0-100% load)
- **Line Regulation:** ≤ 3% (±10% input voltage)

### Losses
- **No-Load Loss:** ≤ 2W
- **Full-Load Loss:** ≤ 8W

### Isolation
- **Primary to Secondary:** 4kV
- **Primary to Core:** 2kV
- **Secondary to Core:** 500V

## Applications
- Industrial control systems
- HVAC control panels
- Building automation
- Machine control interfaces
- Power supply units

## Compliance & Certifications
- [ ] CE marking
- [ ] UL/cUL certification
- [ ] IEC 61558 compliance testing
- [ ] RoHS Declaration of Conformity
- [ ] EMC testing (EN 61000-6-2, EN 61000-6-4)

## Documentation References
- Electrical schematic: `technical-drawings/XEX001-schematic.pdf`
- Mechanical drawing: `technical-drawings/XEX001-mechanical.pdf`
- Bill of Materials: `BOM.md`
- Test procedures: `testing/test-plan.md`

## Development Notes

### Current Status
- Design phase complete
- Prototype pending
- Testing not started

### Key Design Decisions
1. Selected EI core for cost-effectiveness and availability
2. Dual secondary outputs for flexibility
3. Screw terminals for easy field installation
4. Thermal fuse for safety compliance

### Open Issues
- Final wire gauge selection pending thermal testing
- Enclosure design for IP54 version
- Cost optimization for volume production

## Revision History

| Version | Date | Author | Description |
|---------|------|--------|-------------|
| 1.0 | 2025-11-06 | Development Team | Initial specification |

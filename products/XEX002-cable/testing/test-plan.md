# XEX002 Cable Assembly - Test Plan

**Product:** XEX002 Industrial Control Cable Assembly
**Revision:** 1.0
**Date:** 2025-11-06
**Status:** Draft

## Test Overview

### Purpose
This test plan defines testing requirements, procedures, and acceptance criteria for XEX002 cable assemblies to ensure they meet specifications, industry standards, and customer requirements.

### Test Phases
1. **Development Testing** - Prototype validation
2. **Qualification Testing** - Design verification
3. **Production Testing** - 100% screening
4. **Periodic Testing** - Ongoing quality monitoring

---

## 1. Development Testing (Prototype Phase)

### 1.1 Electrical Tests

#### 1.1.1 Continuity Test
**Objective:** Verify all conductors are properly connected
**Equipment:** Multimeter or continuity tester
**Procedure:**
1. Test each pin end-to-end
2. Verify correct pin mapping
3. Check for shorts between conductors

**Acceptance Criteria:**
- Resistance < 1Ω per conductor (3m length)
- No shorts between conductors
- Correct pin-to-pin mapping

#### 1.1.2 Contact Resistance Test
**Objective:** Measure connector contact resistance
**Equipment:** Milliohmmeter
**Procedure:**
1. Measure resistance at each contact
2. Test with connectors mated
3. Mate/unmate 10 times and re-test

**Acceptance Criteria:**
- Initial contact resistance: ≤ 10 mΩ
- After cycling: ≤ 15 mΩ

#### 1.1.3 Insulation Resistance Test
**Objective:** Verify insulation quality
**Equipment:** Megohmmeter (500V DC)
**Procedure:**
1. Test conductor-to-conductor
2. Test conductor-to-shield
3. Measure for 1 minute

**Acceptance Criteria:**
- All measurements ≥ 100 MΩ

#### 1.1.4 Dielectric Withstand Test (Hi-Pot)
**Objective:** Verify insulation integrity
**Equipment:** Hi-pot tester
**Procedure:**
1. Apply 1500V AC between conductors
2. Apply 1500V AC conductor-to-shield
3. Hold for 1 minute

**Acceptance Criteria:**
- No breakdown or flashover
- Leakage current < 5mA

#### 1.1.5 Capacitance Test
**Objective:** Measure cable capacitance
**Equipment:** LCR meter
**Procedure:**
1. Measure conductor-to-conductor capacitance
2. Measure conductor-to-shield capacitance

**Acceptance Criteria:**
- Conductor-to-conductor: ≤ 150 pF/m
- Within ±10% between pairs

#### 1.1.6 Shield Continuity & Effectiveness
**Objective:** Verify shield integrity
**Equipment:** Multimeter, RF test equipment
**Procedure:**
1. Test shield resistance end-to-end
2. Verify drain wire connection
3. Measure shielding effectiveness (optional)

**Acceptance Criteria:**
- Shield resistance < 1Ω
- Drain wire properly connected

### 1.2 Mechanical Tests

#### 1.2.1 Pull Force Test
**Objective:** Verify connector retention and strain relief
**Equipment:** Force gauge
**Test Points:**
- Connector pull-off force
- Wire pull-out from connector
- Strain relief effectiveness

**Procedure:**
1. Apply axial force to connector
2. Increase gradually until failure or 80N
3. Test both ends

**Acceptance Criteria:**
- Connector retention: ≥ 80N
- No wire pull-out at < 80N
- Strain relief secure

#### 1.2.2 Insertion/Extraction Force Test
**Objective:** Verify connector mating force
**Equipment:** Force gauge
**Procedure:**
1. Measure insertion force
2. Measure extraction force
3. Repeat for 100 cycles

**Acceptance Criteria:**
- Insertion: 10-40N
- Extraction: 10-40N
- Consistent through cycles

#### 1.2.3 Durability (Mating Cycles) Test
**Objective:** Verify connector durability
**Equipment:** Automated mate/unmate tester
**Procedure:**
1. Mate and unmate connector
2. Repeat for 10,000 cycles
3. Perform electrical tests every 1000 cycles

**Acceptance Criteria:**
- No mechanical damage
- Electrical performance maintained
- Contact resistance increase < 50%

#### 1.2.4 Bend/Flex Test
**Objective:** Verify cable flexibility and durability
**Equipment:** Flex tester
**Procedure:**
1. Bend cable to 4× diameter radius
2. Flex for 1,000,000 cycles
3. Check continuity every 100,000 cycles

**Acceptance Criteria:**
- No conductor breaks
- No insulation cracks
- Continuity maintained

### 1.3 Environmental Tests

#### 1.3.1 Temperature Cycling
**Standard:** IEC 60068-2-14
**Objective:** Verify performance across temperature range
**Profile:**
- Low: -25°C (4 hours)
- High: +80°C (4 hours)
- Cycles: 10

**Acceptance Criteria:**
- No cracking or damage
- Electrical specs maintained
- Connectors functional

#### 1.3.2 Humidity Test
**Standard:** IEC 60068-2-78
**Profile:**
- 95% RH, 40°C, 48 hours
**Acceptance Criteria:**
- Insulation resistance ≥ 10 MΩ
- No corrosion on contacts

#### 1.3.3 Salt Spray Test (Corrosion)
**Standard:** ASTM B117
**Duration:** 48 hours
**Scope:** Connector metal parts
**Acceptance Criteria:**
- No visible corrosion on contacts
- Connector functionality maintained

#### 1.3.4 Vibration Test
**Standard:** IEC 60068-2-6
**Profile:**
- Frequency: 10-500 Hz
- Acceleration: 10g
- Duration: 2 hours per axis

**Acceptance Criteria:**
- No mechanical damage
- Connectors remain secure
- Electrical continuity maintained

#### 1.3.5 Shock Test
**Standard:** IEC 60068-2-27
**Profile:**
- 50g peak, 11ms duration
- 3 shocks per axis (18 total)

**Acceptance Criteria:**
- No damage or loosening
- Electrical function maintained

---

## 2. Qualification Testing (Pre-Production)

### 2.1 Qualification Test Matrix

| Test | Standard | Sample Size | Requirement |
|------|----------|-------------|-------------|
| Hi-pot | IEC 61076 | 5 | 1500V AC, 1 min |
| Mating cycles | IEC 61076 | 3 | 10,000 cycles |
| Temperature cycling | IEC 60068-2-14 | 5 | -25 to +80°C |
| Vibration | IEC 60068-2-6 | 3 | 10g, 10-500Hz |
| Salt spray | ASTM B117 | 3 | 48 hours |
| Flex life | Custom | 3 | 1M cycles |

### 2.2 Long-Term Reliability
**Duration:** 1000 hours
**Conditions:** 70°C, 85% RH
**Sample Size:** 5 units
**Monitoring:** Test every 250 hours

---

## 3. Production Testing (100% Screening)

### 3.1 Incoming Inspection
- [ ] Connector visual inspection
- [ ] Cable dimensional check
- [ ] Component certifications review

### 3.2 In-Process Testing
- [ ] Visual inspection of solder joints
- [ ] Strain relief installation check
- [ ] Heat shrink application check

### 3.3 Final Testing (Every Unit)

**Test Sequence:**

#### Step 1: Visual Inspection
- Workmanship per IPC/WHMA-A-620 Class 2
- Connector orientation correct
- Labels applied correctly
- No physical damage
- Proper strain relief

#### Step 2: Continuity Test
- All conductors continuous
- Correct pin mapping
- No shorts between pins
- Shield continuity

**Pass Criteria:** < 1Ω per conductor, no shorts

#### Step 3: Hi-Pot Test
- 1500V AC, 2 seconds
- Conductor to conductor
- Conductor to shield

**Pass Criteria:** No breakdown, leakage < 5mA

#### Step 4: Insulation Resistance
- 500V DC megger test
- All conductor pairs

**Pass Criteria:** ≥ 100 MΩ

#### Step 5: Functional Test
- Mate/unmate connectors (3 times)
- Visual inspection of connectors
- Verify proper engagement

**Pass Criteria:** Smooth mating, no damage

### 3.4 Sample Testing (Per Lot)

**Sampling Plan:** AQL 1.5, Level II
**Lot Size:** 500 units
**Sample Size:** 50 units

**Additional Tests:**
- Pull force test (connector retention)
- Contact resistance measurement
- Detailed visual inspection

---

## 4. Test Equipment Requirements

| Equipment | Specifications | Calibration |
|-----------|----------------|-------------|
| Multimeter | 0.1% accuracy, 4-wire | Annual |
| Milliohmmeter | 1µΩ resolution | Annual |
| Megohmmeter | 500V DC, 10GΩ range | Annual |
| Hi-pot Tester | 0-3kV AC, 50mA | Annual |
| LCR Meter | 100Hz-10kHz | Annual |
| Force Gauge | 0-200N, 0.1N resolution | Annual |
| Flex Tester | Programmable cycles | Annual |
| Environmental Chamber | -40 to +150°C, 95% RH | Annual |

---

## 5. Test Documentation

### Required Records
- Test procedure (this document)
- Test data sheets (raw data)
- Pass/fail results
- Serial number traceability
- Operator identification
- Date and time
- Equipment calibration certificates
- Non-conformance reports

### Test Report Template
```
Product: XEX002 Cable Assembly
Serial Number: ______________
Date: ______________
Operator: ______________
Lot Number: ______________

Tests Performed:
☐ Visual Inspection - PASS / FAIL
☐ Continuity Test - PASS / FAIL
☐ Hi-Pot Test - PASS / FAIL
☐ Insulation Resistance - PASS / FAIL
☐ Functional Test - PASS / FAIL

Overall Result: PASS / FAIL
Inspector Signature: ______________
```

---

## 6. Acceptance Criteria Summary

| Parameter | Specification | Test Method |
|-----------|--------------|-------------|
| Conductor resistance | < 21Ω/km | Continuity test |
| Contact resistance | ≤ 10mΩ initial | Milliohm meter |
| Insulation resistance | ≥ 100MΩ | Megger (500V DC) |
| Hi-pot | 1500V AC, 1 min | Hi-pot tester |
| Pull force | ≥ 80N | Force gauge |
| Mating cycles | > 10,000 | Durability test |
| Flex life | > 1,000,000 | Flex tester |
| Temperature range | -25 to +80°C | Environmental chamber |

---

## 7. Failure Analysis

### Common Failure Modes
1. **Open circuit:** Broken conductor or poor solder joint
2. **Short circuit:** Insulation damage or contamination
3. **High resistance:** Poor crimp or solder connection
4. **Connector damage:** Improper assembly or handling
5. **Strain relief failure:** Insufficient grip or installation error

### Root Cause Analysis
- Document failure symptoms
- Perform visual inspection
- Disassemble if necessary
- Identify root cause
- Implement corrective action
- Re-test after repair

---

## 8. Quality Control Checkpoints

### Assembly Checkpoints
1. **Pre-assembly:** Components verified
2. **Wire prep:** Lengths and strip correct
3. **Soldering:** Per IPC J-STD-001
4. **Strain relief:** Properly installed
5. **Heat shrink:** Fully shrunk, no gaps
6. **Final inspection:** Complete assembly

### Rejection Criteria
- Solder defects (cold joint, insufficient, excess)
- Exposed conductors
- Damaged insulation
- Improper strain relief
- Wrong connector orientation
- Missing or incorrect labeling

---

## 9. Test Schedule

| Phase | Duration | Sample Size | Start After |
|-------|----------|-------------|-------------|
| Development | 2 weeks | 5 units | Prototype build |
| Qualification | 8 weeks | 15 units | Dev test pass |
| Production setup | 1 week | 50 units | Qual test pass |
| Production | Ongoing | 100% + samples | Production start |

---

## 10. Safety Precautions

### Electrical Safety
- Hi-pot testing requires trained personnel only
- Use proper PPE (insulating gloves, safety glasses)
- Ensure proper grounding of test equipment
- Post warning signs during hi-pot testing

### Mechanical Safety
- Use safety guards on flex testers
- Properly secure samples in test fixtures
- Wear safety glasses during pull tests

---

## Revision History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | 2025-11-06 | Initial test plan | Development Team |

---

## Approvals

| Role | Name | Signature | Date |
|------|------|-----------|------|
| Engineering Manager | | | |
| Quality Manager | | | |
| Production Manager | | | |

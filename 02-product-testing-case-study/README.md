# Consumer Electronics Product Testing

## 1. Project Overview

This portfolio case study explores a structured product-testing approach for a hypothetical Smart Wi-Fi Video Doorbell.

The objective is to develop practical test scenarios for evaluating product functionality, connectivity, power stability, thermal behaviour and reliability.

This case study demonstrates how product requirements can be translated into test procedures, expected outcomes, observations and defect-investigation steps.

**Test subject:** Smart Wi-Fi Video Doorbell (hypothetical product)

**Testing focus:** Functional testing, connectivity, power, thermal behaviour and reliability.

**Project status:** Test plan development. No physical product has been tested. Test scenarios and sample outcomes, where included, are illustrative and not actual test results.

---

## 2. Testing Objectives

- Verify that the product performs its intended functions.
- Evaluate Wi-Fi connectivity and connection stability.
- Assess power supply stability and operating behaviour.
- Identify potential overheating or thermal-related issues.
- Evaluate the product's performance during continuous operation.
- Document failures and observations systematically.
- Develop a structured approach to root cause investigation.

---

## 3. Product Requirements

The hypothetical product is expected to:

1. Power on and operate normally.
2. Connect to a configured Wi-Fi network.
3. Transmit video to the associated application.
4. Respond to motion detection.
5. Maintain stable operation during continuous use.
6. Operate without unexpected reboots.
7. Maintain stable performance under normal operating conditions.

These requirements form the basis for the test scenarios developed in this case study.

---

## 4. Test Scenarios

### Test Case 1: Power-On and Startup

**Objective:** Verify that the device starts correctly when power is applied.

**Procedure:**
1. Connect the device to its specified power supply.
2. Observe the startup sequence.
3. Check the status indicators.
4. Verify that the device becomes operational.

**Expected Result:** The device starts normally without abnormal behaviour, unexpected resets or visible signs of malfunction.

**Pass Criteria:** The device completes its startup sequence and becomes operational.

---

### Test Case 2: Wi-Fi Connectivity

**Objective:** Verify that the device connects to the configured Wi-Fi network.

**Procedure:**
1. Configure the device with the appropriate Wi-Fi credentials.
2. Power on the device.
3. Observe the connection status.
4. Verify communication with the application.

**Expected Result:** The device establishes a connection and communicates with the application.

**Pass Criteria:** Successful connection and communication without unexpected disconnection.

---

### Test Case 3: Video Streaming

**Objective:** Verify the video streaming functionality.

**Procedure:**
1. Connect the device to Wi-Fi.
2. Open the associated application.
3. Access the live video feed.
4. Observe video quality, interruptions and responsiveness.

**Expected Result:** The live video feed is accessible and operates without unexpected interruption.

**Pass Criteria:** Video streaming operates as expected under the defined test conditions.

---

### Test Case 4: Continuous Operation

**Objective:** Assess operational stability during extended use.

**Procedure:**
1. Power on the device.
2. Establish Wi-Fi connectivity.
3. Access the video feed.
4. Maintain continuous operation for a defined test duration, such as 60 minutes.
5. Record any disconnections, freezes or unexpected reboots.

**Expected Result:** The device operates continuously without unexpected rebooting or loss of functionality.

**Pass Criteria:** No unexpected reboot or critical interruption occurs during the test period.

---

### Test Case 5: Thermal Behaviour

**Objective:** Investigate whether operating temperature may affect product performance.

**Procedure:**
1. Operate the device under defined conditions.
2. Monitor temperature at appropriate accessible points using suitable measurement equipment.
3. Record temperature at regular intervals.
4. Observe any changes in connectivity or functionality.
5. Compare recorded measurements against the manufacturer's specified limits, where available.

**Expected Result:** The device remains within its specified operating temperature limits and maintains normal functionality.

**Pass Criteria:** Temperature remains within specified limits without thermal-related malfunction.

---

### Test Case 6: Power Stability

**Objective:** Investigate whether power-related issues affect device operation.

**Procedure:**
1. Verify the specified supply voltage.
2. Inspect the power connection.
3. Measure supply voltage using appropriate equipment.
4. Observe device behaviour during operation.
5. Investigate unexpected reboots or interruptions.

**Expected Result:** The device receives an appropriate and stable power supply and operates normally.

**Pass Criteria:** No power-related instability is observed during the defined test.

---

## 5. Test Documentation

A structured test record should include:

| Field | Description |
|---|---|
| Test ID | Unique test identification |
| Test name | Name of the test |
| Test objective | Purpose of the test |
| Test conditions | Environment and operating conditions |
| Test procedure | Steps followed |
| Expected result | Defined acceptable behaviour |
| Actual result | Observed behaviour |
| Status | Pass, Fail or Not Tested |
| Evidence | Photographs, measurements or logs |
| Notes | Additional observations |

---

## 6. Defect Investigation Scenario

**Hypothetical failure:** 15% of devices experience unexpected rebooting or Wi-Fi disconnection after approximately 20–30 minutes of operation.

### Potential causes

- Power supply instability.
- Excessive temperature.
- Firmware-related malfunction.
- Wi-Fi connectivity instability.
- Component failure.
- PCB or soldering-related issues.

### Investigation approach

**Step 1: Reproduce the issue**

Repeat the test under controlled conditions and record the time until the failure occurs.

**Step 2: Investigate the power supply**

Check supply voltage and, where appropriate, voltage fluctuations under operating load.

**Step 3: Investigate thermal behaviour**

Monitor temperature and examine whether the failure correlates with temperature increase.

**Step 4: Investigate Wi-Fi connectivity**

Check signal strength, network stability and whether the disconnection is network-related or accompanied by a reboot.

**Step 5: Review logs**

Examine available system logs, error messages and reboot records.

**Step 6: Isolate the cause**

Change one test condition at a time and compare results to identify a potential root cause.

**Step 7: Document findings**

Record the issue, test conditions, evidence, suspected cause and recommended next steps.

---

## 7. Root Cause Investigation Principles

A systematic investigation should:

- Reproduce the failure.
- Collect measurable evidence.
- Avoid assumptions.
- Isolate variables.
- Compare normal and abnormal behaviour.
- Document findings.
- Verify corrective actions through retesting.

---

## 8. Limitations

This case study is based on a hypothetical product and illustrative test scenarios.

No physical device, laboratory equipment, firmware logs or real measurements have been used in this portfolio project.

The procedures are designed to demonstrate test planning and structured engineering investigation rather than report actual product test results.

---

## 9. Skills Demonstrated

- Test planning.
- Requirement-based testing.
- Functional testing methodology.
- Power and electrical fundamentals.
- Connectivity testing.
- Thermal investigation methodology.
- Defect documentation.
- Root cause investigation.
- Systematic engineering problem-solving.

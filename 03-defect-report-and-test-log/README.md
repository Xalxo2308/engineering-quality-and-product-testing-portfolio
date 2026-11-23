# Defect Reporting and Test Results Documentation

## 1. Purpose

This document provides a structured template for recording product testing results, documenting defects and tracking issues identified during product inspection and testing.

The objective is to ensure that defects are recorded consistently, communicated clearly and investigated systematically.

---

## 2. Defect Report Template

| Field | Description |
|---|---|
| Defect ID | Unique defect reference |
| Date identified | Date the defect was observed |
| Product | Product name or model |
| Test ID | Associated test case |
| Defect title | Short description of the issue |
| Severity | Critical, High, Medium or Low |
| Priority | Urgency of investigation or resolution |
| Environment | Test conditions |
| Expected result | Intended behaviour |
| Actual result | Observed behaviour |
| Steps to reproduce | Steps required to reproduce the issue |
| Evidence | Photos, videos, measurements or logs |
| Suspected cause | Potential explanation, if identified |
| Status | Open, Under Investigation, Resolved or Closed |
| Corrective action | Action taken or proposed |
| Retest result | Outcome of verification |
| Tester notes | Additional observations |

---

## 3. Severity Classification

### Critical

Failure that causes a serious safety risk, critical functionality loss or major product failure.

### High

Failure that significantly affects important product functionality or prevents normal use.

### Medium

Failure that affects functionality but does not prevent the product from being used entirely.

### Low

Minor issue with limited functional impact, cosmetic impact or inconvenience.

Severity should be determined based on the actual impact of the defect, not simply how easy it is to fix.

---

## 4. Priority Classification

### High Priority

Requires urgent attention due to significant customer impact, operational impact or risk.

### Medium Priority

Requires resolution within an appropriate timeframe but does not require immediate action.

### Low Priority

Can be addressed later without significantly affecting product operation or customer experience.

Severity and priority are related but are not identical. Severity describes the impact of a defect, while priority determines how urgently it should be addressed.

---

## 5. Sample Defect Report

**Illustrative example only — not an actual test result.**

| Field | Example |
|---|---|
| Defect ID | DEF-001 |
| Product | Smart Wi-Fi Video Doorbell |
| Test ID | TC-004 |
| Defect title | Unexpected reboot during continuous operation |
| Severity | High (illustrative classification) |
| Priority | High (illustrative classification) |
| Environment | Continuous operation test |
| Expected result | Device operates continuously without unexpected reboot |
| Actual result | Device unexpectedly reboots during the test |
| Steps to reproduce | Power device, connect to Wi-Fi, initiate video streaming and maintain operation |
| Evidence | Not available — hypothetical scenario |
| Suspected cause | Undetermined |
| Status | Open |
| Corrective action | Investigate power stability, thermal behaviour, firmware and connectivity |
| Retest result | Not tested |

---

## 6. Defect Investigation Workflow

1. Identify the issue.
2. Record the observed behaviour.
3. Compare actual behaviour with expected behaviour.
4. Reproduce the defect.
5. Document test conditions and evidence.
6. Assess severity and priority.
7. Investigate potential causes.
8. Recommend or implement corrective action.
9. Retest after corrective action.
10. Verify the result and update the defect status.

---

## 7. Retesting and Verification

Retesting should verify whether the corrective action has resolved the original defect.

The retest should:

- Follow the original test procedure.
- Use documented test conditions.
- Confirm whether the defect can still be reproduced.
- Record the outcome.
- Identify any new issues introduced by the corrective action.

### Retest Record

| Field | Entry |
|---|---|
| Defect ID | |
| Retest date | |
| Retest procedure | |
| Expected result | |
| Actual result | |
| Retest status | Pass / Fail / Not Tested |
| Evidence | |
| Tester notes | |

---

## 8. Quality Documentation Principles

Effective defect documentation should be:

- Clear and objective.
- Reproducible.
- Evidence-based.
- Consistent.
- Traceable to the original test.
- Focused on observed behaviour rather than assumptions.

---

## 9. Project Limitations

This repository demonstrates defect reporting and test documentation methodologies through templates and illustrative scenarios.

The example defect is hypothetical and is not based on testing a physical product.

The templates can be adapted for real-world product inspection, electronics testing, troubleshooting and quality assurance activities.

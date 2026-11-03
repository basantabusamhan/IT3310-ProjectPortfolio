# Risk Register: RCHN Patient Intake and Scheduling System

**Consultant:** Basant Abusamhan  
**Role:** Associate Consultant, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** November 3, 2026

---

## Risk Entries

### Risk 1
**Description:** If intake and scheduling workflows differ more than expected across the six clinics, then additional requirements and configuration work may delay standardization for the RCHN project.

**Probability:** High  
**Impact:** High  
**Score:** 9  
**Response Strategy:** Mitigate. The team will review and document the workflows at all six clinics early in the project. Clinic managers and front desk staff will help confirm common requirements and identify differences before configuration begins.

**Trigger or Monitoring Condition:** Conflicting workflow requirements are identified or common requirements remain unconfirmed by the end of Week 1.

**Owner:** Product Manager, because this role is responsible for gathering clinic requirements and making sure the system supports the needs of users across all six clinics.

### Risk 2
**Description:** If clinic staff are unavailable for planned training or pilot activities, then training may be delayed and employees may not be prepared to use the new system.

**Probability:** Medium  
**Impact:** High  
**Score:** 6  
**Response Strategy:** Mitigate. The Project Manager will coordinate with clinic managers to confirm staff availability and schedule training in advance. Quick reference instructions and make-up sessions will be provided when needed.

**Trigger or Monitoring Condition:** A clinic has not confirmed staff availability before its scheduled training date or attendance is lower than planned.

**Owner:** Project Manager, because this role coordinates the project schedule, clinic managers, and training activities.

### Risk 3
**Description:** If configuration of the intake forms or scheduling workflow takes longer than planned, then testing may start late and delay the Week 4 testing milestone.

**Probability:** Medium  
**Impact:** High  
**Score:** 6  
**Response Strategy:** Mitigate. The team will monitor intake form and scheduling configuration tasks separately. Test cases will be prepared while configuration is taking place so testing can begin as soon as components are ready.

**Trigger or Monitoring Condition:** Either configuration task is expected to finish late or is not ready when Week 4 testing is scheduled to begin.

**Owner:** Scrum Master, because this role monitors team progress, identifies blockers, and helps keep configuration and testing activities on schedule.

### Risk 4
**Description:** If testing does not identify scheduling conflicts or important workflow defects before acceptance, then users may experience booking errors or double bookings, affecting the quality and readiness of the new system.

**Probability:** Medium  
**Impact:** High  
**Score:** 6  
**Response Strategy:** Mitigate. The Developer will help test available appointment times, occupied time slots, appointment updates, cancellations, and saved appointments. Defects will be documented, corrected, and tested again before acceptance.

**Trigger or Monitoring Condition:** Testing identifies an incorrect booking, double booking, or unresolved critical defect at the Week 4 testing milestone.

**Owner:** Developer, because this role is responsible for technical testing, identifying defects, and helping correct problems before the system is accepted.

### Risk 5
**Description:** If stakeholders request features outside the approved Phase One scope, such as an online scheduling portal or billing integration, then additional work may affect the project schedule, cost, and available resources.

**Probability:** Medium  
**Impact:** Medium  
**Score:** 4  
**Response Strategy:** Avoid. The Project Manager will keep the approved Phase One scope clear and review additional requests through the formal change process. Out-of-scope features will not be added unless the project sponsor reviews and approves the change.

**Trigger or Monitoring Condition:** A stakeholder requests a feature that is not included in the approved Phase One scope.

**Owner:** Project Manager, because this role is responsible for managing scope, reviewing change requests, and communicating possible schedule and resource impacts.

---

## Bring Forward

**Week 5 assumptions:**

Assumption 1: RCHN will confirm the Phase One project scope before detailed scheduling and resource planning.

Assumption 2: The intake and scheduling workflows across all six clinics can be standardized into one replacement system.

**Week 7 backlog item:**

As a clinic front desk staff member, I want to view available appointment times and check for scheduling conflicts before booking an appointment, so that I can avoid double bookings and schedule patients correctly.

**Week 8 schedule item:**

Activity: Test intake and scheduling workflows.  
Predecessors: B and C.  
Planned Week: Week 4.  
Milestone: Intake and scheduling workflows tested.

---

## Assumption Connection

Risk 1 connects to my Week 5 assumption that the intake and scheduling workflows across all six clinics can be standardized into one replacement system. This became a risk because the clinics may have different processes and requirements. If those differences are greater than expected, additional work may be needed before the system can be standardized. This could affect the project objective of providing a consistent system across all six clinics.

Risk 5 connects to my Week 5 assumption that RCHN will confirm the Phase One project scope before detailed scheduling and resource planning. This became a risk because stakeholders may request additional features after planning begins. If the scope is not kept clear, new requests could increase the workload and affect the project schedule, cost, and resources.

---

## Score Justification

For Risk 1, I rated probability as High because the project involves six different clinics that may have different intake and scheduling workflows. I rated impact as High because additional requirements and configuration work could delay the project and make it harder to create one consistent system for all clinics.

For Risk 4, I rated probability as Medium because testing may identify most problems, but some scheduling conflicts or workflow defects could still be missed. I rated impact as High because incorrect appointments or double bookings could affect patient scheduling, system quality, and go-live readiness. These problems would need to be corrected before the system is accepted.

---

## Risk Reflection

### Highest Priority Risk and Project Impact

My highest-priority threat is Risk 1 with a course score of 9. It deserves the most attention because the six clinics may have different intake and scheduling workflows. If these differences are not identified early, the team may need additional time to gather requirements and configure the system.

If it occurred, it could affect the schedule by delaying configuration and testing. It could affect cost and resources by requiring additional work from the project team. It could also affect quality and stakeholder confidence if the final system does not support the needs of all six clinics.

### Risk vs. Issue Distinction

After reviewing my five risks, I confirmed that each one is a future uncertainty rather than a problem that has already happened. Risk 1 is the possibility of discovering differences between clinic workflows. Risk 2 is the possibility that staff may not be available for training. Risk 3 is the possibility of configuration delays. Risk 4 is the possibility that testing may miss important defects. Risk 5 is the possibility that stakeholders may request features outside the approved scope.

The distinction matters because risks need to be monitored and prevented before they happen. Issues are problems that have already occurred and need to be addressed. By identifying these risks early, the NovaTech team can prepare responses and reduce their impact on the RCHN project.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*

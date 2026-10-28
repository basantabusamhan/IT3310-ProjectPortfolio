# Project Schedule: RCHN Patient Intake and Scheduling System

**Consultant:** Basant Abusamhan  
**Role:** Associate Consultant, Project Manager, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** October 27, 2026

---

## Work Breakdown Structure

### Grouping 1: Project Initiation and Requirements
- 1.1 Review project scope, objectives, and constraints
- 1.2 Gather intake and scheduling requirements from clinic staff
- 1.3 Confirm requirements with RCHN stakeholders

### Grouping 2: Project Planning and Workflow Design
- 2.1 Standardize patient intake form fields
- 2.2 Design consistent scheduling workflows for six clinics
- 2.3 Prioritize and approve the product backlog

### Grouping 3: System Configuration and Testing
- 3.1 Configure patient intake forms and scheduling workflows
- 3.2 Test scheduling functions and check for double bookings
- 3.3 Conduct user acceptance testing with clinic representatives

### Grouping 4: Training, Deployment, and Project Closure
- 4.1 Prepare training materials for clinic staff
- 4.2 Train staff and prepare the clinics for implementation
- 4.3 Obtain stakeholder approval and document project closure

### WBS Rationale

My WBS is based on the RCHN project scope of improving patient intake and scheduling across six clinics. It starts with gathering requirements and planning the workflows before moving into system configuration and testing. The final phase covers staff training, implementation preparation, and project closure. These work packages address problems such as inconsistent intake forms, scheduling conflicts, double bookings, and confusion among front desk staff. The detailed technical requirements, implementation dates, and any additional features still need to be confirmed with RCHN stakeholders.

---

## Task Dependencies

- Confirm intake and scheduling requirements → Configure intake and scheduling workflows, Finish-to-Start.
- Configure scheduling workflows → Prepare staff training materials, Start-to-Start.
- Conduct user acceptance testing → Complete testing documentation, Finish-to-Finish.

### Dependency Logic

If confirming the requirements is delayed by two weeks, system configuration could also be delayed because the team needs approved requirements before starting the work. This could affect workflow testing, user acceptance testing, training, and the implementation milestone. The team could reduce the impact by preparing training materials and other independent tasks while waiting. However, the team should not skip requirement approvals or testing just to save time. Any schedule changes should be reviewed with the project stakeholders.

---

## Activity Schedule

| ID | Activity | Duration (working days) | Predecessors | Start week |
|---|---|---:|---|---:|
| A | Confirm project requirements | 5 | None | 1 |
| B | Standardize patient intake forms | 10 | A | 2 |
| C | Configure scheduling workflows | 10 | A | 2 |
| D | Test intake and scheduling workflows | 5 | B,C | 4 |

### Scheduling Assumptions

I estimated the durations based on the amount of work involved in each activity. Confirming requirements is estimated at five working days, while standardizing intake forms and configuring scheduling workflows each require ten days. Testing is estimated at five days. I selected these predecessors because the team needs confirmed requirements before configuring the system, and both configuration activities must finish before testing begins. These are preliminary estimates, not approved project dates. The schedule could change depending on stakeholder availability, technical requirements, or feedback from clinic staff.

---

## Milestones

- **Milestone 1: RCHN requirements approved.** Target: End of Week 1. Exit criteria: RCHN stakeholders have reviewed and approved the patient intake and scheduling requirements for the six clinics.
- **Milestone 2: Intake and scheduling workflows tested.** Target: End of Week 4. Exit criteria: User acceptance testing is complete, clinic representatives have reviewed the results, and no unresolved critical defects remain. Any required approvals are documented.

### Critical Path Analysis

Path A → B → D takes 3 + 4 + 2 = 9 days. Path A → C → D takes 3 + 6 + 2 = 11 days. The critical path is A → C → D because it is the longest path. The total project duration in this exercise is 11 working days. If an activity on the critical path is delayed by two days, the project could finish two days later unless the team can recover the time through schedule adjustments. The other path has two days of float because it takes nine days compared with the eleven-day critical path. This calculation applies to the separate critical path exercise, not to my four-activity RCHN schedule.

---

## Schedule Reflection

### Scope Connection

The WBS grouping for Project Planning and Workflow Design connects to the Week 5 scope of improving patient intake and scheduling across six RCHN clinics. Standardizing patient intake form fields helps make information more consistent, while designing scheduling workflows helps reduce double bookings and confusion among front desk staff. These work packages organize the work needed to address the project problems. The exact requirements and final workflow designs still need stakeholder confirmation.

### Objective Connection

The milestone for completing and testing the intake and scheduling workflows supports the project objective of improving consistency and reducing scheduling problems across the six clinics. The milestone requires testing to be completed and critical defects to be resolved before the team moves forward. The team still needs to confirm the final acceptance criteria with RCHN stakeholders and agree on the implementation timeline. This will help ensure the milestone reflects the project's approved objectives.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*

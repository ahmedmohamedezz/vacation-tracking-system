# vacation-tracking-system

## Problem Statement

- For many businesses today, the independence of workers has been ever increasing. It is not uncommon for workers to divide their time across multiple projects and to report to multiple project managers.

- As a result, managers have fewer informal interactions with their workers and find it increasingly difficult to be aware of and manage their workers’ vacation time.

## Requirements (Vision, Functional, Non-Functional, Constraints)

![constraints](./images/constraints.png)

- A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

## Notes Regarding Non-Fucntional Requirements

> such a vague requirement that should never be recorded as an official requirement can make the system fail if not met from the endusers point-of-view

- such vague requirement can't be verified, or tested. but, they exist so they can be used to support and justify other, more concrete requirements or design decisions.

- what is meant by **easy to use**? consider a system that requires enduser to write text in formatted style (bold, italics, lists). would a system that lets users enter special key-codes to apply such effect be easier to use than one with built-in functionality to apply them on the users behalf ?

- however, if ease of use was desired rather than a critical requirement. the added complexity to provide ease of use could not be justified

## Domain

### The system solve 2 problems

1. Let Employees contorl their vacations.

   - give individual employees the capability and responsibility to **manage** their vacations (sick leave, personal time off, ...) with respect to their employment agreements with the company.

   - which result in a sense of empowerment to the employees.

2. Streamline the functions of the human resources (HR) department

     - to minimize noncore, business-related activities of management.
  
## Actors

![actors-and-activities](./images/actors-and-activities.png)

## System Top Level View

![system top level use case](./images/system-top-level-use-case.png)

---

## Flows and Use Cases

> for each use case, you will find a dedicated markdown file containing the use-case description, actors, goal, preconditions, flow, data model, flowchart, and pseudocode

1. **Manage Time**: happy scenario. allow employees to manage their vacations (sick leave, personal time off, ...).

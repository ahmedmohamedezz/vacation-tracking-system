# vacation-tracking-system

## Problem Statement

- For many businesses today, the independence of workers has been ever increasing. It is not uncommon for workers to divide their time across multiple projects and to report to multiple project managers.

- As a result, managers have fewer informal interactions with their workers and find it increasingly difficult to be aware of and manage their workers’ vacation time.

## Decision

- so, the company decided to build a flexible vacation time management application for managers and employees alike to use to manage their vacation time.

## Vision

- A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.

## Functional Requirements

- Enables manager approval (optional)

- Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future

- Uses e-mail notification to request manager approval and notify employees of request status changes

- Keeps activity logs for all transactions

- Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides

- Allows managers to directly award personal leave time (with system-set limits)

- Provides a Web service interface for other internal systems to query any given employee’s vacation request summary

- Interfaces with the HR department legacy systems to retrieve required employee information and changes

## Non-Functional Requirements

- The system should be easy to use

- Implements a **flexible** rules-based system for validating and verifying leave time requests

- Uses existing hardware and middleware

- Is implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication

## Notes Regarding Non-Fucntional Requirements

> such a vague requirement that should never be recorded as an official requirement can make the system fail if not met from the endusers point-of-view

- such vague requirement can't be verified, or tested. but, they exist so they can be used to support and justify other, more concrete requirements or design decisions.

- what is meant by **easy to use**? consider a system that requires enduser to write text in formatted style (bold, italics, lists). would a system that lets users enter special key-codes to apply such effect be easier to use than one with built-in functionality to apply them on the users behalf ?

- however, if ease of use was desired rather than a critical requirement. the added complexity to provide ease of use could not be justified

## Constraints

- **past** requests's access must be within the previous calendar year.

- **future** requests's access must be up to a year and a half in the future

- mail notifications must be sent in case of employee req status change, or awarded time leave from manager

- mail notifications must be sent to direct manager if an employee requested a time leave

- all transactions must be logged (req made, req approve, req reject, req status overrided)

## Domain

- The system solve 2 problems:

1. Let Employees contorl their vacations. give individual employees the capability and responsibility to **manage** this particular aspect of their employment agreements with the company. which result in a sense of empowerment to the employees.

2. Streamline the functions of the human resources (HR) department, to minimize noncore, business-related activities of management.
  
## Actors

- employees:  main user of this system. use the system to manage his/her vacation time

- managers: approve/reject requests, award employees

- HRs: manage recodrds (browse, add, delete)

- System Admins: responsible for the smooth running of the system’s technical resources (servers, DBs). and  for collecting & archiving system logs

- mail service: notify employee & managers for requests & status changes

- internal systems: query any given employee’s vacation request summary

- HR legacy systems: retrieve employee information and changes

## System Top Level View

![system top level use case](./system-top-level-use-case.png)

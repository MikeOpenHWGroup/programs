# Verification Environment for the CVA6 MMU/PMP - Project Concept/Launch Proposal

**Date of proposal**

2025-05-23

Updated: see git revision history

**Author(s)**

Tanuj-Kumar Khandelwal - Research Engineer - CEA List (Grenoble)<br>

Comments and additions by Mike Thompson, OpenHW Foundation

## High Level Summary of project, project components, and deliverables

### Summary
The Memory Management Unit is an important block of processor designs. It helps virtual memory management, address translation and memory protection. 
The MMU/PMP used in CVA6 is highly configurable and require an extensive verification. We propose a standalone UVM testbench with following features: 

   - Psuedo Randomly constraint stimulis 
   - Random and directed tests 
   - Reusable coponents 
   - Generation of page table on the fly 
   - Verification of reset of the fly 
   - Generic and easy to use compilation and simulation scripts
   - Verification of USER/Supervisior/Machine Mode

### Components
  - Main goal of the project is to bring MMU/PMP to TRL 4. 

### Deliverables
  - UVM TestBench 
  - Verification Document
  - Testplan

## Summary of market or input requirements

### Known market/project requirements at PC gate
  - 64 bit MMU/PMP verified

### Potential future enhancements
Future developments may add features such as
  - Verification of Hypervision Extension 

## Who would make use of OpenHW output
It will benefit anyone with following requirements: 
- System Integrators looking for an "Industrial Grade" SV32/SV39 MMU.

## Initial Estimate of Timeline
In order to open-source the MMU/PMP we would like to accomplish the
following tasks:
  - Improve Testplan and verification document. Estimated effort is low: 1 person/month.
  - Create UVM verification environment for standalone
    (without core) testing of the MMU/PMP. Estimated effort is
    medium-high: 6 person/month.

## Explanation of why OpenHW should do this project
  - The MMU/PMP bench allows to run and verify different MMU/PMP features stand alone without core. It makes the verification easier and faster. 
  - Deepen engagement of key EU research organizationn CEA with OpenHW projects

## Industry landscape: description of competing, alternative, or related efforts in the industry
Hereafter some of the features of other open-source, MMU verification 
  - 10xEngineer verification  environnement


## OpenHW Members/Participants committed to participate

Tanuj-Kumar Khandelwal - Research Engineer - CEA List (Grenoble)<br>

Additional participation for specification and verification plan
reviewing welcomed.

## Project Leader(s)

### Technical Project Leader(s)

Tanuj-Kumar Khandelwal - Research Engineer - CEA List (Grenoble)<br>

### Project Manager, if a PM is designated

## Next steps/Investigation towards Project Launch (**PC only**)

  - Review of specifications from interested parties and the Cores Task
    Group.

  - Review verification plan. Discuss approaches for verification with
    interested parties and the verification task group. Determine a
    verification phase approach.

  - Meeting with other OpenHWG members/staff to discuss about repository
    structure, simulation tools.

### Repository Requirements
  - Separate repository for the MMU/PMP Verification as it can be used for different cores

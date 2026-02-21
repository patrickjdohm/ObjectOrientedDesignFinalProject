# Object Oriented Design Final Project
This is a repo to hold our final project.
# Final Course Project (26 Points)
# Tool-Assisted Refactoring and Design Evaluation
**Graduate-Object-Oriented Development**

## Project Overview
In this project, you will analyze an existing object-oriented software system using **reverse-engineering tools**, apply **tool-supported refactoring**, and evaluate the impact of refactoring using **object-oriented design metrics**.

The project emphasizes:
- Tool-assisted design understanding
- Evidence-based refactoring decisions
- Object-oriented design quality
- Metrics-based interpretation (not metric optimization)

You are **not expected** to manually inspect or fully understand the source code.

## Project Constraints
- Duration: **4 weeks**
- Language: **Java**
- Work in **groups of five**
- Use **only free tools**
- All refactorings must be **tool-supported** (no manual refactoring)

## Step 1: Tool-Assisted Design Analysis (Reverse Engineering)
### Goal
Understand the system's **object-oriented structure** using automated tools.
### Required Activities
Using one or more reverse-engineering tools, extract:

- A **class diagram** (focus on key classes only)
- A **package/component-level diagram**
- **CK metrics** for the original system

### Required Metrics
Compute at least **four(4)** CK metrics such as:

- WMC (Weighted Methods per Class)
- CBO (Coupling Between Objects)
- RFC (Response for a Class)
- LCOM (Lack of Cohesion of Methods)
- DIT/NOC (optional)

### Deliverables (Step 1)
- Extracted diagrams (images or PDFs)
- Table of CK metrics (before refactoring)
- **Short analysis (1-2 pages)** addressing:
* Overall system structure
* Potential refactoring candidates suggested by diagrams and metrics

## Step 2: Tool-Supported Refactoring
### Goal
Indentify and apply **at least one (1) refactoring** based soley on **tool output**
### Constraints
- Refactoring decisions must be motivated by:
* Extracted diagrams and/or CK metrics
- Refactorings must be applied using **IDE or refactoring tools**
- No manual refactoring based on source code inspection

### Examples of Acceptable Refactorings 
- Extract Class
- Move Method
- Rename Class/Method
- Introduce Interface
- Simplify inheritance hierarchy
### Deliverables (Step 2)
- Description of the refactoring:
* What tool indicated the design issue?
* What design problem was identified?
- Description of applied refactoring
- Evidence that the system still builds successfully

## Step 3: Post-Refactoring Evaluation
### Goal
Evaluate whether refactoring resulted in **measurable design changes**.

### Required Activities
- Recompute the **same CK metrics** after refactoring
- Compare
* Before vs after values
* Affected vs. unaffected classes (if applicable)
### Analysis Questions
- Which metrics changed?
- Were changes positive, negative, or neutral?
- Do the results match your expectations?
- What design trade-offs are visible?

**No statistical testing is required**

## Approved Tools (Free Use Only)
Students muse use **freely available tools only**. Recommended tools include:

- Eclipse IDE
- ObjectAid UML Explorer (Eclipse plugin)
- Eclipse built-in dependency analysis tools
- CK metrics tool (open-source CK implementation)
- Eclipse built-in refactoring support

Other free tools may be used **only if** the tool name and version are clearly stated and no paid license is required.

## Provided Systems

Students must select **on Java system** from the **instructor-provided Github project list**.

## Deliverables
### GitHub Repository
- Original system (or link)
- Refactored version
- Diagrams 
- CK metrics data (before and after)

### Final Report (6-8 pages)
Required sections:
1. Introduction
1. Tool-Assisted Design Analysis
1. Refactoring Identification & Execution
1. Metrics Comparison & Discussion
1. Threats & Limitations
1. Conclusion

Submit the Github link via Blackboard.


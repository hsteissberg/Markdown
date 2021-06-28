# **DRAFT** Documentation of Activities
## Delivery Order W912HZ20F0209/Contract W912HZ-20-D-0004

## *Conduct FRESCO Framework & Model Debugging, Perform Model Evaluations and Validation*
<br/>
<br/>
<br/>
<br/>
6/23/2021<br/>
<br/>
<img src="images/00_Limno_Official_Logo.jpg" style="vertical-align: bottom;" width=300>

<div style="page-break-after: always;"/>

# Introduction
The U.S. Army has a continuing need to understand human and environmental health risks associated with military-relevant compounds (MRCs) and with movement off-site of range munition constituents (MCs). The U.S. Army Engineer Research and Development Center is now developing a renewed product ⸺ the Fate and Risk Evaluation System for Contaminants (FRESCO™) ⸺ that builds on and updates the Training Range Environmental Evaluation and Characterization System (TREECS™, 2008-present) and the earlier Adaptive Risk Assessment Modeling System (ARAMS™, 2000-2007) to address the Army’s needs and further support the Operational Range Assessment Program.   

## Understanding Risks
FRESCO™ extends ARAMS™ and TREECS™ capabilities for modeling fate and transport of MRCs and MCs to establish media concentrations for comparison to risk-based screening levels (Level 1 risk assessment). The extended capabilities are being implemented in concert with modernization of the supporting data, the codebase ⸺ including the underlying Framework for Risk Analysis in Multimedia Environmental Systems (FRAMES) modeling framework developed at the Department of Energy’s Pacific Northwest National Laboratory (PNNL) ⸺ and documentation to deliver a sustainable and reliable platform for MC/MRC risk assessment for the long term. 

## Current Work
Under delivery order W912HZ20F0209 (*Conduct FRESCO Framework & Model Debugging, Perform Model Evaluations and Validation*) for contract W912HZ-20-D-0004, LimnoTech is responsible for four tasks:

* TASK 1. Conduct FRESCO™ Framework, Models, and Components Debugging.
* TASK 2. Conduct FRESCO™ Framework, Models and Components Testing and Evaluation.
* TASK 3. Conduct FRESCO™ Framework, Models, and Components Validation using Existing Army Datasets.
* TASK 4. Development of a Final Report documenting FRESCO™ Framework, Models, and Components.

Deliverables for this order include updated code as well as documentation of the process and outcomes for debugging, evaluating, and validating that code. This report, which  provides the required documentation, is organized into the following sections:

* Overview of code development and management.
* Components and organization 
* Task 1 – Debugging 
* Task 2 – Test and evaluate 
* Task 3 – Validate  
* Summary and next steps

<div style="page-break-after: always;"></div>

# Overview of Code Development and Management
The FRESCO development process is built around the GitHub development platform (https://github.com/about). GitHub repositories are used to store and version-track the source code and other components of the FRESCO system, and to organize debugginng and development activity. Because of the complexity of FRESCO and its components, the source code, help contens, and other files are distributed across the following individual repositories:

**==== LIST OF REPOSITORIES HERE**

A snapshot of the contents of these repositories as of *xx/xx/2021* is available at *URL*. The snapshot is a ZIP archive file containing individual ZIP archive files for each repository.

*Include issues in snapshot*


The main repository for FRESCO is at https://github.com/LimnoTech/FRESCO, and includes GitHub Milestones, Projects, and Issues used to manage the development process. 

The development technology stack is informed by the targeted delivery of FRESCO as a desktop program executable on a Microsoft Windows 10 workstation. The FRESCO user interace is primarily implemented in Microsoft C#.NET (UI), but version 1.0 still includes some legacy components written in Microsoft Visual Basic 6 and in Microsoft or Borland C++. The primary development platform is therefore Microsoft Visual Studio 2019 (Community Edition) (***VERSION NUMBER***). Key dependencies are:

* R
* MapWindows
* Spread FarPoint
* ***OTHERS?***

The various components (executables, libraries, help files, and data files) are combined into an installation package using Revenera InstallShield 2020 ***Rx*** Professional. The InstallShield configuration file is included as part of ***FRESCO REPO? SEPARATE REPO?***. 


<div style="page-break-after: always;"></div>

# Components and organization 

*History lesson -- FRAMES -> ARAMS -> TREECS*

*GitHub Projects*

*Match to requirements document*

**==== LIST 0.1, 1.0, and 1.1 FUNCTIONALITY ISSUES**

*Directory organization in install?*


<div style="page-break-after: always;"></div>

# Task 1 – Debugging 

Under this task, LimnoTech performed debugging of the framework, models, and components to ensure correct operation consistent with similar operations conducted with the predecessor model TREECS. Correct operation was evaluated for a number of individual actions and for complete scenarios in a manner informed by SME Mark Dortch. When incorrect operations were identified, issues labeled as "bug" were created in GitHub and used to track mitigation and confirmation of corrections. The table below lists the debugging issues identified and corrected during the course of this delivery order.


*Table: FRESCO GitHub Issues tagged as "bug" (illustrative)*

| Issue # | Issue Title | User Name | Labels | State | Milestone | Date Created |
|--|--|--|--|--|--|--|
| 16    | New folk add an issue                                                                                                | tslawecki          | bug                 | open          | FRESCO v 0.1            | 2020-12-23T18:01:06Z |
| 45    | Plotting hydrologic time series in Excel locks up                                                                    | tslawecki          | bug                 | open          | FRESCO v 1.0            | 2021-01-07T18:01:45Z |
| 47    | Minor error warnings when save a .trp file in a directory with another .trp file                                     | MarkDortch         | bug                 | open          | FRESCO v 1.0            | 2021-01-14T17:15:52Z |
| 54    | WFF Surface Water and Aquifer Percent Plus Operator                                                                  | MarkDortch         | bug                 | open          |                         | 2021-01-30T19:38:15Z |
| 55    | Potential bug when linking MEPAS human exposure module to the TREECS source loading/Tier 2 soil model within FRAMES. | MarkDortch         | bug                 | open          |                         | 2021-02-02T00:47:59Z |
| 56    | Potential bug associated with MEPAS source in soil model UI in FRESCO/FRAMES                                         | MarkDortch         | bug                 | open          |                         | 2021-02-02T00:53:56Z |
| 58    | Resurfacing SU issue?                                                                                                | tslawecki          | bug                 | open          | FRESCO v 1.0            | 2021-02-18T12:44:38Z |
| 85    | Vadose and Aquifer Model UI                                                                                          | tslawecki          | bug                 | closed        |                         | 2021-05-20T16:31:18Z |
| 86    | RECOVERY not running                                                                                                 | tslawecki          | bug                 | open          |                         | 2021-05-20T17:14:21Z |


<div style="page-break-after: always;"></div>

# Task 2 – Test and evaluate 

*Intro text recapping scope of task*

**==== LIST OF TESTING/EVALUATION ISSUES FROM GITHUB HERE**

*THESE ARE NON-BUG ISSUES*


<div style="page-break-after: always;"></div>

# Task 3 – Validate  

*Intro text recapping scope of task*

*provide access to installers and test projects*

**==== LIST OF VALIDATION TESTS (TREECS PROJECTS RUN UNDER FRESCO AND COMPARED) HERE**


<div style="page-break-after: always;"></div>

# Summary and next steps

Abbreviated recap of Tasks 1-3

Next steps - move to 1.1, hanging chads, new case study, training and workshop

# Table Of Contents
need to do this

# 1 - Intro
This SBOM PoC is (at least conceptually in Duncan's head) a combination of several efforts:
- OpenC2 virtual plugfest/hackathon in preparation for [TTD-PlugfestHackathon](../TTD-PlugfestHackathon/)
- NTIA SBOM Transfer PoC - see [here](https://www.ntia.gov/sbom) and [here](https://www.ntia.gov/SoftwareTransparency)
- others TBD including potentially
   - [Integrated Adaptive Cyber Defense or IACD](https://www.iacdautomate.org/) SOAR PoC showing playbooks and automated orchestration
  - [CACAO](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cacao) playbook PoC
  - [Open Cybersecurity Alliance](https://opencybersecurityalliance.org/) PoC

See [Section 3](#3-goals-and-objectives)
for goals and objectives of each of these.

See [Section 2](#2-organizations-participating)
for organizations participating
and how their goals tie to these efforts.

See [Section 4](#4-work-plan) 4 on how the work will be organized

See Sections 5 - N on blah blah with the details

## 1.1 Vision
The vision of this activity is that it will prove several concepts
associated with several independent efforts (e.g. OpenC2, NTIA SBOM, ...).
This work is intended to be virtual
(ie no physical meetings needed)
and consist of many pairwise
interworking steps growing to larger many-party working scenarios or use cases.
Examples of scenarios include:
- an automated response to an attack on a device which did not create an SBOM. See https://youtu.be/9KnagMQ6SNI at ~3 min 10 sec as example
- a device coming online in a network, it's SBOM being queried with OpenC2, and:
    - device does not have SBOM, so orchestrator denies access to network
    - device has SBOM, sense making looks up components and discovers vulnerabilities exist, so orchestrator:
       - sandboxes device,
       - automagically installs component updates (including updating SBOM,
       - allows access to network
    - device has SBOM, sense making looks up components and discovers vulnerabilities exist, so orchestrator allows access
- ditto previous with mud (either standalone or in combination with OpenC2)
- an automated response to an attack on a device which did create an SBOM, and had automated update when CVE annouced . See  https://youtu.be/9KnagMQ6SNI at ~4 min 50 sec as example

EDITOR's NOTE: Duncan action item to make one video for scenarios above, and to remake as scenarios evolve as new organizations contribute


# 2 - Organizations Participating
Here is the list of organizations who have agreed to participate, hotlinked to pages showing what they are interested in and what they plan to contribute to this effort.
- [sFractal Consulting](./sFractalGoals.md)
- [NSA](./NSAGoals.md)
- [Huntington Ingalls Industries](./HIIGoals.md)
- [New Context](./NewContextGoals.md)


# 3 - Goals and Objectives
This effort is a mashup of several efforts
by a combination of many organizations,
all with goals related to one or more of the efforts.
The organization goals/objectives pages (see [Section 2](#2-organizations-participating))
will be combined into individual pages per effort:
- [OpenC2 Plugfest/Hackathon Goals & Objectives](./Oc2Goals.md)
- [NTIA SBOM Transfer PoC Goals & Objectives](./SbomGoals.md)
- [IACD Goals & Objectives](./IacdGoals.md)
- [CACAO Goals & Objectives](./CacaoGoals.md)
- [Opencyber Security Alliance Goals & Objectives](./OcaGoals.md)

# 4 - Work Plan
blah blah on how organized. Crib from NTIA SBOM Healthcare PoC and use their terminology and definitions (eg iterations, waves, ...).
In addition, define use cases and scenarios and how pairwise pyramid will work

# 5 -
.
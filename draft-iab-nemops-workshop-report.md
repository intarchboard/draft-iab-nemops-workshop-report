---
title: "Report from the IAB Workshop on the Next Era of Network Management Operations (NEMOPS)"
abbrev: "NEMOPS Workshop Report"
category: info

docname: draft-iab-nemops-workshop-report-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
keyword:
 - YANG
 - NETCONF
 - RESTCONF
 - NMOPS
 - RFC3535
venue:
  github: "intarchboard/draft-iab-nemops-workshop-report"
  latest: "https://intarchboard.github.io/draft-iab-nemops-workshop-report/draft-iab-nemops-workshop-report.html"
author:
 -
    fullname: "Wes Hardaker"
    email: "hardaker@isi.edu"
 -
    fullname: "Dhruv Dhody"
    email: "dd@dhruvdhody.com"
normative:

informative:
  RFC3535:
  RFC6241:
  RFC7950:
  RFC8040:
  RFC8309:
  I-D.ietf-core-comi:
  I-D.boucadair-nmop-rfc3535-20years-later:
  SURVEY:
    target: https://ietf.iad1.qualtrics.com/jfe/form/SV_9vQxBRiZqDntarc
    title: Next Era of Network Management Operations (NEMOPS) workshop survey
    date: October 2024
  SURVEY-INSIGHTS:
    target: https://datatracker.ietf.org/meeting/interim-2024-nemopsws-02/materials/slides-interim-2024-nemopsws-02-sessa-6-insights-from-operator-outreach-survey-03.pdf
    title: Insights from Operator Survey & Outreach
    date: December 2024
  SCHONWALDER:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-composable-declarative-reproducible-verifiable-network-and-service-configurations-00.pdf
    title: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations
    author:
      -
        ins:  J. Schönwälder
        name: Jürgen Schönwälder
    date: November 2024
  LARSSON:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-rfc3535-years-later-from-an-operators-perspective-deutsche-telekom-00.pdf
    title: RFC3535, 20 Years Later from an Operator's Perspective (Deutsche Telekom)
    author:
      -
        ins:  K. Larsson
        name: Kristian Larsson
      -
        ins:  K. Lambrechts
        name: Kris Lambrechts
      -
        ins:  I. Farrer
        name: Ian Farrer
    date: November 2024
  HARDAKER:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-lessons-learned-from-30-years-of-net-snmp-00.pdf
    title: Lessons Learned from 30 Years of Net-SNMP
    author:
      -
        ins:  W. Hardaker
        name: Wes Hardaker
    date: November 2024
  NET-SNMP:
    target: http://www.net-snmp.org/
    title: Net-SNMP
  BORMANN:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-coreconf-managing-iot-devices-with-yang-models-00.pdf
    title: "CORECONF: Managing IoT Devices with YANG Models"
    author:
      -
        ins:  C. Bormann
        name: Carsten Bormann
    date: November 2024
  SHAKIR:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-rethinking-standardisation-of-network-management-00.pdf
    title: Rethinking Standardisation of Network Management
    author:
      -
        ins:  R. Shakir
        name: Rob Shakir
    date: September 2024
  OPENCONFIG:
    target: https://www.openconfig.net/
    title: OpenConfig
  KELLER:
    target: https://www.ietf.org/slides/slides-nemopsws-nemops-rfc3535-and-the-forgotten-word-00.pdf
    title: "NEMOPS: RFC3535 and the forgotten word — Or Provisioning is only a subset of Network Management"
    author:
      -
        ins:  N. Warnke
        name: Nils Warnke
      -
        ins:  R. Geib
        name: Rüdiger Geib
      -
        ins:  M. Horneffer
        name: Martin Horneffer
      -
        ins:  H. Keller
        name: Holger Keller
    date: November 2024
  JIMENEZ:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-evolving-challenges-and-solutions-in-network-management-00.pdf
    title: Evolving Challenges and Solutions in Network Management
    author:
      -
        ins:  J. Jiménez
        name: Jaime Jiménez
      -
        ins:  S. Mansfield
        name: Scott Mansfield
      -
        ins:  R. Rodriguez A
        name: Raquel Rodriguez A
      -
        ins:  M. Pesonen
        name: Mikko Pesonen
      -
        ins:  V. Torvinen
        name: Vesa Torvinen
      -
        ins:  J. Karvonen
        name: Janne Karvonen
    date: November 2024
  CONTRERAS:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-rfc3535-years-later-an-update-of-operators-requirements-on-network-management-protocols-and-modelling-00.pdf
    title: "RFC 3535, 20 Years Later: An Update of Operators Requirements on Network Management Protocols and Modelling"
    author:
      -
        ins:  M. Boucadair
        name: Mohamed Boucadair
      -
        ins:  L. M. Contreras
        name: Luis Miguel Contreras Murillo
      -
        ins:  O. Gonzalez de Dios
        name: Oscar Gonzalez de Dios
      -
        ins:  T. Graf
        name: Thomas Graf
      -
        ins:  R. Rahman
        name: Reshad Rahman
      -
        ins:  L. Tailhardat
        name: Lionel Tailhardat
    date: October 2024
  GRAF:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-agile-incremental-driven-development-for-network-management-01.pdf
    title: Agile Incremental Driven Development for Network Management
    author:
      -
        ins:  T. Graf
        name: Thomas Graf
      -
        ins:  H. Keller
        name: Holger Keller
      -
        ins:  D. Voyer
        name: Dan Voyer
      -
        ins:  P. Lucente
        name: Paolo Lucente
      -
        ins:  B. Claise
        name: Benoit Claise
      -
        ins:  R. Wilton
        name: Rob Wilton
      -
        ins:  A. Huang-Feng
        name: Alex Huang-Feng
      -
        ins:  P. Francois
        name: Pierre Francois
    date: November 2024
  CLAISE:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-knowledge-graph-framework-for-network-operations-00.pdf
    title: Knowledge Graph Framework for Network Operations
    author:
      -
        ins:  B. Claise
        name: Benoit Claise
      -
        ins:  T. Graf
        name: Thomas Graf
      -
        ins:  H. Keller
        name: Holger Keller
      -
        ins:  D. Voyer
        name: Dan Voyer
      -
        ins:  P. Lucente
        name: Paolo Lucente
      -
        ins:  D. Lopez
        name: Diego Lopez
      -
        ins:  I. Martinez-Casanueva
        name: Ignacio Dominguez Martinez-Casanueva
      -
        ins:  B. Peters
        name: Brad Peters
      -
        ins:  P. Fasano
        name: Paolo Fasano
      -
        ins:  P. Ran
        name: Pang Ran
      -
        ins:  W. Cheng
        name: Weiqiang Cheng
      -
        ins:  M. Mackey
        name: Michael Mackey
    date: November 2024
  WATSEN:
    target: https://www.ietf.org/slides/slides-nemopsws-nemops-position-paper-kent-watsen-00.pdf
    title: Four Thoughts for How to Improve Network Management for Operators
    author:
      -
        ins:  K. Watsen
        name: Kent Watsen
    date: November 2024
  WILTON:
    target: https://datatracker.ietf.org/doc/slides-nemopsws-paper-device-network-management-current-status-and-future-direction/
    title: Device Network Management - Current Status, and Future Direction
    author:
      -
        ins:  R. Wilton
        name: Rob Wilton
      -
        ins:  N. Corran
        name: Nick Corran
    date: November 2024
  GUDI:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-evolving-network-management-architecture-integrating-coreconf-with-netconf-for-efficient-telemetry-and-management-00.pdf
    title: "Evolving Network Management Architecture: Integrating CORECONF with NETCONF for Efficient Telemetry and Management"
    author:
      -
        ins:  M. Gudi
        name: Manoj Gudi
      -
        ins:  A. Pelov
        name: Alexander Pelov
      -
        ins:  L. Toutain
        name: Laurent Toutain
      -
        ins:  J. Bonnin
        name: Jean-Marie Bonnin
    date: November 2024
  FOROUGHI:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-projecting-data-mesh-to-model-driven-telemetry-a-path-to-data-ecosystems-management-operations-00.pdf
    title: "Projecting Data Mesh to Model-driven Telemetry: A Path to Data Ecosystem’s Management Operations"
    author:
      -
        ins:  P. Foroughi
        name: Parisa Foroughi
      -
        ins:  L. Ciavaglia
        name: Laurent Ciavaglia
    date: November 2024
  MARTINEZ:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-iab-nemops-position-paper-telefonica-00.pdf
    title: "IAB NEMOPS Position Paper - Telefonica"
    author:
      -
        ins:  I. Martinez-Casanueva
        name: Ignacio Dominguez Martinez-Casanueva
    date: November 2024
  JIMENEZ:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-managing-iot-devices-with-lwmm-00.pdf
    title: Managing IoT Devices with LwM2M
    author:
      -
        ins:  J. Jiménez
        name: Jaime Jiménez
    date: November 2024
  GIRALT:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-towards-a-unified-compute-and-communication-infrastructure-for-application-and-network-management-00.pdf
    title: Towards a Unified Compute and Communication Infrastructure for Application and Network Management
    author:
      -
        ins:  L. M. Contreras
        name: Luis Miguel Contreras Murillo
      -
        ins:  R. Schott
        name: Roland Schott
      -
        ins:  S. Randriamasy
        name: Sabine Randriamasy
      -
        ins:  R. Yang
        name: Richard Yang
      -
        ins:  J. Ros-Giralt
        name: Jordi Ros-Giralt
    date: November 2024
  ECKERT:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-resilient-remote-managability-of-wide-area-network-infrastructures-00.pdf
    title: Resilient Remote Manageability of Wide-Area Network Infrastructures
    author:
      -
        ins:  T. Eckert
        name: Toerless Eckert
      -
        ins:  M. Richardson
        name: Michael Richardson
    date: November 2024
  BLESS:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-an-invariant-for-future-resilient-network-management-operations-00.pdf
    title: An Invariant for Future Resilient Network Management Operations
    author:
      -
        ins:  R. Bless
        name: Roland Bless
    date: November 2024
  SCHARF:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-network-management-challenges-for-ip-based-cyber-physical-networks-00.pdf
    title: Network Management Challenges for IP-based Cyber-Physical Networks
    author:
      -
        ins:  M. Scharf
        name: Michael Scharf
    date: November 2024
--- abstract
The "Next Era of Network Management Operations (NEMOPS)" workshop was convened by the Internet Architecture Board (IAB) on December 3-5, 2024 as a three-day online meeting. It builds on a previous 2002 workshop, the outcome of which was documented in RFC 3535 identifying 14 operator requirements for consideration in future network management protocol design and related data models, along with some recommendations for the IETF. Much has changed in the Internet’s operation and technological foundations since then. The NEMOPS workshop reviewed the past outcomes and identified any operational barriers that prevented these technologies from being widely implemented. It sketched new requirements for future network management operations collaboratively with the industry, network operators and protocol engineers, and developed a suggested action plan and recommendations for the IETF.

Note that this document is a report on the proceedings of the workshop.  The views and positions documented in this report were expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

--- middle

# Introduction

The IAB organized a workshop in 2002 to establish a dialog between network operators and protocol developers, and to guide IETF when working on network management protocols. The outcome of that workshop was documented in the "Overview of the 2002 IAB Network Management Workshop" {{RFC3535}} which identified 14 operator requirements for consideration in future network management protocol design and related data models, along with some recommendations for the IETF.

Those requirements were instrumental in developing first the NETCONF protocol (in the NETCONF Working Group) {{RFC6241}}, the associated YANG data modeling language (in the NETMOD Working Group) {{RFC7950}}, RESTCONF {{RFC8040}}, and most recently CORECONF {{I-D.ietf-core-comi}}.

The recent NEMOPS IAB workshop focussed on the following key topics:

* Review the outcomes and results of the 2002 workshop (current deployments, state of the art) and identify any operational barriers that prevent these technologies from being widely implemented (limitations, hurdles).
* Sketch new requirements for future network management operations in a collaborative manner with the industry, network operators, and protocol engineers.
* Develop a plan of action and recommendations for the IETF.

## About this workshop report content

The Internet Architecture Board (IAB) holds occasional workshops designed to consider long-term issues and strategies for the Internet, and to suggest future directions for the Internet architecture.  This long-term planning function of the IAB is complementary to the ongoing engineering efforts performed by working groups of the Internet Engineering Task Force (IETF).

This document is a report on the proceedings of the workshop. The views and positions documented in this report are expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

Furthermore, the content of the report comes from presentations given by workshop participants and notes taken during the discussions, without interpretation or validation.  Thus, the content of this report follows the flow and dialogue of the workshop but does not necessarily attempt to capture a consensus, unless stated otherwise.

# Outreach and Survey {#outreach}

There has been a noticeable decline in the direct participation of network operators in the IETF and its associated discussions on network management protocols and operations. Many operators prioritize operational conferences over standards development organizations (SDOs), such as RIPE, NANOG, APRICOT, LACNIC, AutoConn, etc.

To address this, the IAB workshop's Program Committee (PC) planned outreach initiatives to foster discussions and gather interest by engaging with operators at these venues and conducting information/requirement-gathering sessions. Participants were encouraged to submit 'position papers' or 'expressions of interest' to join the workshop. Additionally, a survey [SURVEY] was conducted to collect valuable insights to inform the workshop.

The PC continues to engage with network operators after the workshop to facilitate information sharing and gather their feedback, helping to shape the next steps and outcomes of the workshop.

# Workshop Scope and Discussion
The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day. On the last day, a discussion on the key takeaways from the workshop and possible next steps took place.

## Session I: Past (lookback, analysis)

The first day of the workshop focused on reflecting on the past by reviewing the evolution of network management since the 2002 workshop, analyzing both the successes and the challenges encountered along the way. The presentations covered a range of topics, including reflections on the history of network management, lessons learned from widely used tools, practices in constrained networks, and the need to reconsider how network management models and protocols are standardized within the IETF.

### Reflections

The workshop began by reflecting on the IAB’s role in shaping the evolution of network management away from CLI/SNMP/MIB, focusing on the context and key outcomes of the previous workshop, an assessment of the current state, and an acknowledgement of some regrets (such as XML as the data representation format). {{SCHONWALDER}} emphasized the need to shift the focus from device-level configuration to network and service-level configuration. Key properties highlighted for effective network and service configurations included being Composable (assembled out of modular configurations), Declarative (define state while systems determine themselves how to move to it), Reproducible (reliably and consistently recreated), and Verifiable (tools to verify properties).

An operator’s perspective highlighted that the recommendations of {{RFC3535}} (which led to the development of YANG and NETCONF) have been successful in addressing device configuration. In certain areas, the advancements in semantics and protocols for streaming telemetry have even surpassed the original scope of {{RFC3535}}. {{LARSSON}} cautioned against making changes that could disrupt the ecosystem. The presentation emphasized the need to prioritize service modeling in the IETF and addressed the challenges of mapping to the Business Support Systems (BSS) domain. It also stressed the importance of including the operational state in service models to enable closed-loop automation for end-to-end (E2E) services. Revisiting {{RFC8309}}, which asserts that the operational state of a service is not part of a customer service model but can be achieved through extensions, was suggested. Additionally, the lack of open-source NMS implementations, tools, and device model implementations was identified as a significant barrier to advancing standardization efforts. The IETF could play a key role in fostering and enabling collaborations to address these challenges including an off-box translation tool of the IETF device model to vendor proprietary models.

### Lessons to be Learned

{{HARDAKER}} emphasized that the success of Net-SNMP {{NET-SNMP}} was driven by empowering users through simplicity. He stressed that the focus should remain on ensuring ease of use and adaptability of the protocols. Emphasis was placed on the two distinct audiences for standardized network management protocols: toolkit vendors and system operators. Their requirements for protocol simplicity differ, and it is essential to address the needs of both to ensure success. {{BORMANN}} presented an overview of the CORECONF architecture, showcasing how model-driven network management techniques can be applied to manage IoT devices (which is different from other network management scenarios), with a focus on the unique characteristics of constrained nodes. Some participants noted that the binary encoding of CBOR has applications that extend beyond the IoT networks.

Drawing from the experience of OpenConfig {{OPENCONFIG}}, {{SHAKIR}} emphasized that protocol definition and data models cannot be done in isolation. It must integrate lessons learned from implementation and large-scale deployment. He highlighted the importance of enabling quick iterations, shipping rapidly, embracing open-source, readily available tools, adopting systems thinking driven by business outcomes, and reusing existing technologies rather than developing solutions exclusively for operator network management. A call was made for IETF to rethink the approach to standardize data models and the associated network management protocols.

### Discussion

The open discussion highlighted the divergence between vendor implementations of standards and what is accessible via YANG models, particularly when compared to CLI. Common challenges identified included performance issues at scale, the steep learning curve for network management protocols, models, and tools, and the backward compatibility of models. Some participants suggested that the IETF should focus on system-level APIs that address specific problems. Additionally, the lack of simple tools for smaller networks operating under tight timelines and budgets was emphasized. A key question raised was whether the proliferation of protocols and languages complicates adoption, and if converging on a single approach would improve adoption.

## Session II: Present (identified problems & requirements)

The second day of the workshop concentrated on challenges and emerging requirements for future network management operations. The presentation emphasized the importance of validation, observability, automation, and the need for agile, incremental development of both network models and management protocols. A compilation of new requirements is being maintained in {{I-D.boucadair-nmop-rfc3535-20years-later}}. The final presentation of the day provided a summary of the survey results and operator feedback gathered from outreach events.

### Operator Feedback

{{KELLER}} shared Deutsche Telekom’s perspective, emphasizing that while YANG performs well for provisioning, it currently falls short in providing the operational stability required for validation. Achieving fully closed-loop automated and autonomous networking will require a greater focus on observability, particularly through advancements in streaming telemetry.

{{JIMENEZ}} discussed the challenges associated with the SDN Transport Automation Platform, including issues with data streaming, scalability, diverse models, and mechanisms to secure the network management protocols. The presentation also emphasized how advancements in AI and machine learning, along with the potential adaptation of protocols designed for constrained environments, could drive the next evolution in network management.

Using YANG-Push as an example, {{GRAF}} highlights how standards development often fails to align with the needs of network operators, the constraints of network vendors, and the integration requirements. Most critically, it lacks an agile, incremental development process. The presentation advocated for adopting an iterative approach to standards development, focusing on delivering minimal viable products as part of the process.

{{CONTRERAS}} emphasized the importance of reassessing deployment assumptions and incorporating updated operator requirements. The authors are addressing these aspects through {{I-D.boucadair-nmop-rfc3535-20years-later}}, leveraging feedback and discussions from the workshop.

### Survey

As outlined in {{outreach}}, the workshop program committee organized outreach initiatives to gather direct feedback and conducted a survey. {{SURVEY-INSIGHTS}} provided an overview of the respondents’ backgrounds, as well as insights into the most widely used tools, protocols, and APIs for configuration, monitoring, and other network operations. Notably, the survey revealed that Ansible and CLI are the most popular configuration tools, NetConf is the preferred configuration protocol, and Prometheus and SNMP are widely used for monitoring. The survey also captured feedback on network automation and streaming telemetry. Additionally, valuable insights from direct operator feedback were also presented (see {{insights}}).

### Discussion

The open discussion featured feedback from implementers, highlighting how divergence in vendor implementations creates complexity and necessitates workarounds. Challenges were noted in mapping standard models to internal device models and legacy devices. The conversation also emphasized the importance of developing open-source reference implementations, compliance testing, and interoperability solutions.

## Session III: Future (possible solutions, recommendations and next steps)

The final day of the workshop centred on exploring potential future solutions and identifying key takeaways, recommendations, and next steps. Initial presentations covered topics such as the use of the Knowledge Graph Framework and concrete suggestions for future directions. To conclude the workshop, the chairs worked to summarize the key takeaways (see {{key}}) that garnered consensus among the participants.

### Future Directions

{{CLAISE}} highlighted the challenges of integrating data models across different silos, protocols, and data structures, emphasizing the need for a machine-readable approach to expose semantics. A potential solution was proposed using a knowledge graph based on the Semantic Web Stack, along with the need to define a basic ontology for the networking domain in an iterative manner. {{WATSEN}} recommends prioritizing the following areas: (1) RESTCONF (including YANG-Push Lite), (2) the Network Management Datastore Architecture (NMDA), (3) Data Model Adapters, and (4) Device Protocol Adapters. {{WILTON}} recommends reducing unnecessary complexity, delivering timely solutions, fostering open collaboration between vendors and operators, and prioritizing simplicity. Practical suggestions include focusing on YANG-Push Lite, introducing YANG 2.0 through incremental updates, developing NETCONFv2, and managing IETF YANG models as code or APIs rather than embedding them within RFCs.

### Discussion

The open discussion delved into the absence of NMDA in OpenConfig, the history of introducing gNMI in the IETF, and the challenges of building consensus on common ground and converging on a single protocol. It also explored approaches to handling YANG models within the IETF, such as leveraging GitHub, along with the challenges associated with its use. The discussion emphasized the need for process experimentation, particularly at the working group or area level, and considered ways to involve operators in an iterative process.

Some topics absent from the workshop discussions included tooling and strategies to support tool development. The primary focus was on YANG and NETCONF/RESTCONF, while several other network management protocols and techniques currently used received little attention.

## Key Takeaways {#key}

At the end of the third day, the discussion turned to key takeaways that had consensus. In the process of discussion there were some realizations where additional work was also needed.

[XXX: note at this point these are cut and paste from the slides and not properly edited/cleaned/moved around]

### Ecosystem conclusions

These takeaways try to document the general thinking of the participants with respect to the entire Network Management ecosystem as it exists today.

1. The current network management protocols, models and tools still
   fail the ‘ease of use’ requirement.  Participants noted that the
   tools almost matter more than the protocols.
1. The overall ecosystem is still fragmented for both protocols and
   data models.  SNMP is still used extensively for monitoring, and
   the CLI is still heavily relied on in in many networks.  Popular
   protocols include SNMP, CLI, NETCONF, RESTCONF, gNMI, etc.
1. Documentation about the architecture and usage of the network
   management ecosystem is lacking.  More work is needed to create
   general architecture documentation, deployment guides, tutorials,
   training material, and getting started guides.
1. Transitioning between network management frameworks is challenging,
   just like it is for transitioning between other protocols like IPv4
   to IPv6.
1. Model-driven network management is generally a success where it is
   implemented and possible to use.
1. More easily usable network management tools for the operators are
   needed.  The lack of open-source tools is seen as a barrier to
   adoption.  Tools need good use cases, example flows and better
   analysis of when and how they work and have been successful.

### Protocol conclusions

1. Netconf and YANG are not used much for monitoring tasks.
1. Netconf and YANG do not have full coverage on many devices.
1. Polling-based solutions are still frequently deployed.
1. Full coverage of NetConf support on devices does not exist today.
1. Polling-based solutions are still frequently deployed.  Push-based solutions are often desired but are not yet widely available.

1. False: Netconf for configuration has been successful in some larger-scale deployment
    1. Let’s discuss this further on the list
    1. Service config?
1. False: Full device control and configuration frequently requires CLI and screen scraping

### Modeling conclusions

1. Some YANG models can become too complex, though not as a fault of
   the language.
1. Multi-vendor compatibility support is required.
1. Even vendor-specific features, not just standardized protocol
   features, need to be exposed through network management protocols
   for a network management ecosystem to be viable.
1. Greater support for service-level modeling is needed.  Device level
   modeling can be a building block to achieve a sufficient
   service-level model but is not a complete solution by itself.
1. Network configuration needs to be verifiable to ensure any
   potential changes can be accepted by devices.  Model translation
   adapters (likely performed on the management station not the end
   device) may be the best path forward to simultaneously achieve this
   and a goal of supporting one configuration set across a diversity
   of devices with different internal models.
1. Full coverage of YANG models on all devices does not exist today.

### Standardization conclusions

1. A methodology of rapid model development procedures is needed to
   ensure model deployment can keep pace with new feature deployment.
   We need a solution that significantly increases the speed and
   predictable timeline for developing and publishing models within
   the IETF.  New approaches and methods to make models live outside
   of published RFCs should be explored.  An experiment should be
   started to test a new rapid development approach.
1. Protocol and model complexity should be reduced to keep additions
   and changes to a minimal set of agreed-upon core features.
1. More standardization focus is needed on the scalability of the
   different roles of network management: monitoring, configuration,
   notifications.
1. Enhancements to network management protocols and models need to be
   backed by real-world operator use cases and expected adoption by
   vendors.  Vendors and operators will need to work together to
   ensure these goals are appropriately met.

### Additional work needed

Here we list the things that the group realized needed significantly more attention in order to come to a conclusion.

--- back

# Insights from Operator Feedback {#insights}

[TODO: Check if this is useful in the RFC or should it be removed]

## General Insights

1. In network deployments, operations are typically at the bottom of the ladder. It's the most squeezed for time and resources. Network engineers are not typically seasoned developers. The development of needed in-house tools often takes years to develop. There is a need for tools that are easy to use and just work.
2. Vast majority of smaller operators use CLI and open source to manage their networks.
3. There is debate fatigue. The protocol/model debate is a recurring conversation. The problem isn’t going away.
4. It was suggested that other domains (e.g., K8N/automation) are years ahead of the current network engineering stack.
5. Support for multiple friendly, stable and feature rich libraries for programming languages is needed. Many DevOps routines use shell scripts, others use a high-level programming language. In any case, on the client side, multiple programming languages are used.
6. Screen scraping is both necessary and evil. This most often occurs when interacting with a device having only a CLI.
7. It was noted that there could be an outreach to Academia to establish programs to teach lessons using modern management stacks, and then a new generation of engineers could be helping to improve tooling and automation, with university (and/or IETF) hackathons.

## Data Models

1. In some network deployments, the focus is solely on service-level models, such that device-level protocols and device-level models are unimportant. This assumes the existence of a device adaptation layer to transcode service-level models to device-level models and conform to the device-specific protocol.
2. There is a need for solutions to not hide vendor-specific knobs. Currently, vendors compete by differentiating their offerings in unique ways. The reason why an Operator may choose a particular vendor is because of its differentiating features. Whilst standard models enable conformance, they must not hide the vendor-specific knobs. YANG deviations are a partial solution to not hiding vendor knobs.
3. It was emphasized that streaming telemetry requires picking a model and sticking with it. It is quite a commitment and the current environment makes the decision harder.
4. It was noted that IETF's focus should be on defining abstract/service-level data models since it is the only thing the community may ever agree on.
5. There was a point about navigating non-device-specific models being difficult. If understood correctly, the Network Engineer knows the CLI command but has trouble grepping for it in YANG modules defined by SDOs.
6. There was a wish that IETF and OpenConfig models would merge.

# Position Papers

20 position papers were submitted to the workshop call for papers. All papers are available at <https://datatracker.ietf.org/group/nemopsws/materials/>.

This is the list of all papers:

* J Schönwälder: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations {{SCHONWALDER}}
* K. Larsson, K. Lambrechts, and I. Farrer: RFC3535, 20 Years Later from an Operator’s Perspective (Deutsche Telekom) {{LARSSON}}
* W. Hardaker: Lessons Learned from 30 Years of Net-SNMP {{HARDAKER}}
* C. Bormann: CORECONF: Managing IoT Devices with YANG Models {{BORMANN}}
* R. Shakir: Rethinking Standardisation of Network Management {{SHAKIR}}
* N. Warnke, R. Geib, M. Horneffer, and H. Keller: NEMOPS: RFC3535 and the forgotten word — Or Provisioning is only a subset of Network Management {{KELLER}}
* J. Jiménez, S. Mansfield, R. Rodriguez A., M. Pesonen, V. Torvinen, and J. Karvonen: Evolving Challenges and Solutions in Network Management {{JIMENEZ}}
* M. Boucadair, L. M. Contreras, O. Gonzalez de Dios, T. Graf, R. Rahman, and L. Tailhardat: RFC 3535, 20 Years Later: An Update of Operators Requirements on Network Management Protocols and Modelling {{CONTRERAS}}
* T. Graf, H. Keller, D. Voyer, P. Lucente, B. Claise, R. Wilton, A. Huang-Feng, and P. Francois: Agile Incremental Driven Development for Network Management {{GRAF}}
* B. Claise, T. Graf, H. Keller, D. Voyer, P. Lucente, D. Lopez, I. D. Martinez-Casanueva, B. Peters, P. Fasano, P. Ran, W. Cheng, and M. Mackey: Knowledge Graph Framework for Network Operations {{CLAISE}}
* K. Watsen: Four Thoughts for How to Improve Network Management for Operators {{WATSEN}}
* R. Wilton and N. Corran: Device Network Management: Current Status and Future Direction {{WILTON}}
* M. Gudi, A. Pelov, L. Toutain, and J.-M. Bonnin: Evolving Network Management Architecture: Integrating CORECONF with NETCONF for Efficient Telemetry and Management {{GUDI}}
* P. Foroughi and L. Ciavaglia: Projecting Data Mesh to Model-driven Telemetry: A Path to Data Ecosystem’s Management Operations {{FOROUGHI}}
* I. D. Martinez-Casanueva: IAB NEMOPS Position Paper - Telefonica {{MARTINEZ}}
* J. Jiménez: Managing IoT Devices with LwM2M {{JIMENEZ}}
* L. M. Contreras, R. Schott, S. Randriamasy, R. Yang, and J. Ros-Giralt: Towards a Unified Compute and Communication Infrastructure for Application and Network Management {{GIRALT}}
* T. Eckert and M. Richardson: Resilient Remote Manageability of Wide-Area Network Infrastructures {{ECKERT}}
* R. Bless: An Invariant for Future Resilient Network Management Operations {{BLESS}}
* M. Scharf: Network Management Challenges for IP-based Cyber-Physical Networks {{SCHARF}}

# Workshop Participants

The workshop participants were Alex Huang, Alexander Clemm, Alexander PELOV, Benoit Claise, Boris Khasanov, Brad Peters (nbn), Carsten Bormann, Chongfeng Xie, Cindy Morgan, Dan Voyer, Darren Loher, Dean Bogdanovic, Dean Bogdanović, Dhruv Dhody, Diego Lopez, Ebben Aries, Frank (Chong Feng), Holger Keller, Ian Farrer, Jaime Jimenez, James Cumming, Janne Karvonen, Jason Sterne, Jiaming Ye, Jinming Li, John Carson, Julien Maisonneuve, Jürgen Schönwälder, Kent Watsen, Kris Lambrechts, Kristian Larsson, Laurent Ciavaglia, Laurent Toutain, Liz Flynn, Luis M. Contreras (Telefonica), Mahesh Jethanandani, Manoj Gudi, Martin Horneffer, Matthew Bocci, Med Boucadair, Michael Mackey, Michael Richardson, Michael Scharf, Mikko Pesonen, Nacho Dominguez (Telefonica), Naveen Achyuta, Nick Corran, Nils Warnke, Oscar Gonzalez de Dios, Paolo Lucente, Parisa Foroughi, Per Andersson, Phil Shafer, Qin Wu, Qiufang Ma, Raquel Rodriguez, Reshad, Reshad Rahman, Rob Shakir, Rob Wilton, Roland Bless (KIT), Roland Schott, Rüdiger Geib, Rui Zhuang, Ruibo Han, Sabine Randriamasy, Scott Mansfield (Ericsson), Scott Robohn, Shengnan Yue, Suresh Krishnan, Thomas Graf, Toerless Eckert, Wangbo, Warren Kumari, Wes Hardaker, Wim Henderickx, Xue Yang, Y. Richard Yang, Yangbo, Yisong Liu, and Zhenqiang Li.

# Workshop Program Committee

The workshop program committee members were Wes Hardaker (co-chair), Dhruv Dhody (co-chair), Qin Wu, Suresh Krishnan, Benoît Claise, Mohamed Boucadair, Mahesh Jethanandani, Kent Watsen, and Warren Kumari.

# IAB Members at the Time of Approval
{:numbered="false"}

Internet Architecture Board members at the time this document was approved for publication were: TODO

# Acknowledgments
{:numbered="false"}

TBD

---
title: "Report from the IAB Workshop on the Next Era of Network Management Operations"
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
  I-D.ietf-core-comi:
  SURVEY:
    target: https://ietf.iad1.qualtrics.com/jfe/form/SV_9vQxBRiZqDntarc
    title: Next Era of Network Management Operations (NEMOPS) workshop survey
    date: October 2024
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
--- abstract

The "Next Era of Network Management Operations (NEMOPS)" workshop was convened by the Internet Architecture Board (IAB) on December 3-5, 2024 as a three-day online meeting. It builds on a previous 2002 workshop, the outcome of which was documented in RFC 3535 identifying 14 operator requirements for consideration in future network management protocol design and related data models, along with some recommendations for the IETF. Much has changed in the Internet’s operation and technological foundations since then. The NEMOPS workshop reviewed the past outcomes and identified any operational barriers that prevented these technologies from being widely implemented. It sketched new requirements for future network management operations collaboratively with the industry, network operators and protocol engineers, and developed a suggested action plan and recommendations for the IETF.

Note that this document is a report on the proceedings of the workshop.  The views and positions documented in this report were expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

--- middle

# Introduction

The IAB organized a workshop in June 2002 to establish a dialog between network operators and protocol developers, and to guide IETF when working on network management protocols. The outcome of that workshop was documented in the "Overview of the 2002 IAB Network Management Workshop" [RFC3535] which identified 14 operator requirements for consideration in future network management protocol design and related data models, along with some recommendations for the IETF.

Those requirements were instrumental in developing first the NETCONF protocol (in the NETCONF Working Group) [RFC6241], the associated YANG data modeling language (in the NETMOD Working Group) [RFC7950], RESTCONF [RFC8040], and most recently CORECONF [I-D.ietf-core-comi].

The NEMOPS workshop aimed to discuss the following key topics:

* Review the outcomes and results of the 2002 workshop (current deployments, state of the art) and identify any operational barriers that prevent these technologies from being widely implemented (limitations, hurdles).
* Sketch new requirements for future network management operations in a collaborative manner with the industry, network operators, and protocol engineers.
* Develop a plan of action and recommendations for the IETF.

## About this workshop report content

The Internet Architecture Board (IAB) holds occasional workshops designed to consider long-term issues and strategies for the Internet, and to suggest future directions for the Internet architecture.  This long-term planning function of the IAB is complementary to the ongoing engineering efforts performed by working groups of the Internet Engineering Task Force (IETF).

This document is a report on the proceedings of the workshop. The views and positions documented in this report are expressed during the workshop by participants and do not necessarily reflect IAB's views and positions.

Furthermore, the content of the report comes from presentations given by workshop participants and notes taken during the discussions, without interpretation or validation.  Thus, the content of this report follows the flow and dialogue of the workshop but does not necessarily attempt to capture a consensus, unless stated otherwise.

# Outreach and Survey

There has been a noticeable decline in the direct participation of network operators in the IETF and its associated discussions on network management protocols and operations. Many operators prioritize operational conferences over standards development organizations (SDOs), such as RIPE, NANOG, APRICOT, LACNIC, AutoConn, etc.

To address this, the Program Committee (PC) planned outreach initiatives to foster discussions and gather interest by engaging with operators at these venues and conducting information/requirement-gathering sessions. Participants were encouraged to submit position papers or expressions of interest to join the workshop. Additionally, a survey [SURVEY] was conducted to collect valuable insights to inform the workshop.

The PC intends to continue engaging with network operators after the workshop to facilitate information sharing and gather their feedback, helping to shape the next steps and outcomes of the workshop.

# Workshop Scope and Discussion
The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day. On the last day, a discussion on the key takeaways from the workshop and possible next steps took place.

## Session I: Past (lookback, analysis)

The first day of the workshop focused on reflecting on the past by reviewing the evolution of network management since the 2002 workshop, analyzing both the successes and the challenges encountered along the way. The presentations covered a range of topics, including reflections on the history of network management, lessons learned from widely used tools, practices in constrained networks, and the need to reconsider how network management models and protocols are standardized within the IETF.

The workshop began by reflecting on the IAB’s role in shaping the evolution of network management, focusing on the context and key outcomes of the previous workshop, an assessment of the current state, and an acknowledgement of some regrets. {{SCHONWALDER}} emphasized the need to shift the focus from device-level configuration to network and service-level configuration. Key properties highlighted for effective network and service configurations included being Composable, Declarative, Reproducible, and Verifiable. An operator’s perspective highlighted that the recommendations of {{RFC3535}}, which led to the development of YANG and NETCONF, have been successful in addressing device configuration. In certain areas, the advancements in semantics and protocols for streaming telemetry have even surpassed the original scope. {{LARSSON}} stressed the need to prioritize service modeling, including operational state, to support closed-loop automation. Furthermore, the absence of open-source tools, NMS and device model implementations was recognized as a significant obstacle to advancing standardization efforts.

{{HARDAKER}} emphasized that the success of Net-SNMP {{NET-SNMP}} was driven by empowering users through simplicity. He stressed that the focus should remain on ensuring ease of use and adaptability of the protocols. Emphasis was placed on the two distinct audiences for standardized network management protocols: toolkit vendors and system operators. Their requirements for protocol simplicity differ, and it is essential to address the needs of both to ensure success. {{BORMANN}} presented an overview of the CORECONF architecture, showcasing how model-driven network management techniques can be applied to manage IoT devices, with a focus on the unique characteristics of constrained nodes. Some participants noted that the binary encoding of CBOR has applications that extend beyond IoT networks.

Drawing from the experience of OpenConfig {{OPENCONFIG}}, {{SHAKIR}} emphasized that protocol definition cannot be done in isolation. It must integrate lessons learned from implementation and large-scale deployment. He highlighted the importance of enabling quick iterations, shipping rapidly, embracing open-source culture, adopting systems thinking driven by business outcomes, and reusing existing technologies rather than developing solutions exclusively for network management.

## Session II: Present (identified problems & requirements)

## Session III: Future (possible solutions, recommendations and next steps)

## Key Takeaways

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

# Position Papers

20 position papers were submitted to the workshop call for papers. All papers are available at <https://datatracker.ietf.org/group/nemopsws/materials/>.

This is the list of all papers:

* J Schönwälder: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations {{SCHONWALDER}}
* K. Larsson, K. Lambrechts, and I. Farrer: RFC3535, 20 Years Later from an Operator’s Perspective (Deutsche Telekom) {{LARSSON}}
* W. Hardaker: Lessons Learned from 30 Years of Net-SNMP {{HARDAKER}}
* C. Bormann: CORECONF: Managing IoT Devices with YANG Models {{BORMANN}}
* R. Shakir: Rethinking Standardisation of Network Management {{SHAKIR}}

# Workshop Participants

The workshop participants were Alex Huang, Alexander Clemm, Alexander PELOV, Benoit Claise, Boris Khasanov, Brad Peters (nbn), Carsten Bormann, Chongfeng Xie, Cindy Morgan, Dan Voyer, Darren Loher, Dean Bogdanovic, Dean Bogdanović, Dhruv Dhody, Diego Lopez, Ebben Aries, Frank (Chong Feng), Holger Keller, Ian Farrer, Jaime Jimenez, James Cumming, Janne Karvonen, Jason Sterne, Jiaming Ye, Jinming Li, John Carson, Julien Maisonneuve, Jürgen Schönwälder, Kent Watsen, Kris Lambrechts, Kristian Larsson, Laurent Ciavaglia, Laurent Toutain, Liz Flynn, Luis M. Contreras (Telefonica), Mahesh Jethanandani, Manoj Gudi, Martin Horneffer, Matthew Bocci, Med Boucadair, Michael Mackey, Michael Richardson, Michael Scharf, Mikko Pesonen, Nacho Dominguez (Telefonica), Naveen Achyuta, Nick Corran, Nils Warnke, Oscar Gonzalez de Dios, Paolo Lucente, Parisa Foroughi, Per Andersson, Phil Shafer, Qin Wu, Qiufang Ma, Raquel Rodriguez, Reshad, Reshad Rahman, Rob Shakir, Rob Wilton, Roland Bless (KIT), Roland Schott, Rüdiger Geib, Rui Zhuang, Ruibo Han, Sabine Randriamasy, Scott Mansfield (Ericsson), Scott Robohn, Shengnan Yue, Suresh Krishnan, Thomas Graf, Toerless Eckert, Wangbo, Warren Kumari, Wes Hardaker, Wim Henderickx, Xue Yang, Y. Richard Yang, Yangbo, Yisong Liu, and Zhenqiang Li.

# Workshop Program Committee

The workshop program committee members were Wes Hardaker, Dhruv Dhody, Qin Wu, Suresh Krishnan, Benoît Claise, Mohamed Boucadair, Mahesh Jethanandani, Kent Watsen, and Warren Kumari.

# IAB Members at the Time of Approval
{:numbered="false"}

Internet Architecture Board members at the time this document was approved for publication were: TODO

# Acknowledgments
{:numbered="false"}

TBD

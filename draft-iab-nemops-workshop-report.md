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
SCHOENWAELDER:
  target: https://www.ietf.org/slides/slides-nemopsws-paper-composable-declarative-reproducible-verifiable-network-and-service-configurations-00.pdf
  title: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations
    author:
      -
        ins:  J Schoenwaelder
        name: Jurgen Schoenwaelder
    date: November 2024        
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

# Workshop Scope and Discussion

The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three main themes for each of the three discussion slots. During each discussion, those papers were presented sequentially with open discussion held at the end of each day.

## Session I: Past (lookback, analysis)

## Session II: Present (identified problems & requirements)

## Session III: Future (possible solutions, recommendations and next steps)

## Key Take Aways

--- back

# Position Papers

20 position papers were submitted to the workshop call for papers. All papers are available at: https://datatracker.ietf.org/group/nemopsws/materials/

This is the list of all papers:

* J Schönwälder: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations {{SCHOENWAELDER}}
* 

# Workshop Participants

The workshop participants were

# Workshop Program Committee

The workshop program committee members were Wes Hardaker, Dhruv Dhody, Qin Wu, Suresh Krishnan, Benoît Claise, Mohamed Boucadair, Mahesh Jethanandani, Kent Watsen, and Warren Kumari.

# IAB Members at the Time of Approval
{:numbered="false"}

Internet Architecture Board members at the time this document was approved for publication were: TODO

# Acknowledgments
{:numbered="false"}

TBD

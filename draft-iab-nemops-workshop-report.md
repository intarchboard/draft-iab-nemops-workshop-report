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
  SCHONWALDER:
    target: https://www.ietf.org/slides/slides-nemopsws-paper-composable-declarative-reproducible-verifiable-network-and-service-configurations-00.pdf
    title: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations
    author:
      -
        ins:  J. Schönwälder
        name: Jürgen Schönwälder
    date: November 2024

--- abstract

The "Next Era of Network Management Operations (NEMOPS)" workshop was convened by the Internet Architecture Board (IAB) on December 3-5, 2024 as a three-day online meeting. It builds on a previous 200[...]

Note that this document is a report on the proceedings of the workshop.  The views and positions documented in this report were expressed during the workshop by participants and do not necessarily ref[...]

--- middle

# Introduction

The IAB organized a workshop in June 2002 to establish a dialog between network operators and protocol developers, and to guide IETF when working on network management protocols. The outcome of that w[...]

Those requirements were instrumental in developing first the NETCONF protocol (in the NETCONF Working Group) [RFC6241], the associated YANG data modeling language (in the NETMOD Working Group) [RFC795[...]

The NEMOPS workshop aimed to discuss the following key topics:

* Review the outcomes and results of the 2002 workshop (current deployments, state of the art) and identify any operational barriers that prevent these technologies from being widely implemented (limi[...]
* Sketch new requirements for future network management operations in a collaborative manner with the industry, network operators, and protocol engineers.
* Develop a plan of action and recommendations for the IETF.

## About this workshop report content

The Internet Architecture Board (IAB) holds occasional workshops designed to consider long-term issues and strategies for the Internet, and to suggest future directions for the Internet architecture. [...]

This document is a report on the proceedings of the workshop. The views and positions documented in this report are expressed during the workshop by participants and do not necessarily reflect IAB's v[...]

Furthermore, the content of the report comes from presentations given by workshop participants and notes taken during the discussions, without interpretation or validation.  Thus, the content of this [...]

# Workshop Scope and Discussion

The workshop was organized across three days with all-group discussion slots, one per day. The following topic areas were identified and the program committee organized paper submissions into three ma[...]

## Session I: Past (lookback, analysis)

## Session II: Present (identified problems & requirements)

## Session III: Future (possible solutions, recommendations and next steps)

## Key Takeaways

At the end of the third day the discussion turned to key takeaways
that had consensus.  In the process of discussion there were some
realizations where additional work was also needed.

[XXX: note at this point these are cut and paste from the slides and
not properly edited/cleaned/moved around]

### Ecosystem conclusions

1. The current network management protocols/models/tools still fail the ‘ease of use’ requirement
    1. The tools may matter more than the protocols
1. The overall ecosystem is still fragmented for both protocols and data models
    1. SNMP (for monitoring) and CLI is still the rule in many networks (this is a potential obstacle)
    1. Transitions between frameworks is challenging (see IPv4 -> IPv6)
    1. Fragments: SNMP, CLI, NETCONF, RESTCONF, gNMI, etc…
    1. gNMI is popular for stream
1. Model-driven network management is generally a success
1. Documentation for how the network management ecosystem works is lacking
    1. Could use architecture documentation, deployment guides, tutorials, training, getting started
1. Easily usable network management tools for the operators are needed
    1. Lack of open source tools are a barrier to adoption
    1. We need more discussion about tooling success paths
    1. Tools need good use cases / example use cases and flows

### Protocol conclusions

1. False: Netconf for configuration has been successful in some larger scale deployment
    1. Let’s discuss this further on list
    1. Service config?
1. Netconf/YANG is not used much (yet?) for monitoring
1. False: Full device control and configuration frequently requires CLI and screen scraping
1. Full coverage of NetConf support on devices is missing
1. Polling based solutions are still frequently deployed

### Modeling conclusions

[XXX: note -- I don't think we talked about this slide much -Wes]

1. YANG models can sometimes get too complex (not a fault of the language)
1. Vendor-specific features need to be exposed through network management protocols
1. More service-level modeling is needed
    1. Device level modeling needs to be a building block but is not a complete service-level solution
1. Network configuration needs to be verifiable
1. Multi-vendor compatibility support is required.
1. Full coverage of YANG models on all devices is missing
1. Model translation adaptors may be the best path forward
    1. Likely off-device

### Standardization conclusions

1. More rapid model development procedures are (still) needed 
    1. Faster than how the IETF produces (simple) results today (especially models)
    1. New approaches/methods to make it live outside the RFCs should be explored
    1. Need more predictable timelines
1. More focus is needed on scalability of all network management roles (monitoring, configuration, notifications)
1. We should reduce complexity for future changes to a minimal agreed set of core features
    1. For both protocol and models
1. Network management enhancements needs to be backed by operator use cases and vendor buy-in
    1. Vendors and operators should must work together
1. An rapid development experiment would be an interesting approach


### Additional work needed

Here we list the things that the group realized needed significant
more attention in order to come to conclusion about.

...

--- back

# Position Papers

20 position papers were submitted to the workshop call for papers. All papers are available at: https://datatracker.ietf.org/group/nemopsws/materials/

This is the list of all papers:

* J Schönwälder: Composable, Declarative, Reproducible, Verifiable Network and Service Configurations {{SCHONWALDER}}

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

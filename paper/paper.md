---
title: 'BioHackEU26 report for Project 10: Enabling workflows and EDAM annotations to display in community website deployments'
title_short: 'BioHackEU26 #10: workflows and EDAM for ETT'
tags:
  - computational workflows
  - WorkflowHub
  - EDAM
  - ontology
  - ELIXIR Toolkit Theme
authors:
  - name: 
    affiliation: 
    role: 
  - name: 
    affiliation: 
    role: 
  - name: Ove Johan Ragnar Gustafsson
    orcid: 0000-0002-2977-5032
    affiliation: 1
    role: Conceptualization, writing – original draft
  - name: Danielle Welter
    orcid: 0000-0003-1058-2668
    affiliation: 2
    role: Data curation, Writing – review & editing
affiliations:
  - name: 
    index: 
  - name: 
    index: 
  - name: Australian BioCommons, University of Melbourne, Melbourne, Victoria, Australia
    index: 1
  - name: Luxembourg National Data Service, Esch-sur-Alzette, Luxembourg
    index: 2 
date: 11 November 2026
cito-bibliography: paper.bib
event: BH26EU
biohackathon_name: "BioHackathon Europe 2026"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Barcelona, Spain, 2026"
group: Project 10
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/supernord/biohackathon-2026-project-10
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


> **Note:** Please keep sections to a maximum of only two levels.


# Introduction

> Modified and extended project abstract from BioHackathon 2026:

The [ELIXIR Toolkit Theme (ETT)](https://elixir-belgium.github.io/elixir-toolkit-theme/) enables diverse research and infrastructure communities to easily deploy static websites using a GitHub repository. This is beneficial as it facilitates broad and open contributions and collaborations, provides version control and development flexibility, and streamlines the process of building and populating a website. The popularity of the lightweight and standardised ETT model is demonstrated by [numerous deployments](https://elixir-belgium.github.io/elixir-toolkit-theme/#this-theme-is-known-to-be-used-in), including [RDMkit](https://rdmkit.elixir-europe.org/) [@citesAsAuthority:Alper_RDMkit_A_Research_2025], [RSQkit](https://everse.software/RSQKit/) [@citesAsAuthority:rsqkit_community_2025_14923573], and [WorkflowHub documentation](https://about.workflowhub.eu/) [@citesAsAuthority:gustafsson2025workflowhub].

Crucially, these websites often centralise the sharing of digital resources that can be reused by specific communities. For example, the [Australian Structural Biology Computing (ASBC) Community](https://australian-structural-biology-computing.github.io/index) maintains an ETT website as a shared space: the intention is for the community to be able to find activities, resources, news, and events, as well as how to join the community conversation [@citesAsAuthority:michie2025roadmap]. In this context, *resources* refers to any digital object that supports the requirements of the community, including, but not limited to, software tools and workflows. 

Including these resources in an ETT website currently requires manual curation, which is time consuming for ETT website maintainers and does not directly support making the software and workflows findable, accessible, interoperable, and reusable (FAIR) [@citesAsAuthority:barker2022introducing,wilkinson2025applying]. The ideal approach would be to use the existing FAIR infrastructure ecosystem to register software and workflows, enable the ETT to interoperate with this ecosystem, and then automatically populate a website with the relevant software or workflows. This approach leverages the registries to both curate and make resources FAIR, shares the curation burden across the contributing communities, and provides the opportunity to simultaneously add ontology annotations from registry entries to ETT websites.

The ETT already offers the possibility of annotating pages with identifiers from registries like [FAIRsharing](https://fairsharing.org/) [@citesAsAuthority:sansone2019fairsharing] and [bio.tools](https://bio.tools/) [@citesAsAuthority:mendes2026bio]. However, support for workflows and ontologies is not implemented. This project thus worked to extend the ETT and enable creation of interactive tables to present workflows, and automation of workflow metadata import from WorkflowHub, as well as extension of the ETT integration with bio.tools to support EDAM ontology annotations at both the workflow table and ETT webpage (i.e. schema.org) level.

Ultimately, developers from any community can continue using bio.tools and WorkflowHub to make their software FAIR, and community coordinators can independently and automatically import and embed these in an ETT deployment, benefitting from both the registry entry and its rich EDAM concept annotations. When implemented for the ETT, these features will increase the findability of the website pages and enable better integration across multiple community instances of the ETT.


# Results

## Project goals

The BioHackathon project had the following goals:

1. Enable interactive workflow tables for the ETT, by implementing a proof of concept integration between a community website and the WorkflowHub API.
2. Enable support for annotation with ontology terms on ETT, including import of ontology annotations from bio.tools based on existing annotations of pages.
3. Create working examples, including documentation, that can be included on the [ETT test deployment page](https://elixir-belgium.github.io/elixir-toolkit-theme/all_trainings). 



## WorkflowHub import

Idea for table include https://australianbiocommons.github.io/workflowfinder/

Source collection on WorkflowHub: https://workflowhub.eu/collections/40 


## EDAM annotations


# Discussion



## Acknowledgements

The authors acknowledge all the organisers and participants at the ELIXIR BioHackathon Europe 2026 in Barcelona, Spain, for helping make this project a success.

This work is supported by Australian BioCommons, which is enabled by NCRIS via Bioplatforms Australia funding.

# References

```{=latex}
\AtEndDocument{%
```

# Appendices

If you want the Appendix (-ces) to show up after the references, wrap them in 
after the header, like done in this Markdown file. Look at the [source](paper.md)
to see the exact structure.

```{=latex}
}
```

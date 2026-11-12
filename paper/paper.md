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
  - name: 
    affiliation: 
    role: 
affiliations:
  - name: 
    index: 
  - name: 
    index: 
  - name: Australian BioCommons, University of Melbourne, Melbourne, Victoria, Australia
    index: 1
  - name: 
    index:  
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

Whilst ETT already offers the possibility of annotating pages with identifiers from FAIRsharing and bio.tools [@citesAsAuthority:mendes2026bio], support for workflows and ontologies is not implemented. This project will extend the ETT to enable 1) automation of workflow imports from WorkflowHub, 2) creation of interactive tables to present the communities workflows, and 3) automated addition of EDAM ontology annotations at both the workflow table and webpage (i.e. schema.org) level. The latter will build on the existing integration with bio.tools, offer the possibility of manual curation, and increase the findability of these webpages. Moreover, ontology terms (e.g. EDAM) are already used to annotate the bio.tools elements already included on many ETT instances, including RDMkit.

Workflow developers from any community can thus continue using WorkflowHub to make their workflows FAIR, and community coordinators can independently and automatically import these to an ETT deployment along with EDAM annotations. This support would be beneficial for increasing the findability of the pages and enabling better integration across multiple instances of ETT.


# Results

## Project goals

1. Translate a proof of concept integration with the WorkflowHub API to the ELIXIR Toolkit Theme, including GitHub actions, configs, htmls, and css.
2. Enable support for annotation with ontology terms on ETT, including import of ontology annotations from bio.tools based on existing annotations of pages.
3. Create working examples, including documentation, that can be included on the ETT test deployment page: e.g. https://elixir-belgium.github.io/elixir-toolkit-theme/all_trainings 


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

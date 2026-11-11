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


**Note:** Please keep sections to a maximum of only two levels.


# Introduction

Project abstract from BioHackathon:

The ELIXIR Toolkit Theme (ETT, <https://elixir-belgium.github.io/elixir-toolkit-theme/>) enables communities to deploy websites via GitHub, facilitating broad contributions and collaborations, and streamlining the process of building and populating the site. The popularity of the ETT is demonstrated by numerous deployments, including RDMkit, RSQkit, and WorkflowHub [@citesAsAuthority:gustafsson2025workflowhub] documentation. These deployments can also centralise sharing of digital resources such as workflows intended for reuse by communities. This use case requires a streamlined way to find, view, and understand workflows, in the context of an ETT deployed website.

Whilst ETT already offers the possibility of annotating pages with identifiers from FAIRsharing and bio.tools [@citesAsAuthority:mendes2026bio], support for workflows and ontologies is not implemented. This project will extend the ETT to enable 1) automation of workflow imports from WorkflowHub, 2) creation of interactive tables to present the communities workflows, and 3) automated addition of EDAM ontology annotations at both the workflow table and webpage (i.e. schema.org) level. The latter will build on the existing integration with bio.tools, offer the possibility of manual curation, and increase the findability of these webpages. Moreover, ontology terms (e.g. EDAM) are already used to annotate the bio.tools elements already included on many ETT instances, including RDMkit.

Workflow developers from any community can thus continue using WorkflowHub to make their workflows FAIR, and community coordinators can independently and automatically import these to an ETT deployment along with EDAM annotations. This support would be beneficial for increasing the findability of the pages and enabling better integration across multiple instances of ETT.


# Results

## Project goals

1. Translate a proof of concept integration with the WorkflowHub API to the ELIXIR Toolkit Theme, including GitHub actions, configs, htmls, and css.
2. Enable support for annotation with ontology terms on ETT, including import of ontology annotations from bio.tools based on existing annotations of pages.
3. Create working examples, including documentation, that can be included on the ETT test deployment page: e.g. https://elixir-belgium.github.io/elixir-toolkit-theme/all_trainings 


## WorkflowHub import

Use case driver
https://australian-structural-biology-computing.github.io/index

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

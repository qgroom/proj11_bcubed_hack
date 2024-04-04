---
title: 'A GUI for general biodiversity indicators'
tags:
  - Shiny
  - biodiversity indicators
authors:
  - name: Shawn Dove
    orcid: 0000-0001-9465-5638
    affiliation: 1
  - name: Emily L. Pascoe
    orcid: 0000-0003-3493-3485
    affiliation: 2
  - name: Mathias Dillen
    orcid: 0000-0002-3973-1252
    affiliation: 3
  - name: Quentin Groom
    orcid: 0000-0002-0596-5376
    affiliation: 3  
  - name: Melanie De Nolf
    orcid: 0000-0001-6032-5198
    affiliation: 3  
  - name: Arman Pili
    orcid: 0000-0002-3952-9732
    affiliation: 4
  - name: Yanina Sica
    orcid: 0000-0002-1720-0127
    affiliation: 1
  - name: Fabio L. Matos
    orcid: 0000-0002-5447-4055
    affiliation: 5    

affiliations:
 - name: Justus Liebig University Giessen, Giessen, Germany
   index: 1
 - name: Conservation Genomics Research Unit, Research and Innovation Centre, Fondazione Edmund Mach, Trento, Italy
   index: 2
 - name: Meise Botanic Garden, Nieuwelaan 38, 1860 Meise, Belgium
   index: 3
 - name: Macrocology, Institute of Biochemistry and Biology, University of Potsdam, 14469 Potsdam, Germany
   index: 4
 - name: Centro de Estudos do Ambiente e do Mar (CESAM) & Departamento de Biologia, Universidade de Aveiro, Campus Universitário de Santiago, Aveiro, Portugal
   index: 5
date: 04. April 2024
bibliography: paper.bib
authors_short: Dove et al.
group: Project 11
event: Hacking Biodiversity Data Cubes for Policy, Brussels, Belgium, 2024
biohackathon_name: Hacking Biodiversity Data Cubes for Policy
biohackathon_url: https://b-cubed.eu/b-cubed-hackathon
biohackathon_location: Brussels, Belgium
---


# A GUI for general biodiversity indicators

BioHackathon series: B-Cubed Hackathon: Hacking Biodiversity Data Cubes For Policy. Brussels, Belgium, 2 – 5 April 2024

## Background
We are currently in a global biodiversity crisis [@singh2002biodiversity], and in order to guide and unify protection and conservation efforts we need clear policies at the local, national, and international levels. Biodiversity indicators provide essential information for policy-makers, which usually require knowledge of data management and analyses (e.g., coding) to calculate. Consequently there is a disconnect between the research scientists producing the biodiversity indicators, and the end-users, meaning many users must rely on ready-made or commissioned analyses. Within the EU-project B-Cubed, we aim to provide flexible workflows to align with policy objectives. But to be truly user-friendly, these should be provided in a graphical, interactive format that does not require the user to understand coding. The goal of this hackathon project was to develop a front end for a general biodiversity indicators package in the form of a Shiny app.

## Hackathon results
We created a GUI to visualise biodiversity indices calculated from data cubes. The GUI is a Shiny app composed of a side panel which is used to read a data cube (we use a data cube created in GBIF), and tabs for visualising metadata and biodiversity indices. The b3gbi R package is used to calculate and visualise biodiversity indices. 

Mention that finding a collaborative environment (e.g., Posit cloud) was almost impossible!!

## Conclusion
During the hackathon we were unable to find a free online tool which enabled the team to simultaneously edit an R script.

## Future work
## GitHub repositories created
## Acknowledgements

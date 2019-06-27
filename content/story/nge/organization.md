+++
title = "Organization"
date =  2018-03-19T14:23:00-07:00
weight = 5
+++

{{<mermaid align="left">}}
graph TD;
    E[Empress] -->|Grand Chancellor| IS[Imperial Senate]
    E -->|Grand Vizier| IC[Imperial Council]
    E -->|Chairman| IB[Imperial Bank]
    E -->|Grand Master| KI[Knights Imperial]
    E -->|Grand Inquisitor| III[Imperial Inquisition]
    III --> SC[Imperial Court]
    III -->|Inquisitors| KI
    E -->|Supreme Justice| SC
    IC -->|Grand Moffs| RG[Regional Government]
    RG -->|Moffs| SG[Sector Government]
    SG -->|Governors| PG[Planetary Governments]
    IC --> IB
    IC --> S[Imperial Security]
    E -->|Supreme Commander| IM[Imperial Military]
    IM -->|Grand Generals| Army
    IM -->|Grand Admirals| Navy
    IM -->|Director| II[Imperial Intelligence]



{{< /mermaid >}}


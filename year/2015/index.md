---
layout: main-2015
title: The 1st Workshop on Data Systems for Interactive Analysis
---

This is the website for the First Workshop on Data Systems for
Interactive Analysis, to be held in conjunction with
[IEEE VIS 2015](http://ieeevis.org/year/2015/info/vis-welcome/welcome)
in Chicago, October 26th, at the Palmer House Hilton in Chicago.

<div style="padding-top:20px"></div>

The goal of this workshop is to foster innovative research at the
**intersection of databases, machine learning, and interactive
visualization**.

Database researchers have developed techniques for storing and
querying massive amounts of data, including methods for distributed,
streaming and approximate computation. Machine learning techniques
provide ways to discover unexpected patterns and to automate and scale
well-defined analysis procedures. Recent systems research has looked
at how to develop novel database systems architectures to support the
iterative, optimization-oriented workloads of machine learning
algorithms.

Of course, both the inputs and outputs of these systems are ultimately
driven by people, in support of analysis tasks. The life-cycle of data
involves an iterative, interactive process of determining which
questions to ask, the data to analyze, appropriate features and
models, and interpreting results. In order to achieve better analysis
outcomes, data processing systems require improved interfaces that
account for the strengths and limitations of human perception and
cognition. Meanwhile, to keep up with the rising tide of data,
interactive visualization tools need to integrate more techniques from
databases and machine learning.

**In this workshop, we will explore the idea that the next generation of
database, machine learning, and interactive visualization systems
should not be designed in isolation**. For example, machine learning
techniques might recommend improved data transformation and visual
encoding decisions. Or, database query optimizers might take advantage
of perceptual constraints, while prefetching methods reduce latency by
modeling likely interactions.

This workshop seeks to jump start cross-pollination between these
fields. The program will be split between invited talks from
researchers in these communities, and speculative, ongoing work that
straddles the areas. 

## Program

* 2:00-2:40: Keynote, Joe Hellerstein, UC Berkeley and Trifacta
* 2:40-3:40: Papers session 1
  * Manasi Vartak, Silu Huang, Tarique Siddiqui, Samuel Madden, Aditya
    Parameswaran. **Towards Visualization Recommendation Systems**
  * Dominik Moritz, Jeffrey Heer, and Bill Howe. [Dynamic Client-Server
    Optimization for Scalable Interactive Visualization on the Web](papers/2015/moritz.pdf) ([bibtex](bib/moritz2015dynamic.bib))
  * Jean-Daniel Fekete. [ProgressiVis: a Toolkit for Steerable
    Progressive Analytics and Visualization](papers/2015/fekete.pdf) ([bibtex](bib/fekete2015progressivis.bib))
  * Leilani Battle, Mike Stonebraker, Remco Chang. **Front-End Aware
    Optimizations for Scalable Visual Exploration Systems**
  * Eugene Wu and Arnab Nandi. [Towards Perception-aware Interactive Data
    Visualization Systems](papers/2015/wu.pdf) ([bibtex](bib/wu2015towards.bib))
  * Alper Sarikaya and Michael Gleicher. [Using WebGL as an Interactive Visualization Medium: Our Experience Developing SplatterJs](papers/2015/sarikaya.pdf) ([bibtex](bib/sarikaya2015webgl.bib))
* 4:15-4:55: Papers session 2
  * Cicero Pahins, Joao Comba. **HashedCubes: A Data Structure for
    Real-Time Exploration of Large Multidimensional Datasets**
  * Fabio Miranda, Lauro Lins, James T. Klosowski, and Claudio
    Silva. **TopKube: A Rank-Aware Data Cube for Real-Time Exploration of
    Spatiotemporal Datasets**
  * Paul Rosen, Alan Morris, Gene Payne, Bill Keach, Ian Harvey, Bryony
    Richards-McClung, John McLennan, Randy Polson, Raymond Levey, Terry
    Ring, Elizabeth Jurrus, and Greg M. Jones. [Klareco: An
    Indexing-based Architecture for Interactive Visualization of
    Heterogeneous Data Sources](papers/2015/rosen.pdf) ([bibtex](bib/rosen2015klareco.bib))
  * Adam Dziedzic, Jennie Duggan, Aaron J. Elmore, Vijay Gadepally, and
    Michael Stonebraker. [BigDAWG: a Polystore for Diverse Interactive
    Applications](papers/2015/dziedzic.pdf) ([bibtex](bib/dziedzic2015bigdawg.bib))
* 4:55-5:50: Discussion
* 5:50-6:00: Closing

## Invited Speaker: Joe Hellerstein

We are very excited to announce that
[Joe Hellerstein](http://db.cs.berkeley.edu/jmh/) from UC Berkeley
will be the keynote speaker for the workshop. 

### Talk: People, data, computation: an evolving trifecta

When working on human interaction with data, a recurring theme is the
need to simultaneously address issues in HCI, database systems, and
statistical methods. Ironically, these complexities are rooted in the
goal of providing increased simplicity and power for users. I’ll
reflect briefly on my own experience with these issues in topics like
online aggregation and data wrangling, and consider the nature of this
complexity as we negotiate the evolving dialog between people, data
and computation.

Joseph M. Hellerstein is the Jim Gray Professor of Computer Science at the University of California, Berkeley, whose work focuses on data-centric systems and the way they drive computing. He is an
[ACM Fellow](http://awards.acm.org/award_winners/hellerstein_4354833.cfm),
an
[Alfred P. Sloan Research Fellow](http://www.sloan.org/sloan-research-fellowships/)
and the recipient of three
[ACM-SIGMOD "Test of Time" awards](http://www.sigmod.org/sigmod-awards/sigmod-awards#time)
for his research. In 2010, Fortune Magazine included him in their list
of 50 smartest people in technology, and MIT's Technology Review
magazine included his work on their
[TR10 list of the 10 technologies "most likely to change our world"](http://www2.technologyreview.com/article/418545/tr10-cloud-programming/). Hellerstein
is the co-founder and Chief Strategy Officer of
[Trifacta](http://www.trifacta.com), a software vendor providing
intelligent interactive solutions to the messy problem of wrangling
data. He serves on the technical advisory boards of a number of
computing and Internet companies including [EMC](http://www.emc.com),
[SurveyMonkey](http://www.surveymonkey.com),
[Captricity](http://www.captricity.com), and
[Dato](http://www.dato.com), and previously served as the Director of
Intel Research, Berkeley.

<!-- ## Accepted papers

* Leilani Battle, Mike Stonebraker, Remco Chang. **Front-End Aware
  Optimizations for Scalable Visual Exploration Systems**
* Adam Dziedzic, Jennie Duggan, Aaron J. Elmore, Vijay Gadepally, and
  Michael Stonebraker. **BigDAWG: a Polystore for Diverse Interactive
  Applications**
* Jean-Daniel Fekete. [ProgressiVis: a Toolkit for Steerable
  Progressive Analytics and Visualization](papers/2015/fekete.pdf)
* Fabio Miranda, Lauro Lins, James T. Klosowski, and Claudio
  Silva. **TopKube: A Rank-Aware Data Cube for Real-Time Exploration of
  Spatiotemporal Datasets**
* Dominik Moritz, Jeffrey Heer, and Bill Howe. **Dynamic Client-Server
  Optimization for Scalable Interactive Visualization on the Web**
* Cicero Pahins, Joao Comba. **HashedCubes: A Data Structure for
  Real-Time Exploration of Large Multidimensional Datasets**
* Paul Rosen, Alan Morris, Gene Payne, Bill Keach, Ian Harvey, Bryony
  Richards-McClung, John McLennan, Randy Polson, Raymond Levey, Terry
  Ring, Elizabeth Jurrus, and Greg M. Jones. [Klareco: An
  Indexing-based Architecture for Interactive Visualization of
  Heterogeneous Data Sources](papers/2015/rosen.pdf)
* Alper Sarikaya and Michael Gleicher. [Using WebGL as an Interactive Visualization Medium: Our Experience Developing SplatterJs](papers/2015/sarikaya.pdf)
* Manasi Vartak, Silu Huang, Tarique Siddiqui, Samuel Madden, Aditya
  Parameswaran. **Towards Visualization Recommendation Systems**
* Eugene Wu and Arnab Nandi. **Towards Perception-aware Interactive Data
  Visualization Systems**

(More links to PDFs will be added as we receive final submissions from
authors.)-->

## Topics

This workshop will focus on interactive systems: techniques,
methods, architecture, systems that enable the user to interactively
explore and analyze large amounts of data in the back end with
little or no latency. We encourage late-breaking work,
research in progress, and position papers in interactive analysis,
broadly construed. For example, topics of interest to the workshop include (but are not limited to):

* design of database architectures for interactive analysis
* novel database applications for interactive analysis
* novel database techniques based on perceptual constraints and
  human-centered design
* evaluation of database systems for interactive analysis
* identify unique characteristics of databases for supporting visualization
* communication protocols between front and back ends
* techniques for data storage, retrieval, compression, transformation,
  sampling, and streaming
* techniques for metadata generation
* front-end architectures that exploit these novel back-end capabilities

We are interested, more generally, in the questions that arise at the
*intersection* of these systems. 

## Important Dates (Updated!)

* Submission Deadline: ~~2015-07-31~~ 2015-08-17
* Notifications: ~~2015-08-15~~ 2015-08-31
* Final versions due: ~~2015-08-30~~ 2015-09-15
* Event: 2015-10-26, Monday, 2-6PM

## Paper format and submission

Submissions should follow IEEE TVCG guidelines, which can be found
[here](http://junctionpublishing.org/vgtc/Tasks/camera_tvcg.html). 
Submissions should not exceed five total pages, the last page of which
should contain only references.

## Submission

Papers should be submitted via email to:
[workshop@interactive-analysis.org](mailto:workshop@interactive-analysis.org). Please contact the workshop
organizers at [organizers@interactive-analysis.org](mailto:organizers@interactive-analysis.org) for any
questions regarding the submission process or the workshop itself.

## Registration 

At least one author from an accepted paper will be required to attend the workshop. Registration for the workshop can be done via [VIS 2015](http://ieeevis.org/year/2015/info/vis-welcome/welcome).

## Organizers

* [Remco Chang](http://www.cs.tufts.edu/~remco/), Chair, Tufts Univiersity.
* [Carlos Scheidegger](http://cscheid.net), Chair, University of Arizona.
* [Danyel Fisher](http://research.microsoft.com/en-us/people/danyelf/), Chair, Microsoft Research.
* [Jeffrey Heer](http://jheer.org), Chair, University of Washington.
* [Leilani Battle](http://people.csail.mit.edu/leilani/), student organizer, MIT.
* [Nivan Ferreira](http://www.cs.arizona.edu/~nivanferreira/), senior organizer, University of Arizona.

---
layout: main-2017
title: "The 2nd Workshop on Data Systems for Interactive Analysis"
---

This is the website for the Workshop on Data Systems for
Interactive Analysis (DSIA). The [first edition of DSIA](/year/2015/) was held at
[IEEE VIS 2015](http://ieeevis.org/year/2015/info/vis-welcome/welcome). 
We are thrilled to announce a second edition of the workshop, to be
held at [IEEE VIS 2017](http://ieeevis.org).

# 2017 Program

* 8:30-8:35 Opening Statement
* 8:35-9:25 [Keynote](#keynote): Interactive Data Science, Tim Kraska, Brown University
* 9:25-10:10 Papers Session 1  
  * **[A Progressive K-D Tree for Approximate K-Nearest Neighbors]({{ site.baseurl }}/papers/2017/Jo-ProgressiveKD-2017.pdf)**  
    Jaemin Jo, Jinwook Seo, Jean-Daniel Fekete
    ([bibtex]({{ site.baseurl }}/bib/2017/Jo-ProgressiveKD-2017.bib))
  * **Load-n-Go: Fast Approximate Join Visualizations That Improve Over Time**  
    Marianne Procopio, Carlos Scheidegger, Eugene Wu, Remco Chang
    ([bibtex]({{ site.baseurl }}/bib/2017/Procopio-LoadnGo-2017.bib))
  * **[Track Xplorer: A System for Visual Analysis of Sensor-based Motor Activity Predictions]({{ site.baseurl }}/papers/2017/Cavallo-Xplorer-2017.pdf)**  
    Marco Cavallo, Çağatay Demiralp
    ([bibtex]({{ site.baseurl }}/bib/2017/Cavallo-Xplorer-2017.bib); [supplement]({{ site.baseurl }}/papers/2017/Cavallo-Xplorer-2017-supplement.pdf))
* 10:10-10:30 Break
* 10:30-12:00 Papers Session 2  
  * **Foresight:Rapid Data Exploration Through Guideposts**  
    Çağatay Demiralp, Peter Haas, Srinivasan Parthasarathy, Tejaswini Pedapati
    ([bibtex]({{ site.baseurl }}/bib/2017/Cagatay-Foresight-2017.bib))
  * **[High-Dimensional Scientific Data Exploration via Cinema]({{ site.baseurl }}/papers/2017/Woodring-Cinema-2017.pdf)**  
    Jonathan Woodring, James Ahrens, John Patchett, Cameron Tauxe, David Rogers
    ([bibtex]({{ site.baseurl }}/bib/2017/Woodring-Cinema-2017.bib))
  * **[Coupling Visualization, Simulation, and Deep Learning for Ensemble Steering of Complex Energy Models]({{ site.baseurl }}/papers/2017/Bush-EnsembleSteering-2017.pdf)**  
    Brian Bush, Nicholas Brunhart-Lupo, Bruce Bugbee, Venkat Krishnan, Kristin Potter, Kenny Gruchalla
    ([bibtex]({{ site.baseurl }}/bib/2017/Bush-EnsembleSteering-2017.bib))
  * **[A Client-based Visual Analytics Framework for Large Spatiotemporal Data under Architectural Constraints]({{ site.baseurl }}/papers/2017/Wang-Spatiotemporal-2017.pdf)**  
    Guizhen Wang, Abish Malik, Chittayong Surakitbanharn, Jose lorencio de Queiroz Neto, Shehzad Afzal, Siqiao Chen, David Wiszowaty, David Ebert
    ([bibtex]({{ site.baseurl }}/bib/2017/Wang-Spatiotemporal-2017.bib))
  * **[Position Statement: The Case for a Visualization Performance Benchmark]({{ site.baseurl }}/papers/2017/Battle-Benchmark-2017.pdf)**  
    Leilani Battle, Remco Chang, Jeffrey Heer, Michael Stonebraker
    ([bibtex]({{ site.baseurl }}/bib/2017/Battle-Benchmark-2017.bib))
  * **A Game-theoretic Approach to Data Interaction**  
    Ben McCamish, Arash Termehchy, Behrouz Touri
    ([bibtex]({{ site.baseurl }}/bib/2017/McCamish-GameTheoretic-2017.bib))
* 12:00-12:10 Closing Statement

{:#keynote}
### Keynote

<img src="/img/kraska-2017.jpg" style="float: right; padding:10px">
**Interactive Data Science**  
Tim Kraska  
Brown University

Unleashing the full potential of Big Data requires a paradigm shift in the algorithms and tools used to analyze data towards more interactive systems with highly collaborative and visual interfaces. Ideally, a data scientist and a domain expert should be able to make discoveries together by directly manipulating, analyzing and visualizing data on the spot, instead of having week-long forth-and-back interactions between them. Current systems, such as traditional databases or more recent analytical frameworks like Hadoop or Spark, are ill-suited for this purpose. They were not designed to be interactive nor to support the special requirements of visual data exploration. Similarly, most machine learning algorithms are not able to provide initial answers at "human speed" (i.e., sub-seconds), nor are existing methods sufficient to convey the impact of the various risk factors, such as multi hypothesis problem. 
 
In this talk, I will present our vision of a new approach for conducting interactive exploratory analytics and explain why integrating the aforementioned features requires a complete rethinking of the full analytics stack, from the interface to the "guts". I will present recent results towards this vision including our novel interface, analytical engine and automatic error detection, and outline what challenges are still ahead of us.

Bio: Tim Kraska is an Assistant Professor in the Computer Science department at Brown University. Currently, his research focuses building systems for interactive data exploration and transactional systems for modern hardware, especially the next generation of networks. Before joining Brown, Tim spent 3 years as a PostDoc in the AMPLab at UC Berkeley, where he worked on hybrid human-machine database systems and cloud-scale data management systems. Tim received his PhD from the ETH Zurich under the supervision of Donald Kossmann. He was awarded a NSF Career Award (2015), an Airforce Young Investigator award (2015), a Swiss National Science Foundation Prospective Researcher Fellowship (2010), a DAAD Scholarship (2006), a University of Sydney Master of Information Technology Scholarship for outstanding achievement (2005), the University of Sydney Siemens Prize (2005), two VLDB best demo awards (2015 and 2011), and an ICDE best paper award (2013), and recently got selected as a 2017 Alfred P. Sloan Research Fellow in Computer Science.  
<div style="clear:both"></div>

## The DSIA Vision

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

The goal of DSIA is to foster innovative research at the
**intersection of databases, machine learning, and interactive
visualization**.

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

## Important Dates

* Submission Deadline: July 31st, 2017
* Notifications: August 15th, 2017
* Final versions due: August 25th, 2017
* Event: October 2nd, 2017

## Paper format and submission

Submissions should follow IEEE TVCG guidelines, which can be found
[here](http://junctionpublishing.org/vgtc/Tasks/camera_tvcg.html). 
Submissions should not exceed five total pages, the last page of which
should contain only references.

## Submission

Papers should be submitted through the
[Precision Conference System](http://precisionconference.com/~vgtc)
(under "New Submissions" and "VIS Workshops 2017").
<!-- Please contact the workshop organizers at [organizers@interactive-analysis.org](mailto:organizers@interactive-analysis.org) for any questions regarding the submission process or the workshop itself. -->

## Registration 

At least one author from an accepted paper will be required to attend the workshop. Registration for the workshop can be done via [VIS 2017](http://ieeevis.org/).

## Organizers

* [Remco Chang](http://www.cs.tufts.edu/~remco/), Chair, Tufts Univiersity.
* [Carlos Scheidegger](http://cscheid.net), Chair, University of Arizona.
* [Danyel Fisher](http://research.microsoft.com/en-us/people/danyelf/), Chair, Microsoft Research.
* [Jeffrey Heer](http://jheer.org), Chair, University of Washington.

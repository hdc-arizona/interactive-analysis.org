---
layout: main-2018
title: "3rd Workshop on Data Systems for Interactive Analysis"
---

This is the website for the Workshop on Data Systems for
Interactive Analysis (DSIA). The [first edition of DSIA](/year/2015/) was held at
[IEEE VIS 2015](http://ieeevis.org/year/2015/info/vis-welcome/welcome) and the [second edition of DSIA](/year/2017/) was held at
[IEEE VIS 2017](http://ieeevis.org/year/2017/welcome).
We are thrilled to announce a third edition of the workshop, to be
held at [IEEE VIS 2018](http://ieeevis.org/year/2018/welcome) in Berlin.

# Outcomes

We had a fantastic workshop with over 90 attendees. You can find the overview slides and 13! pages of notes at [http://bit.ly/2R19Nov](http://bit.ly/2R19Nov). Slides for the talks are linked in the program below.

# 2018 Program

* 2:20-2:25: Opening Statement
* 2:25-3:05: [Keynote](#keynote): Azza Abouzied [Slides](/talks/2018/keynote-dsia-2018.pdf)
* 3:05-3:25: Papers session (10min per talk)
  * Rita Sevastjanova, Mennatallah El-Assady, Dr. Annette Hautli-Janisz, Aikaterini-Lida Kalouli, Rebecca Kehlbeck, Oliver Deussen, Daniel Keim, Miriam Butt<br/>*Mixed-Initiative Active Learning for Generating Linguistic Insights in Question Classification*
  * Protiva Rahman, Jian Chen, Courtney Hebert, Preeti Pancholi, Mark Lustberg, Kurt Stevenson, Arnab Nandi.<br/>*Exploratory Visualizations of Rules for Validation of Expert Decisions* [Slides](/talks/2018/rules-dsia-2018.pdf)
* 3:25-4:00: Invited Talks (15 minutes per talk)
  * Remco Chang, Carlos Scheidegger<br/>*Connecting Visualization and Data Management Research* [Slides](https://cscheid.net/talks/dsia-2018-dagstuhl-report.pdf)
  * Jean-Daniel Fekete, Michael Sedlmair:<br/>*Trip Report: Dagstuhl Seminar on Progressive Analytics* [Slides](/talks/2018/progressive-dsia-2018.pdf)
* 4:00-4:20: Break
* 4:20-4:45: Invited Talks (10 to 15 minutes per talk)
  * Leilani Battle:<br/>*Evaluating Visual Data Analysis Systems: A Discussion Report*
  * Sebastian Breß, Volker Markl:<br/>*Toward Holistic Optimization of Data-Intensive Visualisation Pipelines* [Slides](/talks/2018/algebra-dsia-2018.pdf)
* 4:45-5:20: Focus groups
  1. Algebra for Visualization
  2. Benchmarking Visual Analysis Systems
  3. Perceptual Challenges
  4. Query Engines and Progressive Visualization
  5. *Audience choice topic*
* 5:20-5:50: Reports from Groups
* 5:50-6:00: Closing Statement
* 6:30: Dinner at [Café-Restaurant Louis](https://maps.google.com/?cid=9651088274628932097). We will walk together from the workshop.

<iframe id="datawrapper-chart-FEtKX" src="//datawrapper.dwcdn.net/FEtKX/1/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="481"></iframe><script type="text/javascript">if("undefined"==typeof window.datawrapper)window.datawrapper={};window.datawrapper["FEtKX"]={},window.datawrapper["FEtKX"].embedDeltas={"100":506,"200":481,"300":481,"400":481,"500":481,"700":481,"800":481,"900":481,"1000":481},window.datawrapper["FEtKX"].iframe=document.getElementById("datawrapper-chart-FEtKX"),window.datawrapper["FEtKX"].iframe.style.height=window.datawrapper["FEtKX"].embedDeltas[Math.min(1e3,Math.max(100*Math.floor(window.datawrapper["FEtKX"].iframe.offsetWidth/100),100))]+"px",window.addEventListener("message",function(a){if("undefined"!=typeof a.data["datawrapper-height"])for(var b in a.data["datawrapper-height"])if("FEtKX"==b)window.datawrapper["FEtKX"].iframe.style.height=a.data["datawrapper-height"][b]+"px"});</script>

{:#keynote}
## Keynote: Azza Abouzied

<img src="/img/azza.jpg" style="float: right; padding:10px">

We are very excited to announce that [Azza Abouzied](http://azza.azurewebsites.net/) from NYU Abu Dhabi will be the keynote speaker for the workshop.

**Abstract:** The research and development of data analytics tools has often occurred independently in two worlds: the data management world and the HCI one. The database community is partly to blame for this phenomenon. The core database design principle of providing minimilastic APIs such as SQL that abstract away storage and processing details was perhaps taken too far. With little intervention allowed into the mechanics of handling or querying data, human interfaces for data tasks were in turn developed independently. These interfaces focused on how best to support users, usually within a specific domain, under the constraints of the underlying data management system. As data analysis becomes more mainstream, this clear division is starting to blur. For example, recent visualization and database research works are starting to examine ways that both worlds can better integrate to improve performance as well as the handling of uncertain data. It is time to push this integration even further and to design complete end-to-end systems.

In this keynote, I examine this integration through the lens of example-driven interfaces (EDIs) for data tasks — a class of mixed-initiative user interfaces that enable users to specify tasks such as data extraction, cleaning, transformation, querying or analysis, in the casual and familiar language of examples. Through tools that we have built and evaluated for data extraction (SEER and Texture), querying (DataPlay and Qetch), and generation (Synner), I demonstrate that designing end-to-end systems not only leads to exciting opportunities in HCI research but also leads us to question and change some fundamental principles of data management systems.

**Bio:** Azza Abouzied is an Assistant Professor of Computer Science at New York University, Abu Dhabi. Azza’s research work focuses on designing novel and intuitive data analytics tools and on supporting complex analytics natively within databases, such as specifying and solving objective optimization problems. Her work combines techniques from various fields such as UI-design, active learning and databases. She received her doctoral degree from Yale in 2013 and BSc (CS) from Dalhousie. She spent a year as a visiting scholar at UC Berkeley. She is the recipient of an NSERC Canada Graduate Scholarships-Doctoral Fellowship, and multiple research paper awards including a SIGMOD Research Highlight Award, a best of VLDB citation and a best CHI paper award. She is also one of the co-founders of Hadapt – a Big Data analytics platform.

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

* Submission Deadline: ~~July 17, 2018~~ July 24, 2018
* Notifications: ~~August 7, 2018~~ August 14, 2018
* Final versions due: ~~August 17, 2018~~ August 20, 2018
* Event: Afternoon of October 21, 2018

## Paper Format and Submission

Submissions should follow IEEE TVCG guidelines, which can be found
[here](http://junctionpublishing.org/vgtc/Tasks/camera.html).
Submissions should not exceed 4 to 6 pages, excluding references.

Papers should be submitted through the
[Precision Conference System](https://new.precisionconference.com/)
(under "New Submissions" and "VIS Workshops 2018").
<!-- Please contact the workshop organizers at [organizers@interactive-analysis.org](mailto:organizers@interactive-analysis.org) for any questions regarding the submission process or the workshop itself. -->

Accepted papers will be presented at the workshop and authors can
choose to include their papers in the IEEE archive. In addition to
their presentation, authors have the option to give a demo of their
systems or tools.

## Registration

At least one author from an accepted paper will be required to attend the workshop. Registration for the workshop can be done via [VIS 2018](http://ieeevis.org/).

## Code of Conduct

DSIA is committed to providing an inclusive and harassment-free environment. Please see the [IEEE VIS Code of Conduct](http://ieeevis.org/year/2018/info/inclusion-and-diversity/code-of-conduct) for details.

## Organizers

* [Dominik Moritz](https://homes.cs.washington.edu/~domoritz/), University of Washington.
* [Joseph Cottam](https://www.pnnl.gov/science/staff/staff_info.asp?staff_num=9106), Pacific Northwest National Laboratory.
* [Leilani Battle](http://cs.umd.edu/~leilani/), University of Washington/ University of Maryland.
* [Marianne Procopio](https://www.eecs.tufts.edu/~procopio/), Tufts University.

## Steering Committee

* [Remco Chang](http://www.cs.tufts.edu/~remco/), Tufts.
* [Carlos Scheidegger](https://cscheid.net/), University of Arizona.
* [Jeffrey Heer](https://homes.cs.washington.edu/~jheer/), University of Washington.
* [Danyel Fisher](https://www.microsoft.com/en-us/research/people/danyelf/), Honeycomb (previously Microsoft Research).
* [Aditya Parameswaran](http://data-people.cs.illinois.edu/), University of Illinois Urbana-Champaign (UIUC).

## Program Committee
* Carsten Binning, TU Darmstadt.
* Tiziana Catarci, Sapienza Universit di Roma.
* Remco Chang, Tufts University.
* Rick	Cole, Tableau Software.
* Çağatay Demiralp,	Stanford University.
* Iddo	Drori,	NYU and Columbia University.
* Michael Gleicher,	University of Wisconsin, Madison.
* Dana	Groff,	MongoDB.
* Jeffrey Heer,	University of Washington.
* Heike Hofmann, Iowa State University.
* Jessica Hullman, University of Washington.
* Niranjan	Kamat,	AWS Redshift.
* Alfons	Kemper, TU Munich.
* Oliver	Kennedy, University at Buffalo.
* Zhicheng	Liu, Adobe Research.
* Carlos	Scheidegger, University of Arizona.
* James Terwilliger, Microsoft Research.
* Eugene	Wu, Columbia University.
* Yifan Wu, University of California, Berkeley.




---
layout: page
permalink: /projects/
---

# Capstone Project List


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Thursday (5 September) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (6 September). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Develop a kernel extension for an Open Source File System [download]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Fall-2019.pdf)

**Project Background**

Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project.  Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.

Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL - write anywhere file layout) for over 20 years. Because of the proprietary nature of the file system we will be using an open source equivalent for this project.   Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

**Project Summary**
In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage. Project Details Over the course of this Capstone project, students will
accomplish the following high-level goals:
 * Download and install FUSE on Linux.
 * Work through the open source “hello” example and a NetApp provided
custom example.
 * Create a read/write file system as an underlying test bed and explore the properties of this system.
 * Write the kernel extension (using the C programming language) to implement a user space reporting function.
 * Execute automated tests during the writing of the kernel extension.  Enhance the automated tests as necessary.

Stretch Goals
 * Enhance the file system to store user space consumed data in an in-memory database.
 * Update the in-memory database based on incoming fileops.
 * Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit

* Team Size: 4 students
* POC: Kurt Johanknecht

### NetApp - Develop an Extendable REST API server and Composite UI Based on Microservices [download]({{site.baseurl}}/projects/pdfs/SDCI-Pitt Capstone Abstract Fall 2019.pdf)

**Project Background**
A principle of the Unix philosophy is “do one thing and do it well”. This is a tenet embodied by the increasingly popular microservice architectural style. The microservice model is commonly associated with the “back-end” of an application. In this style of architecture, the logic behind an application is composed from independent and tightly-coupled microservice pieces.

A shopping website, for instance, might have a microservice for retrieving inventory details, another microservice for managing the shopping cart,and yet another microservice for payment processing. Each piece can be developed independently, and then composed together to form the larger application. A web UI might act as the “front-end” layer for this application. We usually consider this layer as one large piece of the application - but why can’t it also benefit from the microservice model?
The UI for our shopping application could be broken down into independent pieces (a microservice for the inventory search box, one for the navigation bar, etc...) and recomposed into the web page displayed in your browser!

**Project Summary**
The students will develop a proof-of-concept, containerized application. The back-end of the application will be composed of microservices responsible for independently handling different sets of REST API requests. Meanwhile, the front-end of this application will be a web UI composed from independent UI microservices. Once complete, this application will be used as scaffolding for future NetApp-Pitt Capstone projects!

**Project Details**
Over the course of this Capstone project, students will accomplish the following high-level goals:
* Plan and manage their own Agile-style development project.
* Gain real-world experience participating in a collaborative, product-engineering environment
* Research and engage with container technologies, including Docker
* Implement a full-stack application built on a RESTful architecture and microservices

* Team Size: 4 students
* POC: Tim Banyas

### Viz - Lightweight Open Web Analysis

Most web analysis systems are proprietary and heavyweight, meaning that most of their algorithms is hidden and unable to be validated. It leads to a misunderstanding of the answers.  

This project proposes to develop a lightweight open system that does web analysis in the most straightforward and modular way.  It will not hide the implementation and make it available for understanding.  It will be able to be selected as needed and not the heavy-weight requirements. This will be used not only for proper validation, but also as a platform to make web analytics more inclusive.  It should allow for the processing of data without an integration of required hooks that forces users to be locked in simply because of the effort needed to change.  

The application should be developed to provide reusable components that can be used in many types of web analysis as well as other forms of analytics.  We will be using a form of agile software development as it has proven successful in the past for the students as well as the customer. Rather than having to install an application on our systems (which require lots of paperwork, etc.) it would be easier to just have a web-based system that we can use.  

* Team Size: 3 students
* POC: Mike Bigrigg


## CS Faculty Projects

### Augmented Reality in Clinical Training [download]({{ site.baseurl }}/projects/pdfs/Augmented Reality in Clinical Training - Summary Fall 2019.pdf)

This proposal outlines the development of an Augmented Reality solution for training in medical hand hygiene and sterile compounding
techniques. (RP 2019.08.29)

**Goal/Objective**
Create an augmented reality environment to train clinicians in specialized clinical procedures.

**Background**
Training in sterile compounding is a component of pharmacy education and training across the country.
Similarly, training for appropriate hand washing required and procedures in surgical environments are
required of medical students. The resources required for this training can be prohibitive due to the time,
personnel, and space requirements. Coordinating the resources, trainee experiences, and feedback required
in appropriate training is a universal problem for schools, hospitals, and institutions that provide customized
pharmacy sterile compounding and surgical procedures in healthcare.

**Solution**
Creating an augmented reality platform to train users in simulated clinical environments using custom
hardware controllers and software to model and teach clinical procedures and concepts​.

Team:
* Dmitiry Babichenko, ​ Professor of Practice
* Graduate Student Programmer
* Ravi Patel, ​PittPharmacy Innovation Advisor
* CS Capstone Student, Student Programmer(s)


Capstone Outcome/Deliverables
* Project requirements
  - End of any project should have working coding+documentation
  - Will work alongside graduate student programmer
* Recommended, not required:
  - Previous experience programming in Unity
  - Previous experience working with Source control (Github or Azure Teams)
* Communication
  - Must communicate with graduate programmer, stakeholders, and professor for consistent updates and resource requirements
* Expected Outcomes/Experience
  - Work on an evolving project/platform
  - Demonstrable outcome of work in Unity

* Team Size: 2


### Occam: Smarter Search in Workflow Creation
Occam is an open-source software and data preservation tool written in a combination of Ruby, Python, and JavaScript.
This project provides long-term storage and a web-based portal for interacting with archived software.
The focus is on scientific workloads, such as any process involved in producing or analyzing data for scientific publication, and provide a means of repeatably running both builds and workflows.
There are also applications for the humanities and the preservation of interactive art and video games.
When building workflows, a user connects data and software together in a chain as needed to produce new data, plots, etc.
One issue is finding data or software that is relevant to what you wish to do.
Currently, our search does not go beyond basic names, which can be overwhelming.
This project will be about expanding our search capabilities to be more robust.
For instance, if you are using a particular simulator, it could recommend datasets that have been used with it before.
This involves designing an index and/or search heuristic, applying industry-proven projects such as ElasticSearch, and generating fake user activity to evaluate your solution.
The deliverables include writing an entirely new subsystem within our project, designing any new relevant user interfaces, and writing corresponding unit and acceptance tests.

* Team Size: 2 students
* POC: David Wilkinson (wilkie)

### Improving Energy Efficiency via Heterogeneous-aware Scheduling

Computer systems are increasingly being used to support a wide variety of applications such as web browsers, social networks, email clients, audio and video players. Chips with heterogeneous cores have been widely adopted by hardware vendors such as Samsung and Qualcomm to balance performance and power efficiency on mobile devices. Still, the main research challenge for runtime systems is to carefully allocate execution threads to the heterogeneous cores, while meeting strict user-facing performance targets with minimal energy consumption.

This research project will propose to enhance runtime resource management decisions by leveraging existing hardware-assisted performance data. We will explore state-of-the-art machine learning algorithms for online workload characterization to guide task assignment. This work will automatically learn an optimal scheduling policy that can determine energy-efficient resource allocations in the computing platforms. It will continuously track application phases at a fine-grained level and perform application mapping decisions without requiring any application-specific manual-tuning or any modification in the deployed applications. We will conduct an experimental investigation using real development boards running mobile and cloud benchmarks and workloads.

General Areas of Interest: Operating Systems, Computer Architecture, Compilers

Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning

* Team Size: 2 students
* POC: Vinicius Petrucci


### Mobile application for medication adherence

This team will work with SCI faculty researching technology’s potential to improve medication adherence.  Over the course of the semester, the students will build a mobile application for collecting and summarizing medication information and dosing instructions.  While scope is flexible, the application should provide mechanisms for users to manually enter medication name, prescribing doctor, and medication schedule.  Dosing information should be presented in a visual interface; perhaps using different representations (e.g. list and calendar view).  The application should provide a clean user interface and user experience for identifying when medications need to be taken and the user’s actions.  Summary interfaces, for the day, week, and/or month should summarize medication adherence performance (e.g. overall number of doses taken and missed, performance by prescription, performance by day of week).  

For the right team, advanced features could be built into the application.  These include leveraging OCR libraries or online APIs for automatic recognition of medication, dose, and doctor from the medication label.  Implementation will likely require creative user interface design and interaction segmentation to capture information on a cylindrical bottle. Teams could also implement location tracking functionality into the application, leveraging existing toolkits like iBeacon and Eddystone.  These features could power location-based medication reminders.  Students could also push on functionality to allow family members or medical staff to perform lightweight interventions and encouragement (e.g. sending motivating notifications and messages).   

Students can choose programming language and development frameworks that best fit their expertise and interest. Preference would be the construction of a native Android or iOS application, as these platforms are broadly in use. Further, sponsoring faculty are experienced in these platforms and thus can be a resource for the students.

* Team Size: 4 students
* POC: Jacob T. Biehl


### Dynamic performance scaling for heterogeneous processors

Processes typically have different resource needs. With the availability of hardware CPU performance counters and kernel tracking mechanisms, the use of resources can be tracked on a per process basis allowing for better scheduling decisions that save time, improve performance, or decrease energy consumption (that’s why your laptops and cellphones run for a long time--but not long enough). One resource that is of interest is main memory usage. As retrieving data from  main memory takes time (and causes many stalled cycles), energy is wasted if a highly memory-bound process is executing on a very powerful (high frequency) core. With heterogeneous cores or DVFS, these processes can be better treated to do the same computation with much less energy by running on a core that is operating at a lower frequency. The CPU frequency governors in Linux will lower the frequency of a core if the core is underutilized (if it spends enough time without a process to run), but it misses the potential benefit of lowering the frequency while a process is running.

Whether it is worth migrating a process to a less powerful core or lowering the frequency of the processor depends on several factors, such as how long the memory bound phase of a process will last. Profiling is needed to determine at what granularity (and is there a pattern?) processes phase change phases. After profiling, a model is needed to determine when it is worth taking action. Additionally, is it enough to react to process phases or can this be improved by predicting phases using the tracked performance counters and in-kernel events. If so, what counters are the best predictors for which types of phases? Can this be extended to take advantage of other types of phases that cause stalled cycles, or can cache usage be predicted to reduce contention through better placement of processes? There are many tools for tracking performance counters. This project would involve writing C and working with the linux kernel. cs1550 is required, cs1541 would be useful.

* Team Size: 2 students
* POC: Nathan Ackerman

### CS Course Grading App

This program is a web application to be  used by graders to display Java code that has been submitted for assignments in cs007  cs401 cs445 etc.  Students’ java code will be displayed to a grader who will compare that code against a rubric. The grader then enters feedback and scoring for those assignments.

Part of the App has already been developed. Most of the written code simply calls upon PERL scripts written by Tim Hoffman that gather the data files and copy them into a temporary directory for examination and then capture feedback from the grader.
Completion of this application is critical because currently graders must log into the elements machines via terminal and invoke PERL scripts to grade student submissions.  This is undesirable since those running the scripts have to have AFS accounts and need full privilege on directories containing student code and grades. We want to move away from this model and replace it with a carefully limited access application that does not require AFS login.

Needed: Web programmers to complete a project written in (mostly) PHP and (a little) Javascript. You will be handling data stored in JSON format, and may need to implement a database (noSQL, mySQL, ...).  Some experience with PERL would be helpful but not a must.

* Team Size: 2-3 students
* POC: Tim Hoffman

### A match-making website for capstones

This project entails building a match-making website for students projects, like the capstone project you're bidding on.  We need to develop 3 components:

  1. a nice interface for two different stakeholders, namely (a) project providers, such as faculty and NGOs, and (b) project seekers, such as students.  We will need to interview stakeholders and create a requirements document describing the needed elements.
  2. a database to save the information and metadata created by item 1.  We will need to figure out what type of database to use (SQL, noSQL, ...) and design the schema for the database.
  3. an algorithm for matching the two stakeholders.  We will need to define metrics and use existing (or develop new) algorithms that attempt to optimize such metrics; for example, maximize happiness of all stakeholders, minimize extra effort, maximize learning, etc.  The metrics may be multi criteria (that is, more than one metric, with weights.

The students in this project will need to:
  - create a proposal and schedule by the 3rd week
  - meet with the clients once a week to show progress,
  - demo the project 3 weeks before the end of the term, and
  - write a user manual, document the code, and create help functions for the user interface

* Team Size: 2-3 students
* POC: Daniel Mossé


### Deploying an Internet of Things (IoT) infrastructure with embedded devices

The project goal is to deploy an IoT based platform using the CoAP standard as the network/communication protocol. The infrastructure will use CoAP for a Resource Server that will contain information about every other sensor/actuator available in the network. We will use different embedded devices such as ESP 8266, ESP 32, Raspberry Pi's as nodes for the infrastructure.
The student will design and implement the Resource Server with a database backend to persist other nodes information as well as the necessary CRUD (Create, Read, Update, and Delete) functions for managing device information. Furthermore, we will integrate image recognition tasks with Tensorflow, such as Face and Object Recognition into the CoAP network.
Experience with Unix systems and coding with C/C++ and Python are required. Also, students should have taken the CS1550 course.

Faculty Sponsor (Extend of the faculty sponsor supervision, meetings frequency, and method of evaluation) :
  - The student will need to attend weekly meetings.
  - The evaluation will be based on the implementation progress, which will be supervised, trough Git.

* Team Size: 2 students
* POC: Henrique Potter

## Data Mining for Helping Students in Scheduling
This project will make advances in structural educational data mining, analyzing dependencies and pathways for student success, and creating performance prediction models for students.
The outcome for this project is to create a model of a student’s progress and predict his/her performance going forward, at the course granularity. This allows us to recognize successful and unsuccessful pathways that students take through their undergraduate career, to guide students to maximize their chance to graduate.


For example, rather than assuming that students with A/B grades will do well in subsequent courses, we can predict a student’s grade in a particular course in a data-driven way by analyzing their history and comparing with "aggregate students."   Also, we'll try to detect good pathways (eg, 401 should be followed by 445 in the very next semester) and not-so-good pathways (eg, 1502 is taken 2 years after 441).

* Team Size: 2 students
* POC: Daniel Mosse



## Smartphone Gps Duty-Cycle For Saving Battery In Navigation

One of the main battery drainers in smartphones is the GPS and maps applications (map app or mapp). While it is true that most mapps are used in a car, and that many times USB connectors can charge phones in the car, while using the mapp. The goal of this project is to reduce the energy consumed by the mapp and other apps that use GPS, by recognizing what the needs of the application are (e.g., duty cycle requirements while walking are different than while driving in a city, which are different than while driving in a highway).

In this project, we'll learn how a GPS works in depth, how to control it, read related literature on how to do adaptive duty cycling of GPS, and propose new algorithms (perhaps based on machine learning?) for better duty cycling. There will be a lot of self-discovery, therefore students should be good at finding information on their own.

Time permitting, we'll also propose algorithms for optimizing navigation by suggesting which lane to use, with the help of the GPS.

* Team Size: 2 students
* POC: Daniel Mosse


## Synthetic Student Generation

Personalized education is an exciting new field that has spawned from the (limited) success of Massively Open Online Courses and other online course offerings from different educational institutions. These courses have generated a plethora of student data, where machine learning models have been created to assist students in a multitude of ways, such as reading/lecture material recommendation, problem solving suggestions, and peer-interaction encouragement. However, not as much research effort has been directed at cross-course interactions, and similarly, not as much data has been published or analyzed.

This project will ask students to develop a tool that generates large synthetic student datasets that span across several courses in a university setting. Real datasets are difficult to obtain in full, due to privacy and confidentiality policies, as well as exclusive research accessibility. A generated synthetic dataset should allow any researcher to simulate a set of students with certain structural and student characteristics that can be specified as part of their parameters, such as course prerequisites, and grade distributions. The resulting datapoint for each student will essentially read like a student's transcript, complete with a student's schedule of courses and the course grade received for each, along with more specific details regarding the student (e.g. demographics) and courses (e.g. which instructor taught the course).

Requirements: Students must have taken at least one of CS 1571 (AI), CS 1656 (Data Science), CS 1675 (Machine Learning), or an equivalent course that may be offered in other departments, or have previous experiences in research in machine learning or data mining.

* Team Size: 2 students
* POC: Nathan Ong




### Panos Chrysanthis projects [download]({{ site.baseurl }}/projects/pdfs/Panos_Capstone_Projects.pdf)

1. Erasure Coding for HDFS

    **This is more research than project may require a change to CS 1950, will still count towards your capstone**

    Hadoop Distributed File System (HDFS) traditionally uses 3x replication when storing data in order to provide fault tolerance. Erasure coding is an alternative to replication that provides flexibility in selecting the degree of redundancy depending on the fault tolerance requirement. In this project, the student will explore the viability of erasure coding by adding such functionality in Libhdfs3, a library that allows clients to connect to a Hadoop cluster and perform file system operations on HDFS, and subsequently comparing the implemented functionality with traditional replication in terms of performance as well as resilience support.

    - Required Skills: C++, familiarity with multi-threaded programming
    - Team Size: 2 students
    - PittCS Supervisor: Panos K. Chrysanthis
    - Vertica Supervisor: Deepak Majeti
    - Location: ADMT Lab and Vertica, Pittsburgh

2. Evaluating different HDFS C++ clients

    **Can be run as a CS 1950 research, will still count towards your capstone**

    Libhdfs++ and LibHdfs3 are C++ libraries that allow clients to connect to a Hadoop cluster and perform file system operations on HDFS. Furthermore, WebHdfs is a Rest Api that performs the same operations via http. The goal of this project is to compare these different mechanisms in terms of the functionality they support, their performance, and also their ability to handle large concurrent requests. Students will study the code to understand the differences in the libraries’ implementations, and also design experiments to compare the performance and scalability of these mechanisms.

    - Required Skills: C++, familiarity with multi-threaded programming
    - Team Size: 3 students
    - PittCS Supervisor: Panos K. Chrysanthis and Constantinos Costa
    - Vertica Supervisor: Deepak Majeti
    - Location: ADMT Lab and Vertica, Pittsburgh

3. Optimizing Apache Parquet Reads for S3

    **This is more research than project may require a change to CS 1950, will still count towards your capstone**

    Apache Parquet (https://parquet.apache.org/) is a popular columnar file format used for storing and querying big data. Parquet file format is supported by all major analytical tools such as Hive, Spark, Presto, Vertica, etc. Object store file-systems (such as Amazon’s S3) have recently become popular to store data. The cost of reading and writing data to S3 depends on the number of API calls made. The scope of this project is to optimize SQL analytical queries by tuning execution performance and cost of reading/writing data to S3.

    - Required Skills: C++, Knowledge of Object Stores such as Amazon S3
    - Team Size: 2 students
    - PittCS Supervisor: Panos K. Chrysanthis
    - Vertica Supervisor: Deepak Majeti  
    - Location: ADMT Lab and Vertica, Pittsburgh

4. Apache Parquet Column Indexes

    **This is more research than project may require a change to CS 1950, will still count towards your capstone**

    Apache Parquet (https://parquet.apache.org/) is a popular columnar file format used for storing and querying big data. Parquet file format is supported by all major analytical tools such as Hive, Spark, Presto, Vertica, etc. The Parquet specification recently introduced Column Indexes to allow fast data lookup. This project involves implementing and investigating the Column Indexes inside the Apache Parquet C++ library. The investigation will include optimizing Column Indexes for memory and performance when writing and reading parquet files.

    - Required Skills: C++
    - Team Size:  2 students
    - PittCS Supervisor: Panos K. Chrysanthis
    - Vertica Supervisor: Anatoli Shein
    - Location: ADMT Lab and Vertica, Pittsburgh

5. Backup and Restore on HDFS

    **This is more research than project may require a change to CS 1950, will still count towards your capstone**

    Backup and restore are essential database components needed to recover a database from physical failures such as storage or operating system crashes. Hadoop Distributed File System (HDFS) is a popular file-system used by many large enterprises to store cold data. HDFS supports data fault-tolerance and is well-suited to be a backup location. The scope of this project is to implement backup and restore operations in Python that help synchronize data and catalog objects of an entire Vertica database to HDFS. The project will include the performance evaluation and optimization of these backup/restore operations.  
    - Required Skills: Python, C++, familiarity with multi-threaded programming
    - Team Size: 2 students
    - PittCS Supervisor: Panos K. Chrysanthis
    - Vertica Supervisor: Jie Guo
    - Location: ADMT Lab and Vertica, Pittsburgh

6. Context-Aware Path Recommendation

    **Can be run as a CS 1950 research, will still count towards your capstone**

    During extreme weather conditions and natural disasters caused by meteorological phenomena, it is imperative to enable navigation that minimizes the outdoor section of recommended paths. CAPRIO (http://db.cs.pitt.edu/caprio) is a context-aware path recommendation system whose objectives are two-fold: (i) minimizing outdoor exposure; and (ii) minimizing the distance of the recommended path. In this project, the student(s) will extend the system to integrate more information about the potential path (e.g., the accessibility of the building) using the graph integrator module to enrich the quality of the recommended path. The student(s) will also explore the CAPRIO’s data management subsystem to improve the overall robustness and performance of the system.

    - Required Skills: JAVA, familiarity with RESTFul API, HTML and Javascript
    - Team Size: 2 students
    - Supervisors: Panos K. Chrysanthis, Constantinos Costa
    - Location: ADMT Lab


## Non-CS department

### Pitt Green Suite

In this project, you will be developing an app to engage people in actions that support the culture of sustainability at Pitt, while making these decisions and activities fun and engaging.   Engaging people can be hard, so you will need to devise a way to incentivize people to engage – and continue to engage.
The plan, which you may not follow exactly, is to create an app that will conduct a survey in small periodic chunks (e.g., once a day/week), and awards a "badge" for each participation. You'll suggest types of badges or other "cooler" ways to motivate people.  For example, participants can create teams to compete against each other for the most badges, allowing the client to award the winning team.

For this project you will need to:
  - Create an app (web or mobile or both) with a (great) user interface for the survey participants, and an administrative interface to add and manage the questions or other activities. You will design this based on the requirements of the customer and based on interviews with different types of customers.
  - Design a database to store the user data and the survey data.
  - Export a report containing visualization of the survey data in meaningful plots and useful statistics

* Team Size: 2
* POC: Aurora Sharrard (Director of Sustainability)

## Automating a robotic cell culture system
In this project, you will develop a GUI for a computer/phone app that provides control for automation of a robotic cell culture system that was recently developed in my lab (https://www.cell.com/iscience/fulltext/S2589-0042(19)30288-3). The GUI would ideally 1) provide an intuitive wireless interface for uploading/downloading, executing, pausing, and resetting protocols on the robotic system (note that the basic framework for communicating with the system via bluetooth is already in place), and 2) provide an interface that takes as input time courses in an excel-style format and converts them into control commands for the robotic system.  

**Note: If you take this project, you will need to do more than just create a GUI.**

* POC: Dr. Robin Lee, Computational and Systems Biology at the University of Pittsburgh
* Team size: 1-2 students

## Bioinformatics-Focused Projects

**Note:** These projects have a focus on bioinformatics specifically. Preference is given to CS1640 students, or those with a background in bioinformatics or a related discipline.

## Automated data extraction from mammalian cells
In this project you will implement a machine learning approach to automate data extraction from single cells in time-lapse imaging. A recent publication has optimized the approach for images of bacteria (https://www.biorxiv.org/content/10.1101/720615v1). The capstone project would consist of adapting this framework for images of mammalian cells, tracking single cells over time and deferentially monitoring the abundance of fluorescent-protein fusion in the cytoplasm and nucleus.

* POC: Dr. Robin Lee, Computational and Systems Biology at the University of Pittsburgh
* Team size: 1-2 students





## Acoustic Monitoring of Frog Populations

Justin Kitzes's and his lab, approach very large-scale biodiversity data collection is autonomous acoustic recorders - devices that can be placed in the field, automatically turn on and off, and record all sounds in the surrounding area. These recordings are then processed using machine learning models to identify what species were present at each location.

The lab recorded frog calls in Borneo in collaboration with Jen Sheridan at the Carnegie Museum, and wants to apply some basic machine learning-type analysis. You will be using some methods the lab applied previously to other species to try to identify, as best they can, about 30 species from a few hundred hours of ambient soundscape recordings.

* Team Size: 2-3 students
* POC: Justin Kitzes


## Visualization and analysis of adolescents brain fMRI scans

We have recently been performing multi-study analyses of the development of functional brain connectivity through adolescence to understand how brain networks evolve and reconfigure in this time period. This field has had to overcome a lot of methodological challenges due to artifacts and small effect sizes that have led to an interest in multi-site, “big data" studies and replication through open science initiatives. To this end, we been working on analyses combining multiple large, longitudinal studies comprising thousands of fMRI scans of adolescents.  From these, we are interested in charting the developmental trajectories of every functional *connection* in the brain (e.g., the strength of functional interactions between every pair of regions).  This means we have a large number of connections (50k-500k depending on the density of the sampling applied), each with a developmental trajectory as well as various statistical and diagnostic assessments.

The goal of the project would be to build a web interface to allow visualization of this data, both for performing exploratory analyses (e.g., for people interested in a particular region or regions, allow them to quickly identify its developmental role and timing), as well as replication (e.g., for people performing their own developmental studies, determine whether overall patterns replicate in a much larger, multi-site sample).

Technically, what I’d envision is something like a web interface that allows people to select any two brain regions (a la the [Allen brain atlas](http://human.brain-map.org/mri_viewers/data), or [neurosynth](https://neurosynth.org/)), displays information about the regions selected, and either queries a pre-built database (based on analyses we’ve currently been running on the Pittsburgh supercomputing center servers) and executes some optimized analyses in real-time to show information about, e.g., overall developmental patterns, patterns in each of the component studies individually, differential developmental patterns by gender or other demographics, QA metrics such as the effect of head motion on connectivity strength, and potentially more.

* POC: Finnegan Calabro
* Team Size: 2-3 Students

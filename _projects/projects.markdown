---
layout: page
permalink: /projects/
---

# Capstone Project List


Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (15 January) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (17 January). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

### NetApp - Develop a kernel extension for an Open Source File System [download]({{site.baseurl}}/projects/files/NetApp-SOS-Pitt-Capstone-Abstract-Spring-2020.pdf)

[Presentation]({{site.baseurl}}/projects/files/FS Pitt Capstone - Spring 2020 Abstract.pptx)

**Project Background**

Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project. Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.

Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years. Because of the proprietary nature of the file system we will be using an open source equivalent for this project. Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

**Project Summary**
In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.

**Project Details**
Over the course of this Capstone project, students will accomplish the following high-level goals:

* Download and install FUSE on Linux.
* Work through a NetApp provided initial custom example to understand the basic architecture.
* Create a read/write file system as an underlying test bed and explore the properties of this system.
* Write the kernel extension (using the C programming language) to implement a user space reporting function.
* Execute automated tests during the writing of the kernel extension. Enhance the automated tests as necessary.
* Enhance the file system to store user space consumed data in an in-memory database.
* Update the in-memory database based on incoming fileops.
* Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.


* Team Size: 4 students
* POC: Kurt Johanknecht

### NetApp - Extending a Microservice Architecture and Developing a Test Framework [download]({{site.baseurl}}/projects/pdfs/Spring 2020 Capstone Abstract.pdf)

[Presentation]({{site.baseurl}}/projects/files/MS Spring 2020 Capstone.pptx)


**Project Background**
The microservice model is commonly associated with the “back-end” of an application. In this style of architecture, the logic behind an application is composed from independent and loosely coupled microservice pieces. A shopping website, for instance, might have a microservice for retrieving inventory details, another microservice for managing the shopping cart, and yet another microservice for payment processing. Each piece can be developed independently, and then composed together to form the larger application. This is one of the many benefits of the microservice architecture as they are independently deployable.
In order to make sure the highest quality software is delivered; it needs to be tested while it is being developed. For example, if a new microservice is added to the application, we need to run some integration testing to make sure nothing has regressed with the addition of a new microservice. This is especially important when multiple teams are working on the application.

**Project Summary**
The students will develop a proof of concept testing framework for a containerized application. They will utilize and extend the infrastructure created by previous capstone students to create an automation suite that will run tests when new microservices are added to the application. As a stretch goal, students can create a test script generator that will automatically generate test cases for new microservices and run those tests once the microservice is checked into the code line.

**Project Details**
Over the course of this Capstone project, students will accomplish the following high-level goals:
* Plan and manage their own Agile-style development project.
* Gain real-world experience participating in a collaborative, product-engineering environment
* Research and engage with container technologies, including Docker, Kubernetes
* Implement a continuous integration testing framework
* Learn about the REST and microservices architectures

* Team Size: 4 students
* POC: Tim Banyas and Twesha Mitra

### INTALERE - Modernize Hospital Discharge Data Submission Application [download]({{site.baseurl}}/projects/files/Intalere Capstone Project.pdf)

**Project Background**

In most states, hospitals are required to submit accurate and complete discharge data files to the state collection agency each calendar quarter. Managing the collection and submission of this quarterly data to federal and state agencies can be a difficult and time-consuming task. Hospitals need to maintain knowledge of and compliance with rapidly changing rules, as well as have staff with the required technical expertise to manage the process.
CheckNet is utilized by hospitals, ambulatory surgery centers, as well as state data agencies and hospital associations to reduce errors and streamline the collection of discharge data. Easily adapted to the different needs and requirements of any state data agency, the CheckNet solution allows for direct submission of discharge data files via the internet.

**Project Summary**

Students will develop a modern containerized CheckNet application moving the application into the cloud hosted by Microsoft Azure. The front-end of this application is a web UI composed from independent UI microservices.
Students will also receive training and develop in Domain Driven Design which is a methodology where developers work with the domain expert to visually create a model of the business domain. The business domain are the terms used to communicate about concepts in the domain and all of the business rules in the domain. Students will gather information for the domain and graphical models from the domain expert and model it together. This graphical representation of the business domain helps everyone quickly understand the business domain, how things relate to one another and drives the design of the software.

**Project Details**

Over the course of this Capstone project, students will accomplish the following high-level goals:
* Complete Domain Driven Design Training provided by Intalere
* Develop the project in an Agile development methodology  
* Gain real-world experience participating in a collaborative, product-engineering environment
* Research and engage with container technologies, including Docker and Kubernetes as well as work with additional technologies such as Visual Studio, Microsoft Azure .NET Core, and SQL Server
* Ideal student candidates will have experience in Visual Studio and .NET Core/C#

* Team Size: 3 students
* POC: Joe Morrison


### Behaivior - Develop a Mobile Application to Help Support People in Recovery from Opioid Addiction


**Project Background**
This team will work with Behaivior to help support people in recovery from opioid addiction. Over the course of the semester, the students will build a mobile application for collecting and analyzing wearable and smartphone information. While scope is flexible, the application should provide mechanisms for users to manually enter appointment times, medication information, share location information, and connect to resources. The application should provide a clean user interface and user experience for identifying when appointments are, when medications need to be taken and the user’s actions. Summary interfaces, for the day, week, and/or month should summarize appointment adherence, medication adherence performance (e.g. overall number of doses taken and missed, performance by prescription, performance by day of week).

For the right team, advanced features could be built into the application. These include leveraging wearable technologies (SDKs), API’s, Cloud Tech, Mobile Tech (GPS, Contacts) and AI. These technologies will be utilized to assist in data collection, display, and decision making to help provide immediate (real-time) corrections (push notifications) to current Persons in Recovery (PiRs). These features could power location-based behavioral corrections. Students could also push on functionality to allow family members or medical staff to perform lightweight interventions and encouragement (e.g. sending motivating notifications and messages).

Students can choose programming language and development frameworks that best fit their expertise and interest. Preference would be the construction of a native Android or iOS application, as these platforms are broadly in use. Further, sponsors have experience in these platforms and thus can be a resource for the students as well. Currently some of the data collection tech is built in Python, but that’s not a necessity.

* Team Size: 4 students
* POC: Ellie Gordon & Lou Simon

**Note: NDA and/or IP agreement will need to be signed for this project.**


### InvolveMINT
InvolveMINT is planning on creating a Social Resume - a central digital repository and profile that catalogues all work, associated clearances, certifications, clearances, background checks, etc. Many organizations require certain types of certifications or clearances to work on their project. However, individuals with the desire to serve may not have the required clearances or certifications, or have received said certifications, but do not have a central repository for documentation. This presents a barrier, especially  for individuals with low-incomes, to getting involved and supporting the organization and the challenges they address.

Starting with the most common clearances and certifications required by nonprofit organizations, involveMINT’s goal is to chronicle, automate, and then securely store said clearance/certification in a Social Resume as central repository to the furthest extent possible to make it easier for income scarce individuals to provide the required documentation to partake in service projects.

Development stack:
Database - PostgreSQL
Deployment - Heroku
Authentication - Auth0
Frontend - Ionic/Angular
Frontend state management solution - Akita
Backend - Firebase

* POC: Daniel Little
* Team Size: 3 students


**Note: NDA and/or IP agreement will need to be signed for this project.**

## CS Faculty Projects


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

* Team Size: 2-3 students
* POC: David Wilkinson (wilkie)


### Improving Energy Efficiency via Heterogeneous-aware Scheduling

Computer systems are increasingly being used to support a wide variety of applications such as web browsers, social networks, email clients, audio and video players. Chips with heterogeneous cores have been widely adopted by hardware vendors such as Samsung and Qualcomm to balance performance and power efficiency on mobile devices. Still, the main research challenge for runtime systems is to carefully allocate execution threads to the heterogeneous cores, while meeting strict user-facing performance targets with minimal energy consumption.

This research project will propose to enhance runtime resource management decisions by leveraging existing hardware-assisted performance data. We will explore state-of-the-art machine learning algorithms for online workload characterization to guide task assignment. This work will automatically learn an optimal scheduling policy that can determine energy-efficient resource allocations in the computing platforms. It will continuously track application phases at a fine-grained level and perform application mapping decisions without requiring any application-specific manual-tuning or any modification in the deployed applications. We will conduct an experimental investigation using real development boards running mobile and cloud benchmarks and workloads.

General Areas of Interest: Operating Systems, Computer Architecture, Compilers

Helpful Skills: Knowledge of Linux, System Programming (C/C++), Python, Machine Learning

* Team Size: 2-3 students
* POC: Vinicius Petrucci




### A website for handing-in programming assignments

This project will be the modification of an existing website that allows students to hand in source files for programming assignments.

Currently this hand-in system allows students to upload files (usually java) for their programming homework but does not have any mechanism to turn on/off uploads for individual sections of individual students. A clean simple web interface is needed to allows the instructor to enable / disable uploads at the section by section and at individual student level.

This project requires skill in PHP, HTML forms, JavaScript and JSON. We would like to avoid the use of vendor specific platforms such as Node JS etc.

Other enhancements are as follows:
- Modify the script that compiles the uploaded file(s) such that it displays the exact cause of the failure to compile rather than just reporting does not compile.
- Modify the script code that accepts a roster from the instructor such that it provides an interface to see the list of students that are authorized to hand-in – and allows the instructor to add or remove students from the hand-in roster.  This is not the same thing as turning on/off a student’s ability to upload a specific assignment as describe in the first paragraph.


* Team Size: 2-3 students
* POC: Tim Hoffman


### Duty-Cycle For Saving Battery In Navigation

One of the main battery drainers in smartphones is the GPS and maps applications (map app or mapp). While it is true that most mapps are used in cars typically with chargers, sometimes it is good to save the energy consumed by the mapp by turning the GPS on and off based on the mapp needs (e.g., duty cycle requirements while walking are different than while driving in a city, which are different than while driving in a highway).

In this project, we'll work off an existing prototype on rooted phones that controls the GPS duty cycle for static routes.  We will (a) collect data using the existing prototype, (b) connect the prototype to mapping application, such as Google maps or OpenStreetMaps or OpenStreetProject, (c) propose new algorithms (perhaps based on machine learning?) for better duty cycling, predicting when to turn on and off the GPS (before turns), and (d) measure the power gains in different situations.  There will be a lot of self-discovery, therefore students should be good at finding information on their own.

* Team Size: 2-3 students
* POC: Daniel Mosse


### Managing user impatience on Android smartphones

One of the main issues in smartphones is the battery usage. Phones can and do adjust resource usage dynamically, for example, dimming screens or reducing CPU frequency. However, it is not personalized. Are there ways to make it more general and more personal, maximizing battery life, while minimizing user frustration? We have implemented a prototype of such a system, where the users give feedback to the system through different interfaces and the system learns how each user uses the device.

This project is based on a user-level prototype, done as a proof of concept.  We now have to implement or enhance several parts: (a) acquiring data about the usage of resources (CPU, screen brightness, Wi-Fi, network, etc), (b) feed the collected data to a machine learning model locally or in the cloud, (c) install the model in the smartphone kernel to install the correct resource configuration, (d) a resource discovery mechanism, which finds the user preferences (eg, for CPU, start all cores on and slow them down gradually; when the user think it is too slow, s/he will give a feedback to User Impatience), and (e) thorough testing of the final product. Students will participate in any or all of the 5 parts above.

Required Skills: Java

Desired Skills:
  * Android knowledge (Activity, Threads, Services)
  * Android internal files knowledge is desirable but not required
  * MySQL

* Team Size: 2-3 students
* POC: Daniel Mosse and Raphael Fernandes

### Web-based Interactive Degree Pathways

[Presentation]({{site.baseurl}}/projects/files/Interactive Degree Map Capstone Project.pptx)

Goal: Design a web-based, interactive tool to help students visualize and explore SCI degree pathways based on their academic interests and personal timeline
Background: Currently, the most common tool for degree planning is a student’s degree audit or AAR, which can be accessed in Peoplesoft. This tool has numerous limitations, however. It is hard to read, does not show the prereq/coreq structure of the classes, and is not linked to course descriptions. Many universities create flow charts as a tool to recommend a timeline and flow of classes, but they also lack interactivity and often are visually confusing.
Solution: We would like a tool that is visually clear, captures the prereqs/coreqs between courses,
helps a student plan backwards based on their area of interest within a major (e.g. concentrations/specializations/set of electives), helps students to explore the best path for common double major or major/minor pairings, and links the courses to their course descriptions. In addition, we’d like to show what these paths would look like for students intending to complete their degrees over different durations.

Helpful skills: Experience with web frameworks, data integration, interactive UI Design

* Team Size: 3-4 Students
* POC: Adam Lee and Kristine Pugliese



### Privatizers for the Internet of Things - measuring the impact of privatizer functions on image detection models

Internet of Things applications such as smart-home is leveraging the unlimited power of the cloud to process the data collected by sensors and actuators. However, sending this data to remote servers for storage or processing also risks leaking unnecessary data to unknown parties given the history of occurrences from services such as Dropbox and even Google.

Sensing devices that collect rich unstructured data such as cameras coupled with the advances of Visual Machine learning techniques can be used in many applications, which can range from person counting to mood detection. These techniques typically require full raw images from camera feeds, which may also contain unnecessary Personally Identifiable Information (PII) or user profiling data that is not necessarily a for the provided service. In this regard, we can use privatizer functions that have the role of cleaning unstructured data to remove unnecessary data or mitigate a specific attack on this data.

In this project, we will create experiments to study how different simple global random privatizer functions can affect the inference of image-based object detection models. We will use the 2017 validation dataset and experiment with the different mobile_v2 pre-trained models.

The student will learn how to:
- Use Tensorflow with Python to detect objects in images with different models
- Create visual machine learning inference and validation workflows
- Use pandas and numpy libraries
- Format and edit images with numpy functions in Python

* Team Size: 2-3 Students
* POC: Henrique Potter

### Studying the impact of using privatizers across different image-based detection tasks

Project Background: Today, video cameras have the potential to transform many aspects of our life. Advances in deep learning-based techniques have enabled AI-based video analytics, such as reasoning from images, generating rich insights, and discovering relationships. Newer models exist that address binary classification problems (e.g., Is the meeting room occupied?), counting problems (How many people are in the meeting room?), recognize gestures, and so on. But, recording videos also infringes on people's privacy --- the videos can be mined to extract personally identifiable information for profit or malice.

Interestingly, many of the privacy attacks can be prevented by employing privatizers that remove personal information at the cost of additional accuracy and energy. For example, faces can be blurred before videos are processed by third-party algorithms. However, there exist many tradeoffs in employing such privatizers. Blurring faces, for instance, may reduce the accuracy of the algorithm that extracts useful information (i.e., utility) but improve privacy. These privatizers may also consume additional energy to transform the data. We can also use less powerful privatizer that uses less energy but maintains similar utility. Since videos can provide useful analytics and services, our main goal is to study the tradeoffs that privatizers provide in the context of utility, energy, and privacy.

We are looking to study these utility, privacy, and energy tradeoffs across different tasks (e.g., counting people, gesture recognition). This will involve using existing deep learning models on these tasks and measuring the impact of executing the models on privacy and energy. Students are required to know python programming and some familiarity with deep learning-based libraries.

* Team size: 2-3 Students
* POC: Stephen Lee


### Professor Bruce Childers Projects

1. An AI-driven Outlook plug-in to schedule meetings <br> This project involves creating an AI-driven Outlook plug-in that can automatically suggest meeting times for people that request meetings.  The Scheduling-Bot could examine historical calendar information to learn preferences, could pull in teaching schedules, etc., to figure out when to suggest meetings, the location.



2. Create a Voting System for SCI <br> SCI has many committees, which are formed by election. This capstone is to create an online, cloud-hosted platform that allows individuals to (a) specify preferences, with varying rank of choice, to stand for election on various committees; (b) automatically matches preferences to create ballots for committees under constraints (e.g., maximum of 2 people on a ballot); (c) solicits votes among constituents; (d) select winning candidates according to rank choice voting (RCV); (e) delivers a report of voting outcome, including voting rounds with RCV.<br>The project will involve web development, cloud hosting, and algorithm implementation (for matching to create ballots and to conduct the vote with RCV).

* Team size: 2-3 Students
* POC: Bruce Childers


## Bioinformatics-Focused Projects

**Note:** These projects have a focus on bioinformatics specifically. Preference is given to CS1640 students, or those with a background in bioinformatics or a related discipline.

### A web interface to enable the visualization of fMRI data

[Presentation]({{site.baseurl}}/projects/files/fmri_portal.pdf)


We have recently been performing multi-study analyses of the development of functional brain connectivity through adolescence to understand how brain networks evolve and reconfigure in this time period. This field has had to overcome a lot of methodological challenges due to artifacts and small effect sizes that have led to an interest in multi-site, “big data" studies and replication through open science initiatives. To this end, we been working on analyses combining multiple large, longitudinal studies comprising thousands of fMRI scans of adolescents.  From these, we are interested in charting the developmental trajectories of every functional *connection* in the brain (e.g., the strength of functional interactions between every pair of regions).  This means we have a large number of connections (50k-500k depending on the density of the sampling applied), each with a developmental trajectory as well as various statistical and diagnostic assessments.

The goal of the project would be to build a web interface to allow visualization of this data, both for performing exploratory analyses (e.g., for people interested in a particular region or regions, allow them to quickly identify its developmental role and timing), as well as replication (e.g., for people performing their own developmental studies, determine whether overall patterns replicate in a much larger, multi-site sample).

Technically, what the goal is to develop something like a web interface that allows people to select any two brain regions (a la the Allen brain atlas, http://human.brain-map.org/mri_viewers/data, or neurosynth, https://neurosynth.org/), displays information about the regions selected, and either queries a pre-built database (based on analyses we’ve currently been running on the Pittsburgh supercomputing center servers) and/or executes some optimized analyses in real-time to show information about, e.g., overall developmental patterns, patterns in each of the component studies individually, differential developmental patterns by gender or other demographics, QA metrics such as the effect of head motion on connectivity strength, and potentially more.

* Team size: 3-4 Students
* POC: Finnegan Calabro, Departments of Psychiatry and Bioengineering, University of Pittsburgh


### Remote veterinary care app

Proposed regulations by FDA will ban the over-the-counter sale of all antibiotics to livestock producers. In order to administer antibiotics to sick animals, livestock producers will need to get a prescription from a veterinarian. Currently, they can purchase common antibiotics (example: penicillin) from feed/farm stores or via mail order. Unfortunately, there is a shortage of food-animal and rural veterinarians, especially those with small ruminant (sheep, goat) expertise. Many producers are located far from a veterinarian. For veterinarians, it is expensive and time-consuming to visit farms with any frequency. One way to address the problem is through technology, a smart phone app that could connect livestock producers, especially small and limited resource producers, with veterinary expertise.  Producers could submit pictures/videos, data, and symptoms to a veterinarian, who in turn, could respond with possible causes and treatments. Prairie View University has developed an app for this purpose (Vetlink), but the app is geared more towards providing producers with possible disease causes than connecting them with veterinary expertise and improving the communication between veterinarian and client. An app can't replace veterinary consultation, but it may make it easier for both parties to develop valid veterinarian-client-patient relationships that will be essential to livestock producers being able to provide adequate health care to their animals if/when the antibiotic ban takes place. Think of it as remote veterinary care.

* Team size: 3-4 Students
* POC: Susan Schoenian, Sheep & Goat Specialist, University of Maryland

### O’Donnell lab – Machine learning to map cellular localizations

In response to a changing environment, cells reshuffle the localization of key membrane proteins. Mapping these localization changes is crucial for human health; if proteins are not in the correct location they cannot execute their proper cellular function. For example, in diseases like cystic fibrosis, mislocalization of a key membrane channel results in impaired lung function. In the O’Donnell lab, we are interested in characterizing the localization changes for membrane proteins in a high-throughput fashion. Using cutting edge fluorescence microscopy, we can define the intracellular distribution for hundreds of membrane proteins. Quantitative analysis of these distributions requires labor intensive manual manipulations. We are interested in developing an automated pipeline, that likely involves machine learning approaches, to allow for high throughput quantification analyses of protein distribution between the plasma membrane and intracellular compartments. We currently have a large, manually quantified training dataset. Should this experience prove rewarding for the student and beneficial to our research program, we can offer paid summer internships to further aid us in achieving these goals.  

* Team size: 3-4 Students
* POC: Allyson F. O'Donnell


### Machine learning of electronic health records data

Electronic health records (EHR) contain comprehensive patient health history and are promising for early diagnosis of disease or prediction of outcome. Particularly, EHR data in intensive care units (ICU) are ideal for applying machine learning techniques as they are mass in volume, and record very detailed health history information. Examples include demographics, treatment records, periodic vital and lab measurements. However, most of these data are either incomplete, irregular, or unstructured, making it hard to apply standard prediction models. Recurrent neural network is capable of handling time-series inputs. The goal of this project is to build a predictive model for early detection of in-hospital organ failure or mortality using novel neural network techniques. We will use the open source MIMIC-III data.

The breakdown of this project:
1. Data: data wrangling, feature engineering
2. Model training: applying off the shelf packages, or modifying existing implementation, selection of hyperparameters
3. Evaluation: compare with benchmarks on prediction
4. Deploying: creating a GUI or package

* Team size: 3-4 Students
* POC: Lu Tang


### Ectotherm ER: Biological Sciences Outreach module website development

Through Pitt Bio Outreach, we developed curriculum called “Ectotherm ER” that goes out to middle and high schools in which students learn about climate change by participating in citizen science, gathering and analyzing data, and relating that to amphibian populations and disease. Students use agar model frogs to gather temperature data in different microhabitats which is then reported back to the Richards-Zawacki lab in the Department of Biological Sciences and used to create computational models that predict amphibian body temperature in nature, which can help anticipate trends due to changing climates. This curriculum is being used widely in the western PA area, and we are working to publish in a national journal to expand the work across the country. To support the schools, we developed a handbook of materials and worksheets for the students to use as well as an introductory video to familiarize students with the work and the lab that they will be contributing data to.

We would like a website that is the central hub for teachers to access the introductory video, all of the handbook materials needed for the module, as well as a place for schools to input data collected from their location so that the lab can easily access those data and use it in their research. If possible, we would also like the website to show graphs that are generated by the data that is inputted by the schools.

* Team size: 3-4 Students
* POC: Rebecca Gonda

### Benos Lab - Smartphone app

[Presentation]({{site.baseurl}}/projects/files/Takis Capstone_pres.20200110.pdf)


Machine learning is become an important tool nowadays to analyze the complex and large biomedical and clinical datasets that are available.  At the same time, new data types are generated from smartphones and other apps that can transform the field of medicine.  These data too, will need to be integrated and analyzed under the same framework with the standard clinical measurements.

The Benos Lab is developing probabilistic graphical models (a subcategory of machine learning algorithms), specifically designed to analyze complex datasets with a variety of data types.  We have applied those algorithms successfully to a variety of clinical problems including (a) develop a classifier to reduce the number of false positive findings in low dose CT scan screenings for lung cancer, (b) identify biomarkers indicative of combination therapy in cancer and (c) identify microbiota and clinical factors affecting the development of pneumonia in ICU patients.

We would like to expand the data that are typically analyzed by using smartphone apps to collect new data types.  In that respect, we are looking for a highly motivated student, with expertise in developing  such apps to work with us and UPMC clinicians in developing such tools.

For more information on Benos Lab activities: http://www.benoslab.pitt.edu/

* Team size: 3-4 Students
* POC: Takis Benos


### Applying Localized Feature Selection Based on Scatter Separability on RNA sequencing

Localized Feature Selection Based on Scatter Separability (LFSBSS) is a cluster-wise feature selection algorithm for unsupervised learning.
Unlike global feature selection methods where the uniqueness of subgroups is ignored, LFSBSS allows the feature set to optimally adapt to local variations in the sample space.
This locality property particularly suits the need for identifying marker genes used for cell type identification in single cell RNA sequencing studies.

However, the current implementation of LFSBSS takes too much time iterating feature selection and clustering processes especially when it needs to take a large-scale data.
This will be problematic for single cell RNA sequencing data analysis, since they usually comprise thousands of cells with hundreds of genes.
We will implement an algorithm that systematically speeds up the algorithm by 1) prioritizing and grouping genes to use and by 2) modifying the frequency of feature selection and clustering in the function.

* Team size: 3 Students
* POC: Hyun Jung Park

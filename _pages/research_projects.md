---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I have pursued different research interests which broadly fall under the umbrella of computer architecture.
This page shares those experiences.
Please, feel free to shoot me an email (yazakram@ucdavis.edu) if you would like to talk about any of these.

## Architectures for Secure High-Performance Computing

High performance computing (HPC) is moving away from traditional simulation and modeling to large scale computational problems involving large datasets. Sometimes this data can be sensitive, provided by third parties to HPC centers or individual researchers, and raises security concerns. This project aims to provide secure architectures focused on HPC centers keeping the performance loss to minimum.

### Related Research Works

- Enabling Design Space Exploration for RISC-V Secure Compute Environments, Ayaz Akram, Venkatesh Akella, Sean Peisert, Jason Lowe-Power. Fifth Workshop on Computer Architecture Research with RISC-V (CARRV 2021), with ISCA 2021. [paper](https://arch.cs.ucdavis.edu/papers/2021-6-11-gem5-tee)

- Performance Analysis of Scientific Computing Workloads on General Purpose TEEs, Ayaz
Akram, Anna Giannakou, Venkatesh Akella, Jason Lowe-Power and Sean Peisert, 35th IEEE Inter-
national Parallel & Distributed Processing Symposium (IPDPS 2021), May, 2021 [[arxiv version](https://arxiv.org/pdf/2010.13216.pdf)].

- Trusted Execution for High-Performance Computing, Ayaz Akram, 15th EuroSys Doctoral Workshop (EuroDW 2021), 2021. [[paper](/paper/eurodw.pdf)] [[video](https://www.youtube.com/watch?v=7CLwftj1_Hs)]

- Architectures for Secure High-Performance Computing, Ayaz Akram, Young Architect Workshop (YArch ’21) held in conjunction with the International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), April, 2021. [[paper](/papers/yarch.pdf)] [[poster](/papers/yarch_poster.jpg)] [[video](https://www.youtube.com/watch?v=cvL37bn04IQ)]

- Setting up Trusted HPC System in the Cloud, Ayaz Akram, Nov 2020, [Blog Post](https://arch.cs.ucdavis.edu/blog/2020-11-19-cloud-hpc).

- [Using Trusted Execution Environments on High Performance Computing Platforms](/papers/osew-hpc-enclaves-presentation.pdf), Ayaz Akram,
Anna Giannakou, Venkatesh Akella and Jason Lowe-Power and Sean Peisert, In Open-source En-
claves Workshop (OSEW 2019), July 2019.

## Simulation and Modeling

Computer architects mostly use simulation and modeling techniques to evaluate their research ideas. In the past, I have done comprehensive survey and comparative study of different architectural simulation tools. We also performed some work on showing how to perform more accurate [gem5](https://www.gem5.org/) simulations for x86 targets by exposing some issues with out of order cpu model and showing how to calibrate target configurations to achieve better accuracy.

Currently, I mostly focus on gem5. Recently, I have been contributing to the RISCV support in gem5 and building new DRAM cache models using gem5.
I am also involved in a project to build [gem5art](https://gem5art.readthedocs.io/en/latest/), a tool for reproducible and structured experiments with gem5 and build [gem5-resources](https://www.gem5.org/documentation/general_docs/gem5_resources/) to help researchers set-up their gem5 experiments in a short time.

### Related Research Works

- [Enabling reproducible and agile full-system simulation](https://arch.cs.ucdavis.edu/assets/papers/ispass21-gem5art.pdf), Bobby Bruce, Ayaz Akram, Hoa Nguyen,
Kyle Roarty, Mahyar Samani, Marjan Fariborz, Trivikram Reddy, Matt Sinclair, Jason Lowe-Power,
IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS 2021),
March, 2021.

- [Artifact, Reproducibility and Testing Framework for gem5](/papers/ModSim_2020_paper_19.pdf), Ayaz Akram, and et al. In Workshop
on Modeling & Simulation of Systems and Applications (ModSim’2020), August 2020.

- The gem5 Simulator: Version 20.0+, Jason Lowe-Power, Abdul Mutaal Ahmad, Ayaz Akram, and
et al., [arXiv preprint](https://arxiv.org/pdf/2007.03152.pdf), July 2020.

- gem5art: Zen and the Art of gem5 Experiments, Ayaz Akram, and et al. In gem5 Users Workshop
in conjunction with ISCA 2020, June 2020.

- X86 Linux Boot Status on gem5-19, Ayaz Akram, Mar 2020, [Blog Post](https://www.gem5.org/project/2020/03/09/boot-tests.html).

- [Validation of the gem5 Simulator for x86 Architectures](https://sc19.supercomputing.org/proceedings/workshops/workshop_files/ws_pmbss111s2-file1.pdf), Ayaz Akram, and Lina Sawalha, In
IEEE/ACM Performance Modeling, Benchmarking and Simulation of High Performance Computer
Systems (PMBS) in conjunction with Supercomputing Conference (SC19), November 2019.

- [A Survey of Computer Architecture Simulation Techniques and Tools](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8718630), Ayaz Akram, and Lina
Sawalha, In IEEE Access, May 2019.

- [FlexCPU: A Configurable Out-of-Order CPU Abstraction](https://arch.cs.ucdavis.edu/assets/papers/ispass19-flexcpu.pdf), Bradley Wang, Ayaz Akram, and Jason
Lowe-Power, IEEE International Symposium on Performance Analysis of Systems and Software
(ISPASS), March 2019.

- A Comparison of x86 Computer Architecture Simulators, Ayaz Akram and Lina
Sawalha, In ACM/IEEE Supercomputing Conference (SC16) November, 2016. [[Abstract](/papers/post233s2-file3.pdf)] [[Poster](/papers/SC16Poster_Final.pdf)]

- x86 Computer Architectural Simulators: A Comparative Study, Ayaz Akram and Lina Sawalha,
In IEEE 34th International Conference on Computer Design (ICCD), October 2016.

## Performance and Power Analysis of Instruction Set Architectures

Contemporary instruction set architectures (ISAs) and their implementations demand a revisit of the famous debate of the role of ISAs in determining the performance and energy consumption of any processor. According to different computer architects, the compiler and microarchitectural innovations have made ISAs ineffective. On contrary,  many researchers believe that there is still an important role played by ISAs to determine the performance and energy efficiency of processors. This project studies differences among various ISAs and evaluates applications' performance and energy efficiency compiled for different ISAs on diverse microarchitectures. Another goal of this project is to use machine learning techniques to correlate observed differences across ISAs to particular microarchitectural/non-microarchitectural events and ISA factors.

### Related Research Works

- [A Study of Performance and Power Consumption Differences Among Different ISAs](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8875032), Ayaz Akram,
and Lina Sawalha, In IEEE 21st Euromicro Conference on Digital System Design (DSD), August, 2019.

- A Comparative Study of ISA Multimedia Extensions for HPC, Ayaz Akram and Sajjad Rahnama, [ECS-201C Project Report](/papers/simd_perf.pdf), Spring 2019, UC Davis.

- A Study on the Impact of Instruction Set Architectures on Processors Performance, Ayaz Akram,
[Master’s Thesis](https://scholarworks.wmich.edu/cgi/viewcontent.cgi?article=2517&context=masters_theses). Url: https://scholarworks.wmich.edu/masters_theses/1519.

- [The Impact of ISAs on Performance](/papers/Ayaz_WDDD2017.pdf), Ayaz Akram and Lina Sawalha, In 14th Annual Workshop
on Duplicating, Deconstructing, and Debunking (WDDD) in conjunction with ISCA-44, June 2017.

## Microarchitectural Side Channel Attacks

### Related Research Works

- WHISPER A Tool for Run-time Detection of Side-Channel Attacks, M Mushtaq, J Bricq, MK
Bhatti, Ayaz Akram, V Lapotre, G Gogniat, P Benoit, In IEEE Access, May 2020.

- Meet the Sherlock Holmes of Side Channel Leakage: A Survey of Cache SCA Detection Techniques,
Ayaz Akram, M Mushtaq, MK Bhatti, V Lapotre, G Gogniat, In IEEE Access, April 2020.

- Sherlock Holmes of Cache Side-Channel Attacks in Intel’s x86 Architecture, Maria Mushtaq, Ayaz
Akram, Muhammad Khurram Bhatti, Usman Ali, Vianney Lapotre, and Guy Gogniat, In IEEE
Conference on Communications and Network Security (CNS), June 2019.

- Machine Learning For Security: The Case of Side-Channel Attack Detection at Run-time, Maria
Mushtaq, Ayaz Akram et al, In Proceedings of 25th IEEE International Conference on Electronics
Circuits and System (ICECS), December 2018.

- Run-time Detection of Prime+Probe Side-Channel Attack on AES Encryption Algorithm, Maria
Mushtaq, Ayaz Akram et al, In Proceedings of Global Information Infrastructure and Networking
Symposium (GIIS), October 2018.

- NIGHTs-WATCH: A Cache-based Side-channel Intrusion Detector Using Hardware Performance
Counters, Maria Mushtaq, Ayaz Akram et al, In Proceedings of the 7th International Workshop
on Hardware and Architectural Support for Security and Privacy (HASP) in conjunction with ISCA-
45, June 2018.

- Cache-Based Side-Channel Intrusion Detection using Hardware Performance Counters, Maria Mush-
taq, Ayaz Akram et al, In 16th CryptArchi Workshop, Lorient France, June 2018.

## Machine Learning for Computer Architecture

### Related Research Works

- The Tribes of Machine Learning and the Realm of Computer Architecture, Ayaz Akram, and
Jason Lowe-Power, [arXiv preprint](https://arxiv.org/pdf/2012.04105.pdf), December, 2020.

## Other Works

### Instruction Prefetching

As the pipeline depth increases to extract out more parallelism aggressively, the need for a continuous supply of fetched instructions increases as well. Relying on repeating behavior of instruction stream and pre-fetching instructions before their actual use, is one of the many used techniques to improve memory performance associated to instructions as it helps to reduce the number of Instruction cache misses and can also overlap miss latencies. Different ideas have been proposed to implement these prefetchers. This project involved studying different instruction prefetching techniques (Next line prefetchers, Return Address Stack Based Prefetching, Proactive instruction prefetch) by implementing them in gem5 simulator and comparing them with a newly proposed technique based on benchmark working set signatures. This project uses different workloads from BigData Bench suite.

**Related (Preliminary) Work**

Phase Based Instruction Prefetcher, Ayaz Akram, [ECE5950 Project Report](/papers/report.pdf), Fall 2015, WMU.


### System Mode Emulation in QEMU for OCTEON MIPS64

System emulation is a better alternative to native testing of applications on embedded hardware in terms of cost, time and management. In this project, we have extended Quick Emulator (QEMU v1.0.1) to support Cavium Octeon MIPS64 processor-based embedded systems. The performance of guest Octeon MIPS64 system is also compared against native using synthetic and applications benchmarks. My specific responsibilities in this project were to provide emulation support for devices like Interrupt Controller, Timers, Console and Ethernet Controller(e1000). I also performed experiments to evaluate and improve the performance of emulated system compared to native hardware system.

**Related Work**

Emulating an Octeon MIPS64 based Embedded System on X86 in QEMU, Muhammad Amir Mehmood, Qurrat ul Ain, Ayaz Akram, Abdul Qadeer and Abdul Waheed, In IEEE 19th International Multi-topic Conference (INMIC), December, 2016.

### Enabling Green Video Streaming over the Internet of Things

I worked on the embedded systems side of this project i.e. setting up wireless sensor nodes using stm32f4 discovery boards and Contiki OS. I worked on porting Contiki OS to the required platform and also worked on adding wifi support in Contiki for the stm32f4 discovery board based platform.

### Android-based ECG monitoring System

This project involves the development of a low power and portable ECG monitoring device based on MSP430 microcontroller and an Android Phone. The motivation behind this project was to provide a reliable solution to cardiovascular patients to help them do an independent ECG  analysis. Such solutions are cheap and easy to use in academic settings. The ECG monitoring system based on MSP430 microcontroller was fully integrated with sensing electrodes on the transmitter side. The controller converted the analog signal to a digital signal via an inbuilt analog-to-digital converter, conditioned and filtered it for transmission via a Bluetooth transceiver IC compatible with the MSP430. The real-time data was received by the smartphone and displayed in real-time.

**Related Work**

Android Based ECG Monitoring System, Ayaz Akram, Raheel Javed and Awais Ahmad, In International Journal of Science and Research (IJSR), November 2013.

### Comparative Study of Edge Detection Techniques

Edge detection in a particular image is one of the basic steps of many image processing algorithms. It is therefore important to check the fidelity of edge detection techniques.  This project provided a comparison of different edge detection schemes that fall into three main categories of edge detectors: Gradient-based edge detectors, Laplacian-based edge detectors, and Non-derivative based edge detectors. A quantitative (using Pratts figure of merit) and qualitative (using real-life images) comparison of different edge detection techniques was performed.

**Related Work**

Comparison of Edge Detectors, Ayaz Akram and Asad Ismail, In International Journal of Computer Science and Information Technology Research, October 2013. (Journal of Computer Science and Information Technology Research, October 2013.

### Others

- A Review of Memory Disambiguation, Ayaz Akram, [ECE 5950 review paper](/papers/mem_disamb.pdf), Fall 2015.
- Binary Translation Techniques, Ayaz Akram, [ECE 6970 Report](/papers/Binary_Translation.pdf), Summer I 2015.

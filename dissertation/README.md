# Dissertation

## Proforma

### Original Aims of the Project

> My project aimed to:

> 1. Provide an educational environment for children to explore video processing on the Raspberry Pi.

> 2. Provide an example to other developers in accessing the video processing capabilities of the Raspberry Pi.

> through,

> a. Determining a set of capabilities to control.

> b. Developing an API for the capabilities.

> c. Developing a visual language.

> d. Creating a development environment.

> e. Evaluating the project with a small structured used study.

### Work Completed

> I have created the first video processing educational application for the Raspberry Pi.

> I carried out performance analysis of key video processing technologies, demonstrated current limitations, developed a video mixing API and contributed to existing open source projects.

> I implemented all core work items and extended the project through:

> 1. Supporting external content sources.

> 2. Adding general-purpose computation.

> 3. Adding optimisations such as video caching.

> 4. Extending the evaluation to a large child user study (50 person) and controlled experiment (5 person), which obtained promising evidence of contribution towards learning outcomes.

## §1: Introduction

### §1.2: Background

> The Raspberry Pi is a cheap credit card sized computer, developed with the intention to provide a platform for programming experimentation and teaching of basic Computer Science in schools. Critically for this project, the hardware is particularly suited for video processing, with comparatively weak general-purpose performance. Whilst the CPU is a modest 700 Mhz, 256 Mb chip, the GPU is capable of BluRay quality playback and fast 3D processing (Upton, 2013).> There are many examples of existing educational applications for assisting with exploration of Computer Science and programming. Some have been ported to the Raspberry Pi, of which a particularly notable example is MIT’s Scratch (Maloney et al., 2010), a programming language learning environment. Scratch exposes the capabilities of the underlying machine through abstractions based on the physical environment of the user, with agents such as a cartoon cat and actions such as moving n steps. The user interacts with programmable characters whose behaviour is specified by composing blocks in a visual language.> There are currently few applications exploiting the Raspberry Pi’s video processing capabilities and no educational applications. Although the hardware has the potential to achieve strong video processing performance, the Raspberry Pi software platform is early in development and so there are high barriers to entry in creating video processing applications.

## §5: Conclusion

### §5.1: Comparison with original goals

> In the proposal, I specified the main success criterion of successful creation of sample programs in the visual language, which demonstrate video processing behaviours from a test suite of end user scenarios. Through 15 hours of user studies, involving over 50 participants, I have satisfied this criterion.
> I refined the proposal by specifying two main objectives (§1‎ .3). Objective 1 has been demonstrated through the user studies and Objective 2, providing an example to other developers in accessing the video processing capabilities, has been achieved through development of the Video API (§3‎.6.1) and open source contributions to the existing YT and PYOMXPLAYER projects (§2‎.3.2 and §3‎ .6.1).
> I completed all core work items (§2‎ .1.1) and extended the project by supporting an external content source, YouTube; by providing exploration of basic data structures through information structures in the YouTube domain; and by running a large child user study (50 person).I have evaluated the project through users studies and performance analysis. I identified the relative importance of usability problems in the system and through statistical significance testing of the controlled experiment results obtained a promising suggestion (p-level 0.07) that interaction with the system may contribute towards attainment of learning outcomes (§‎4.3.2).

### §5.2: Future work

> This project takes an alternative approach to the current market leaders by providing a domain-specific visual language representation of a user’s program next to the equivalent PYTHON code. In contrast, in products such as SCRATCH, users only interact with a domain-specific representation and have no way to see their program in a general-purpose language. This alternative multi- representation approach offers promising educational advantages, which could be explored through comparing the attainment of learning outcomes with and without the PYTHON code representation.

> Investigating usability problems in the language and editor (§4‎ .3.2.1) has identified where the most significant problems are and therefore where the usability of the system might be most beneficially improved. Furthermore, basic performance analysis of the editor has shown its behaviour needs to be optimised to meet the response needs of users.> The language and editor have been designed to support more advanced video manipulation capabilities as they become available. Since the early technological investigations (§2‎ .3.3) there have been promising developments, which may be able to provide hardware decode of video alongside hardware accelerated video manipulation.

### §5.3: The Future

> The technological expectations of children are radically changing. Such is the pace of technological change that technologies that were ground breaking for one generation become ubiquitous and taken for granted by the next. To create compelling educational products, children need to be given the ability to create programs of a comparable standard to the consumer devices they use.
> In many ways the Raspberry Pi is the spiritual successor of the BBC Micro, a platform that inspired a generation to take up Computer Science. Indeed the Raspberry Pi foundation originally sought to brand their device as its direct successor. However, whilst the BBC Micro offered compelling general-purpose performance, for example by comparison to videogame consoles of the time, the Raspberry Pi’s general-purpose performance is modest and so it is important to focus on its main hardware strength, video processing.> In this project I have created the first video processing educational application for the Raspberry Pi and broken new ground for other people to create more powerful, yet inexpensive and compelling, educational applications for the Raspberry Pi.
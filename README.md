# Detection-of-X-ray-Transients

## Introduction

### Problem Statement

To carry out operations on data, by a computer to retrieve, transform and classify information as required by building a GUI using Kivy to navigate through data and allow specific selection based on time periods and preparing a graph using Matplotlib that shows detection of transients that is displayed  when asked for a particular time period or set of data

###  Domain

#### Machine Learning

Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.
The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly.

Machine learning is closely related to computational statistics, which focuses on making predictions using computers. The study of mathematical optimization delivers methods, theory and application domains to the field of machine learning. Data mining is a field of study within machine learning, and focuses on exploratory data analysis through unsupervised learning. In its application across business problems, machine learning is also referred to as predictive analytics.

Deep learning is an artificial intelligence function that imitates the workings of the human brain in processing data and creating patterns for use in decision making. Deep learning is a subset of machine learning in artificial intelligence (AI) that has networks capable of learning unsupervised from data that is unstructured or unlabeled. Also known as deep neural learning or deep neural network.

#### Graphical User Interface

The graphical user interface is a form of user interface that allows users to interact with electronic devices through graphical icons and audio indicator such as primary notation, instead of text-based user interfaces, typed command labels or text navigation. GUIs were introduced in reaction to the perceived steep learning curve of command-line interfaces (CLIs), which require commands to be typed on a computer keyboard.

Designing the visual composition and temporal behavior of a GUI is an important part of software application programming in the area of human–computer interaction. Its goal is to enhance the efficiency and ease of use for the underlying logical design of a stored program, a design discipline named usability. Methods of user-centered design are used to ensure that the visual language introduced in the design is well-tailored to the tasks.

Kivy is a Python binding of the cross-platform GUI toolkit Qt, implemented as a Python plug-in. Kivy is free software developed by the British firm Riverbank Computing. It is available under similar terms to Qt versions older than 4.5; this means a variety of licenses including GNU General Public License (GPL) and commercial license, but not the GNU Lesser General Public License (LGPL). Kivy supports Microsoft Windows as well as various flavors of UNIX, including Linux and MacOS (or Darwin). 

Kivy implements around 440 classes and over 6,000 functions and methods including:
a substantial set of GUI widgets
classes for accessing SQL databases (ODBC, MySQL, PostgreSQL, Oracle, SQLite) 
QScintilla, Scintilla-based rich text editor widget
data aware widgets that are automatically populated from a database
an XML parser
SVG support
classes for embedding ActiveX controls on Windows (only in commercial version)

### Introduction to Transient X-ray sources

The definition of "transient" found in the dictionary reads: passing away with time; not permanent; temporary. Certain cosmic X-raysources behave in just such a manner. They seem to appear in the sky for a short time and then disappear. Some of them eventually reappear - after years or decades. The class of sources called "transients" was created to distinguish such sources as different from the more permanent, stable sources observed in the X-ray sky. It is important to remember that the object in the sky does not really disappear, just the X-ray emission we see coming from it.

There are many reasons that certain sources have this kind of "now you see me, now you don't" behavior. It is believed that sudden large changes in the accretion rate of the compact object in a binary system lie at the heart of the transient behavior. The reasons why the accretion rate may suddenly change in a big way are clear for some systems (it can be a natural cycle in the behavior of the normal star), but not clear for others. Finding a consistent explanation for the behavior of all the kinds of transient behavior observed is an active area of astronomical research.

### Source of data and dataset

The data that we are using for the project has been recorded from a satellite sent by ISRO. The satellite does its job by recording the activities happening in space and storing the data.

Scanning Sky Monitor (SSM) is one of the payloads on AstroSat [Agrawal, 2006, Singh et. al.,2014], a multiwavelength satellite to observe the Universe in the broad energy band spanning from Optical, Near-UV (NUV), Far-UV (FUV), Soft X-rays to Hard X-rays. AstroSat was launched on 28th September, 2015, by the Indian Space Research Organization. There are five payloads on-board AstroSat which are Ultra Violet Imaging Telescope UVIT, Large Area X-ray Proportional Counter LAXPC, Soft X-ray Telescope SXT, Cadmium-Zinc Telluride Imager CZTI and Scanning Sky Monitor SSM. X-ray sky is highly variable with a number of transient X-ray sources, most of which remain below detection threshold and brighten up once a while. It is necessary to keep looking for any such transient phenomenon of already known X-ray sources in addition to having a finite possibility of detecting new transient sources.The database we are using for the project is the data recorded by this very satellite. It is in the form of FITS file. There are five payloads on the satellite Astrosat. We receive the data from one of the payloads - Scanning Sky Monitor (SSM)We handle the data that are in FITS format. FITS (Flexible Image Transport System) is a portable file standard widely used in the astronomy community to store images and tables.  

### About the project 

The project includes organizing the data and building a GUI to surf through the data and allow specific selection based on time periods. We are using Kivy to build the GUI.  After the GUI is built, a back-end will be prepared using python programming language. The end result is a graph that shows detection of a transient. The graph is built using Matplotlib.

## Literature Review

Aarran Shaw, Phil Charles [1]:X-ray astronomy is impossible at the surface of the Earth – our atmosphere absorbs this part of the electromagnetic spectrum. Development of X-ray astronomy had to wait until X-ray detectors could be launched into space. Cosmic X-ray astronomy began in 1962 with the discovery of the first extrasolar X-ray source, Sco X-1, using rocket-borne instruments, a technology that was to dominate during the rapid advance of the field during the rest of the 1960s. Rocket flights offer only limited observation time, between 3 and 5 minutes per flight, but there were enough of them offering regular sampling of the galactic plane to identify, in May 1967, a source that had not been there when the region was last explored in 1965, and which had disappeared when its position was scanned again in September 1967. The first transient X-ray source, Cen X-2, had been discovered.

J. R. Callingham, S. A. Farrell, B. M. Gaensler, G. F. Lewis and M. J. Middleton [2]:We present detailed analysis of the transient X-ray source 2XMMi J003833.3+402133 detected by XMM-Newton in 2008 January during a survey of M31. The X-ray spectrum is well fitted by either a steep power law plus a blackbody model or a double blackbody model. Prior observations with XMM-Newton, Chandra, Swift, and ROSAT spanning 1991-2007, as well as an additional Swift observation in 2011, all failed to detect this source. No counterpart was detected in deep optical imaging with the Canada-France-Hawaii Telescope down to a 3σ lower limit of g = 26.5 mag. This source has previously been identified as a black hole X-ray binary in M31. While this remains a possibility, the transient behavior, X-ray spectrum, and lack of an optical counterpart are equally consistent with a magnetar interpretation for 2XMMi J003833.3+402133. The derived luminosity and blackbody emitting radius at the distance of M31 argue against an extragalactic location, implying that if it is indeed a magnetar it is located within the Milky Way but 22° out of the plane. The high Galactic latitude could be explained if 2XMMi J003833.3+402133 were an old magnetar, or if its progenitor was a runaway star that traveled away from the plane prior to going supernova.

P. Romano, E. Bozzo, P. Esposito, B. Sbarufatti, F. Haberl, G. Ponti, P. D’Avanzo, L. Ducci, A. Segreto, C. Jin, N. Masetti, M. Del Santo, S. Campana and V. Mangano[3]:Supergiant fast X-ray transients (SFXTs) are high mass X-ray binaries (HMXBs) hosting a neutron star and an OB supergiant companion. We examine the available Swift data, as well as other new or archival/serendipitous data, on three sources: IGR J17407−2808, 2XMM J185114.3−000004, and IGR J18175−2419, whose X-ray characteristics qualify them as candidate SFXT, to explore their properties and test whether they are consistent with an SFXT nature. Since IGR J17407−2808 and 2XMM J185114.3−000004 triggered the Burst Alert Telescope on board Swift, the Swift data enable us to provide their first arcsecond localisations, leading to an unequivocal identification of the source CXOU J174042.0−280724 as the soft X-ray counterpart of IGR J17407−2808, as well as their first broadband spectra, which can be fit with models generally describing accreting neutron stars in HMXBs. While still lacking optical spectroscopy to assess the spectral type of the companion, we propose 2XMM J185114.3−000004 as a very strong SFXT candidate. The nature of IGR J17407−2808 remains, instead, more uncertain. Its broadband properties cannot exclude the fact that the emission originates from either an HMXB (and in that case, an SFXT) or, more likely, a low-mass X-ray binary. Finally, based on the deep non-detection in our XRT monitoring campaign and a careful reanalysis of the original INTEGRAL data in which the discovery of the source was first reported, we show that IGR J18175−2419 is likely a spurious detection.

## Software and hardware requirements

### Software:

OS: Linux
PyTorch:PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing. It is primarily developed by Facebook's AI Research lab. It is free and open-source software released under the Modified BSD license
NumPy:NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 
Matplotlib: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+
Kivy: Kivy is a free and open source Python library for developing mobile apps and other multitouch application software with a natural user interface (NUI). It is distributed under the terms of the MIT License, and can run on Android, iOS, GNU/Linux, OS X, and Windows.
KERAS: Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML. Designed to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible
CUDA - version 3: CUDA is a parallel computing platform and application programming interface model created by Nvidia. It allows software developers and software engineers to use a CUDA-enabled graphics processing unit for general purpose processing – an approach termed GPGPU.

### Hardware:

Processor – Intel Core i5 and above 
Hard Disk – 512GB
Graphics card – GTX 980
Memory – 8GB RAM

## System Development Process

Learning required tools:
Given some time to require the tools for the project development. These tools included AI, ML, Matplotlib,Kivy,etc

Data collection:
Collect data and store it accordingly.

Data organization:
The acquired data was then organized into proportionate folders for the training and testing purpose.

GUI development:
Develop a GUI for display and operation purpose of data.

Data training and graph plotting:
The loaded data is then trained using CNN and then the same is validated too. The final detection graph of the transient is also plotted.

Data testing:
The trained algorithm is then tested. The accuracy is calculated in this phase.

Extracting results:
The prediction of the testing image is done and checked if the algorithm can give out the accurate result.

## Methodology

### Iterative Model

The Iterative SDLC model does not need the full list of requirements before the project starts. The development process may start with the requirements to the functional part, which can be expanded later. The process is repetitive, allowing to make new versions of the product for every cycle. Every iteration (which last from two to six weeks) includes the development of a separate component of the system, and after that, this component is added to the functional developed earlier. Speaking with math terminology, the iterative model is a realization of the sequential approximation method; that means a gradual closeness to the planned final product shape.

### Software Technologies Used

#### Front-end

Kivy
Kivy is a free and open source Python library for developing mobile apps and other multitouch application software with a natural user interface (NUI). It is distributed under the terms of the MIT License, and can run on Android, iOS, GNU/Linux, OS X, and Windows.
Kivy is the main framework developed by the Kivy organization, alongside Python for Android, Kivy iOS, and several other libraries meant to be used on all platforms. In 2012, Kivy got a $5000 grant from the Python Software Foundation for porting it to Python 3.3. Kivy also supports the Raspberry Pi which was funded through Bountysource. 
The framework contains all the elements for building an application such as:
extensive input support for mouse, keyboard, TUIO, and OS-specific multitouch events,
a graphic library using only OpenGL ES 2, and based on Vertex Buffer Object and shaders,
a wide range of widgets that support multitouch,
an intermediate language (Kv) used to easily design custom widgets.
Kivy is the evolution of the PyMT project, and is recommended for new projects. 

#### Back-end

Python
Python is a widely used general-purpose, high-level programming language.
Python allows programming in Object-Oriented and Procedural paradigms.
Python programs generally are smaller than other programming languages like Java. Programmers have to type relatively less and indentation requirement of the language, makes them readable all the time.
Python language is being used by almost all tech-giant companies like – Google, Amazon, Facebook, Instagram, Dropbox, Uber… etc.

#### Visualization

Matplotlib
Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+. There is also a procedural "pylab" interface based on a state machine (like OpenGL), designed to closely resemble that of MATLAB, though its use is discouraged.[3] SciPy makes use of Matplotlib.

## Testing

We developed the backend code that for plotting the graph for the detection of transients and also for the time converter (MJD to ms). Testing the code gave us no error and thus the code was executed properly with accurate answers. Thus, the testing of the code we built has been successfully acquired legitimate accuracy as the result.

## Results and discussions

We developed a converter that converts MJD to JD, Datetime and to milliseconds. This converter is necessary to plot a light curve for each stare.
We developed a GUI for the front end using Kivy which we had to program using Python and Kivy language. This GUI helps us course through the files easily since the previous approach required to type commands in the command prompt for every action. This GUI will help us course through the various files and plot a light curve where it is required.

## Conclusion

The following project work has been completed:
The project has been selected and the work regarding the same has been started.
Learning the required tools like Matplotlib, Kivy, etc has been completed.
The data has been collected.
The collected data has been organized.
The draft of GUI has been made. Enhancing of the draft GUI is currently under process.

Therefore, the project has been completed up to analysis and design as it was meant to and the required amount of work has been accomplished.

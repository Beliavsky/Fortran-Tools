### Fortran Tools

(C) indicates a commercial product

* [Automatic Documentation](#automatic-documentation)
* [Build Tools](#build-tools)
* [Compilers](#compilers)
* [Emacs Plugins](#emacs-plugins)
* [Fixed to Free Source Form Conversion](#fixed-to-free-source-form-conversion)
* [Graphical User Interfaces](#graphical-user-interfaces)
* [Indentation and Formatting](#indentation-and-formatting)
* [Interoperability](#interoperability)
* [Parallel Programming](#parallel-programming)
* [Plotting](#plotting)
* [Preprocessors](#preprocessors)
* [Profiling](#profiling)
* [Refactoring](#refactoring)
* [Static Analysis](#static-analysis)
* [Text Editors, Integrated Development Environments, and Plugins](#text-editors-integrated-development-environments-and-plugins)
* [Translation from Fortran](#translation-from-fortran)
* [Translation to Fortran](#translation-to-fortran)
* [Unclassified](#unclassified)
* [Unit Testing](#unit-testing)

### Automatic Documentation
[Doxygen](https://github.com/doxygen/doxygen): generates an on-line documentation browser (in HTML) and/or an off-line reference manual (in LaTeX) from a set of documented source files. There is also support for generating output in RTF (MS-Word), PostScript, hyperlinked PDF, compressed HTML, DocBook and Unix man pages. 

[f90tohtml](https://github.com/degeron/f90tohtml): Perl script to convert fortran source files into a hyperlinked web site

[ford](https://github.com/Fortran-FOSS-Programmers/ford): Automatically generates FORtran Documentation from comments within the code, from Fortran-FOSS-Programmers

### Build Tools
[easy](https://github.com/urbanjost/easy): steps to setup a GitHub repository with fpm, and GitHub actions including ford(1) documentation and unit tests, by urbanjost

[FCM](https://github.com/metomi/fcm): modern Fortran build system + wrappers to Subversion for scientific software development, from metomi

[FoBiS.py, Fortran Building System for poor people](https://github.com/szaghi/FoBiS): automatic parsing of files for dependency-hierarchy creation in case of use and include statements, and automatic building of all programs found into the root directory parsed or only a specific selected target, by szaghi et al.

[fortdepend](https://github.com/ZedThree/fort_depend.py): python script to generate dependencies for Fortran projects, by ZedThree

[fortrandep](https://github.com/orvedahl/fortrandep): Python tool to determine Makefile dependencies for a Fortran project, by Ryan Orvedahl

[Fortran Package Manager (fpm)](https://github.com/fortran-lang/fpm): package manager and build system for Fortran, from fortran-lang. Documentation is [here](https://awvwgk.github.io/fpm-docs/en/index.html)

[Fortran Package Manager for Visual Studio](https://github.com/everythingfunctional/fpm-for-VS): adds options and menu entries for building, running and testing your Fortran project using the Fortran Package Manager (fpm), by everythingfunctional

[fpm](https://github.com/fortran-lang/fpm): Fortran Package Manager (fpm) is a package manager and build system for Fortran, from fortran-lang

[jams_makefile](https://github.com/mcuntz/jams_makefile): provides a portable, versatile way of compiling Fortran, C, C++, and mixed projects, by mcuntz

[makedepf90](https://github.com/outpaddling/makedepf90): generates make dependencies for Fortran code, by Erik Edelman

[Makefile-maker](https://github.com/Garl4nd/Makefile-maker): automatic Fortran makefile maker, by Garl4nd. The program first scans all Fortran files for imports of other source files and creates a directed dependency graph, where each vertex represents the file and an arrow from A to B correspond to the File A depending on B.

[makemake](https://github.com/janberges/makemake): Python script that generates Makefiles for modular Fortran programs, by Jan Berges. It recursively searches the working directory for .f90 files and determines their dependencies.

[meson](https://github.com/mesonbuild/meson): next-generation build system

[MinGW package for the Fortran package manager](https://github.com/awvwgk/mingw-w64-fpm-pkgbuild): provides package build instructions for the Fortran package manager (fpm) compatible with the MSYS2 toolchain. This project provides prebuilt MinGW packages at the release page.

[mkhelper](https://github.com/skosukhin/mkhelper): collection of utilities to be used with GNU Autoconf and GNU Make for building Fortran projects, by skosukhin

[run-fortran](https://github.com/lycantropos/run-fortran): sorts Fortran files based on modules definitions and usages, by lycantropos

[xmake](https://github.com/xmake-io/xmake): lightweight cross-platform build utility based on Lua. It uses xmake.lua to maintain project builds. The two Fortran compilers supported are gfortran and ifort.

### Compilers
[Absoft](https://www.absoft.com/): designed to build code in the most efficient way possible, the Pro Fortran compiler utilizes advanced technology. This includes load balancing, AVX and OpenMP 3.1 support, AMDAL HPC scientific and engineering math library,  Parallel versions of Lapack and BLAS libraries, Fast Data Visualization, and much more. (C)

[AMD Optimizing C/C++/Fortran Compiler (AOCC)](https://developer.amd.com/amd-aocc/): high performance, production quality code generation tool. The AOCC environment provides various options to developers while building and optimizing C, C++, and Fortran applications targeting 32-bit and 64-bit Linux® platforms.

[Arm Fortran Compiler](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-compiler-for-linux/arm-fortran-compiler): tailored for server, HPC, and scientific codes, with support for Fortran and OpenMP. The compiler is built on the open source Flang front-end, and the LLVM‑based optimization and code generation back-end. (C)

[f18-llvm-project](https://github.com/flang-compiler/f18-llvm-project): fork of llvm/llvm-project for f18. In sync with f18-mlir and f18.

[flang](https://github.com/flang-compiler/flang): flang (also known as "Classic Flang") is an out-of-tree Fortran compiler targeting LLVM. It is an open-sourced version of pgfortran, a commercial Fortran compiler from PGI/NVIDIA

[fortran-ios](https://github.com/ColdGrub1384/fortran-ios): script that acts like a Fortran compiler that uses Flang to build sources for iOS arm64, by Emma Cold

[Fortran kernel for Jupyter with Coarray support](https://github.com/sourceryinstitute/jupyter-CAF-kernel): from sourceryinstitute

[gfortran](https://gcc.gnu.org/wiki/GFortran): GNU Fortran project, developing a free Fortran 95/2003/2008 compiler for GCC, the GNU Compiler Collection. The gfortran development effort uses an open development environment in order to attract a larger team of developers and to ensure that gfortran can work on multiple architectures and diverse environments. Gfortran installation on various platforms is discussed at [fortran-lang](https://fortran-lang.org/learn/os_setup/install_gfortran). For Windows there is [Quickstart Fortran](https://fortran-lang.discourse.group/t/quickstart-fortran-installer-for-windows/2270).

[gfortran-for-macOS](https://github.com/fxcoudert/gfortran-for-macOS): gfortran for macOS Intel, by fxcoudert.

[g95](https://www.g95.org/downloads.shtml): stable, production Fortran 95 compiler available for multiple cpu architectures and operating systems. Parts of the F2003 and F2008 standards have been implemented

[HPE Cray Programming Environment](https://buy.hpe.com/us/en/software/high-performance-computing-software/high-performance-computing-software/hpe-cray-programming-environment/p/1012707351): fully integrated software suite with compilers, tools, and libraries designed to improve programmer productivity, application scalability, and performance. Besides support for multiple programming languages, programming models, compilers, I/O libraries, and scientific libraries, the suite offers a variety of supported tools for areas including debugging, performance analysis, workload management, and environment setup. (C)

[IBM Fortran](https://www.ibm.com/products/fortran-compiler-family): XL Fortran for AIX®: Build optimized and tuned Fortran applications on IBM AIX.
<br />XL Fortran for Linux: Optimize your HPC and cognitive Fortran applications for Linux on IBM Power® Systems, including the POWER9™ processors.
<br />VS Fortran: Develop efficient applications for IBM Z® and z/VM® with IBM VS FORTRAN. (C)

[Intel Fortran](https://software.intel.com/content/www/us/en/develop/tools/oneapi/components/fortran-compiler.html): built on a long history of generating optimized code that supports industry standards while taking advantage of built-in technology for Intel® Xeon® Scalable processors and Intel® Core™ processors. Staying aligned with Intel’s evolving and diverse architectures, the compiler now supports GPUs.

[Lahey Fortran Professional v7.9 Windows](https://www.lahey.com/): combines the 32/64-bit LGF Rainier compiler with the classic Lahey/Fujitsu LF95 compiler. LGF Rainier has full Fortran 95/90/77 compliance with extensive support for the Fortran 2003 and 2008 standards. (C)

[Lahey/GNU Fortran - Rainier Edition Windows 32 & 64-bit](https://www.lahey.com/): full Fortran 95/90/77 compliance with extensive support for the Fortran 2003 and 2008 standards; targets 32 and 64-bit Windows. Includes the automatic-parallelizing GFortran compiler, Visual Studio 2015 Shell (compatible with VS2019 & VS2017), Lahey's Exclusive Visual Studio Fortran support, Winteracter WiSK Graphics package, and more. (C)

[lfortran](https://github.com/lfortran/lfortran): modern open-source (BSD licensed) interactive Fortran compiler built on top of LLVM. It can execute user's code interactively to allow exploratory work (much like Python, MATLAB or Julia) as well as compile to binaries with the goal to run user's code on modern architectures such as multi-core CPUs and GPUs.

[Mercurium](https://github.com/bsc-pm/mcxx):  C/C++/Fortran source-to-source compilation infrastructure aimed at fast prototyping developed by the Programming Models group at the Barcelona Supercomputing Center. Mercurium is used, together with the Nanos++ Runtime Library, to implement the OmpSs programming model. Both tools provide also an implementation of OpenMP 3.1.

[NAG](https://www.nag.com/content/nag-fortran-compiler): robust and highly tested Fortran compiler, valued for its checking capabilities and detailed error reporting. Available on Linux, Microsoft Windows and Mac OS X, including Apple Silicon Macs. (C)

[NEC](https://www.nec.com/en/global/solutions/hpc/sx/tools.html): Fortran compiler conforms to the Fortran-2003 standard (ISO/IEC 1539-1:2004) and supports many features from Fortran-2008 (ISO/IEC 1539-1:2010). NEC has more than 30 years’ experience in compiler technology for high-end vector machines, and these newly developed compilers will be based on this experience and support all the optimization strategies that NEC compilers are known for. (C)

[NVIDIA HPC Software Development Kit](https://developer.nvidia.com/hpc-sdk): NVIDIA HPC SDK C, C++, and Fortran compilers support GPU acceleration of HPC modeling and simulation applications with standard C++ and Fortran, OpenACC® directives, and CUDA®. GPU-accelerated math libraries maximize performance on common HPC algorithms, and optimized communications libraries enable standards-based multi-GPU and scalable systems programming.

[ompi](https://github.com/open-mpi/ompi): open source Message Passing Interface (MPI) implementation that is developed and maintained by a consortium of academic, research, and industry partners

[Oracle Developer Studio Fortran compiler, f95](https://docs.oracle.com/cd/E77782_01/html/E77790/aevbb.html): provides the following features and extensions: Optimized automatic and explicit loop parallelization for multiprocessor systems, VAX/VMS Fortran extensions, OpenMP parallelization directives, and global, peephole, and potential parallelization optimizations produce high performance applications. (C)

[ROSE](https://github.com/rose-compiler/rose): compiler infrastructure to build source-to-source program transformation and analysis tools for large-scale C (C89 and C98), C++ (C++98 and C++11), UPC, Fortran (77/95/2003), OpenMP, Java, Python and PHP applications

[Silverfrost Fortran FTN95](https://www.silverfrost.com/12/ftn95/ftn95_feature_details.aspx): full Fortran 95 standards compliant compiler, capable of producing fast executables for Win32 and for Microsoft .NET. FTN95 ships with the world's best runtime checking and a great range of supporting software. There is a free [personal edition](https://www.silverfrost.com/default.aspx?id=32). (C)

[xcc-project](https://github.com/JianpingZeng/xcc-project): C/C++/Fortran compiler collection written in Java, by JianpingZeng

### Emacs Plugins
[align-f90](https://github.com/jannisteunissen/align-f90): alignment support for Fortran 90 in Emacs, by jannisteunissen

[Emacs](https://github.com/emacs-mirror/emacs): extensible, customizable, free text editor. Download [here](https://www.gnu.org/software/emacs/download.html).

[f90-iface](https://github.com/wence-/f90-iface): Emacs-based browser for Fortran 90 generic interfaces, by wence- and monnier

[f90-namelist-mode](https://github.com/ZedThree/f90-namelist-mode): extension to Emacs f90-mode to handle Fortran namelists, by ZedThree

[fortpy](https://github.com/rosenbrockc/fortpy): Python Emacs Intellisense and Unit Testing Support for Fortran, by rosenbrockc and wsmorgan

[fortpy-el](https://github.com/rosenbrockc/fortpy-el): Lisp package for emacs that integrates with fortpy to provide context-specific auto-completion and intellisense for Fortran 2003, including object oriented constructs, by rosenbrockc

[fortran-index-args](https://github.com/ffevotte/fortran-index-args): numbers subroutine arguments and shows indexes before each argument in the list, by ffevotte. Such indexes are just displayed on screen, but do not modify the underlying buffer.

[Fortran layer](https://github.com/ciappi/fortran-layer): basic Spacemacs configuration layer for the Fortran language, by Marco Scopesi

[Fortran-tags](https://github.com/raullaasner/fortran-tags): Fortran source code indexing tool with the focus of finding the definition of any variable or procedure, by raullaasner et al. It is able to correctly locate all global and local variables and is expected to work with any Fortran 2008 conforming code with some exceptions as mentioned below.

[fprettify.el](https://github.com/osada-yum/fprettify.el): interface to fprettify, auto-formatter for modern Fortran code, by osada-yum

### Fixed to Free Source Form Conversion
[f2f](https://github.com/MRedies/f2f_mirror): Perl script which does much of the tedious work of converting FORTRAN 77 source code into modern Fortran, by Colby Lemon

[f77tof90](https://github.com/mattdturner/f77tof90): Python script that reads in a Fortran 77 (.f or .F) fixed form file and converts it to a free form Fortran 90 file (.f90 or .F90), by mattdturner. It was successfully used to convert a legacy codebase (over 400 .f/.F files and millions of lines of code) from Fortran 77 to Fortran 90.

[FORTRAN77_to_Fortran90](https://github.com/Koushikphy/FORTRAN77_to_Fortran90): convert old fixed source FORTRAN 77 code to free form Fortran 90 code, by Koushikphy

[fortran-legacy-tools](https://github.com/ylikx/fortran-legacy-tools): tools to deal with Fortran code: fixed to free source form converter, upper- to lowercase converter, formatter for variable declarations, by ylikx

[freestyle](https://github.com/bast/freestyle): script to convert fixed form Fortran files (written in Fortran 77) and header files to free form, by bast

[GConvert](https://github.com/GeorgeTsikas/GConvert): program to convert fixed form Fortran into code that works as fixed or free form, by GeorgeTsikas.

[to_f90](https://github.com/jbdv-no/to_f90): Alan Miller's tool for converting Fortran 77 code to free-form Fortran 90 code, from jbdv-no

### Graphical User Interfaces
[EGGX/ProCALL](https://www.ir.isas.jaxa.jp/~cyamauch/eggx_procall/): X11 graphics library for C, C++ and FORTRAN created to achieve simplicity. One can easily create 2D graphics on the X Window System by using BASIC-style drawing functions. 

[GINO](http://gino.co.uk/): high-end feature-rich API for creating complex 2D and 3D graphics and GUI applications. The GINO products are available for Fortran under Windows and Linux. (C)

[gtk-fortran](https://github.com/vmagnin/gtk-fortran): cross-platform library to build Graphical User Interfaces (GUI), by Vincent Magnin et al. Gtk-fortran is a partial GTK / Fortran binding written in Fortran, thanks to the ISO_C_BINDING module for interoperability between C and Fortran.

[Winteracter](http://winteracter.com/): GUI toolset for the Fortran programming language. It consists of various visual development tools and a substantial subroutine library. Several Fortran compilers are supported. (C)

### Indentation and Formatting
[ajt-fortran.vim](https://github.com/robertodr/ajt-fortran.vim): port of Ajit J. Thakkar's Vim indent script

[findent](https://github.com/MFTabriz/findent): indent and convert Fortran sources, by wvermin and MFTabriz

[FortranIndent](https://github.com/Kairzhan/FortranIndent): tools to indent Fortran 90 sources, from Kairzhan

[fprettify](https://github.com/pseewald/fprettify): auto-formatter for modern Fortran code that imposes strict whitespace formatting, written in Python, by pseewald

[IndentPatternFortran](https://github.com/JHenneberg/IndentPatternFortran): general indentation patterns for Fortran, by JHenneberg

### Interoperability
[Cython fortran-file](https://github.com/cphyc/cython_fortran_file): fast and easy reader for record-based binary format, as written by Fortran, by Corentin Cadiou

[F2x](https://github.com/DLR-SC/F2x): versatile, template-based Fortran wrapper written in Python. Compared to the popular tool f2py it comes with two important differences: a full Fortran parser based on the work by the OpenFortranParser, and a very flexible code generation backend that uses Jinja2 templates.

[f90wrap](https://github.com/jameskermode/f90wrap): Fortran 90 to Python interface generator with derived type support, by jameskermode et al.

[FORTRAN format interpreter for Python (py-fortranformat)](https://github.com/brendanarnold/py-fortranformat): Generates text from a Python list of variables or will read a line of text into Python variables according to the FORTRAN format statement passed, by Brendan Arnold and michaelackermannaiub

[FortranNamelist](https://github.com/jonathanschilling/FortranNamelist): Java reading class for Fortran namelists, by Jonathan Schilling

[Fortran Namelist Reader](https://github.com/scivision/fortran-namelist): Python and Matlab readers for Fortran namelist => dict / struct, from scivision

[fpydemo](https://github.com/banskt/fpydemo): demonstration of packaging a command line tool written in Python and Fortran, by Saikat Banerjee

[gfort2py](https://github.com/rjfarmer/gfort2py): library to allow calling Fortran code compiled with gfortran from Python 2.7 or Python 3, by Robert Farmer and Ondřej Čertík

[shroud](https://github.com/LLNL/shroud): creates a Fortran or Python interface to a C or C++ library, from LANL. It can also create a C API for a C++ library.

[vecLibFort](https://github.com/mcg1969/vecLibFort): lightweight but flexible "shim" designed to rectify the incompatibilities between the Accelerate/vecLib BLAS and LAPACK libraries shipped with Mac OS X and FORTRAN code compiled with modern compilers such as GNU Fortran, by Michael C. Grant and Robert Huston

### Parallel Programming
[allgebra](https://github.com/ricosjp/allgebra): docker images for developing C++ and Fortran HPC programs, by termoshtt and t-hishinuma

[hipfort](https://github.com/ROCmSoftwarePlatform/hipfort): Fortran Interface For GPU Kernel Libraries

[gpufort](https://github.com/ROCmSoftwarePlatform/gpufort): source-to-source translation tool for CUDA Fortran and Fortran+X in the spirit of [hipify](https://github.com/ROCm-Developer-Tools/HIPIFY)

[mpich](https://github.com/pmodels/mpich): high-performance and widely portable implementation of the
MPI-3.1 standard from the Argonne National Laboratory

[Omni Compiler](https://github.com/omni-compiler/omni-compiler): compiler for code including XcalableMP, XcalableACC, and OpenACC directives. The base languages supported by Omni Compiler are C language (C99) and Fortran 2008 in XcalableMP, and C language (C99) in XcalableACC and OpenACC.

[OpenCoarrays](https://github.com/sourceryinstitute/opencoarrays): supports Fortran 2018 compilers by providing a parallel application binary interface (ABI) that abstracts away the underlying parallel programming model, which can be the Message Passing Interface (MPI) or OpenSHMEM, 
from sourceryinstitute

### Plotting
[accis](https://github.com/ihutch/accis): plotting and graphics library by Ian Hutchinson. Related project: [PLOTTRACES](https://github.com/ihutch/PLOTTRACES)

[asgl](https://github.com/salilab/asgl): produces a PostScript or Encapsulated PostScript file that can contain scatter plots, line plots, histograms, 2D density plots, and/or bond-and-stick plots of molecules, by Andrej Šali

[CHART_COUPE](https://github.com/meom-group/CHART_COUPE): Fortran plotting package based on NCL libraries, tuned for geophysical numerical model output, from meom-group

[DISLIN](https://www.dislin.de/): high-level plotting library for displaying data as curves, polar plots, bar graphs, pie charts, 3D-color plots, surfaces, contours and maps, available for several C, C++, Fortran 77 and Fortran 90/95 compilers on the operating systems Unix, Linux, FreeBSD, Windows, Mac OSX and MS-DOS. The DISLIN distributions can be used freely without any restrictions. Access to the source code and a preferred support is available via a contract.

[fplot](https://github.com/jchristopherson/fplot): provides a convenient interface for plotting with gnuplot, by jchristopherson

[fortplot](https://github.com/asarkar2/fortplot): plot module for Fortran so that plotting can be done in real time (on the fly), by Anjishnu Sarkar

[giza](https://github.com/danieljprice/giza): 2D scientific plotting library built on cairo, by Daniel Price et al. Provides uniform output to pdf, ps, png and X-Windows. Written in C with no dependencies (other than cairo) as a direct replacement for PGPLOT.

[gnufor2](https://bitbucket.org/alberto743/gnufor2/src/master/): Fortran 90 module by Alexey Kuznetsov with subroutines for plotting data, including 2D, 3D plots, surfaces, polar coordinates, and histograms. It is a modification of the [GNUFOR](https://people.math.sc.edu/Burkardt/f_src/gnufor/gnufor.html) interface written by John Burkardt.

[gnuplotfortran](http://gnuplotfortran.sourceforge.net/): Fortran 95 gnuplot interface for some Unix-like OS'es, by Madhusudan Singh. This provides some routines that enables direct access of a child gnuplot session from a Fortran 95 program. [fortranposix](https://sourceforge.net/projects/fortranposix/) must be installed.

[graffer](https://github.com/jtappin/graffer): interactive tool for generating plots of data and/or functions, by James Tappin. The original graffer was an IDL program. This version provides most of the same functionality in a Fortran program using gtk-fortran and plplot for the GUI and plotting respectively. To display functions gdl (gnudatalanguage) or IDL is required.

[M_calcomp](https://github.com/urbanjost/M_calcomp): old graphics library used in conjunction with M_draw for work with old codes, by urbanjost. The CALCOMP library is a simple set of FORTRAN callable graphic routines that allows users to quickly construct plots.

[M_slices](https://github.com/urbanjost/M_slices): basic slice plot module based on M_draw(3f) and built using fpm, by urbanjost. This version requires X11 Windows.

[MUESLI](https://perso.univ-rennes1.fr/edouard.canot/muesli/): numerical and graphical library, written mainly in Fortran 95, by Édouard Canot. Fortran Muesli Library contains all necessary materials to numerically work with a dynamic array (dynamic in size, type and structure), called mfArray. Fortran Graphics Library contains graphics routines which use the mfArray objects.

[ogpf](https://github.com/kookma/ogpf): Object-Based Interface to gnuplot from Fortran, by kookma

[PG2PLplot](https://github.com/AstroFloyd/PG2PLplot): facilitate the transition from Fortran code linked against [PGPlot](https://sites.astro.caltech.edu/~tjp/pgplot/) to linking it against [PLplot](http://plplot.sourceforge.net/), which is open source and maintained. Currently, many PGPlot routines are included, but the code is by no means exhaustive.

[PGPLOT](https://sites.astro.caltech.edu/~tjp/pgplot/) PGPLOT Graphics Subroutine Library is a Fortran- or C-callable, device-independent graphics package for making simple scientific graphs, by Tim Pearson. It is intended for making graphical images of publication quality with minimum effort on the part of the user. For most applications, the program can be device-independent, and the output can be directed to the appropriate device at run time.

[plotterf90](http://www.netlib.org/graphics/plotterf90.tgz): graphics subroutine library producing Postscript, by Masao Kodama

[Plotutil](https://github.com/Roninkoi/Plotutil): uses gnuplot to draw plots from data files, by Roninkoi. Has array handling utils and code for sorting and line fitting.

[PLplot](http://plplot.org/): can be used to create standard x-y plots, semi-log plots, log-log plots, contour plots, 3D surface plots, mesh plots, bar charts and pie charts. Multiple graphs (of the same or different sizes) may be placed on a single page, and multiple pages are allowed for those device formats that support them. C library with bindings to Fortran 2003 and many other languages.

[PlPlotLib](https://github.com/zoziha/PlPlotLib): wrapper for PlPlot inspired by the interface of matplotlib, by zoziha. It is intended to fill the need for rapid feedback while developing numerical simulations, and does not replace more sophisticated packages such as matplotlib or even direct use of PlPlot.

[pltFor](https://github.com/DamienMinenna/pltFor): Fortran-Python interface library by Damien Minenna to plot figures directly in Fortran, by calling Matplotlib 

[PyFerret](https://github.com/NOAA-PMEL/PyFerret): Ferret is an interactive computer visualization and analysis environment designed to meet the needs of oceanographers and meteorologists analyzing large and complex gridded data sets, from NOAA/PMEL. It runs on recent Unix and Mac systems, using X windows for display. PyFerret, introduced in 2012, is a Python module wrapping Ferret.

[pyplot-fortran](https://github.com/jacobwilliams/pyplot-fortran): generate plots from Fortran using Python's matplotlib.pyplot, by Jacob Williams

[SPLASH](https://github.com/danieljprice/splash): visualisation tool for Smoothed Particle Hydrodynamics (SPH) simulations in one, two and three dimensions, developed mainly for astrophysics, by Daniel Price et al. It uses a command-line menu but data can be manipulated interactively in the plotting window. SPLASH can also be used as a standalone plotting tool for any kind of tabulated or image data from ascii, csv or .fits files.

### Preprocessors
[f90 do nest](https://github.com/hattom/f90_do_nest): Python script to generated deeply nested do loops in Fortran, by Thomas Hayward-Schneider. It will generate "classical" nested do/enddo in f90code.F90 and also a do concurrent version in f90code_conc.F90.

[FMacro](https://github.com/hsnyder/FMacro): template preprocessor for Fortran, by Harris Snyder. Aims to address Fortran's lack of support for generic programming with a simple preprocessor, modeled after some of the language committee's early ideas for a template language feature, to be included in a future Fortran standard.

[fortiel](https://github.com/Jhuighuy/fortiel): Fortran preprocessor and metaprogramming engine, by Jhuighuy

[fypp](https://github.com/aradi/fypp): Python-powered preprocessor, by aradi. It can be used for any programming languages but its primary aim is to offer a Fortran preprocessor, which helps to extend Fortran with condititional compiling and template metaprogramming capabilities

[prep](https://github.com/urbanjost/prep): Fortran pre-processor written in Fortran, by urbanjost

### Profiling
[Caliper](https://github.com/LLNL/Caliper): library to integrate performance profiling capabilities into applications, from LANL. To use Caliper, developers mark code regions of interest using Caliper's annotation API. Applications can then enable performance profiling at runtime with Caliper's configuration API.

[HPCToolkit](http://hpctoolkit.org/): integrated suite of tools for measurement and analysis of program performance on computers ranging from multicore desktop systems to the nation's largest supercomputers. By using statistical sampling of timers and hardware performance counters, HPCToolkit collects accurate measurements of a program's work, resource consumption, and inefficiency and attributes them to the full calling context in which they occur. 

[timemory](https://github.com/NERSC/timemory): performance measurement and analyis package with modular and reusable components which can be used to adapt to any existing C/C++ performance measurement and analysis API and is arbitrarily extendable by users within their application, from NERSC

### Refactoring
[Fortran Language Program Remodeling system (FLPR)](https://github.com/lanl/FLPR):  C++17 library for manipulating Fortran source code, from LANL. This package contains a "best effort" Fortran 2018 input parser for fixed and free form inputs, data structures for manipulating source code at the program unit, statement, and physical line levels, and sample applications that illustrate usage and provide some ideas as to how you could use the library.

[Glasgow Fortran Source-to-Source Compiler (RefactorF4Acc)](https://github.com/wimvanderbauwhede/RefactorF4Acc): automatic refactoring tool to make Fortran code acceleration-ready, by wimvanderbauwhede and rouson. RefactorF4Acc's main purpose is to make legacy FORTRAN 77 acceleration-ready. In the process it converts FORTRAN 77 code into Fortran 95. In addition, RefactorF4Acc has a backend to translate modules to C/OpenCL.

[Fortran Kernel Generator: KGen](https://github.com/NCAR/KGen): Python tool that extracts partial codes out of a large Fortran application and converts them into a standalone/verifiable/executable kernel, by Youngsung Kim and John Dennis

[fortrantools](https://github.com/CodethinkLabs/fortrantools): tools to enable the use old or proprietary Fortran code with gfortran. They are intended to be used together with the gcc extensions in CodethinkLab's gcc branch.

### Static Analysis
[camfort](https://github.com/camfort/camfort): refactoring and verification tool for scientific Fortran programs. It currently supports Fortran 66, 77, and 90 with various legacy extensions.

[Cleanscape FortranLint](https://stellar.cleanscape.net/products/fortranlint/): static source code analysis tool that reduces your organizational exposure to risks from latent software problems by automatically identifying problems at their source -- in the Fortran code prior to compiling or executing programs. (C)

[Code Comprehension Assistance for Evidence-Based performance Tuning (CCA/EBT)](https://github.com/ebt-hpc/cca-ebt): extracts the syntactic/semantic structures from Fortran code and then provides outline views of the loop-nests and the call trees decorated with source code metrics.

[flint](https://github.com/JonasToth/flint): Little linter for Fortran, with static analysis and formatting, by JonasToth

[flint](https://github.com/marshallward/flint): aspires to be a Fortran parser, delinter, and analyser, by marshallward. For now, it is a Fortran tokenizer, with tools for parsing and automated documentation.

[flint](https://pypi.org/project/flinter/): source-code static analyzer and quality checker with multiple programming languages support. For fortran, it intends to follow the coding conventions mentioned in [OMS Documentation Wiki page](https://alm.engr.colostate.edu/cb/wiki/16983).

[Forcheck](http://www.codework-solutions.com/development-tools/forcheck-fortran-analysis/): oldest and most comprehensive Fortran analysis tool on the market. It performs a static analysis of a Fortran program or separate Fortran program units. (C)

[fortlint](https://github.com/ratnania/fortlint): Fortran static source code analysis for more secured and bug free applications

[fortrancallgraph](https://github.com/fortesg/fortrancallgraph): static source code analysis for Fortran, tracking variables in a routine's callgraph, from fortesg

[fortran-callgraph](https://github.com/hydro-jules/fortran-callgraph): Tool to create call graphs from JULES source code

[FORTRAN_callgraph_browser](https://github.com/cemac/FORTRAN_callgraph_browser): browsing tool that reads in a directory of Fortran code and displays it as an interactive graph, by Dan Ellis and Richard Rigby

[Fortran code quality](https://github.com/eirik-kjonstad/fortran-code-quality): simple Python script that parses Fortran files and gives feedback on a few metrics relating to code quality, by Eirik F. Kjønstad and Sander Roet

[Fortran linter](https://github.com/cphyc/fortran-linter): simple fortran syntax checker, including automatic fixing of the code, from cphyc

[fortran-linter](https://github.com/uchchwhash/fortran-linter): linter for Fortran 77 using Parsec-like parsing combinators in Python, by uchchwhash

[fortran_python_tools](https://github.com/jinyun1tang/fortran_python_tools): analyzes the variable usage of fixed source form Fortran 77 code, by jinyuntang

[FortranTree](https://github.com/imaliyov/FortranTree): parses Fortran source code and creates a call tree graph with Python, by imaliyov. The code relies on pygraphviz and fparser.

[fortran-vars](https://github.com/camfort/fortran-vars): static analysis library for Fortran code. It is built on top of the open source project fortran-src which provides lexing, parsing and basic analyses of Fortran code. Fortran-vars focuses on supporting the Fortran 77 standard and extensions. It provides a Fortran memory model with a symbol table and storage table, constant expressions evaluation, constant propagation analysis.

[fpt - Tools for Fortran Engineering](http://simconglobal.com/fpt_summary.html) - Error Checking, Measurement and Assessment, Structural Engineering, Software Migration, Run-time Testing, and more. (C)

[fsource](https://github.com/mwallerb/fsource): Fortran static analysis tool written in pure Python, by mwallerb

[ftnchek](https://www.dsm.fordham.edu/~ftnchek/): static analyzer for Fortran 77 programs. It is designed to detect certain errors in a Fortran program that a compiler usually does not.

[i-CodeCNES](https://github.com/cnescatlab/i-CodeCNES): static code analysis tool to help developers write code compliant with CNES coding rules for Fortran 77, Fortran 90 and Shell, from cnescatlab

[K-scope](https://github.com/K-scope/K-scope): source code analysis tool with graphical user interface that visualizes program structures for Fortran 90 and FORTRAN 77 source code. This tool simply visualizes call tree from AST based on compiler's static analysis.

[plusFORT](https://www.fortran.uk/fortran-analysis-and-refactoring-with-plusfort/plusfort-evaluation-version/pss-evaluation-starter-pack/) - multi-purpose suite of tools for analyzing and improving Fortran programs. (C)

[Simple Lint GitHub Action (simple_lint)](https://github.com/NOAA-GFDL/simple_lint): runs simple lint-like actions on files in a git repository, from NOAA-GFDL. The current list of lint actions are to check for trailing whitespace, check Fortran files for use of tab characters, and check Fortran files for lines longer then a specified length.

### Text Editors, Integrated Development Environments, and Plugins
[atom-build-fpm](https://github.com/everythingfunctional/atom-build-fpm): plugin for running the Fortran Package Manager (fpm) from within Atom

[Code::Blocks](https://www.codeblocks.org/): free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable.

[linter-gfortran](https://github.com/AtomLinter/linter-gfortran): linting Fortran code in [Atom](https://github.com/atom) with gfortran

[Fortran IntelliJ Idea plugin](https://github.com/satamas/fortran-plugin): Fortran language plugin for IntelliJ Idea, by satamas

[Fortran Language Server](https://github.com/hansec/fortran-language-server): A Fortran implementation of the Language Server Protocol using Python (2.7+ or 3.0+), by hansec. Editor extensions using this language server to provide autocomplete and other IDE-like functionality are available for Atom, Visual Studio Code, Visual Studio, (Neo)vim, and Emacs.

[Fortran Language Server (fortls)](https://github.com/gnikit/fortls): based on @hansec's original Language Server implementation but the two projects have since diverged. fortls (this project) is now developed independently by gnikit of the upstream hansec/fortran-language-server project and contains numerous bug fixes and new features the original fortran-language-server does not.

[fortran.tmbundle](https://github.com/textmate/fortran.tmbundle): TextMate support for Fortran. TextMate is a graphical text editor for macOS 10.12 or later.

[fossil](https://github.com/nrwade0/Fossil): Fortran IDE designed in Python by someone eager to learn Fortran but in an easy and accessible way, by nrwade0

[Modern-Fortran](https://github.com/eirik-kjonstad/modern-fortran-syntax): language syntax for highlighting of Fortran code in [Sublime Text](https://www.sublimetext.com/), by eirik-kjonstad. It highlights modern Fortran (Fortran 90 and newer) and incorporates features introduced in Fortran 2003, 2008, and 2018.

[neovim](https://github.com/neovim/neovim): Vim-fork focused on extensibility and usability

[Simply Fortran](http://simplyfortran.com/): modern Fortran development environment for Microsoft Windows, Apple macOS, and GNU/Linux systems. Free 30-day trial. (C)

[SublimeLinterFortran](https://github.com/Panadestein/SublimeLinterFortran): linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to gfortran, by Ramón L. Panadés-Barrueta and Tejas Shetty. It will be used with files that have free format Fortran syntax.

[vim](https://github.com/vim/vim): improved version of the UNIX editor Vi. Many new features have been added: multi-level undo, syntax highlighting, command line history, on-line help, spell checking, filename completion, block operations, script language, etc. Download [here](https://www.vim.org/download.php). 

[vimf90](https://github.com/rudrab/vimf90): Fortran ide for vim

[vim-findent](https://github.com/cradesto/vim-findent): vim plugin for [Findent](https://github.com/MFTabriz/findent), which indents Fortran sources, by cradesto

[vim-tmux-IDE](https://github.com/luco00/vim-tmux-IDE): minimal vim IDE by luco00. Sets a connection with external terminal via tmux to interactively execute code (Python, R, Julia, Fortran, Go are supported).

[Visual Studio Code (vscode)](https://github.com/microsoft/vscode): combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle, from Microsoft. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

[vscode-fortran-support](https://github.com/krvajal/vscode-fortran-support): extension that provides support for the Fortran programming language. It includes syntax highlighting, debugging, code snippets and a linting based on gfortran.

[vscode-modern-fortran-formatter](https://github.com/yukiuuh/vscode-modern-fortran-formatter): formatter extension for modern Fortran using fprettify, by Yuki Hanayama

### Translation from Fortran
[f2c](https://github.com/juanjosegarciaripoll/f2c): convert Fortran 77 to C

[f2cpp](https://github.com/victorliu/f2cpp): Converts Fortran 77 code to C++, by victorliu. Unlike f2c, the output of f2cpp.pl may or may not compile, however, only a small number of hand-tuned changes are typically needed. The resulting code is much cleaner than f2c's output, and much closer to the original intent of the original Fortran code.

[f2j](https://github.com/jonathanschilling/f2j): translate Fortran 77 to Java, especially for BLAS, LAPACK and ARPACK

[f2matlab](https://github.com/benbarrowes/f2matlab): converts Fortran 90 code to Matlab m-files, by benbarrowes. Accordingly, only basic data types and constructions are recommended.

[f4go](https://github.com/Konstantin8105/f4go): Transpiling Fortran code to golang code, by Konstantin8105

[fortran2julia](https://github.com/algorithmx/fortran2julia): Python script to translate Fortran 90 to Julia, by algorithmx

### Translation to Fortran
[c2f](https://github.com/Beliavsky/c2f): partial C to Fortran translator by David Frank

[matlab2fmex](https://sourceforge.net/projects/matlab2fmex/): small translator which aims to convert numerical Matlab m-files to Fortran90 mex files, by Ben Barrowes. matlab2fmex first translates an m-file to a Fortran90 mex source file then compiles that Fortran90 file using Matlab's mex and the local compiler.

[matlab2fortran](https://github.com/ebranlard/matlab2fortran): performs some simple conversions from Matlab code to Fortran, by ebranlard

[Mc2For](https://github.com/Sable/Mc2For): MATLAB to Fortran compiler, from Sable

[pyccel](https://github.com/pyccel/pyccel): Pyccel can be viewed as a Python-to-Fortran/C converter or a compiler for a Domain Specific Language with Python syntax

### Unclassified
[automates](https://github.com/ml4ai/automates): Automated Model Assembly from Text, Equations, and Software, from ml4ai

[fortran-sigwatch](https://github.com/scivision/fortran-sigwatch): library of routines to provide simple signal watching for Fortran programs, originally by Norman Gray, modified by Michael Hirsch. This allows a minimal level of control of a running program from outside it, for example to tell it to checkpoint itself on receipt of a signal.

[FORTRAN Testing Framework (FTFramework)](https://github.com/agforero/FTFramework): collection of Python and Bash scripts to enable easy testing of Fortran compilers using BATS, by agforero

[irep](https://github.com/LLNL/irep): tool for filling C/C++ or Fortran data structures from Lua input tables, from LLNL

[nmltab](https://github.com/aekiss/nmltab): Python 3 module and command-line tool to tabulate, semantically diff, superset and consistently format Fortran namelist files, with output to text, markdown, csv, latex and namelists, by Andrew Kiss and Aidan Heerdegen. Requires Python 3.4 or later, and f90nml (amongst other packages).

[nml-to-f90](https://github.com/perrette/nml-to-f90): generates Fortran source code for handling parameter I/O from a namelist, by perrette

[OpenAD](https://github.com/Augertron/OpenAD): tool for automatic differentiation (AD) of numerical computer programs

### Unit Testing
[fortran-testanything](https://github.com/dennisdjensen/fortran-testanything): test library supporting the Test Anything Protocol (TAP) inspired by Perl's Test::More module, by dennisdjensen

[FortranTestGenerator](https://github.com/fortesg/fortrantestgenerator): automatically generates unit tests for subroutines of existing Fortran applications based on an approach called Capture & Replay, from fortesg

[fortran-unit-test](https://github.com/dongli/fortran-unit-test): unit test library in Fortran to encourage scientific programmer to write tests, by dongli

[Fortran_UnitTest](https://github.com/zhenkunl/Fortran_UnitTest): unit test library based on OOP, by zhenkunl. It is strongly inspired by Zofu, and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test).

[Fortran Unit Test Library](https://github.com/zhenkunl/Fortran_UnitTest): pure Fortran library using Object-Oriented Programming (OOP), by zhenkunl. It is strongly inspired by [Zofu](https://github.com/acroucher/zofu), and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test). 

[FRUIT](https://github.com/mortele/FRUIT): Fortran unit test framework in Ruby, by mortele and michaelkonecny 

[fytest](https://github.com/aradi/fytest): lightweight unit testing framework for Fortran, by aradi. Thanks to its header-only design, it can be easily bundled with any Fortran project without creating extra dependencies.

[pFUnit](https://github.com/Goddard-Fortran-Ecosystem/pFUnit): unit testing framework enabling JUnit-like testing of serial and MPI-parallel software written in Fortran, from Goddard-Fortran-Ecosystem. Limited support for OpenMP is also provided in the form of managing exceptions in a thread-safe manner.

[tap](https://github.com/gzahl/tap): minimal producer implementation of the "Test Anything Protocol" (TAP) in Fortran 90, from gzahl

[test-drive](https://github.com/awvwgk/test-drive): lightweight, procedural unit testing framework based on nothing but standard Fortran, by awvwgk. Integration with meson, cmake and Fortran package manager (fpm) is available.

[Vegetables](https://gitlab.com/everythingfunctional/vegetables/-/tree/main/): testing framework written using functional programming principles, by Brad Richardson. As many of its procedures as possible are marked with the pure keyword while still allowing the framework to test impure code.

### Fortran Tools

(C) indicates a commercial product
* [Automatic Differentiation](#automatic-differentiation)
* [Automatic Documentation](#automatic-documentation)
* [Build Tools](#build-tools)
* [Code Generation](#code-generation)
* [Command Line Parsing](#command-line-parsing)
* [Compilers](#compilers)
* [Debugging](#debugging)
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

### Automatic Differentiation
[AD_dnSVM](https://github.com/lauvergn/AD_dnSVM): Fortran Automatic Differentiation tool using forward mode for scalars (S), Vectors (V) and Matrices (M), by David Lauvergnat. It has no limit in terms of the number of independent variables (this number is defined at runtime) and can compute up to third derivatives.

[ADF95](https://github.com/jingchangshi/ADF95): modification of Jingchang Shi to work with gfortran of program described in [ADF95: Tool for automatic differentiation of a FORTRAN code designed for large numbers of independent variables](https://www.sciencedirect.com/science/article/abs/pii/S0010465505000810?via%3Dihub), by Christian W. Straka, Computer Physics Communications, Volume 168, Issue 2, 1 June 2005, Pages 123-139, with preprint [here](https://arxiv.org/abs/cs/0503014)

[adifor](https://www.mcs.anl.gov/research/projects/adifor/): given a Fortran 77 source code and a user's specification of dependent and independent variables, ADIFOR will generate an augmented derivative code that computes the partial derivatives of all of the specified dependent variables with respect to all of the specified independent variables in addition to the original result.

[adjac](https://github.com/pv/adjac): automatic differentiation for generating sparse Jacobians, using Fortran 95 and operator overloading, by Pauli Virtanen

[Audito](https://github.com/Michel-Heinz/Audito): automatic differentiation tool for Fortran, by Michel V. Heinz. The mathematical operators have been overloaded to work with the newly defined types, which include not only the function value, but also the gradient, Hessian and Laplacian.

[auto_deriv](https://elsevier.digitalcommonsdata.com/datasets/2wxp5vxj2m/1): module comprised of a set of Fortran 95 procedures which can be used to calculate the first and second partial derivatives (mixed or not) of any continuous function with many independent variables, by S. Stamatiadis, and S.C. Farantos, part of the Computer Physics Communications Program Library. The mathematical function should be expressed as one or more fortran 77/90/95 procedures. 

[autodiff](https://github.com/sgeard/autodiff): automatic differentiation for up to 4th derivatives, by Simon Geard

[Auto-Diff](https://github.com/zoziha/Auto-Diff): implementation in Modern Fortran of backward mode automatic differentiation, by zoziha.

[Dual Number Automatic Differentiation (DNAD)](https://github.com/joddlehod/dnad): update of code from Yu, W. and Blair, M.: "DNAD, a Simple Tool for Automatic Differentiation of Fortran Codes Using Dual Numbers," Computer Physics Communications, vol. 184, 2013, pp. 1446-1452, by oddlehod. Related project: [Fortran_DNAD](https://github.com/nickbrady/Fortran_DNAD). A [fork](https://github.com/oyvindyr/dnad) by oyvindyr uses [fypp](https://github.com/aradi/fypp) macros. The benefit of this approach is that interfaces and implementations of mathematical functions can be "injected" into the modules where they are used.

[fazang](https://github.com/yizhang-yiz/fazang): library for reverse-mode automatic differentiation, inspired by Stan/Math library, by Yi Zhang. Zoziha has [updated](https://github.com/zoziha/fazang) the project to work with gfortran and ifort.

[OpenAD](https://github.com/Augertron/OpenAD): tool for automatic differentiation (AD) of numerical computer programs

[Tapenade](https://team.inria.fr/ecuador/en/tapenade/): automatic differentiation engine developed at Inria. It can be run online or be downloaded and installed locally as a set of Java classes (JAR archive).

[Transformation of Algorithms in Fortran (TAF)](http://fastopt.de/products/taf/taf.shtml): source-to-source translator for Fortran 77-95 code, i.e. TAF accepts Fortran 77-95 code as input, applies a semantic transformation, and generates Fortran 77-95 code. TAF supports several semantic transformations. The most important one is Automatic Differentiation (AD), i.e. generation of code for evaluation of the first-order derivative (Jacobian matrix). (C)

### Automatic Documentation
[Doxygen](https://github.com/doxygen/doxygen): generates an on-line documentation browser (in HTML) and/or an off-line reference manual (in LaTeX) from a set of documented source files. There is also support for generating output in RTF (MS-Word), PostScript, hyperlinked PDF, compressed HTML, DocBook and Unix man pages. 

[f90tohtml](https://github.com/degeron/f90tohtml): Perl script to convert fortran source files into a hyperlinked web site

[ford](https://github.com/Fortran-FOSS-Programmers/ford): Automatically generates FORtran Documentation from comments within the code, from Fortran-FOSS-Programmers

[ProTeX](http://wiki.seas.harvard.edu/geos-chem/index.php/Automatic_documentation_with_protex): Perl script that can strip information from a standard Fortran document header and save that to a LaTeX file, by Arlindo Da Silva et al.

[version-f](https://github.com/minhqdao/version-f): implementation of [Semantic Versioning 2.0.0](https://semver.org/) by Minh Dao that aims to be a user-friendly tool for handling versions in Fortran projects

### Build Tools
[Buildnis](https://github.com/Release-Candidate/Buildnis): distributed, platform independent build system that can handle C++20 and Fortran modules and is flexible enough to build anything else and handle various build steps

[easy](https://github.com/urbanjost/easy): steps to setup a GitHub repository with fpm, and GitHub actions including ford(1) documentation and unit tests, by urbanjost

[F90_makefile_builder](https://github.com/benjamin-pieczynski/F90_makefile_builder): Python program to build a makefile for a Fortran 90 program by searching through each module for dependencies, by Benjamin Pieczynski. The algorithm determines the order of the dependencies and builds the make file in the correct order.

[Fab](https://github.com/metomi/fab): build system for Fortran and C projects. Initially designed to build the Met Office’s major scientific applications, LFRic and the UM.

[FCM](https://github.com/metomi/fcm): modern Fortran build system + wrappers to Subversion for scientific software development, from metomi

[FF08Depends](https://www.megms.com.au/ff08depends.htm): command line tool for obtaining file dependency information for Fortran 2008 source files, written in Fortran 2003 by IanH

[FoBiS.py, Fortran Building System for poor people](https://github.com/szaghi/FoBiS): automatic parsing of files for dependency-hierarchy creation in case of use and include statements, and automatic building of all programs found into the root directory parsed or only a specific selected target, by szaghi et al.

[fortdep](https://github.com/gronki/fortdep): Python3 script for generating dependencies between Fortran modules for make, by Dominik Gronkiewicz

[fortdepend](https://github.com/ZedThree/fort_depend.py): python script to generate dependencies for Fortran projects, by ZedThree

[fortrandep](https://github.com/orvedahl/fortrandep): Python tool to determine Makefile dependencies for a Fortran project, by Ryan Orvedahl

[Fortran_makedeps](https://github.com/jamesbiddle/Fortran_makedeps): small Python script to scan Fortran sources and generate makefile-appropriate dependencies, by James Biddle

[fortranMakeUtils](https://github.com/deniseiras/fortranMakeUtils): Python scripts for generating dependency trees and makefiles, by Denis Eiras

[Fortran Package Manager for Visual Studio](https://github.com/everythingfunctional/fpm-for-VS): adds options and menu entries for building, running and testing your Fortran project using the Fortran Package Manager (fpm), by everythingfunctional

[fpm](https://github.com/fortran-lang/fpm): Fortran Package Manager (fpm) is a package manager and build system for Fortran, from fortran-lang

[fpm-completions](https://github.com/ShinobuAmasaki/fpm-completions): command-line completion functions for the Fortran Package Manager, by Shinobu Amasaki. Zsh is required to use this package, currently.

[fpm-gui](https://github.com/arjenmarkus/fpm-gui): straigtforward graphical user interface for the Fortran Package Manager (fpm), by Arjen Markus

[fpm-registry](https://github.com/fortran-lang/fpm-registry): centralized registry of fpm packages for the fortran-lang site

[fpm-search](https://github.com/urbanjost/fpm-search): lists available packages in the fpm-registry from the command line, by urbanjost and Sebastian Ehlert. This allows for quickly locating fpm(1) packages and generating the associated dependency lines to insert into fpm(1) package manifest files (fpm.toml) that wish to use them.

[githubactions_intro](https://github.com/ofmla/githubactions_intro): introduces Github Actions as a tool for lightweight automation of scientific data workflows, with examples in Python and Fortran using gnuplot, by Oscar Mojica

[homebrew-fortran](https://github.com/fortran-lang/homebrew-fortran): provides package build instructions for tools and libraries around Fortran compatible with the [Homebrew toolchain](https://brew.sh/), by Federico Perini et al. Available packages from this tap are fpm: Fortran package manager and lfortran: Modern interactive LLVM-based Fortran compiler.

[Intel® oneAPI Math Kernel Library Link Line Advisor](https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl-link-line-advisor.html#gs.1d3b29): requests information about the computer system and on how one intends to use the Intel® oneAPI Math Kernel Library (link dynamically or statically, use threaded or sequential mode, and so on) and automatically generates the appropriate link line for the application

[jams_makefile](https://github.com/mcuntz/jams_makefile): provides a portable, versatile way of compiling Fortran, C, C++, and mixed projects, by mcuntz

[makedepf90](https://github.com/outpaddling/makedepf90): generates make dependencies for Fortran code, by Erik Edelman

[Makefile-maker](https://github.com/Garl4nd/Makefile-maker): automatic Fortran makefile maker, by Garl4nd. The program first scans all Fortran files for imports of other source files and creates a directed dependency graph, where each vertex represents the file and an arrow from A to B correspond to the File A depending on B.

[makemake](https://github.com/BlameTroi/makemake): Perl script first developed by Michael Wester to construct correct makefiles for modern Fortran code and modified for newer compilers and to work for C++ by Katherine Holcomb. Its usage is discussed [here](https://learning.rc.virginia.edu/courses/fortran-introduction/make/).

[makemake90](https://github.com/janberges/makemake90): Python script that generates Makefiles for modular Fortran programs, by Jan Berges. It recursively searches the working directory for .f90 files and determines their dependencies.

[meson](https://github.com/mesonbuild/meson): next-generation build system. [Test-meson](https://github.com/tg2414/fortran) is an example Python project with Fortran code.

[MinGW package for the Fortran package manager](https://github.com/awvwgk/mingw-w64-fpm-pkgbuild): provides package build instructions for the Fortran package manager (fpm) compatible with the MSYS2 toolchain. This project provides prebuilt MinGW packages at the release page.

[mkhelper](https://github.com/skosukhin/mkhelper): collection of utilities to be used with GNU Autoconf and GNU Make for building Fortran projects, by skosukhin

[mkmf](https://github.com/NOAA-GFDL/mkmf): tool written in perl5 that will construct a makefile from distributed source, from NOAA-GFDL. A single executable program is the typical result.

[pyfpm](https://github.com/awvwgk/pyfpm): provides a pydantic model of the fpm package manifest format used in the Fortran package manager, by Sebastian Ehlert

[run-fortran](https://github.com/lycantropos/run-fortran): sorts Fortran files based on modules definitions and usages, by lycantropos

[verbose-goggles](https://github.com/goddard-guryon/verbose-goggles): Generates Fortran project templates, by Goddard Guryon. The create_project.sh script takes a project name (and optionally a project directory name) as inputs, creates the project folder, the build and docs folders within it, and saves template files for CMake and Doxygen.

[xmake](https://github.com/xmake-io/xmake): lightweight cross-platform build utility based on Lua. It uses xmake.lua to maintain project builds. The two Fortran compilers supported are gfortran and ifort.

### Code Generation
[ChatGPT](https://openai.com/blog/chatgpt): generates Fortran code from a problem description in English or another natural language and translates code from other programming languages to Fortran, sometimes with errors. The [RunGPT](https://chrome.google.com/webstore/detail/rungpt-execute-chatgpt-co/ddfiefcjflpdpanadjmgpogkfnjaifod) Chrome extension allows code to be compiled with gfortran and run within the ChatGPT web interface. Other LLMs that can generate Fortran code are [Perplexity](https://www.perplexity.ai/), [Groq](https://groq.com/), and [Claude](https://claude.ai/chats), [Vertex AI with Gemini](https://cloud.google.com/vertex-ai) from Google, and [GitHub Copilot](https://github.com/features/copilot).

[IRPF90](http://irpf90.ups-tlse.fr/): Fortran programming environment which helps the development of large Fortran codes by applying the Implicit Reference to Parameters method (IRP)

[Maple](https://www.maplesoft.com/): has a [Fortran](https://www.maplesoft.com/support/help/Maple/view.aspx?path=CodeGeneration/Fortran) command that translates Maple code to Fortran 77 (C)

[MathCode F90](https://www.wolfram.com/products/applications/mathcodef90/): generates standalone Fortran 90 code from Mathematica code, optionally connected via MathLink to Mathematica (C)

[Matlab](https://www.mathworks.com/): the [fortran](https://www.mathworks.com/help/symbolic/generate-c-or-fortran-code.html) function generates Fortran code fragments from a symbolic expression, or generates files containing code fragments (C)

[Maxima](https://maxima.sourceforge.io/) the built-in [fortran](https://maxima.sourceforge.io/docs/manual/maxima_73.html) command prints an expression as a Fortran statement. [F77](http://ftp.math.utah.edu/u/ma/hohn/linux/lisp/maxima-doc/www.mcs.kent.edu/docs/maxima/max/section3.10.html) is an enhancement.

[Parametric Fortran](https://web.engr.oregonstate.edu/~erwig/pf/): Fortran program-generator generator that can produce extensions of Fortran, specialized to support the programming of particular applications, by Martin Erwig et al. Extensions are specified through parameter structures that can be referred to in Fortran programs to describe the dependency of program parts on these parameters.

[PSyclone](https://github.com/stfc/PSyclone): domain-specific compiler and code transformation system for Finite Difference/Volume/Element Earth-system models in Fortran

[sympy](https://www.sympy.org/en/index.html): Python library for symbolic mathematics that can [generate Fortran code](https://docs.sympy.org/latest/modules/codegen.html), as [illustrated](https://fortran-lang.discourse.group/t/code-generation-using-sympy/321) by Ivan Pribec

### Command Line Parsing
[argv-fortran](https://github.com/jacobwilliams/argv-fortran): better get_command_argument for Fortran that returns the argument in an allocatable character string, by Jacob Williams

[cmdff](https://gitlab.com/everythingfunctional/cmdff): makes nicer command lines for Fortran codes, by Brad Richardson

[command_args](http://flibs.sourceforge.net/command_args.html): automatically handles the command-line arguments that are passed to the program, by Arjen Markus

[f90getopt](https://github.com/haniibrahim/f90getopt): getopt()- and getopt_long()-like functionality (similar to the C-functions) for Fortran 90, by Hani Andreas Ibrahim, based on code by Mark Gates

[fArgParse](https://github.com/Goddard-Fortran-Ecosystem/fArgParse): command line argument parsing for Fortran, part of the [Goddard Fortran Ecosystem](https://github.com/Goddard-Fortran-Ecosystem)

[FLAP](https://github.com/szaghi/FLAP): library designed to simplify the (repetitive) construction of complicated CLI in Fortran 2003, by Stefano Zaghi. FLAP has been inspired by the python module argparse and tries to mimic it.

[FTN_Getopt](https://doku.lrz.de/dyn/Doku_Kurse/Fortran/getopt/): supplies a method for handling command arguments in a manner similar to the getopt facility in C, by Reinhold Bader 

[M_CLI](https://github.com/urbanjost/M_CLI): cracks the command line when given a NAMELIST and a prototype string that looks very much like an invocation of the program, by urbanjost and Laurence Kedward. Using the NAMELIST group has the benefit that there is no requirement to convert the strings to their required types or to duplicate the type declarations.

[M_CLI2](https://github.com/urbanjost/M_CLI2): cracks the command line when given a prototype string that looks very much like an invocation of the program, by urbanjost et al. A call to get_args(3f) or one of its variants is then made for each parameter name to set the variables appropriately in the program.

[M_kracken95](https://github.com/urbanjost/M_kracken95): Fortran 95 version of the kracken(3f) procedure (and related routines) for command line parsing, by urbanjost

[optionsf90](https://github.com/cngilbreth/optionsf90): module for defining and parsing command-line options and input parameters for Fortran programs, by Christopher N. Gilbreth. Its design is inspired by Python's optparse module.

[paramcard](https://github.com/tueda/paramcard): command-line parameter input made simple, by Takahiro Ueda

### Compilers
[AMD Optimizing C/C++/Fortran Compiler (AOCC)](https://developer.amd.com/amd-aocc/): high performance, production quality code generation tool. The AOCC environment provides various options to developers while building and optimizing C, C++, and Fortran applications targeting 32-bit and 64-bit Linux® platforms.

[AOMP](https://github.com/ROCm/aomp): open-source Clang/LLVM based compiler with added support for the OpenMP® API on Radeon™ GPUs. Instructions to install f18 are [here](https://github.com/ROCm/aomp/tree/aomp-dev/f18bin#readme).

[Arm Fortran Compiler](https://developer.arm.com/Tools%20and%20Software/Arm%20Fortran%20Compiler): tailored for server, HPC, and scientific codes, with support for Fortran and OpenMP. The compiler is built on the open source Flang front-end, and the LLVM‑based optimization and code generation back-end. (C)

[f18-llvm-project](https://github.com/flang-compiler/f18-llvm-project): fork of llvm/llvm-project for f18. In sync with f18-mlir and f18.

[flang](https://github.com/flang-compiler/flang): flang (also known as "Classic Flang") is an out-of-tree Fortran compiler targeting LLVM. It is an open-sourced version of pgfortran, a commercial Fortran compiler from PGI/NVIDIA

[fortran-ios](https://github.com/ColdGrub1384/fortran-ios): script that acts like a Fortran compiler that uses Flang to build sources for iOS arm64, by Emma Cold

[Fortran kernel for Jupyter with Coarray support](https://github.com/sourceryinstitute/jupyter-CAF-kernel): from sourceryinstitute

[fortran-setup](https://github.com/ipqa-research/fortran-setup): script to set up a system to use Fortran on an Ubuntu-based system, by Federico E. Benelli. It installs a Python package manager for some Python-based tools, gfortran, optionally Intel oneAPI HPC, BLAS and LAPACK, gdb, fuzzy-finder ([fzf](https://github.com/junegunn/fzf)), Fortran Package Manager ([fpm](https://github.com/fortran-lang/fpm)), [findent](https://github.com/MFTabriz/findent), flinter, [FORD](https://github.com/Fortran-FOSS-Programmers/ford), [fortls](https://github.com/fortran-lang/fortls), and fortran_project, a script to generate and open projects.

[fortran.rs](https://github.com/Xavier2p/fortran.rs): interpreter for Fortran, written in Rust, by Xavier2p, Development in progress

[Full-Stack-Fortran](https://github.com/StarGate01/Full-Stack-Fortran): toolchain to compile Fortran to Webassembly, and a few projects using it, by Christoph Honal et al.

[gfortran](https://gcc.gnu.org/wiki/GFortran): GNU Fortran project, developing a free Fortran 95/2003/2008 compiler for GCC, the GNU Compiler Collection. The gfortran development effort uses an open development environment in order to attract a larger team of developers and to ensure that gfortran can work on multiple architectures and diverse environments. Gfortran installation on various platforms is discussed at [fortran-lang](https://fortran-lang.org/learn/os_setup/install_gfortran). For Windows there is [Quickstart Fortran](https://fortran-lang.discourse.group/t/quickstart-fortran-installer-for-windows/2270).

[gfortran-for-macOS](https://github.com/fxcoudert/gfortran-for-macOS): gfortran for macOS Intel, by fxcoudert.

[g95](https://www.g95.org/downloads.shtml): stable, production Fortran 95 compiler available for multiple cpu architectures and operating systems. Parts of the F2003 and F2008 standards have been implemented

[HPE Cray Programming Environment](https://buy.hpe.com/us/en/software/high-performance-computing-software/high-performance-computing-software/hpe-cray-programming-environment/p/1012707351): fully integrated software suite with compilers, tools, and libraries designed to improve programmer productivity, application scalability, and performance. Besides support for multiple programming languages, programming models, compilers, I/O libraries, and scientific libraries, the suite offers a variety of supported tools for areas including debugging, performance analysis, workload management, and environment setup. (C)

[IBM Fortran](https://www.ibm.com/products/fortran-compiler-family): XL Fortran for AIX®: Build optimized and tuned Fortran applications on IBM AIX.
<br />XL Fortran for Linux: Optimize your HPC and cognitive Fortran applications for Linux on IBM Power® Systems, including the POWER9™ processors.
<br />VS Fortran: Develop efficient applications for IBM Z® and z/VM® with IBM VS FORTRAN. (C)

[Intel Fortran](https://software.intel.com/content/www/us/en/develop/tools/oneapi/components/fortran-compiler.html): built on a long history of generating optimized code that supports industry standards while taking advantage of built-in technology for Intel® Xeon® Scalable processors and Intel® Core™ processors. Staying aligned with Intel’s evolving and diverse architectures, the compiler now supports GPUs.

[lfortran](https://github.com/lfortran/lfortran): modern open-source (BSD licensed) interactive Fortran compiler built on top of LLVM. It can execute user's code interactively to allow exploratory work (much like Python, MATLAB or Julia) as well as compile to binaries with the goal to run user's code on modern architectures such as multi-core CPUs and GPUs.

[macos-cross-compiler](https://github.com/shepherdjerred/macos-cross-compiler): compile C, C++, and Fortran code on Linux that will be executed on macOS, by Jerred Shepherd. This project is focused on supporting newer versions of macOS.

[Mercurium](https://github.com/bsc-pm/mcxx):  C/C++/Fortran source-to-source compilation infrastructure aimed at fast prototyping developed by the Programming Models group at the Barcelona Supercomputing Center. Mercurium is used, together with the Nanos++ Runtime Library, to implement the OmpSs programming model. Both tools provide also an implementation of OpenMP 3.1.

[modern-fortran-docker](https://github.com/modern-fortran/modern-fortran-docker): Dockerfile to build a modern-fortran Docker image. It is based on Ubuntu 23.10, which has several enhancements to the Linux kernel and supports GCC GFortran v13.2.0. This Dockerfile installs gfortran, OpenMPI, and OpenCoarrays and also git clones the modern-fortran projects.

[NAG](https://www.nag.com/content/nag-fortran-compiler): robust and highly tested Fortran compiler, valued for its checking capabilities and detailed error reporting. Available on Linux, Microsoft Windows and Mac OS X, including Apple Silicon Macs. (C)

[NEC](https://www.nec.com/en/global/solutions/hpc/sx/tools.html): Fortran compiler conforms to the Fortran-2003 standard (ISO/IEC 1539-1:2004) and supports many features from Fortran-2008 (ISO/IEC 1539-1:2010). NEC has more than 30 years’ experience in compiler technology for high-end vector machines, and these newly developed compilers will be based on this experience and support all the optimization strategies that NEC compilers are known for. (C)

[NVIDIA HPC Software Development Kit](https://developer.nvidia.com/hpc-sdk): NVIDIA HPC SDK C, C++, and Fortran compilers support GPU acceleration of HPC modeling and simulation applications with standard C++ and Fortran, OpenACC® directives, and CUDA®. GPU-accelerated math libraries maximize performance on common HPC algorithms, and optimized communications libraries enable standards-based multi-GPU and scalable systems programming.

[ompi](https://github.com/open-mpi/ompi): open source Message Passing Interface (MPI) implementation that is developed and maintained by a consortium of academic, research, and industry partners

[Open Fortran Compiler (ofc)](https://github.com/CodethinkLabs/ofc): goals are to provide a FORTRAN static code analysis tool, a FORTRAN modernizer which can reprint legacy FORTRAN as F90 where possible, and an alternative FORTRAN front-end for open-source compilers.

[Oracle Developer Studio Fortran compiler, f95](https://docs.oracle.com/cd/E77782_01/html/E77790/aevbb.html): provides the following features and extensions: Optimized automatic and explicit loop parallelization for multiprocessor systems, VAX/VMS Fortran extensions, OpenMP parallelization directives, and global, peephole, and potential parallelization optimizations produce high performance applications. (C)

[playground](https://github.com/fortran-lang/playground): interactive Fortran playground in the browser, by Ashirwad Mishra et al. Its main purpose is for newcomers to easily get a taste for the language and learn the essentials of Fortran programming.

[ROSE](https://github.com/rose-compiler/rose): compiler infrastructure to build source-to-source program transformation and analysis tools for large-scale C (C89 and C98), C++ (C++98 and C++11), UPC, Fortran (77/95/2003), OpenMP, Java, Python and PHP applications

[flang-wasm](https://github.com/r-wasm/flang-wasm): contains tools to build a patched version of LLVM's flang-new compiler that can be used to compile Fortran sources for WebAssembly. A pre-built Fortran runtime library is also built for WebAssembly using Emscripten.

[Silverfrost Fortran FTN95](https://www.silverfrost.com/12/ftn95/ftn95_feature_details.aspx): full Fortran 95 standards compliant compiler, capable of producing fast executables for Win32 and for Microsoft .NET. FTN95 ships with the world's best runtime checking and a great range of supporting software. There is a free [personal edition](https://www.silverfrost.com/default.aspx?id=32). (C)

[VSI Fortran for OpenVMS](https://vmssoftware.com/products/fortran/): supports the FORTRAN 66, FORTRAN 77, Fortran 90, and Fortran 95 standards

[xcc-project](https://github.com/JianpingZeng/xcc-project): C/C++/Fortran compiler collection written in Java, by JianpingZeng

### Debugging
[Fortran Stacktrace](https://github.com/SINTEF/fortran-stacktrace): generates stack traces by providing a Fortran wrapper around the C++ library [backward-cpp](https://github.com/bombela/backward-cpp). It also integrates with the Fortran error-handling library in order to generate errors that includes a stacktrace.

[serialbox](https://github.com/GridTools/serialbox): data serialization library and tools for C/C++, Fortran, and Python3, used to build validation frameworks against reference runs, from ETH Zurich

[ups](https://github.com/sth/ups): source level C, C++ and Fortran debugger that runs under X11, by Mark Russell. Currently supported systems are FreeBSD and GNU/Linux on Intel x86 and Solaris on SPARC.

### Emacs Plugins
[align-f90](https://github.com/jannisteunissen/align-f90): alignment support for Fortran 90 in Emacs, by jannisteunissen

[Doom Emacs Fortran Module](https://github.com/doomemacs/doomemacs/tree/master/modules/lang/fortran): enables a complete, modern development environment for Fortran. It has integration with [fpm](https://github.com/fortran-lang/fpm), LSP support via [fortls](https://github.com/fortran-lang/fortls), auto-formatting via fprettier, and support for gfortran and Intel Fortran.

[Emacs](https://github.com/emacs-mirror/emacs): extensible, customizable, free text editor. Download [here](https://www.gnu.org/software/emacs/download.html).

[f90format](https://github.com/BlameTroi/f90format): package that hooks up [fprettify](https://github.com/pseewald/fprettify) with Steve Purcell's [emacs-reformatter](https://github.com/purcell/emacs-reformatter) to format modern Fortran source, by Troy Brumley

[f90-iface](https://github.com/wence-/f90-iface): Emacs-based browser for Fortran 90 generic interfaces, by wence- and monnier

[f90-namelist-mode](https://github.com/ZedThree/f90-namelist-mode): extension to Emacs f90-mode to handle Fortran namelists, by ZedThree

[fortpy](https://github.com/rosenbrockc/fortpy): Python Emacs Intellisense and Unit Testing Support for Fortran, by rosenbrockc and wsmorgan

[fortpy-el](https://github.com/rosenbrockc/fortpy-el): Lisp package for emacs that integrates with fortpy to provide context-specific auto-completion and intellisense for Fortran 2003, including object oriented constructs, by rosenbrockc

[fortran-index-args](https://github.com/ffevotte/fortran-index-args): numbers subroutine arguments and shows indexes before each argument in the list, by ffevotte. Such indexes are just displayed on screen, but do not modify the underlying buffer.

[Fortran layer](https://github.com/ciappi/fortran-layer): basic Spacemacs configuration layer for the Fortran language, by Marco Scopesi

[Fortran-tags](https://github.com/raullaasner/fortran-tags): Fortran source code indexing tool with the focus of finding the definition of any variable or procedure, by raullaasner et al. It is able to correctly locate all global and local variables and is expected to work with any Fortran 2008 conforming code with some exceptions as mentioned below.

[fprettify.el](https://github.com/osada-yum/fprettify.el): interface to fprettify, auto-formatter for modern Fortran code, by osada-yum

### Fixed to Free Source Form Conversion
[ccx_fff](https://github.com/calculix/ccx_fff): Python script converting old Fortran 77 code to the one with free form, from calculix. Shifts comments and continuation marks for better code folding. 

[EZUP](https://github.com/Beliavsky/EZUP): tool to convert Fortran fixed source form to free source form to be compatible with [ELF90](http://www.lahey.com/elfpage.htm), by August Miller

[f2f](https://github.com/MRedies/f2f_mirror): Perl script which does much of the tedious work of converting FORTRAN 77 source code into modern Fortran, by Colby Lemon

[f2f90](https://github.com/btrettel/f2f90): utility to convert FORTRAN 77 fixed source form to Fortran 90 free source form, by Michael Metcalf, Peter A. Rochford, and Ben Trettel

[f77tof90](https://github.com/mattdturner/f77tof90): Python script that reads in a Fortran 77 (.f or .F) fixed form file and converts it to a free form Fortran 90 file (.f90 or .F90), by mattdturner. It was successfully used to convert a legacy codebase (over 400 .f/.F files and millions of lines of code) from Fortran 77 to Fortran 90.

[ffixed2free](https://github.com/MeteoSwiss/ffixed2free): converts FORTRAN fixed-format source code (FORTRAN 77 style) to free-format source code (Fortran 90 style), by Pirmin Kaufmann and Martin Schraner. Ffixed2free does not require the fixed-format code to be restricted to the FORTRAN 77 standard.

[FORTRAN77_to_Fortran90](https://github.com/Koushikphy/FORTRAN77_to_Fortran90): convert old fixed source FORTRAN 77 code to free form Fortran 90 code, by Koushikphy

[fortran-legacy-tools](https://github.com/ylikx/fortran-legacy-tools): tools to deal with Fortran code: fixed to free source form converter, upper- to lowercase converter, formatter for variable declarations, by ylikx

[fortran_tools](https://github.com/arktools/fortran_tools): Python 2 script by James Goppert and Lenna Peterson

[freestyle](https://github.com/bast/freestyle): script to convert fixed form Fortran files (written in Fortran 77) and header files to free form, by bast

[GConvert](https://github.com/GeorgeTsikas/GConvert): program to convert fixed form Fortran into code that works as fixed or free form, by GeorgeTsikas.

[to_f90](https://github.com/jbdv-no/to_f90): Alan Miller's tool for converting Fortran 77 code to free-form Fortran 90 code, from jbdv-no

### Graphical User Interfaces
[EGGX/ProCALL](https://www.ir.isas.jaxa.jp/~cyamauch/eggx_procall/): X11 graphics library for C, C++ and FORTRAN created to achieve simplicity. One can easily create 2D graphics on the X Window System by using BASIC-style drawing functions. 

[ftk](https://github.com/arjenmarkus/ftk): provides a straightforward means to build graphical user-interfaces in Fortran based on Tcl/Tk, by Arjen Markus. In its current state it is proof of concept, not a full-fledged library.

[GINO](http://gino.co.uk/): high-end feature-rich API for creating complex 2D and 3D graphics and GUI applications. The GINO products are available for Fortran under Windows and Linux. (C)

[gtk-fortran](https://github.com/vmagnin/gtk-fortran): cross-platform library to build Graphical User Interfaces (GUI), by Vincent Magnin et al. Gtk-fortran is a partial GTK / Fortran binding written in Fortran, thanks to the ISO_C_BINDING module for interoperability between C and Fortran.

[tiny file dialogs](https://sourceforge.net/projects/tinyfiledialogs/): offers many modal and file dialogs in C and provides the iso_c_binding interface / module to call these functions from Fortran, by Guillaume Vareille

[Winteracter](http://winteracter.com/): GUI toolset for the Fortran programming language. It consists of various visual development tools and a substantial subroutine library. Several Fortran compilers are supported. (C)

### Indentation and Formatting
[ajt-fortran.vim](https://github.com/robertodr/ajt-fortran.vim): port of Ajit J. Thakkar's Vim indent script

[FF08Obfuscate](https://www.megms.com.au/ff08obfuscate.htm): command line tool for generating a superficially obfuscated variant of the source of a Fortran 2008 program, written in Fortran 2003 by IanH. It does this by modifying the identifiers in the program and rendering the code without any source comments.

[findent](https://github.com/MFTabriz/findent): indents and beautifies Fortran source, fixed and free format, and converts Fortran fixed format to Fortran free format, by wvermin and MFTabriz. [Findent-pypi](https://github.com/gnikit/findent-pypi), by gnikit, has PyPi wheels.

[flower](https://github.com/urbanjost/flower): converts free-format Fortran code to all lowercase or all uppercase, by urbanjost. In each case comments and quoted text are left as-is.

[FortranIndent](https://github.com/Kairzhan/FortranIndent): tools to indent Fortran 90 sources, from Kairzhan

[FortranIndenter_UNESP_2007](https://github.com/rafaeldr/FortranIndenter_UNESP_2007): indenter for Fortran 77 developed in C, by Rafael Delalibera Rodrigues and Paulo Henrique Arantes Urgal

[fprettify](https://github.com/pseewald/fprettify): auto-formatter for modern Fortran code that imposes strict whitespace formatting, written in Python, by pseewald

[f90split](https://github.com/urbanjost/f90split): splits free source form Fortran code into multiple files, one module or procedure per file, by Michel Olagnon, adapted by urbanjost for use with the Fortran Package Manager. Contained procedures are stored within their parent procedure

[IndentPatternFortran](https://github.com/JHenneberg/IndentPatternFortran): general indentation patterns for Fortran, by JHenneberg

[xpand](https://github.com/urbanjost/xpand): expands tabs in files. removes trailing white space, and optionally removes multiple blank lines, by urbanjost. It is primarily intended for use on systems without access to the Unix command expand(1).

### Interoperability
[Cython fortran-file](https://github.com/cphyc/cython_fortran_file): fast and easy reader for record-based binary format, as written by Fortran, by Corentin Cadiou

[Cython_ISO_Fortran_binding](https://github.com/sakamoti/Cython_ISO_Fortran_binding): code for using ISO_Fortran_binding.h from Cython, by Yuichiro Sakamoto. By using ISO_Fortran_binding.pxd, it is possible to call Fortran from Cython in the same way as one calls Fortran from C.

[extutils-f77](https://github.com/PDLPorters/extutils-f77): Perl module that tries to figure out how to link C programs with Fortran subroutines on a system, adding a list of Fortran runtime libraries, by mohawk2 et al.

[f2py-with-derived-types](https://github.com/Nicholaswogan/f2py-with-derived-types): demonstrates how to use f2py with Fortran derived types with type-bound procedures, by Nick Wogan

[F2x](https://github.com/DLR-SC/F2x): versatile, template-based Fortran wrapper written in Python. Compared to the popular tool f2py it comes with two important differences: a full Fortran parser based on the work by the OpenFortranParser, and a very flexible code generation backend that uses Jinja2 templates.

[f90nml](https://github.com/marshallward/f90nml): Python module and command line tool, by Marshall Ward et al., that provides a simple interface for the reading, writing, and modifying Fortran namelist files. A namelist file is parsed and converted into an Namelist object, which behaves like a standard Python dict

[f90_port](https://github.com/escribapetrus/f90_port): tests Erlang ports to Fortran, by Pedro Schreiber, explained [here](https://dev.to/escribapetrus/transparent-execution-of-fortran-code-from-the-erlang-machine-using-ports-37ba)

[f90wrap](https://github.com/jameskermode/f90wrap): Fortran 90 to Python interface generator with derived type support, by jameskermode et al.

[fffi](https://github.com/pyccel/fffi): tool to transparently use shared libraries generated by Fortran in Python with NumPy arrays, from the [pyccel](https://github.com/pyccel/pyccel) project. It is based on CFFI and currently assumes the use of gfortran or Intel Fortran.

[fgen](https://pypi.org/project/fgen/): provides Python interfaces to Fortran code, specifically derived types, by Jared Lewis and Zebedee Nicholls. An example of fgen-wrapped Fortran code is at [fgen-example](https://github.com/lewisjared/fgen-example).

[fimport](https://github.com/pv/fimport): Python import hook for importing Fortran module, by Pauli Virtanen

[fmodpy](https://github.com/tchlux/fmodpy): lightweight, efficient, highly automated, Fortran wrapper for Python, by Thomas Lux. The generated wrappers are self contained, written purely in Python, and are immediately sharable to any other POSIX platform with a Fortran compiler installed. 

[fortformat](https://github.com/joshua-laughner/fortformat): Rust parser for Fortran format strings, by Joshua Laughner

[Forthon](https://github.com/dpgrote/Forthon): Python wrapper generator for Fortran, allowing access to functions and subroutines, by David Grote et al.

[FortModGen](https://github.com/neut-devel/FortModGen): generate consistent Fortran and C/C++ data structures, and a consistent C/C++ API from a toml configuration file for global object interop, from neut-devel

[fortran2cc2fortran](https://github.com/hansalemaos/fortran2cc2fortran): Fortran to C / C to Fortran (nested) index converter, by Hans Alemão

[Fortran90Namelists.jl](https://github.com/singularitti/Fortran90Namelists.jl): Julia implementation of Python [f90nml](https://github.com/marshallward/f90nml) for working with Fortran namelists

[FortranFile](https://github.com/ncke/FortranFile): read data using Swift from files using a Fortran format specification, by Nick Everitt

[FortranFiles.jl](https://github.com/traktofon/FortranFiles.jl): Julia package for reading/writing Fortran unformatted (i.e. binary) files, by Frank Otto et al.

[Fortran filesystem](https://github.com/scivision/fortran-filesystem): file system path manipulation utilities for standard Fortran, from scivision. Inspired by Python pathlib and C++17 filesystem.

[FORTRAN format interpreter for Python (py-fortranformat)](https://github.com/brendanarnold/py-fortranformat): Generates text from a Python list of variables or will read a line of text into Python variables according to the FORTRAN format statement passed, by Brendan Arnold and michaelackermannaiub

[fortran_magic](https://github.com/mgaitan/fortran_magic): extension for IPython/Jupyter that helps to use Fortran in an interactive session, by Martín Gaitán

[FortranNamelist](https://github.com/jonathanschilling/FortranNamelist): Java reading class for Fortran namelists, by Jonathan Schilling

[Fortran Namelist Reader](https://github.com/scivision/fortran-namelist): Python and Matlab readers for Fortran namelist => dict / struct, from scivision

[fortran-namelist](https://github.com/sajinh/fortran-namelist): Ruby library to manipulate Fortran namelists, by Saji Hameed

[fortran-unix](https://github.com/interkosmos/fortran-unix): Fortran 2008 ISO C binding interfaces to selected POSIX and SysV types, functions, and routines on 64-bit Unix-like operating systems, by interkosmos

[fpydemo](https://github.com/banskt/fpydemo): demonstration of packaging a command line tool written in Python and Fortran, by Saikat Banerjee

[ftest](https://github.com/bnaras/ftest): demonstrates how to call R functions from Fortran, by Balasubramanian Narasimhan. A fully worked example is provided in the form of a vignette.

[fython](https://github.com/nicolasessisbreton/fython): Fython is Fortran with a Python syntax, by Nicolas Essis-Breton. Fython code can be used in Python with a standard import statement.

[GenericF2PY](https://github.com/sonofeft/GenericF2PY): demonstrates how to handle Fortran binaries in Python modules, by Charlie Taylor

[gfort2py](https://github.com/rjfarmer/gfort2py): library to allow calling Fortran code compiled with gfortran from Python 2.7 or Python 3, by Robert Farmer and Ondřej Čertík

[h2m-Autofortran-Tool](https://github.com/Kaiveria/h2m-Autofortran-Tool): allow easy calls to C routines from Fortran programs, by Garnet Liu and Michelle Anderson. Given a header file in standard C, h2m will produce a Fortran module providing function interfaces which maintain interoperability with C. Features for which there are no Fortran equivalents will not be translated and warnings will be written to standard error.

[haskell-fortran](https://github.com/freckletonj/haskell-fortran): example of how to use Haskell's foreign function interface (FFI), and C's Fortran FFI, to connect ultimately Fortran code to Haskell, and to Haskell's HMatrix library, by Josh Freckleton

[jansfortrankernel](https://github.com/jans-code/jansfortrankernel): Jupyter kernel implementation of Fortran, by Jan Arman Parpin

[libfde](https://github.com/Zorkator/libfde): Fortran Development Extensions (library), by Zorkator

[M_process](https://github.com/urbanjost/M_process): read and write lines to or from a process from Fortran via a C wrapper, by urbanjost

[M_system](https://github.com/urbanjost/M_system): module that allows Fortran to call commonly available C routines that perform basic system operations like creating and deleting files and directories, changing and querying file permits, getting basic ID and process information, ... and other POSIX system requests, by urbanjost

[multilingual-julia](https://github.com/ahbarnett/multilingual-julia): minimally complete examples of Julia calling and being called by Fortran, C, and Python, by Alex Barnett

[Mwrap](https://github.com/zgimbutas/mwrap): interface generation system in the spirit of SWIG or matwrap, by Zydrunas Gimbutas et al. From a set of augmented MATLAB script files, MWrap will generate a MEX gateway to desired C/C++/Fortran function calls and MATLAB function files to access that gateway. [Mwrapdemo](https://github.com/ahbarnett/mwrapdemo) by Alex Barnett contains simple, minimally complete examples showing how to use MWrap to link to a C or Fortran library, pass in and out 1D and 2D arrays, handle complex, float, and Boolean types, and use OpenMP.

[namelist_python](https://github.com/leifdenby/namelist_python): Fortran namelist parser in Python, by Leif Denby et al.

[nml](https://github.com/jsta/nml): R package for parsing Fortran namelist files, by Jem Stachelek et al.

[nml](https://github.com/maddenp/nml): query/modify utility in Clojure for Fortran namelists, by Paul Madden and Jemma Stachelek

[nml](https://github.com/manorom/nml): serialize and deserialize Fortran namelist input in Rust using the [serde](https://serde.rs/) framework, by manorom

[node-fortran](https://github.com/IonicaBizau/node-fortran): bridge that allows Fortran code to be from Node.js, by Ionică Bizău

[process_model](https://github.com/Cambridge-ICCS/process_model): reads a TensorFlow SavedModel and outputs Fortran code to interface it to the [fortran-tf-lib](https://github.com/Cambridge-ICCS/fortran-tf-lib), by Simon Clifford et al.

[pyifb](https://github.com/rjfarmer/pyifb): Python interface to Fortran's ISO_Fortran_binding.h, by Robert Farmer

[RFortranRcpp](https://github.com/Konrad1991/RFortranRcpp): communication between Fortran, Rcpp and R, by Konrad1991.  Passing R or Fortran user code to Fortran code from a package.

[setup_mex](https://github.com/equipez/setup_mex): provides scripts that attempt to facilitate setting up the MATLAB MEX on macOS or Windows, by Zhang Zaikun. For Fortran, it will install (automatically) the Fortran compiler from Intel oneAPI

[shroud](https://github.com/LLNL/shroud): creates a Fortran or Python interface to a C or C++ library, from LANL. It can also create a C API for a C++ library.

[Simplified Wrapper and Interface Generator (SWIG)](https://github.com/swig-fortran/swig): creates Fortran wrapper code from C++ headers

[SUtools](https://github.com/bnaras/SUtools): Tools for autogenerating Fortran registration code for R, by Balasubramanian Narasimhan

[thenamelisttool](https://github.com/UMR-CNRM/thenamelisttool): provide command line tools useful to work with namelists or pack of namelists (update them, compare them, ...), by Louis-François Meunier and Alexandre Mary

[TorchFort](https://github.com/NVIDIA/TorchFort): deep learning training and inference interface for HPC programs implemented using LibTorch, the C++ backend used by the PyTorch framework. This library can be invoked directly from Fortran or C/C++ programs.

[vecLibFort](https://github.com/mcg1969/vecLibFort): lightweight but flexible "shim" designed to rectify the incompatibilities between the Accelerate/vecLib BLAS and LAPACK libraries shipped with Mac OS X and FORTRAN code compiled with modern compilers such as GNU Fortran, by Michael C. Grant and Robert Huston

### Parallel Programming
[allgebra](https://github.com/ricosjp/allgebra): docker images for developing C++ and Fortran HPC programs, by termoshtt and t-hishinuma

[Codee](https://www.codee.com/): automatic code inspection platform specialized in performance for time-critical C/C++/Fortran applications (C). Training materials are [here](https://www.nersc.gov/users/training/events/codee-training-series-apr2023/).

[fortran-parser](https://github.com/ToxPuro/fortran-parser): Fortran preprocessor in Python, by Touko Puro, designed for multithreading and GPU offloading through OpenMP, featuring automatic privatization of modified global variables in multithreaded code, Fortran array operation unrolling to DO-loops with automatic declaratives to spread work either along CPU or GPU threads, automatic declarations for global variables needed in target regions, and function inlining which helps OpenMP offloading

[gpufort](https://github.com/ROCmSoftwarePlatform/gpufort): source-to-source translation tool for CUDA Fortran and Fortran+X in the spirit of [hipify](https://github.com/ROCm-Developer-Tools/HIPIFY)

[hipfort](https://github.com/ROCmSoftwarePlatform/hipfort): Fortran Interface For GPU Kernel Libraries

[Hybrid-Fortran](https://github.com/muellermichel/Hybrid-Fortran): directive-based extension for the Fortran language to support GPGPU. Its input is Fortran code with Hybrid Fortran extensions, and its output is CUDA Fortran or OpenMP Fortran code.

[mpich](https://github.com/pmodels/mpich): high-performance and widely portable implementation of the MPI-3.1 standard from the Argonne National Laboratory

[occa](https://github.com/libocca/occa): portable, and vendor neutral framework for parallel programming on heterogeneous platforms. The OCCA API provides unified models for heterogeneous programming concepts—such as a device, memory, or kernel—while the OCCA Kernel Language (OKL) enables the creation of portable device kernels using a directive-based extension to the C-language.

[ohhelp-for-fpm](https://github.com/Nkzono99/ohhelp-for-fpm): dynamic load balancing and scalability library that supports massively parallel particle-in-cell simulations using MPI. Each process handles the particle calculations within the partitioned area while taking on some of the particles handled by other processes so that the overall load is balanced.

[Omni Compiler](https://github.com/omni-compiler/omni-compiler): compiler for code including XcalableMP, XcalableACC, and OpenACC directives. The base languages supported by Omni Compiler are C language (C99) and Fortran 2008 in XcalableMP, and C language (C99) in XcalableACC and OpenACC.

[OMPify](https://github.com/talkad/OMPify): generates OpenMP pragmas for C, C++ and Fortran code snippets using Transformers.

[OpenCoarrays](https://github.com/sourceryinstitute/opencoarrays): supports Fortran 2018 compilers by providing a parallel application binary interface (ABI) that abstracts away the underlying parallel programming model, which can be the Message Passing Interface (MPI) or OpenSHMEM, 
from sourceryinstitute

[SPEL_OpenACC](https://github.com/peterdschwartz/SPEL_OpenACC): code associated with the paper [SPEL: Software tool for Porting E3SM Land Model with OpenACC in a Function Unit Test Framework](https://ieeexplore.ieee.org/document/10029551), by Peter Schwartz et al., 2022 Workshop on Accelerator Programming Using Directives (WACCPD). It provides a robust method to port the [E3SM Land Model (ELM)](https://e3sm.org/model/e3sm-model-description/v1-description/v1-land/) onto GPUs.

[stng](https://github.com/uwplse/stng): compiler for Fortran stencils using verified lifting, by Alvin Cheung et al. It takes input codes in Fortran and automatically rewrites them to Halide, a new high-performance domain-specific language that leverages GPUs for computation.

[System FOR Automated Parallelization (SAPFOR)](https://github.com/dvm-system/sapfor): software development suite that is focused on cost reduction of manual program parallelization, by kaniandr and zoocide. It was primarily designed to perform a source-to-source transformation of a sequential program for execution on heterogeneous clusters.

### Plotting
[accis](https://github.com/ihutch/accis): plotting and graphics library by Ian Hutchinson. Related project: [PLOTTRACES](https://github.com/ihutch/PLOTTRACES)

[asgl](https://github.com/salilab/asgl): produces a PostScript or Encapsulated PostScript file that can contain scatter plots, line plots, histograms, 2D density plots, and/or bond-and-stick plots of molecules, by Andrej Šali

[CHART_COUPE](https://github.com/meom-group/CHART_COUPE): Fortran plotting package based on NCL libraries, tuned for geophysical numerical model output, from meom-group

[DISLIN](https://www.dislin.de/): high-level plotting library for displaying data as curves, polar plots, bar graphs, pie charts, 3D-color plots, surfaces, contours and maps, available for several C, C++, Fortran 77 and Fortran 90/95 compilers on the operating systems Unix, Linux, FreeBSD, Windows, Mac OSX and MS-DOS. The DISLIN distributions can be used freely without any restrictions. Access to the source code and a preferred support is available via a contract.

[Dislin_x_y_plot](https://github.com/andizuend/Dislin_x_y_plot): generates plots from within a Fortran program nearly as easily as with the provided [Dislin](https://www.dislin.de/) "quickplots", by Andi Zuend. However, unlike the quickplots, this module offers a lot more options for controlling the plot page, axis system and various curve properties. It also makes adding multiple x--y data sets (curves) to a single plot easy.

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

[PLplot](http://plplot.org/): can be used to create standard x-y plots, semi-log plots, log-log plots, contour plots, 3D surface plots, mesh plots, bar charts and pie charts. Multiple graphs (of the same or different sizes) may be placed on a single page, and multiple pages are allowed for those device formats that support them. C library with bindings to Fortran 2003 and many other languages. [archlinux-plplot-fortran](https://github.com/easifem/archlinux-plplot-fortran) has a plplot build for Fortran on archlinux, by Vikas Sharma.

[PlPlotLib](https://github.com/zoziha/PlPlotLib): wrapper for PlPlot inspired by the interface of matplotlib, by zoziha. It is intended to fill the need for rapid feedback while developing numerical simulations, and does not replace more sophisticated packages such as matplotlib or even direct use of PlPlot.

[pltFor](https://github.com/DamienMinenna/pltFor): Fortran-Python interface library by Damien Minenna to plot figures directly in Fortran, by calling Matplotlib 

[PSPLOT](https://hcas.nova.edu/tools-and-resources/psplot/index.html): library of Fortran-callable subroutines which can be combined in a calling program to produce PostScript plot files. Intended for users interested in generating technical drawings or graphics for technical journals in PostScript format.

[PyFerret](https://github.com/NOAA-PMEL/PyFerret): Ferret is an interactive computer visualization and analysis environment designed to meet the needs of oceanographers and meteorologists analyzing large and complex gridded data sets, from NOAA/PMEL. It runs on recent Unix and Mac systems, using X windows for display. PyFerret, introduced in 2012, is a Python module wrapping Ferret.

[pyplot-fortran](https://github.com/jacobwilliams/pyplot-fortran): generate plots from Fortran using Python's matplotlib.pyplot, by Jacob Williams

[SPLASH](https://github.com/danieljprice/splash): visualisation tool for Smoothed Particle Hydrodynamics (SPH) simulations in one, two and three dimensions, developed mainly for astrophysics, by Daniel Price et al. It uses a command-line menu but data can be manipulated interactively in the plotting window. SPLASH can also be used as a standalone plotting tool for any kind of tabulated or image data from ascii, csv or .fits files.

### Preprocessors
[efpp](https://github.com/akageyama/efpp): preprocessor for eFortran, a dialect of modern Fortran presented in S. Hosoyamada and A. Kageyama, [A Dialect of Modern Fortran for Simulations in Methods and Applications for Modeling and Simulation of Complex Systems](https://link.springer.com/chapter/10.1007/978-981-13-2853-4_34), Communications in Computer and Information Science, vol 946, pages 439-448, 2018 (Proceedings of AsiaSim2018).

[exceptions](https://github.com/arjenmarkus/exceptions): experiment with exceptions in Fortran via a simple preprocessing step, by Arjen Markus

[f90 do nest](https://github.com/hattom/f90_do_nest): Python script to generated deeply nested do loops in Fortran, by Thomas Hayward-Schneider. It will generate "classical" nested do/enddo in f90code.F90 and also a do concurrent version in f90code_conc.F90.

[FMacro](https://github.com/hsnyder/FMacro): template preprocessor for Fortran, by Harris Snyder. Aims to address Fortran's lack of support for generic programming with a simple preprocessor, modeled after some of the language committee's early ideas for a template language feature, to be included in a future Fortran standard.

[fortiel](https://github.com/Jhuighuy/fortiel): Fortran preprocessor and metaprogramming engine, by Jhuighuy

[fypp](https://github.com/aradi/fypp): Python-powered preprocessor, by aradi. It can be used for any programming languages but its primary aim is to offer a Fortran preprocessor, which helps to extend Fortran with condititional compiling and template metaprogramming capabilities

[prep](https://github.com/urbanjost/prep): Fortran pre-processor written in Fortran, by urbanjost

### Profiling
[Caliper](https://github.com/LLNL/Caliper): library to integrate performance profiling capabilities into applications, from LANL. To use Caliper, developers mark code regions of interest using Caliper's annotation API. Applications can then enable performance profiling at runtime with Caliper's configuration API.

[HPCToolkit](http://hpctoolkit.org/): integrated suite of tools for measurement and analysis of program performance on computers ranging from multicore desktop systems to the nation's largest supercomputers. By using statistical sampling of timers and hardware performance counters, HPCToolkit collects accurate measurements of a program's work, resource consumption, and inefficiency and attributes them to the full calling context in which they occur. 

[MALloc Tracker (malt)](https://github.com/memtt/malt): finds where and how memory is allocated in C/C++/Fortran applications

[Reference-Counter](https://github.com/sourceryinstitute/reference-counter): extensible, object-oriented reference-counting utility for Fortran, described in Rouson, Morris & Xia (2012) [This Isn't Your Parents' Fortran: Managing C++ Objects with Modern Fortran.](https://ieeexplore.ieee.org/document/6159199) Computing in Science & Engineering 14(2), 46-54.

[timemory](https://github.com/NERSC/timemory): performance measurement and analyis package with modular and reusable components which can be used to adapt to any existing C/C++ performance measurement and analysis API and is arbitrarily extendable by users within their application, from NERSC

### Refactoring
[Fortran Language Program Remodeling system (FLPR)](https://github.com/lanl/FLPR):  C++17 library for manipulating Fortran source code, from LANL. This package contains a "best effort" Fortran 2018 input parser for fixed and free form inputs, data structures for manipulating source code at the program unit, statement, and physical line levels, and sample applications that illustrate usage and provide some ideas as to how you could use the library.

[Glasgow Fortran Source-to-Source Compiler (RefactorF4Acc)](https://github.com/wimvanderbauwhede/RefactorF4Acc): automatic refactoring tool to make Fortran code acceleration-ready, by wimvanderbauwhede and rouson. RefactorF4Acc's main purpose is to make legacy FORTRAN 77 acceleration-ready. In the process it converts FORTRAN 77 code into Fortran 95. In addition, RefactorF4Acc has a backend to translate modules to C/OpenCL.

[Fortran Kernel Generator: KGen](https://github.com/NCAR/KGen): Python tool that extracts partial codes out of a large Fortran application and converts them into a standalone/verifiable/executable kernel, by Youngsung Kim and John Dennis

[fortrantools](https://github.com/CodethinkLabs/fortrantools): tools to enable the use old or proprietary Fortran code with gfortran. They are intended to be used together with the gcc extensions in CodethinkLab's gcc branch.

[Refactoring Of QUEstionable FORTran (Roquefort)](https://github.com/NLESC-JCER/roquefort): creates module to replace existing common blocks, removes unused variable imported from modules, transforms implicit variable declaration to explicit variable declaration, and moves variables to a new module, from NLESC-JCER

### Static Analysis
[camfort](https://github.com/camfort/camfort): refactoring and verification tool for scientific Fortran programs. It currently supports Fortran 66, 77, and 90 with various legacy extensions.

[Cleanscape FortranLint](https://stellar.cleanscape.net/products/fortranlint/): static source code analysis tool that reduces your organizational exposure to risks from latent software problems by automatically identifying problems at their source -- in the Fortran code prior to compiling or executing programs. (C)

[CompareFortranNamelists](https://github.com/kellekai/CompareFortranNamelists): Python class to compare Fortran namelists, by Kai Keller

[Code Comprehension Assistance for Evidence-Based performance Tuning (CCA/EBT)](https://github.com/ebt-hpc/cca-ebt): extracts the syntactic/semantic structures from Fortran code and then provides outline views of the loop-nests and the call trees decorated with source code metrics.

[FF08Diff](https://www.megms.com.au/ff08diff.htm): command line tool for obtaining the semantic difference (difference in meaning, rather than appearance) between two sets of Fortran 2008 source files, written in Fortran 2003 by IanH

[flint](https://github.com/JonasToth/flint): Little linter for Fortran, with static analysis and formatting, by JonasToth

[flint](https://github.com/marshallward/flint): aspires to be a Fortran parser, delinter, and analyser, by marshallward. For now, it is a Fortran tokenizer, with tools for parsing and automated documentation.

[flint](https://pypi.org/project/flinter/): source-code static analyzer and quality checker with multiple programming languages support. For fortran, it intends to follow the coding conventions mentioned in [OMS Documentation Wiki page](https://alm.engr.colostate.edu/cb/wiki/16983).

[Forcheck](http://www.codework-solutions.com/development-tools/forcheck-fortran-analysis/): oldest and most comprehensive Fortran analysis tool on the market. It performs a static analysis of a Fortran program or separate Fortran program units. (C)

[fordoctest](https://github.com/fedebenelli/fordoctest/): assures consistent documentation of a Fortran code, by Federico E. Benelli, checking on the source files included in a [FORD](https://github.com/Fortran-FOSS-Programmers/ford) file and warning if there is more than one module per file or if there are undocumented isolated procedures, modules, module procedures, or procedure arguments.

[fortitude](https://github.com/PlasmaFAIR/fortitude): Fortran linter and formatter, written in Rust, from PlasmaFAIR

[FortranAS](https://github.com/akoerner/FortranAS): [Antlr4](https://github.com/antlr/antlr4)-powered FORTRAN parsing and code clone detection tool. FortranAS leverages grammars-v4 to generate parsers and lexers and supports any FORTRAN version with available corresponding grammars.

[fortree](https://github.com/EstherTaillifet/fortree): Python app that creates call trees of your Fortran code, by Esther Taillifet. Fortree makes call trees, definition trees and dependencies trees.

[ForUML](https://github.com/t2time/ForUML): reverse engineering tool that generates Unified Modeling Language (UML) class diagrams from object-oriented Fortran programs, by azizn and Damian Rouson. ForUML understands and diagrams Fortran class relationships, including inheritance and aggregation. ForUML also detects and depicts operator overloading, constructors, and parallel data structures (coarrays).

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

[fxtran](https://github.com/pmarguinaud/fxtran): parses Fortran source code and decorates it with XML tags. The result is an XML file which can be searched with XPath, and modified with the DOM API.

[i-CodeCNES](https://github.com/cnescatlab/i-CodeCNES): static code analysis tool to help developers write code compliant with CNES coding rules for Fortran 77, Fortran 90 and Shell, from cnescatlab. Related project: [sonar-icode-cnes-plugin](https://github.com/cnescatlab/sonar-icode-cnes-plugin)

[K-scope](https://github.com/K-scope/K-scope): source code analysis tool with graphical user interface that visualizes program structures for Fortran 90 and FORTRAN 77 source code. This tool simply visualizes call tree from AST based on compiler's static analysis.

[plusFORT](https://www.fortran.uk/fortran-analysis-and-refactoring-with-plusfort/plusfort-evaluation-version/pss-evaluation-starter-pack/) - multi-purpose suite of tools for analyzing and improving Fortran programs, free for personal, educational and academic users working on non-commercial projects. (C)

[pyft](https://github.com/UMR-CNRM/pyft): Python script that reads a Fortran code, parses it in xml, performs some manipulations, and reverts it to Fortran, from UMR-CNRM. It can add and remove variable declarations, find unused variables, convert code to lower or upper case, and do other things listed [here](https://github.com/UMR-CNRM/pyft/blob/main/doc/Documentation.md).

[Simple Lint GitHub Action (simple_lint)](https://github.com/NOAA-GFDL/simple_lint): runs simple lint-like actions on files in a git repository, from NOAA-GFDL. The current list of lint actions are to check for trailing whitespace, check Fortran files for use of tab characters, and check Fortran files for lines longer then a specified length.

[tree-sitter-fortran](https://github.com/stadelmanma/tree-sitter-fortran): Fortran grammar for [tree-sitter](https://github.com/tree-sitter/tree-sitter), by Matthew Stadelman et al.

[Understand](https://scitools.com/): static analysis tool focused on source code comprehension, metrics, and standards testing, supporting standards through Fortran 2008 (C)

### Text Editors, Integrated Development Environments, and Plugins
[atom-build-fpm](https://github.com/everythingfunctional/atom-build-fpm): plugin for running the Fortran Package Manager (fpm) from within Atom

[Code::Blocks](https://www.codeblocks.org/): free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. SYLau has created a short [tutorial](https://github.com/SYLau/Tutorial) on using Fortran with Code::Blocks.

[linter-gfortran](https://github.com/AtomLinter/linter-gfortran): linting Fortran code in [Atom](https://github.com/atom) with gfortran

[f90.kak](https://github.com/freevryheid/f90.kak): modern Fortran syntax for [kakoune](https://kakoune.org/) editor, by Andre Smit

[FortranCodeNav](https://github.com/tiemenschreuder/FortranCodeNav): Visual Studio Extension which helps navigate modern Fortran code, by Tiemen Schreuder. It contains several parsers to generate a code structure representation which is used to provide jump-to and search functionality with limited context-awareness.

[Fortran IntelliJ Idea plugin](https://github.com/satamas/fortran-plugin): Fortran language plugin for IntelliJ Idea, by satamas

[Fortran Language Server](https://github.com/hansec/fortran-language-server): A Fortran implementation of the Language Server Protocol using Python (2.7+ or 3.0+), by hansec. Editor extensions using this language server to provide autocomplete and other IDE-like functionality are available for Atom, Visual Studio Code, Visual Studio, (Neo)vim, and Emacs.

[Fortran Language Server (fortls)](https://github.com/gnikit/fortls): based on @hansec's original Language Server implementation but the two projects have since diverged. fortls (this project) is now developed independently by gnikit of the upstream hansec/fortran-language-server project and contains numerous bug fixes and new features the original fortran-language-server does not.

[fortranNeoVIM](https://github.com/Vuncano/fortranNeoVIM): neovim config for Fortran programming, by Vuncano. Config files made using Lua, inpired by third part config. Also [FortranDictionary_vim](https://github.com/Vuncano/FortranDictionary_vim), a Fortran keyword dictionary, or word list, made to use specially with vim's built-in dictionary completion

[fortran_syntax_highlighter_lite-xl](https://github.com/RohanVashisht1234/fortran_syntax_highlighter_lite-xl): syntax highlighter for Fortran in [lite-xl](https://lite-xl.com/), by Rohan Vashisht

[fortran.tmbundle](https://github.com/textmate/fortran.tmbundle): TextMate support for Fortran. TextMate is a graphical text editor for macOS 10.12 or later.

[fortran-vim-plugin](https://github.com/terminationshock/fortran-vim-plugin): Vim plugin for Fortran developers that can be used to jump to the declaration of a variable, subroutine, function, etc. and to all its references, by Tobias Melson

[fossil](https://github.com/nrwade0/Fossil): Fortran IDE designed in Python by someone eager to learn Fortran but in an easy and accessible way, by nrwade0

[Guide_VSCode-fortran](https://github.com/JHenneberg/Guide_VSCode-fortran): comprehensive guide on how to set up a complete development environment for Fortran in Visual Studio Code, by Julian Henneberg

[Modern-Fortran](https://github.com/eirik-kjonstad/modern-fortran-syntax): language syntax for highlighting of Fortran code in [Sublime Text](https://www.sublimetext.com/), by eirik-kjonstad. It highlights modern Fortran (Fortran 90 and newer) and incorporates features introduced in Fortran 2003, 2008, and 2018.

[neovim](https://github.com/neovim/neovim): Vim-fork focused on extensibility and usability

[Photran](https://www.eclipse.org/photran/): IDE and refactoring tool for Fortran based on Eclipse and the CDT. Photran supports Fortran 77-2008. It includes 39 refactoring, including Rename, Extract Procedure, and loop transformations

[qtcreator-fortran](https://github.com/jonaslindemann/qtcreator-fortran): support for Fortran projects and source files in [Qt Creator](https://www.qt.io/product/development-tools) as well as syntax-highlighting, by Jonas Lindemann

[Simply Fortran](http://simplyfortran.com/): modern Fortran development environment for Microsoft Windows, Apple macOS, and GNU/Linux systems. It includes the Aplot library for creating two-dimensional graphs and plots quickly from Fortran routines and [AppGraphics](https://simplyfortran.com/features/appgraphics) for creating graphics and graphical user interfaces from either Fortran or C. Free 30-day trial. (C)

[SublimeLinterFortran](https://github.com/Panadestein/SublimeLinterFortran): linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to gfortran, by Ramón L. Panadés-Barrueta and Tejas Shetty. It will be used with files that have free format Fortran syntax.

[TiddlyFor](https://github.com/kookma/TiddlyFor): single file, self-contained wiki, a a flavor of [TiddlyWiki](https://tiddlywiki.com/), for a Fortran programmer but that can be used for any other purposes, by Mohammad Rahmani. It can be put on the web, sent as an email attachment, or put on a thumb drive. Some features are syntax highlighting for modern Fortran and support for math formulas through katex. 

[vim](https://github.com/vim/vim): improved version of the UNIX editor Vi. Many new features have been added: multi-level undo, syntax highlighting, command line history, on-line help, spell checking, filename completion, block operations, script language, etc. Download [here](https://www.vim.org/download.php). 

[vimf90](https://github.com/rudrab/vimf90): Fortran ide for vim

[vim-findent](https://github.com/cradesto/vim-findent): vim plugin for [Findent](https://github.com/MFTabriz/findent), which indents Fortran sources, by cradesto

[vim-fortran-fpm](https://github.com/avysk/vim-fortran-fpm): convenience functions for integrating vim with Fortran Package Manager, by Alexey Vyskubov

[vim-FORTRAN-UPPER](https://github.com/wcdawn/vim-FORTRAN-UPPER): vim plugin for automatic capitalization in Fortran source, by William C. Dawn

[vim-tmux-IDE](https://github.com/luco00/vim-tmux-IDE): minimal vim IDE by luco00. Sets a connection with external terminal via tmux to interactively execute code (Python, R, Julia, Fortran, Go are supported).

[Visual Studio Code (vscode)](https://github.com/microsoft/vscode): combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle, from Microsoft. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

[vs-fortran-ls-client](https://github.com/JHenneberg/vs-fortran-ls-client): Language Server Protocol client that connects to [Chris Hansen's Fortran Language Server](https://github.com/hansec/fortran-language-server/) to add IntelliSense for Fortran to Visual Studio 2017

[vscode-fortran-support](https://github.com/krvajal/vscode-fortran-support): extension that provides support for the Fortran programming language. It includes syntax highlighting, debugging, code snippets and a linting based on gfortran.

[vscode-modern-fortran-formatter](https://github.com/yukiuuh/vscode-modern-fortran-formatter): formatter extension for modern Fortran using fprettify, by Yuki Hanayama

[Yapakit](http://yapakit.fortran.pagesperso-orange.fr/): free Fortran source code editor for Windows, Linux or Mac. It can automatically an html documentation of a project and generate Fortran 90 dependencies for inclusion in a makefile, taking module dependencies into account

### Translation from Fortran
[f2c](https://github.com/juanjosegarciaripoll/f2c): convert Fortran 77 to C

[F2C-Translator](https://github.com/bin123apple/F2C-Translator): translates Fortran to C++, by Bin Lei. Also [HPC-Code-translation-and-generation](https://github.com/bin123apple/HPC-Code-translation-and-generation): tests the translation and generation performance of Fortran HPC code using CodeXGLUE and ChatGPT, and 
[OpenMP-Fortran-CPP-Translation](https://github.com/bin123apple/OpenMP-Fortran-CPP-Translation), associated with the paper [Creating a Dataset for High-Performance Computing Code Translation using LLMs: A Bridge Between OpenMP Fortran and C++](https://arxiv.org/abs/2307.07686)

[f2cpp](https://github.com/victorliu/f2cpp): Converts Fortran 77 code to C++, by victorliu. Unlike f2c, the output of f2cpp.pl may or may not compile, however, only a small number of hand-tuned changes are typically needed. The resulting code is much cleaner than f2c's output, and much closer to the original intent of the original Fortran code.

[f2j](https://github.com/jonathanschilling/f2j): translate Fortran 77 to Java, especially for BLAS, LAPACK and ARPACK

[f2matlab](https://github.com/benbarrowes/f2matlab): converts Fortran 90 code to Matlab m-files, by benbarrowes. Accordingly, only basic data types and constructions are recommended.

[f2perl](https://f2perl.sourceforge.net/): translates Fortran 77 into Perl, by Steve Hancock. Also at [GitHub](https://github.com/shancock9/f77-to-perl).

[f4go](https://github.com/Konstantin8105/f4go): Transpiling Fortran code to golang code, by Konstantin8105

[F77Ccompiler](https://github.com/sthfaceless/F77Ccompiler): compiler from Fortran 77 to C, by Danil

[Fortran-CPP-HPC-code-translation-dataset](https://github.com/bin123apple/OpenMP-Fortran-CPP-Translation): data set for the preprint [Creating a Dataset for High-Performance Computing Code Translation: A Bridge Between HPC Fortran and C++](https://arxiv.org/abs/2307.07686) (2023), by Bin Lei et al.

[Fortran to C++ Conversion from Objexx](https://objexx.com/Fortran_to_Cpp.html): conversion process preserves the structure and syntax of the Fortran to retain the value of the existing documentation and developer knowledge. Another product [converts Fortran to Python](https://objexx.com/Fortran_to_Python.html) (C).

[fortran2julia](https://github.com/algorithmx/fortran2julia): Python script to translate Fortran 90 to Julia, by algorithmx

[fortran2julia](https://github.com/TomRottier/fortran2julia): parses to JSON by [fortran-parser](https://github.com/robinrottier/fortran-parser), after which parse.jl converts to JSON to Julia, by Tom Rottier. Requires dotnet runtime to be installed.

[Fortran2Julia.js](https://github.com/ohno/Fortran2Julia.js): converts Fortran codes to Julia codes using regular Expressions, groups and backreferences, by Shuhei Ohno. A web interface is [here](https://ohno.github.io/Fortran2Julia.js/).

[FortranTranspiler.jl](https://github.com/denius/FortranTranspiler.jl): partial transpiler from Fortran to Julia, by Denis Telnov

[Incomplete Fortran to C/C++ converter](https://simulationcorner.net/index.php?page=if2c): translates Fortran 77 to readable C/C++, by Sebastian Macke

[loki](https://github.com/ecmwf-ifs/loki): tool to explore the possible use of source-to-source translation for ECMWF's Integrated Forecasting System (IFS) and associated Fortran software packages. Loki is based on compiler technology (visitor patterns and ASTs) and aims to provide an abstract, language-agnostic representation of a kernel, as well as a programmable (Pythonic) interface that allows developers to experiment with different kernel implementations and optimizations. 

### Translation to Fortran
[c2f](https://github.com/Beliavsky/c2f): partial C to Fortran translator by David Frank

[matlab2fmex](https://sourceforge.net/projects/matlab2fmex/): small translator which aims to convert numerical Matlab m-files to Fortran90 mex files, by Ben Barrowes. matlab2fmex first translates an m-file to a Fortran90 mex source file then compiles that Fortran90 file using Matlab's mex and the local compiler.

[matlab2fortran](https://github.com/ebranlard/matlab2fortran): performs some simple conversions from Matlab code to Fortran, by ebranlard

[Mc2For](https://github.com/Sable/Mc2For): MATLAB to Fortran compiler, from Sable

[pyccel](https://github.com/pyccel/pyccel): Pyccel can be viewed as a Python-to-Fortran/C converter or a compiler for a Domain Specific Language with Python syntax

### Unclassified
[automates](https://github.com/ml4ai/automates): Automated Model Assembly from Text, Equations, and Software, from ml4ai

[bench-cli](https://github.com/Lateralus138/bench-cli): cross-platform command line tool to benchmark commands and other executables/scripts in command lines written in Fortran, by Lateralus138. Very precise and fast.

[Fortran Debug Utilities](https://github.com/plevold/fortran-debug-utils): collection of some utilities useful for debugging code, by Pål Levold

[Fortran-gdb-pp](https://github.com/ZedThree/Fortran-gdb-pp): gdb pretty printer for Fortran dynamic types, by Peter Hill

[fortran-git](https://github.com/interkosmos/fortran-git): Fortran 2008 ISO C binding interfaces to [libgit2](https://github.com/libgit2/libgit2), by interkosmos

[Fortran-RefCount](https://github.com/LadaF/Fortran-RefCount): simple reference counting for Fortran

[fortran-sigwatch](https://github.com/scivision/fortran-sigwatch): library of routines to provide simple signal watching for Fortran programs, originally by Norman Gray, modified by Michael Hirsch. This allows a minimal level of control of a running program from outside it, for example to tell it to checkpoint itself on receipt of a signal.

[Fortran-Standard-Search](https://github.com/vmagnin/Fortran-Standard-Search): shell script searching a string in the titles of the subsection of the Fortran standard, and opening the pages in a PDF viewer, by Vincent Magnin. It is based on pdfgrep, cut and okular.

[FORTRAN Testing Framework (FTFramework)](https://github.com/agforero/FTFramework): collection of Python and Bash scripts to enable easy testing of Fortran compilers using BATS, by agforero

[irep](https://github.com/LLNL/irep): tool for filling C/C++ or Fortran data structures from Lua input tables, from LLNL

[libconfort](https://github.com/gronki/libconfort): a small library to handle simple configuration files from Modern Fortran (2008+), by Dominik Gronkiewicz

[nmltab](https://github.com/aekiss/nmltab): Python 3 module and command-line tool to tabulate, semantically diff, superset and consistently format Fortran namelist files, with output to text, markdown, csv, latex and namelists, by Andrew Kiss and Aidan Heerdegen. Requires Python 3.4 or later, and f90nml (amongst other packages).

[nml-to-f90](https://github.com/perrette/nml-to-f90): generates Fortran source code for handling parameter I/O from a namelist, by perrette

[progRESS+repORT (progrep}](https://github.com/SomajitDey/progrep): utility to show live progress, status and stats of a running simulation or any compute job that executes a given number of iterations, by SomajitDey. Progrep can report for both serial (single-core) and parallel (multi-core/multi-node - e.g. OpenMP/MPI) jobs.

### Unit Testing
[FortCompare](https://github.com/aijac0/fortran_regression_testing_tool): tool to mitigate the amount of behavior changed between two implementations of the same Fortran function or subroutine, by aijac0

[fortran-testanything](https://github.com/dennisdjensen/fortran-testanything): test library supporting the Test Anything Protocol (TAP) inspired by Perl's Test::More module, by dennisdjensen

[FortranTestGenerator](https://github.com/fortesg/fortrantestgenerator): automatically generates unit tests for subroutines of existing Fortran applications based on an approach called Capture & Replay, from fortesg

[fortran-unit-test](https://github.com/dongli/fortran-unit-test): unit test library in Fortran to encourage scientific programmer to write tests, by dongli

[fortran_unit_test](https://github.com/dryman/fortran_unit_test): minimalistic Fortran unit tests with CMake and CTest, by Felix Chern


[Fortran_UnitTest](https://github.com/zhenkunl/Fortran_UnitTest): unit test library based on OOP, by zhenkunl. It is strongly inspired by Zofu, and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test).

[Fortran Unit Test Library](https://github.com/zhenkunl/Fortran_UnitTest): pure Fortran library using Object-Oriented Programming (OOP), by zhenkunl. It is strongly inspired by [Zofu](https://github.com/acroucher/zofu), and its output format is derived from [fortran-unit-test](https://github.com/dongli/fortran-unit-test). 

[Fortran Unit Testing Objects (Fortuno)](https://github.com/aradi/fortuno): flexible and extensible Fortran unit testing framework for testing serial, MPI-parallelized and coarray-parallelized applications, by Bálint Aradi

[FRUIT](https://github.com/mortele/FRUIT): Fortran unit test framework in Ruby, by mortele and michaelkonecny 

[fytest](https://github.com/aradi/fytest): lightweight unit testing framework for Fortran, by aradi. Thanks to its header-only design, it can be easily bundled with any Fortran project without creating extra dependencies.

[pFUnit](https://github.com/Goddard-Fortran-Ecosystem/pFUnit): unit testing framework enabling JUnit-like testing of serial and MPI-parallel software written in Fortran, from Goddard-Fortran-Ecosystem. Limited support for OpenMP is also provided in the form of managing exceptions in a thread-safe manner.

[tap](https://github.com/gzahl/tap): minimal producer implementation of the "Test Anything Protocol" (TAP) in Fortran 90, from gzahl

[test-drive](https://github.com/awvwgk/test-drive): lightweight, procedural unit testing framework based on nothing but standard Fortran, by awvwgk. Integration with meson, cmake and Fortran package manager (fpm) is available. [testdrive_util](https://github.com/degawa/testdrive_util) by Tomohiro Degawa provides procedures to make using test-drive more convenient.

[Vegetables](https://gitlab.com/everythingfunctional/vegetables/-/tree/main/): testing framework written using functional programming principles, by Brad Richardson. As many of its procedures as possible are marked with the pure keyword while still allowing the framework to test impure code.

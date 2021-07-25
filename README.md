### Fortran Tools

(C) indicates a commercial product

* [Automatic Documentation](#automatic-documentation)
* [Build Tools](#build-tools)
* [Compilers](#compilers)
* [Emacs Plugins](#emacs-plugins)
* [Fixed to Free Source Form Conversion](#fixed-to-free-source-form-conversion)
* [Indentation and Formatting](#indentation-and-formatting)
* [Interoperability](#interoperability)
* [Parallel Programming](#parallel-programming)
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
[FCM](https://github.com/metomi/fcm): modern Fortran build system + wrappers to Subversion for scientific software development, from metomi

[FoBiS.py, Fortran Building System for poor people](https://github.com/szaghi/FoBiS): automatic parsing of files for dependency-hierarchy creation in case of use and include statements, and automatic building of all programs found into the root directory parsed or only a specific selected target, by szaghi et al.

[fortdepend](https://github.com/ZedThree/fort_depend.py): python script to generate dependencies for Fortran projects, by ZedThree

[Fortran Package Manager for Visual Studio](https://github.com/everythingfunctional/fpm-for-VS): adds options and menu entries for building, running and testing your Fortran project using the Fortran Package Manager (fpm), by everythingfunctional

[fpm](https://github.com/fortran-lang/fpm): Fortran Package Manager (fpm) is a package manager and build system for Fortran, from fortran-lang

[jams_makefile](https://github.com/mcuntz/jams_makefile): provides a portable, versatile way of compiling Fortran, C, C++, and mixed projects, by mcuntz

[makedepf90](https://github.com/outpaddling/makedepf90): generates make dependencies for Fortran code, by Erik Edelman

[meson](https://github.com/mesonbuild/meson): next-generation build system

[mkhelper](https://github.com/skosukhin/mkhelper): collection of utilities to be used with GNU Autoconf and GNU Make for building Fortran projects, by skosukhin

[run-fortran](https://github.com/lycantropos/run-fortran): sorts Fortran files based on modules definitions and usages, by lycantropos

### Compilers
[Absoft](https://www.absoft.com/): designed to build code in the most efficient way possible, the Pro Fortran compiler utilizes advanced technology. This includes load balancing, AVX and OpenMP 3.1 support, AMDAL HPC scientific and engineering math library,  Parallel versions of Lapack and BLAS libraries, Fast Data Visualization, and much more. (C)

[AMD Optimizing C/C++/Fortran Compiler (AOCC)](https://developer.amd.com/amd-aocc/): high performance, production quality code generation tool. The AOCC environment provides various options to developers while building and optimizing C, C++, and Fortran applications targeting 32-bit and 64-bit Linux® platforms.

[Arm Fortran Compiler](https://developer.arm.com/tools-and-software/server-and-hpc/compile/arm-compiler-for-linux/arm-fortran-compiler): tailored for server, HPC, and scientific codes, with support for Fortran and OpenMP. The compiler is built on the open source Flang front-end, and the LLVM‑based optimization and code generation back-end. (C)

[f18-llvm-project](https://github.com/flang-compiler/f18-llvm-project): fork of llvm/llvm-project for f18. In sync with f18-mlir and f18.

[flang](https://github.com/flang-compiler/flang): flang (also known as "Classic Flang") is an out-of-tree Fortran compiler targeting LLVM. It is an open-sourced version of pgfortran, a commercial Fortran compiler from PGI/NVIDIA

[gfortran](https://gcc.gnu.org/wiki/GFortran): GNU Fortran project, developing a free Fortran 95/2003/2008 compiler for GCC, the GNU Compiler Collection. The gfortran development effort uses an open development environment in order to attract a larger team of developers and to ensure that gfortran can work on multiple architectures and diverse environments. Gfortran installation on various platforms is discussed at [fortran-lang](https://fortran-lang.org/learn/os_setup/install_gfortran).

[gfortran-for-macOS](https://github.com/fxcoudert/gfortran-for-macOS): gfortran for macOS Intel, by fxcoudert.

[g95](https://www.g95.org/downloads.shtml): stable, production Fortran 95 compiler available for multiple cpu architectures and operating systems. Parts of the F2003 and F2008 standards have been implemented

[HPE Cray Programming Environment](https://buy.hpe.com/us/en/software/high-performance-computing-software/high-performance-computing-software/hpe-cray-programming-environment/p/1012707351): fully integrated software suite with compilers, tools, and libraries designed to improve programmer productivity, application scalability, and performance. Besides support for multiple programming languages, programming models, compilers, I/O libraries, and scientific libraries, the suite offers a variety of supported tools for areas including debugging, performance analysis, workload management, and environment setup. (C)

[IBM Fortran](https://www.ibm.com/products/fortran-compiler-family): XL Fortran for AIX®: Build optimized and tuned Fortran applications on IBM AIX.
<br />XL Fortran for Linux: Optimize your HPC and cognitive Fortran applications for Linux on IBM Power® Systems, including the POWER9™ processors.
<br />VS Fortran: Develop efficient applications for IBM Z® and z/VM® with IBM VS FORTRAN.

[Intel Fortran](https://software.intel.com/content/www/us/en/develop/tools/oneapi/components/fortran-compiler.html): built on a long history of generating optimized code that supports industry standards while taking advantage of built-in technology for Intel® Xeon® Scalable processors and Intel® Core™ processors. Staying aligned with Intel’s evolving and diverse architectures, the compiler now supports GPUs.

[Lahey Fortran Professional v7.9 Windows](https://www.lahey.com/): combines the 32/64-bit LGF Rainier compiler with the classic Lahey/Fujitsu LF95 compiler. LGF Rainier has full Fortran 95/90/77 compliance with extensive support for the Fortran 2003 and 2008 standards. (C)

[Lahey/GNU Fortran - Rainier Edition Windows 32 & 64-bit](https://www.lahey.com/): full Fortran 95/90/77 compliance with extensive support for the Fortran 2003 and 2008 standards; targets 32 and 64-bit Windows. Includes the automatic-parallelizing GFortran compiler, Visual Studio 2015 Shell (compatible with VS2019 & VS2017), Lahey's Exclusive Visual Studio Fortran support, Winteracter WiSK Graphics package, and more. (C)

[lfortran](https://github.com/lfortran/lfortran): modern open-source (BSD licensed) interactive Fortran compiler built on top of LLVM. It can execute user's code interactively to allow exploratory work (much like Python, MATLAB or Julia) as well as compile to binaries with the goal to run user's code on modern architectures such as multi-core CPUs and GPUs.

[NAG](https://www.nag.com/content/nag-fortran-compiler): robust and highly tested Fortran compiler, valued for its checking capabilities and detailed error reporting. Available on Linux, Microsoft Windows and Mac OS X, including Apple Silicon Macs. (C)

[NEC](https://www.nec.com/en/global/solutions/hpc/sx/tools.html): Fortran compiler conforms to the Fortran-2003 standard (ISO/IEC 1539-1:2004) and supports many features from Fortran-2008 (ISO/IEC 1539-1:2010). NEC has more than 30 years’ experience in compiler technology for high-end vector machines, and these newly developed compilers will be based on this experience and support all the optimization strategies that NEC compilers are known for.

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

[Fortran-tags](https://github.com/raullaasner/fortran-tags): Fortran source code indexing tool with the focus of finding the definition of any variable or procedure, by raullaasner et al. It is able to correctly locate all global and local variables and is expected to work with any Fortran 2008 conforming code with some exceptions as mentioned below.

### Fixed to Free Source Form Conversion
[f2f](https://github.com/MRedies/f2f_mirror): Perl script which does much of the tedious work of converting FORTRAN 77 source code into modern Fortran, by Colby Lemon

[f77tof90](https://github.com/mattdturner/f77tof90): Python script that reads in a Fortran 77 (.f or .F) fixed form file and converts it to a free form Fortran 90 file (.f90 or .F90), by mattdturner. It was successfully used to convert a legacy codebase (over 400 .f/.F files and millions of lines of code) from Fortran 77 to Fortran 90.

[FORTRAN77_to_Fortran90](https://github.com/Koushikphy/FORTRAN77_to_Fortran90): convert old fixed source FORTRAN 77 code to free form Fortran 90 code, by Koushikphy

[fortran-legacy-tools](https://github.com/ylikx/fortran-legacy-tools): tools to deal with Fortran code: fixed to free source form converter, upper- to lowercase converter, formatter for variable declarations, by ylikx

[freestyle](https://github.com/bast/freestyle): script to convert fixed form Fortran files (written in Fortran 77) and header files to free form, by bast

[GConvert](https://github.com/GeorgeTsikas/GConvert): program to convert fixed form Fortran into code that works as fixed or free form, by GeorgeTsikas.

[to_f90](https://github.com/jbdv-no/to_f90) Alan Miller's tool for converting Fortran 77 code to free-form Fortran 90 code, from jbdv-no

### Indentation and Formatting
[ajt-fortran.vim](https://github.com/robertodr/ajt-fortran.vim): port of Ajit J. Thakkar's Vim indent script

[findent](https://github.com/MFTabriz/findent): indent and convert Fortran sources, by wvermin and MFTabriz

[FortranIndent](https://github.com/Kairzhan/FortranIndent): tools to indent Fortran 90 sources, from Kairzhan

[fprettify](https://github.com/pseewald/fprettify): auto-formatter for modern Fortran code that imposes strict whitespace formatting, written in Python, by pseewald

[IndentPatternFortran](https://github.com/JHenneberg/IndentPatternFortran): general indentation patterns for Fortran, by JHenneberg

### Interoperability
[F2x](https://github.com/DLR-SC/F2x): versatile, template-based Fortran wrapper written in Python. Compared to the popular tool f2py it comes with two important differences: a full Fortran parser based on the work by the OpenFortranParser, and a very flexible code generation backend that uses Jinja2 templates.

[f90wrap](https://github.com/jameskermode/f90wrap): Fortran 90 to Python interface generator with derived type support, by jameskermode et al.

[Fortran Namelist Reader](https://github.com/scivision/fortran-namelist): Python and Matlab readers for Fortran namelist => dict / struct, from scivision

[shroud](https://github.com/LLNL/shroud): creates a Fortran or Python interface to a C or C++ library, from LANL. It can also create a C API for a C++ library.

### Parallel Programming
[hipfort](https://github.com/ROCmSoftwarePlatform/hipfort): Fortran Interface For GPU Kernel Libraries

[mpich](https://github.com/pmodels/mpich): high-performance and widely portable implementation of the
MPI-3.1 standard from the Argonne National Laboratory

[Omni Compiler](https://github.com/omni-compiler/omni-compiler): compiler for code including XcalableMP, XcalableACC, and OpenACC directives. The base languages supported by Omni Compiler are C language (C99) and Fortran 2008 in XcalableMP, and C language (C99) in XcalableACC and OpenACC.

[OpenCoarrays](https://github.com/sourceryinstitute/opencoarrays): supports Fortran 2018 compilers by providing a parallel application binary interface (ABI) that abstracts away the underlying parallel programming model, which can be the Message Passing Interface (MPI) or OpenSHMEM, 
from sourceryinstitute

### Preprocessors
[fortiel](https://github.com/Jhuighuy/fortiel): Fortran preprocessor and metaprogramming engine, by Jhuighuy

[fypp](https://github.com/aradi/fypp): Python-powered preprocessor, by aradi. It can be used for any programming languages but its primary aim is to offer a Fortran preprocessor, which helps to extend Fortran with condititional compiling and template metaprogramming capabilities

[prep](https://github.com/urbanjost/prep): Fortran pre-processor written in Fortran, by urbanjost

### Profiling
[Caliper](https://github.com/LLNL/Caliper): library to integrate performance profiling capabilities into applications, from LANL. To use Caliper, developers mark code regions of interest using Caliper's annotation API. Applications can then enable performance profiling at runtime with Caliper's configuration API.

[timemory](https://github.com/NERSC/timemory): performance measurement and analyis package with modular and reusable components which can be used to adapt to any existing C/C++ performance measurement and analysis API and is arbitrarily extendable by users within their application, from NERSC

### Refactoring
[Fortran Language Program Remodeling system (FLPR)](https://github.com/lanl/FLPR):  C++17 library for manipulating Fortran source code, from LANL. This package contains a "best effort" Fortran 2018 input parser for fixed and free form inputs, data structures for manipulating source code at the program unit, statement, and physical line levels, and sample applications that illustrate usage and provide some ideas as to how you could use the library.

[Glasgow Fortran Source-to-Source Compiler (RefactorF4Acc)](https://github.com/wimvanderbauwhede/RefactorF4Acc): automatic refactoring tool to make Fortran code acceleration-ready, by wimvanderbauwhede and rouson. RefactorF4Acc's main purpose is to make legacy FORTRAN 77 acceleration-ready. In the process it converts FORTRAN 77 code into Fortran 95. In addition, RefactorF4Acc has a backend to translate modules to C/OpenCL.

[Fortran Kernel Generator: KGen](https://github.com/NCAR/KGen): Python tool that extracts partial codes out of a large Fortran application and converts them into a standalone/verifiable/executable kernel, by Youngsung Kim and John Dennis

[fortrantools](https://github.com/CodethinkLabs/fortrantools): tools to enable the use old or proprietary Fortran code with gfortran. They are intended to be used together with the gcc extensions in CodethinkLab's gcc branch.

### Static Analysis
[camfort](https://github.com/camfort/camfort): refactoring and verification tool for scientific Fortran programs. It currently supports Fortran 66, 77, and 90 with various legacy extensions.

[flint](https://github.com/JonasToth/flint): Little linter for Fortran, with static analysis and formatting, by JonasToth

[flint](https://github.com/marshallward/flint): aspires to be a Fortran parser, delinter, and analyser, by marshallward. For now, it is a Fortran tokenizer, with tools for parsing and automated documentation.

[fortlint](https://github.com/ratnania/fortlint): Fortran static source code analysis for more secured and bug free applications

[fortrancallgraph](https://github.com/fortesg/fortrancallgraph): static source code analysis for Fortran, tracking variables in a routine's callgraph, from fortesg

[fortran-callgraph](https://github.com/hydro-jules/fortran-callgraph): Tool to create call graphs from JULES source code

[Fortran linter](https://github.com/cphyc/fortran-linter): simple fortran syntax checker, including automatic fixing of the code, from cphyc

[fortran-linter](https://github.com/uchchwhash/fortran-linter): linter for Fortran 77 using Parsec-like parsing combinators in Python, by uchchwhash

[fsource](https://github.com/mwallerb/fsource): Fortran static analysis tool written in pure Python, by mwallerb

[i-CodeCNES](https://github.com/cnescatlab/i-CodeCNES): static code analysis tool to help developers write code compliant with CNES coding rules for Fortran 77, Fortran 90 and Shell, from cnescatlab

[K-scope](https://github.com/K-scope/K-scope): source code analysis tool with graphical user interface that visualizes program structures for Fortran 90 and FORTRAN 77 source code. This tool simply visualizes call tree from AST based on compiler's static analysis.

[Simple Lint GitHub Action (simple_lint)](https://github.com/NOAA-GFDL/simple_lint): runs simple lint-like actions on files in a git repository, from NOAA-GFDL. The current list of lint actions are to check for trailing whitespace, check Fortran files for use of tab characters, and check Fortran files for lines longer then a specified length.

### Text Editors, Integrated Development Environments, and Plugins
[Code::Blocks](https://www.codeblocks.org/): free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable.

[linter-gfortran](https://github.com/AtomLinter/linter-gfortran): linting Fortran code in [Atom](https://github.com/atom) with gfortran

[Fortran Language Server](https://github.com/hansec/fortran-language-server): A Fortran implementation of the Language Server Protocol using Python (2.7+ or 3.0+), by hansec. Editor extensions using this language server to provide autocomplete and other IDE-like functionality are available for Atom, Visual Studio Code, Visual Studio, (Neo)vim, and Emacs.

[fortran.tmbundle](https://github.com/textmate/fortran.tmbundle): TextMate support for Fortran. TextMate is a graphical text editor for macOS 10.12 or later.

[fossil](https://github.com/nrwade0/Fossil): Fortran IDE designed in Python by someone eager to learn Fortran but in an easy and accessible way, by nrwade0

[Modern-Fortran](https://github.com/eirik-kjonstad/modern-fortran-syntax): language syntax for highlighting of Fortran code in [Sublime Text](https://www.sublimetext.com/), by eirik-kjonstad. It highlights modern Fortran (Fortran 90 and newer) and incorporates features introduced in Fortran 2003, 2008, and 2018.

[Simply Fortran](http://simplyfortran.com/): modern Fortran development environment for Microsoft Windows, Apple macOS, and GNU/Linux systems. Free 30-day trial. (C)

[vim](https://github.com/vim/vim): improved version of the UNIX editor Vi. Many new features have been added: multi-level undo, syntax highlighting, command line history, on-line help, spell checking, filename completion, block operations, script language, etc. Download [here](https://www.vim.org/download.php). 

[vimf90](https://github.com/rudrab/vimf90): Fortran ide for vim

[vim-findent](https://github.com/cradesto/vim-findent): vim plugin for [Findent](https://github.com/MFTabriz/findent), which indents Fortran sources, by cradesto

[Visual Studio Code (vscode)](https://github.com/microsoft/vscode): combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle, from Microsoft. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

[vscode-fortran-support](https://github.com/krvajal/vscode-fortran-support): extension that provides support for the Fortran programming language. It includes syntax highlighting, debugging, code snippets and a linting based on gfortran.

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

[FORTRAN Testing Framework (FTFramework)](https://github.com/agforero/FTFramework): collection of Python and Bash scripts to enable easy testing of Fortran compilers using BATS, by agforero

[irep](https://github.com/LLNL/irep): tool for filling C/C++ or Fortran data structures from Lua input tables, from LLNL

[OpenAD](https://github.com/Augertron/OpenAD): tool for automatic differentiation (AD) of numerical computer programs

### Unit Testing
[FortranTestGenerator](https://github.com/fortesg/fortrantestgenerator): automatically generates unit tests for subroutines of existing Fortran applications based on an approach called Capture & Replay, from fortesg

[FRUIT](https://github.com/mortele/FRUIT): Fortran unit test framework in Ruby, by mortele and michaelkonecny 

[fytest](https://github.com/aradi/fytest): lightweight unit testing framework for Fortran, by aradi. Thanks to its header-only design, it can be easily bundled with any Fortran project without creating extra dependencies.

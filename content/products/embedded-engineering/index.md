---
layout: products

title: "Library"
date: "2025-04-30T10:10:10+05:30"
tags:
  - bundle
description: "Access all courses we create. A structured path to mastering the essentials of Firmware and Systems Software Engineering."
thumbnail: "/products/embedded-engineering/cover.png"
categories: courses
product: "embedded-engineering"

define: &enrolled 314
define: &lastupdated "18 May 2025"

param:
  image: "/products/embedded-engineering/cover.png"
  note: "Claim the Discounted Prices while the course is being developed!"
  bundle:
    - course: "Library"
      subtitle: "`Access all courses we create`.\n\nA structured path to mastering the essentials of Firmware and Systems Software Engineering."
      description: "Embedded Systems Software Engineering includes writing firmware for micro-controllers and system software for application grade CPUs involving boot-loaders, device trees and higher level operating systems. \n\n

      While there are several resources available online. Each offers a narrow view of one entity of the several. We have created and organised courses, that will take you from `Zero to Hero` in Firmware and Systems Software Engineering."
      previewCover: "/products/embedded-engineering/cover.png"
      # previewVideo: "/products/embedded-engineering/portal.mov"
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 4.9
      ratingCount: 25
      studentsCount: *enrolled
      message: "1080481281?h=39e203cc29"
      creators:
        - name: "Piyush Itankar"
          designation: "Embedded Engineer (L5), Google"
          contactLink: "https://www.linkedin.com/in/streetdogg/"
          photo: "https://media.licdn.com/dms/image/v2/D5603AQEf8sg1lv5agw/profile-displayphoto-shrink_200_200/B56ZZReHOAGUAY-/0/1745123574048?e=1751500800&v=beta&t=dPQgn4rStZc-7Gmhgwqj4XEefFJMIRnuIolcPlsK6NY"
          bio: "Electrical Engineer holding a Master’s degree in Embedded Systems, with a proven track record at industry giants. At Intel, contributed expertise to Navigation Firmware, Bluetooth Driver development, and RF validation software. Currently thriving as an Embedded Software Engineer at Google, drove innovation in Firmware development for the Power Management Sub-system on Tensor SoCs (Pixel Phones) and presently advancing system software for the Pixel Watch."
        - name: "Mahmad Bharmal"
          designation: "Embedded Engineer (L4), Google"
          contactLink: "https://www.linkedin.com/in/mahmadbharmal/"
          photo: "https://media.licdn.com/dms/image/v2/D5603AQFFjZHTktgLhA/profile-displayphoto-shrink_400_400/profile-displayphoto-shrink_400_400/0/1700983843809?e=1751500800&v=beta&t=UHSlPtVvxONmxIwp6QamfvgOLakljf6DXCM-yOWuvYs"
          bio: "Computer Science Engineer with a Masters in Embedded Systems Design. Worked on Firmware for Intel's Bluetooth solutions, followed by Silicon Validation Software for the Tensor SoCs, and presently working on the Pixel Watch Software. He is system software expert with a decade of experience."
      lastUpdated: *lastupdated
      language: "English"
      lessons: 200+
      length: "75+ hrs"
      files: 10+
      quizzes:
      tracks: "/products/embedded-engineering/tracks.svg"
      certificate: "/products/embedded-engineering/certificate.png"
      validity: Quarterly and Yearly
      projects: 5+
      learning:
        - Master C programming, converting to Assembly and machine code.
        - Grasp ARM-M, ARM-A, and RISC-V memory maps and programmer's models.
        - Write and debug C programs for practical use.
        - Command C constructs - functions, pointers, structs, unions, enums.
        - Analyze data types - integers, floats, doubles, signed/unsigned, const, volatile.
        - Understand data type memory representation - 2's complement, floating-point encoding.
        - Implement control structures (if, else, switch, loops, goto) and track assembly effects.
        - Manipulate arrays, strings, pointers, and perform pointer arithmetic.
        - Leverage debug tools - GDB, make, addr2line etc.
        - Build mental models for pointers in firmware, Linux, FreeRTOS, Zephyr.
        - Master pointer operations - pointer-to-pointer, arrays, function pointers.
        - Handle pointer arithmetic, void pointers, NULL pointers in kernels.
        - Manage dynamic memory with malloc(), free(); avoid leaks, dangling pointers.
        - Learn low-level programming with RISC-V and Assembly.
        - Write and debug RISC-V (rv32i) assembly programs; convert C to assembly.
        - Use QEMU, GDB, Makefiles for low-level debugging.
        - Develop baremetal firmware, drivers; print “Hello, World!” on UART.
        - Understand ARM Cortex-M, Cortex-A architecture, registers, boot processes.
        - Write Cortex-M assembly, including schedulers with context switching, SysTick.
        - Master exception handling, vector tables, system registers via QEMU.
        - Create, debug Makefiles for build automation; write GNU linker scripts.
        - Use Git, Gerrit for version control, code reviews.
        - Dissect FreeRTOS kernel; port to new targets with task scheduling.
        - Develop Linux kernel modules; manage with insmod, rmmod, lsmod.
        - Implement /proc entries, system calls, device drivers in sandbox.
        - Explore embedded systems roles, job skills, and career paths.
        - Generate digital audio in C using sampling, file operations.
        - Simulate real-world coding with QEMU, Codespace, Multipass.
        - Build mental models of CPU, memory, state machines, scheduling.
        - Tackle interview questions on C, memory, interrupts, bit manipulation.
        - Complete projects - schedulers, digital audio, Linux drivers.
      sections:
        - section: "Low Level with Pyjama Brah! (Public Draft)"
          description: "I am writing a book to teach C by understanding the CPU/Memory programmers model, exploring the ISA for RISC-V, the assembly, writing baremetal firmware/driver, and ends with printing “Hello, World!” on the UART.\n\nThe book covers lot more than just C. Things like Assembly, Makefile, GDB based Debugging, Linker Scripts, C, Driver Writing etc… The public draft is available for FREE for online reading."
          open: "open"
          id: "book"
          sectionDuration:
          chapters:
            - chapter: "Low Level with Pyjama Brah!"
              preview: ""
              type: "pdf"
              meta:
              attachments: ""
        - section: "Roadmap and Career Options"
          description: "This short course focuses on orienting the college graduates and those new to the industry on what the usual roles, responsibilities are and what opportunities they can expect."
          open: "open"
          id: "roadmap"
          chapters:
          - chapter: "Understanding Embedded Systems"
            type: "video"
          - chapter: "what is embedded systems and how it relates to EE, ECE and CS"
            type: "video"
          - chapter: "What is firmware and Systems Engineering"
            type: "video"
          - chapter: "Understanding What Firmware engineering is"
            type: "video"
          - chapter: "Memory Map and the Programmer's model"
            type: "video"
          - chapter: "State Machines and OS Primitives"
            type: "video"
          - chapter: "Roles and Exploring job listing"
            type: "video"
          - chapter: "HLOS, Application Grade CPU and Virtual Memory"
            type: "video"
          - chapter: "Roles and Skills"
            type: "video"
          - chapter: "Exploring Opportunities and Skillset"
            type: "video"
        - section: "The C Language"
          id: "c"
          description: "This course dives into the practical applications of the C language, emphasizing hands-on learning to solidify key concepts. Delivered in an engaging and unconventional style, the lessons go beyond theory, equipping you with the skills to apply C programming in real-world scenarios. By the end of the course, you’ll feel confident in your mastery of the C language, adept at using it alongside the tools and utilities professional C programmers rely on daily."
          open: "open"
          chapters:
          - chapter: "Roadmap and Mindset"
            type: "video"
          - chapter: "Sandbox Environment and Basic C Program"
            type: "video"
          - chapter: "Keep an Eye on Functions, Pointers and Structs"
            type: "video"
          - chapter: "Example of the RAW power - Functions, Struct and Pointers"
            preview: "1-GXQFRaHZc"
            type: "video"
          - chapter: "Mental Model of the System"
            type: "video"
          - chapter: "The mental model of the CPU"
            type: "video"
          - chapter: "The mental model of the Memory"
            type: "video"
          - chapter: "Instruction Encoding and the rv32i ISA"
            type: "video"
          - chapter: "A tour of Toolchain, QEMU, GDB"
            type: "video"
          - chapter: "Demo - assembly to binary, QEMU and GDB"
            type: "video"
          - chapter: "Instruction Encoder Decoder, Makefile and GDB Dashboard"
            type: "video"
          - chapter: "Anatomy of Assembly Program, writing code, debugging in GDB"
            type: "video"
          - chapter: "Decomposing C to Assembly and the relation"
            preview: "2eAv_b4OrAE"
            type: "video"
          - chapter: "Getting CPU from assembly to jump to C program"
            type: "video"
          - chapter: "Introducing the C Keywords"
            type: "video"
          - chapter: "Data types, Variables and Integers"
            type: "video"
          - chapter: "Datatypes - float and double"
            type: "video"
          - chapter: "Exploring sizes of data types and location in memory"
            type: "video"
          - chapter: "How integers are stored - 2s complement"
            type: "video"
          - chapter: "floating point number encoding and few examples"
            type: "video"
          - chapter: "more floating point - float and double"
            type: "video"
          - chapter: "signed and unsigned"
            type: "video"
          - chapter: "const and volatile"
            type: "video"
          - chapter: "demo - const and volatile"
            type: "video"
          - chapter: "void, c standard and gnu C manual"
            type: "video"
          - chapter: "typedef and sizeof"
            type: "video"
          - chapter: "structs and unions"
            type: "video"
          - chapter: "enums as named numbers"
            type: "video"
          - chapter: "if, else, switch, case, default, do, while, for, continue and break"
            type: "video"
          - chapter: "goto and return"
            type: "video"
          - chapter: "Demo - if, else if and else effects at assembly level"
            type: "video"
          - chapter: "Demo - switch case and effects at assembly level"
            type: "video"
          - chapter: "Demo - loops - for, do, while, continue and effects at assembly level"
            type: "video"
          - chapter: "Demo - goto and jumps across functions"
            type: "video"
          - chapter: "auto, register, extern and static"
            type: "video"
          - chapter: "Demo - auto keyword7"
            type: "video"
          - chapter: "Demo - register keyword"
            type: "video"
          - chapter: "Demo - extern keyword"
            type: "video"
          - chapter: "Demo - static keyword"
            type: "video"
          - chapter: "Introduction to Variables and Functions"
            type: "video"
          - chapter: "definition vs declaration"
            type: "video"
          - chapter: "Demo - variable and function names"
            type: "video"
          - chapter: "Arithmetic operations and pitfalls"
            type: "video"
          - chapter: "Problem statement"
            type: "pdf"
          - chapter: "Problem statement walkthrough"
            type: "video"
          - chapter: "Setup, variables and I/O"
            type: "video"
          - chapter: "Using conditions, switch and loops"
            type: "video"
          - chapter: "debugging scanf issue and cleaning up the code"
            type: "video"
          - chapter: "guarding against bad inputs and concluding the project"
            type: "video"
          - chapter: "Strings and concept of array and pointers"
            type: "video"
          - chapter: "Defining and Assigning Arrays"
            type: "video"
          - chapter: "Arrays and out of bound access"
            type: "video"
          - chapter: "Strings and Character arrays"
            type: "video"
          - chapter: "Introduction to the concept of pointers"
            type: "video"
          - chapter: "Syntax related to Pointers"
            type: "video"
          - chapter: "Demo - introduction to working with data pointers"
            type: "video"
          - chapter: "Detour - Endianness"
            type: "video"
          - chapter: "Demo - Difference between array and pointers"
            type: "video"
          - chapter: "Generating Digital Audio - walkthrough"
            type: "video"
          - chapter: "Math concepts and sampling"
            type: "video"
          - chapter: "Generating samples and file operations"
            type: "video"
          - chapter: "Demo - Playing the Digital Audio"
            type: "video"
          - chapter: "Revisiting types of data types"
            type: "video"
          - chapter: "Structures - Sneak peak"
            type: "video"
          - chapter: "Anatomy of Struct and examples"
            type: "video"
          - chapter: "Demo - structs"
            type: "video"
          - chapter: "more being uploaded..."
            type: "video"
        - section: "C Pointers"
          id: "pointers"
          description: "C pointers are crucial in Firmware and System Software (based on the C language) design. Linux, Unix, FreeRTOs, Zephyr, ThreadX etc kernels use C pointers heavily. This Course dives into the mental models and inner workings of pointers!"
          open: "open"
          chapters:
          - chapter: "What to Imagine?"
            type: "video"
          - chapter: "What is a pointer?"
            type: "video"
          - chapter: "Why pointers?"
            type: "video"
          - chapter: "Environment Setup"
            type: "video"
          - chapter: "Declaring|Defining a Pointer"
            type: "video"
          - chapter: "Pointer Variable and Address"
            type: "video"
          - chapter: "* and & in relation to pointer variable"
            type: "video"
          - chapter: "Use of * and &"
            type: "video"
          - chapter: "Array and Pointers - Similarity and differences"
            type: "video"
          - chapter: "Many *s and Many &s"
            type: "video"
          - chapter: "Pointer to pointer"
            type: "video"
          - chapter: "Array of pointers"
            type: "video"
          - chapter: "Different types of Pointers"
            type: "video"
          - chapter: "Pointing to data with a Datatype"
            type: "video"
          - chapter: "Pointer to a struct, *, . and ->"
            type: "video"
          - chapter: "Pointer Arithmetic"
            type: "video"
          - chapter: "Memory model and pointer to data"
            type: "video"
          - chapter: "What is a function pointer?"
            type: "video"
          - chapter: "Function pointers syntax"
            type: "video"
          - chapter: "typedef and function pointers"
            type: "video"
          - chapter: "Example - function pointer array"
            type: "video"
          - chapter: "What is a void pointer?"
            type: "video"
          - chapter: "What is NULL and NULL pointer?"
            type: "video"
          - chapter: "void pointers in - Linux source code"
            type: "video"
          - chapter: "heap/ malloc() and free()"
            type: "video"
          - chapter: "Allocation failure"
            type: "video"
          - chapter: "Memory Leak"
            type: "video"
          - chapter: "Dangling Pointer"
            type: "video"
          - chapter: "Double free()"
            type: "video"
          - chapter: "pointer manipulation and unowned memory"
            type: "video"
          - chapter: "Baremetal Code"
            type: "video"
          - chapter: "FreeRTOS"
            type: "video"
          - chapter: "Linux"
            type: "video"
        - section: "C - Mastering Bit Manipulation"
          id: "bit-manipulation"
          description: "A short course on how to think about and do bit manipulation in the C Language"
          open: "open"
          chapters:
            - chapter: "The idea behind bit manipulation"
              type: "video"
            - chapter: "Operators and practical aspects of Bit Manipulation"
              type: "video"
            - chapter: "Bit Masking, Setting and Clearing Bits"
              type: "video"
        - section: "Data Structures (in C)"
          id: "dsa"
          description: "A short course on understanding, implementing and using data structures in C."
          open: "open"
          chapters:
            - chapter: "Introduction"
              type: "title"
            - chapter: "Need of DSA in Embedded Programming"
              type: "video"
            - chapter: "Setup and work environment"
              type: "video"
            - chapter: "Review of concepts in C"
              type: "title"
            - chapter: "Three essential concepts in C"
              type: "video"
            - chapter: "One dimensional array"
              type: "video"
            - chapter: "Visualizing and working with multi-dimensional array"
              type: "video"
              preview: "C4NpCjed3HM"
            - chapter: "Lectures are being recorded and be released over the weekend."
              type: ""
        - section: "ARM Cortex-M 101 - Introduction"
          id: "m-101"
          description: "An introductory course on the ARM Cortex-M CPUs. How to go about learning them."
          open: "open"
          chapters:
          - chapter: "ARM CPU Architectures"
            type: "video"
          - chapter: "Micro Architecture Vs Architecture"
            type: "video"
          - chapter: "Mental model of CPU Memory interactions"
            type: "video"
          - chapter: "How to master CPU - Different models to learn"
            type: "video"
          - chapter: "Programmers model - Register Set"
            type: "video"
          - chapter: "Modes and Privileges"
            type: "video"
          - chapter: "CPU boot up and Vector Table"
            type: "video"
          - chapter: "Exploring Cortex-M3 registers using QEMU"
            type: "video"
          - chapter: "where to next.... Invitation"
            type: "video"
        - section: "ARM Cortex-M 102 - Scheduler Design using Assembly"
          id: "m-assembly"
          description: "Learn the assembly programming for ARM Cortex-M CPUs by writing a scheduler from scratch, without using any IDE, SDK or boiler plate code. Course is under development. Content will be added when it's ready."
          open: "open"
          chapters:
          - chapter: "End Goal"
            type: "video"
          - chapter: "Environment Setup"
            type: "video"
          - chapter: "Mental Model of the CPU, Systems and the Cortex M Controller"
            type: "video"
          - chapter: "From bit to the Programmers model and NVIC"
            type: "video"
          - chapter: "Various ARM Architecture and CPUs - M0, M3, M23 etc."
            type: "video"
          - chapter: "Programmers model for the M Class CPUs"
            type: "video"
          - chapter: "Privilege and Modes of operation"
            type: "video"
          - chapter: "Boot up process"
            type: "video"
          - chapter: "Exception Handling and Register Save/Restore"
            type: "video"
          - chapter: "Booting the Processor and First Assembly Program"
            preview: "aEE4bK-HnHg"
            type: "video"
          - chapter: "Instructions, Encoding and binary dump"
            type: "video"
          - chapter: "Anatomy of assembly file"
            type: "video"
          - chapter: "Cortex m3 instructions and experiments"
            type: "video"
          - chapter: "Stack manipulation instructions"
            type: "video"
          - chapter: "How can Single CPU run multiple processes?"
            type: "video"
          - chapter: "Anatomy of a Task"
            type: "video"
          - chapter: "Trick to Context Switching and Scheduling"
            type: "video"
          - chapter: "Exception Entry, Exit and SysTick timer"
            type: "video"
          - chapter: "Programming SysTick and confirming the exception"
            type: "video"
          - chapter: "saving and restoring CPU context"
            type: "video"
          - chapter: "Setting up the tasks and the stack and trying to round robin"
            type: "video"
          - chapter: "Round robin and switching between processes"
            type: "video"
          - chapter: "Things to be mindful of"
            type: "video"
          - chapter: "FreeRTOS - the struggle to get to context switching"
            type: "video"
        - section: "GNU Make and Automation"
          id: "make"
          description: "Make is a build automation tool that automatically updates files in your project based on their dependencies. It's primarily used for compiling source code, but can also be used to run other commands or perform tasks."
          open: "open"
          chapters:
          - chapter: "Setup and Quick Introduction"
            type: "video"
          - chapter: "First makefile and basic rules"
            type: "video"
          - chapter: "Dependencies and when make misbehaves"
            type: "video"
          - chapter: "Resolving dependencies - target as a dependency"
            type: "video"
          - chapter: "A better example and variables"
            type: "video"
          - chapter: "Pattern Rules and some internal variables"
            type: "video"
          - chapter: "Variable for target, pattern substitution, functions and debugging makefile"
            type: "video"
          - chapter: "Executing shell commands and assigning value to variable"
            type: "video"
          - chapter: "Organising the source code and use of shell function"
            type: "video"
          - chapter: "Discovering the header paths"
            type: "video"
          - chapter: "Generating the path to headers and targets without recipe"
            type: "video"
          - chapter: "Different names for Makefile and including other makefiles"
            type: "video"
          - chapter: "Passing values form commandline, ?= and +="
            type: "video"
          - chapter: "macros"
            type: "video"
        - section: "GNU Linker Script"
          id: "ld"
          description: "This hands-on course dives into the details of writing linker scripts (based on GNU LD). Linker scripts are a must-have skill for firmware and systems engineers who have to deal with scenarios where the placement of various sections (code, data, etc) in the memory needs granular control. Engineers who work on Bootrom, Firmwares, Bootloaders, or otherwise are involved in lower-level systems code."
          open: "open"
          chapters:
          - chapter: "Environment Setup"
            type: "video"
          - chapter: "Opening and Closing the Codespace Environment"
            type: "video"
          - chapter: "Compilation Process, Linker and the linkerscript"
            type: "video"
          - chapter: "Demo - Resolving addresses and Merging sections"
            type: "video"
          - chapter: "C Code and Allocation in Memory"
            type: "video"
          - chapter: "Diagnostic Tools"
            type: "video"
          - chapter: "Our own linker script: Goal"
            type: "video"
          - chapter: "Anatomy, Memory details, Sections"
            type: "video"
          - chapter: "Sneaky linker and linking multiple objects"
            type: "video"
          - chapter: "Including and discarding sections from same file"
            type: "video"
          - chapter: "Discarding and wildcard"
            type: "video"
          - chapter: ".rodata, problems with Single memory bank"
            type: "video"
          - chapter: "Defining two memories and the problem with .data section"
            type: "video"
          - chapter: "Introducing VMA and LMA"
            type: "video"
          - chapter: "Current location counter, variables and destination info"
            type: "video"
          - chapter: "Address of .data section in the ROM"
            type: "video"
          - chapter: "Code to copy .data section from ROM to RAM"
            type: "video"
          - chapter: "Zero Initialising the .bss section"
            type: "video"
          - chapter: "Creating custom sections and placing it"
            type: "video"
          - chapter: "What is the linker command language"
            type: "video"
          - chapter: "Linker Script and Statement"
            type: "video"
          - chapter: "Expressions"
            type: "video"
          - chapter: "Values"
            type: "video"
          - chapter: "Symbol Names and naming rules"
            type: "video"
          - chapter: "Location Counter"
            type: "video"
          - chapter: "Expression Evaluation"
            type: "video"
          - chapter: "Assignment operation"
            type: "video"
          - chapter: "Assignment statement placement - relative and absolute addresses"
            type: "video"
          - chapter: "Symbol types - Absolute and Relocatable"
            type: "video"
        - section: "FreeRTOS - Teardown and Porting"
          id: "freertos"
          description: "Learn FreeRTOS kernel by tearing it down to it's bare minimum and doing a port for a new target from scratch. This includes booting the CPU from scratch and placing the code in memory manually."
          open: "open"
          chapters:
          - chapter: "What and Why FreeRTOS"
            type: "video"
          - chapter: "Demo walkthrough - End goal and Tools"
            type: "video"
          - chapter: "Codespace Setup"
            type: "video"
          - chapter: "Programmers model and Essentials of ARM M CPU"
            type: "video"
          - chapter: "Demo - Booting the CPU"
            type: "video"
          - chapter: "Jumping from Assembly code to function in C files"
            type: "video"
          - chapter: "Fixing the problem of function calls in C"
            type: "video"
          - chapter: "Getting the FreeRTOS source code and documentation"
            type: "video"
          - chapter: "Starting to Integrate the FreeRTOS-Kernel"
            type: "video"
          - chapter: "Finding and fixing the portmacro.h errors"
            preview: "U_DDLbHN8dI"
            type: "video"
          - chapter: "Finding and adding the FreeRTOSConfig.h"
            type: "video"
          - chapter: "Enabling heap for dynamic memory allocation"
            type: "video"
          - chapter: "Setting the Scheduling Rate"
            type: "video"
          - chapter: "Getting the Kernel to compile successfully"
            type: "video"
          - chapter: "Running the compiled binary"
            type: "video"
          - chapter: "Investigating why task is not getting created"
            type: "video"
          - chapter: "GDB Investigation - Memory Allocation failure"
            type: "video"
          - chapter: "Correcting the boot-up code and memory init"
            type: "video"
          - chapter: "Installing the Exception Handlers"
            type: "video"
          - chapter: "Hunting the cause for the Hard Fault"
            type: "video"
          - chapter: "more lectures being recorded..."
            type: "video"
        - section: "Git and Gerrit - the collaboration kit"
          id: "git"
          description: "Git and Gerrit are pivotal tools in the software development industry, each serving distinct yet complementary roles that enhance collaboration, code quality, and workflow efficiency."
          open: "open"
          chapters:
          - chapter: "Introduction and Team Setup"
            type: "video"
          - chapter: "Simulating the real world on local machine"
            type: "video"
          - chapter: "Quick Tour of GIT - why and how"
            type: "video"
          - chapter: "Where to install git from"
            type: "video"
          - chapter: "the init command"
            type: "video"
          - chapter: "status and adding files to staging area"
            type: "video"
          - chapter: "commits and git data management"
            type: "video"
          - chapter: "discarding experimental changes with checkout"
            type: "video"
          - chapter: "resetting and discarding commits"
            type: "video"
          - chapter: "more lectures are being recorded..."
            type: "video"
        - section: "The ART of Interviewing"
          id: "interviewing"
          description: "Organised collection of topics, projects and questions from the web that a Embedded Engineer should know and be able to reasons about."
          open: "open"
          chapters:
          - chapter: "Introduction and Format of the Course"
            type: "video"
          - chapter: "Key concepts in C"
            type: "video"
          - chapter: "C Program and Memory Layout"
            preview: "kO3_LVszNxI"
            type: "video"
          - chapter: ".text section and behaviour in freestanding and hosted environment"
            type: "video"
          - chapter: "Stack, the location and what all goes there"
            type: "video"
          - chapter: "Understanding Heap and the need"
            type: "video"
          - chapter: "demo - code analysis"
            type: "video"
          - chapter: "structs and union"
            type: "video"
          - chapter: "volatile and const"
            type: "video"
          - chapter: "bit-manipulation and pointers"
            type: "video"
          - chapter: "General Embedded Concepts"
            type: "video"
          - chapter: "Some History of computing system"
            type: "video"
          - chapter: "CPU, Memory, ISA and IO"
            type: "video"
          - chapter: "The concept of Interrupts"
            type: "video"
          - chapter: "More lectures being recorded..."
            type: "video"
        - section: "ARM Cortex-A 101 - Introduction to the 64bit ARM CPUs"
          id: "a-101"
          description: "Introduction to ARM-A Class CPUs implementing the AARCH64 architecture."
          open: "open"
          chapters:
          - chapter: "Who is ARM as the Company?"
            type: "video"
          - chapter: "A Class CPUs, Architecture and Micro Architecture"
            type: "video"
          - chapter: "How to learn CPU - different models"
            type: "video"
          - chapter: "CPU as seen by Software Programmer - Programmers model"
            type: "video"
          - chapter: "Programmers guide and revisiting uArch"
            type: "video"
          - chapter: "Long discussion on Els and Secure/non-secure"
            type: "video"
          - chapter: "Exception Levels"
            type: "video"
          - chapter: "Secure and Non-Secure world"
            type: "video"
          - chapter: "Use cases and Software Execution in different ELs"
            type: "video"
          - chapter: "Use case for Secure World Software Execution"
            type: "video"
          - chapter: "Revisiting the Document"
            type: "video"
          - chapter: "GPRs, QEMU and Demo"
            type: "video"
          - chapter: "Exploring the idea of System Registers, SCTLR as example"
            type: "video"
          - chapter: "Processor State Register - CPSR or PSTATE"
            type: "video"
          - chapter: "Idea of Exceptions and saving CPU state"
            type: "video"
          - chapter: "Special Registers"
            type: "video"
          - chapter: "Boot process - Single core and Multi Core"
            type: "video"
          - chapter: "Setup and Demo - Glitch at the end"
            type: "video"
          - chapter: "Revisiting the Demo"
            type: "video"
          - chapter: "Next"
            type: "video"
        - section: "System Components - MMU/SMMU"
          id: "system-components"
          description: "A Course dedicated to understand the concepts of Virtual memory and the hardware components that enable it - the Memory Management Unit (MMU) and the System Memory Management Unit (SMMU)."
          open: "open"
          chapters:
          - chapter: "Problems with multiple processes and physical addresses"
            type: "video"
          - chapter: "Exploring reasons for Memory Management"
            type: "video"
          - chapter: "More lectures being recorded..."
        - section: "Linux Device Drivers 101 - Writing and understanding a dummy driver"
          id: "ldd-101"
          description: "A hands on Introduction to Linux Device Driver development. Recommended for those getting started with driver development."
          open: "open"
          chapters:
          - chapter: "A sandbox to run our experiments"
            type: "video"
          - chapter: "mac-setup"
            type: "video"
          - chapter: "Linux Setup"
            type: "video"
          - chapter: "Windows-setup"
            type: "video"
          - chapter: "Multipass relaunch and installing utilities"
            type: "video"
          - chapter: "Linux Kernel, System and Bootup"
            type: "video"
          - chapter: "User Space, Kernel Space, system calls and device drivers"
            type: "video"
          - chapter: "Files and File operations, System Calls and Drivers"
            type: "video"
          - chapter: "Our first Loadable module - Minimum Code based"
            type: "video"
          - chapter: "Deep Dive - make and Makefile"
            type: "video"
          - chapter: "Using lsmod utility to list loaded Kernel Modules"
            type: "video"
          - chapter: "insmod, module and the kernel"
            type: "video"
          - chapter: "rmmod, kernel and module unloading"
            type: "video"
          - chapter: "modinfo and the mod.c file"
            type: "video"
          - chapter: "proc file system, system calls and user interaction"
            type: "video"
          - chapter: "Exploring entries in /proc"
            type: "video"
          - chapter: "creating the /proc file entry and screwing up the kernel"
            type: "video"
          - chapter: "Implementing the read operation"
            type: "video"
          - chapter: "Passing data to user from kernel"
            type: "video"
          - chapter: "User space app example and challenge for you"
            type: "video"
          - chapter: "Quick Revision, What we did not cover and where to next.."
            type: "video"
        - section: "Linux Device Drivers (102) - Controlling the Hardware"
          id: "ldd-102"
          description: "Course on writing and understanding how the Linux Device Drivers controls real hardware. In this course, we write a kernel driver for the GPIO port of Raspberry Pi - 4."
          open: "open"
          chapters:
          - chapter: "Introduction and Expectations"
            type: "video"
            preview: "FvNPYyQjfMw"
          - chapter: "Hardware and Demo"
            type: "video"
          - chapter: "The generic Boot flow for SoCs"
            type: "video"
          - chapter: "more videos being recorded"
            type: ""
        - section: "Embedded Systems Podcast!"
          id: "podcast"
          description: "Casual chats with Industry Experts focused on their career paths, technology trends, skills and opportunities."
          open: "open"
          chapters:
          - chapter: "Manav | SoC Design flow, MIPS, RISC-V and Automotive"
            type: "video"
        - section: "Tech Syncs - Workshops on ad-hoc topics"
          id: "tech-syncs"
          description: "Live Tech Syncs with learners every once in a while where we discuss ad-hoc topics relating to Firmware and System Software Engineering."
          open: "open"
          chapters:
          - chapter: "ARM Cortex-M CPUs (part - 1) | 30 April 2025"
            type: "video"
          - chapter: "ARM Cortex-M CPUs : Memory Model (part - 1) | 03 May 2025"
            type: "video"
          - chapter: "RISC-V - Introduction | 08 May 2025"
            type: "video"
          - chapter: "ARM Cortex-M CPUs : Memory Model (part - 2) | 14 May 2025"
            type: "video"
          - chapter: "Understanding PCIE | 28 May 2025 (planned)"
            type: "video"
        - section: "Source Code Walkthrough"
          id: "walkthrough"
          description: "Learn how to tame huge code bases written in C. Techniques, tricks and general patterns that help understanding the structure and abstractions used in a repository."
          open: "open"
          chapters:
          - chapter: "Little Kernel (LK)"
            type: "title"
          - chapter: "Setup and getting started"
            type: "video"
            preview: "6goO1CZ7p78"
          - chapter: "Reverse engineering directory structure"
            type: "video"
          - chapter: "Reverse engineering the APP structure"
            type: "video"
          - chapter: "Deciphering compilation logs"
            type: "video"
          - chapter: "more videos being recorded..."
            type: ""
        - section: "(planned) ARM aarch64 - Bare-metal Programming"
          description: "This course is being recorded at the moment and will be added soon."
          open: "open"
          chapters:
        - section: "(planned) Data-structures and Algorithms for Embedded Engineers"
          description: "This course is being recorded at the moment and will be added soon."
          open: "open"
          chapters:
        - section: "(planned) Python and Automation"
          description: "This course is being recorded at the moment and will be added soon."
          open: "open"
          chapters:
      requirements:
        - GitHub account to do the hands-on coding in Codespaces.
        - Interest in the lower level working of the system.
        - Some exposure to Digital systems is good (but not strictly required).
        - Basic understanding of number systems, logic gates, bits and bytes is good to have (but not strictly required).
      audience:
        - Students in Academia with C as a subject in the course.
        - Early Career Professionals using C as development language.
        - Embedded Systems Engineers.
        - System Software Engineers.
        - Electrical/Electronics Engineers working on hardware programming.
        - Systems Engineer seeking gain system level insights.
        - Those curious to learn the underlying details of Systems and how to program it using C.
        - Those seeking a job change and preparing for interviews.
      reviewSectionTitle: "Praise from our learners"
      reviewSectionDescription: "Here's what those who are learning from the courses have to say about the content and delivery."
      reviews:
        - reviewer: "Rushikesh Patil"
          rating: 5
          featured: true
          review: "One of the most essential and affordable course bundles for aspiring firmware engineers! I particularly appreciated the detailed explanations in the C pointers and ARM Cortex-M & assembly programming courses."
        - reviewer: "Shweta S"
          rating: 5
          review: "A well structured course for beginners to expirenced professionals, one who is keen in learning what the C program does to the underlying system, this course is for them. I personally enjoyed the debugging using the gdb dashboard. I am looking forward to dive deeper as the course unfolds, I highly recommend this course for all the embedded engineers."
        - reviewer: "Rohit Alate"
          rating: 5
          review: "Hello Team, if possible , please create the playlist in some sequence in which we should go through , so it will be really helpful.thanks in advance, and content wise you guys are amazing..... and i would say thanks to team to creating such platform for us..."
        - reviewer: "PADMALAYA RAWAL"
          rating: 5
          review: "This bundle is crazily interactive. Be aware that it will make you addicted to learning more about embedded systems beyond just looking for jobs. Thanks to the team, who are adding more courses to the bundle, it's never going to be outdated! Loving it❤️‍🔥"
        - reviewer: "Inturi Sri Sasi Kiran"
          rating: 5
          review: "I am taking a moment to give shout out the the authors of this course, sorry actually it's not just a course it is standard text book for an Embedded Engineer or who wants learn Embedded Engineering. I will strongly recommend this course to the college students especially those who are looking for a career in the Embedded sector."
        - reviewer: "Gnanesh Sureshchandra"
          rating: 5
          review: "This course gives you exactly what you need to know about pointers! And more importantly how to think about pointers this is really important, and every embedded engineer must know. Once again thanks a lot for this content creators. Expecting more courses from you in future. (for: C Pointers)"
        - reviewer: "Arjun"
          rating: 5
          review: "Awesome, within an hour, if an engineer learns the boot up process of arm - cortex-m, that is unbelievable, instructor is really apt at the matter. Thanks (for: ARM Cortex-M 101)"
        - reviewer: "Selva Gandhi P"
          rating: 5
          review: "I want to say that this course has truly been eye-opening for building my career. Thank you so much, brother, for all the support and guidance. 🙏🏻"
        - reviewer: "Imene Benamor"
          rating: 5
          review: "I'm currently taking this course, and it's been great so far! The content is clear, practical, and easy to follow. I'm already learning a lot and looking forward to diving deeper. Would definitely recommend it to anyone looking to build or strengthen their skills in embedded systems."
        - reviewer: "Earnest Kihara"
          rating: 5
          review: "I wish I had came across this course when I was getting started into embedded C, thankyou Piyush for coming up with this course ,its worth it . I recommend it to all beginner and intermiadiate students and anyone else who feels there is some dots they can't connect in C"
        - reviewer: "Pavankalyan G"
          rating: 5
          review: "Really enjoyed reading this book! It provides great insights and is well-written."
        - reviewer: "@n.5s4584"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kwaiEov46AN__mYTLshOyDgJfnS9npGBzAYALfOGI=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating: 5
          review: "I just wanted to take a moment to appreciate the amazing content you create! Your videos are not only engaging but also incredibly valuable. I’ve learned so much from your channel, and I always look forward to your uploads. Thank you for sharing your knowledge and insights—keep up the great work! Wishing you all the success you deserve."
        - reviewer: "@its_me_to-i4e"
          photo: "https://yt3.ggpht.com/ytc/AIdro_mj1PTnXtbKrudNYF6unc92tNmWG36cHOfo1udycpGb3U-7ha_eNbAtmaLVWjAoHsi59z0=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating: 5
          review: "Your content is amazing! Last time, I bought the advanced C pointer course, and it was so helpful for embedded systems. Please consider making the course fees more affordable so that students like me can easily access them. Keep up the great work"
        - reviewer: "@sharifyy"
          photo: "https://yt3.ggpht.com/ytc/AIdro_mYvoZpJFyDpETsr-Nn2NhLTCwnNju7VLGDF1Bv0px-5A=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating: 5
          review: "your content is amazing, I give it 5 stars"
        - reviewer: "@techpartel9858"
          photo: "https://yt3.ggpht.com/rC37PHOuyl8VqqsWdEyVNKdRKgDoPutmfn-MWlL4iAYgwdlPqrjHjCDbrXtKWuv4qgybu_gY=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating: 5
          review: "The flow of this course is Amazing. It covers a whole system overview of how your C code runs and how it's dumped in your hardware. Everything is excellent. Thank you, @piyush."
        - reviewer: "@Simi-bc8sb"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kyiEEZEs-Crzq8SJwJJ9aDaKqD04Ki4w4B0XhTr9o=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating: 4.9
          review: "Great content. I really appreciate. Thank you"
        - reviewer: "@ElizabethGreene"
          photo: "https://yt3.ggpht.com/ytc/AIdro_lzSPNkz-qAuBGX37IqlrjwqU1aWC867oJ0TWJyIcw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 5
          review: "Was there any reason why you preferred the RISCV32i chip over an x86 chip in QEMU?  I appreciate the lesson in cross compiling too, but was curious why. Thanks for making these. 10/10"
        - reviewer: "@soumyadipkar9451"
          photo: "https://yt3.ggpht.com/ytc/AIdro_nfY73MK2vFdOh4b68xvVqUPDnjeQxRGiRhVMKYZiaikQ=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 5
          review: "Enjoyed the session a lot sir! GDB Dashboard is truly amazing! 🔥"
        - reviewer: "@vimalathithand917"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kgporA3By7tcfvxHINPDGILoCdkyi4KM7s64Zpcn_ikw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating:
          review: "Just what I was looking for ! I'm sure that this series is going to be a blast ! Please don't stop the series in the middle and thanks a lot !"
        - reviewer: "@aadishm4793"
          photo: "https://yt3.ggpht.com/SjiVNC30ZvLCyHEerGIbcy6Ye1GCERCPlhQ9A70aJiHm5_o5lphLZPKJotqp6DYXmW68uqONvw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "30/Jan/2025"
          rating:
          review: "Great content!!"
        - reviewer: "@Ujjaval___"
          photo: "https://yt3.ggpht.com/qrBr5avCgdgeFJDSvuSRes99r73vZ1Px1eKpl8PqB1tw5MYZJmuw5XOsdmtDqytXPE_u8cVm2g=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "30/Jan/2025"
          rating:
          review: "AMAZING VIDEOS"
        - reviewer: "@aadishm4793"
          photo: "https://yt3.ggpht.com/SjiVNC30ZvLCyHEerGIbcy6Ye1GCERCPlhQ9A70aJiHm5_o5lphLZPKJotqp6DYXmW68uqONvw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "30/Jan/2025"
          rating:
          review: "Awesome as all the videos 👍👍🔥"
        - reviewer: "@Padmalayarawal"
          photo: "https://yt3.ggpht.com/Tus9ambPweMlf-GRcBnNjFG0exRlCo-w7btFq4bhhS1XdInSEpx_QKZgOHExfDqRmPcg-SqIhw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "30/Jan/2025"
          rating: 5
          review: "Really loved your new content, can't ask for more crazy stuff."
        - reviewer: "@shabeehabbas4737"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kghj6IsyrE1N06BjvWWGHkFWkZx6Hv7zvTIEH4L9xL3Z2pxlwisykzJylXJN4sVl1laQ=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "29/Jan/2025"
          rating:
          review: "Hello bro just saw the this video and I cant wait to start the course, the roadmap is unconventional which is why I think its the most awesome one, please dont stop uploading such great content ❤❤❤"
        - reviewer: "@ankitrajbhar6045"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kMlhmNrwHbb-na93Sx772XJk4WiX5iiD_6LQIu4jxoEbM=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 5
          review: "This is what I actually needed in life today.. thanks a tons.."
        - reviewer: "Bhanu Sri Dasari"
          rating: 5
          review: "Great content"
        - reviewer: "Ashith Polepalli"
          rating: 5
          review: "Excellent content to learn firmware"
        - reviewer: "Rahul Kumar"
          rating: 5
          review: "no second thought.. go for it"
        - reviewer: "Vikas Naga"
          rating: 5
          review: "The best course in Embedded System so far."
        - reviewer: "Mariyam Shahid"
          rating: 5
          review: "the best content on c!"
        - reviewer: "@EEShyama"
          photo: "https://yt3.ggpht.com/ytc/AIdro_lEZ-lojSo_TMLmbjtJocEMwGBz5u_W63aMWrcQJOs=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          rating:
          review: "Loving these lectures!! Please keep them coming."
        - reviewer: "@RavindraBhandari-nf8vs"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kgeb3tvIBGrdY-IdjHykSG-MSKpwcehWUAO3_O6TXPgadO46BAk4RkoG8qNgXDJBfHxg=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 4
          review: "I like your teaching method 🫡"
      compare:
        - feature: "C language and pointers with focus on machine behavior"
          us: true
          others: false
        - feature: "Detailed analysis of data types and significance."
          us: true
          others: false
        - feature: "Assembly and C Coding without IDE"
          us: true
          others: false
        - feature: "Detailed explanation and view of Programmer's model of CPU."
          us: true
          others: false
        - feature: "Mental models of various components in the System to reason based off."
          us: true
          others: false
        - feature: "A Bottom-Up Approach with the tinge of answering the `Whys`."
          us: true
          others: false
        - feature: "Thorough explanation of toolchain utilities (gcc, as, ld, ar, gdb etc)"
          us: true
          others: false
        - feature: "Connecting the concepts with practical use cases and use in industry."
          us: true
          others: false
        - feature: "Hands-on experiments to prove every concept."
          us: true
          others: false
        - feature: "Focused on practical professional insights"
          us: true
          others: false
        - feature: "Teach multiple CPU architectures (ARM-M, ARM-A, RISC-V)."
          us: true
          others: false
        - feature: "Cover the toolchain utilities like compiler, assembler, linker and debug tools like GDB?"
          us: true
          others: false
        - feature: "Learn at your own pace."
          us: true
          others: false
        - feature: "Superficial and confusing explanation"
          us: false
          others: true
        - feature: "Burn a hole in the pocket with Fee"
          us: false
          others: true
        - feature: "On campus presence required."
          us: false
          others: true
      faqs:
        - q: "What is the difference between these courses (paid) and the content on YouTube?"
          a: "Some lectures from different courses have been put on YouTube as Preview. The are not structured and jump to a topic. The Courses in the Subscription are well structured and focused on developing a skill."
          open: "open"
        - q: "Is this recommended for beginners?"
          a: "Yes! The courses are taught as if the learner has no idea about the subject. Each course starts of by ensuring that the basics needed to understand the followup lectures is understood."
          open: "open"
        - q: "Why a subscription model?"
          a: "We are billed for the hosting and bandwidth by the platform provider. While we would very much like to offer lifetime validity, given the recurring bills, we have to ensure we continue to earn enough to be able to fund the effort and bring more value to our learners. The quarterly plan is for those who cannot afford the yearly subscription but can benefit from burst learning. To get the most out of our content, we recommend subscribing to the yearly plan."
          open: "open"
        - q: "Do I need a special machine configuration to take this course?"
          a: "No! All you will need is an internet connection and the Chrome browser. The hands-on examples and lab work is based on GitHub codespaces platform. We use GitHub Codespace to ensure that you don't struggle with the setup and focus on the learnings. You are always free to setup the environment locally. Although, we won't support that, but you are free to do so. The courses, as much possible use a Emulator target of a real board, so if you wanted to run the code on real board. You can do so."
          open: "open"
        - q: "Why is a GitHub account needed?"
          a: "The Experiments and Labs are based on the GitHub provided Codespaces virtual machine. Codespaces will enable a common work environment for all the learners and avoid the hassle of special setup."
          open: "open"
        - q: "Can I change my email-id post purchase?"
          a: "As much as we'd like to support that, your account will be linked to your email-id post purchase."
          open: "open"
        - q: "What name will be printed on the Certificate?"
          a: "The name you use on the platform will be printed as is on the Certificate when it is generated."
          open: "open"
        - q: "Can I follow the steps on my own PC?"
          a: "Yes for the most part. Better yet would be if you have a linux machine."
          open: "open"
        - q: "I previously purchased a course from inpyjama/pyjamabrah, any discount for me?"
          a: "Yes. We can offer a discount on the yearly subscription. Please reach us at support@pyjamabrah.com and be sure to include the details of your past investment. We will work on a custom discount for you."
          open: "open"
---

**Important:** Planned courses are not yet ready for learners and will be added as the current recording concludes.

# Email from one of the learners ♥️
![](email.png "One of the subscribers wrote to us, this...")

# The Philosophy behind the courses?

We have been creating content for the Embedded Software Engineering community for over a year now. If you have been following us, you would know that we have launched courses in the past, with `Firmware Engineering Arsenal` (later renamed to `Firmware Engineering`) being the most popular one. The Courses on `C lnaguage` and `C Pointer` have been an all time hit and got us to where we are.

We noticed that we (a small) team were having a hard time supporting different courses individually. And learners were feeling left out when we included one course in one bundle but not another. To make life easy for all, we have decided to offer all the courses to everyone under **quarterly** and **yearly** subscription plans. This we believe will free us from the complications that come with attended to everyone on different chat windows.

To help reinforce all the learnings and ensure the learner has a deep sense of practical usage of the lessons, we have introduced **Tech Sync (Workshops)** where we present live on topics and take questions.

![](learning-portal.png "View of the Learning Portal")

## Learning Paths - For anxiety free life!

Embedded Engineering has not had a linear path. We are attempting to being order to the chaos. The courses are deliberately designed and ordered in the way they are. You can take each course individually or just follow the learning paths shown in the image below. The ones of the left are for firmware engineers (or aspiring candidates) and the ones on right are for those interested in systems software engineering.

![](tracks.svg "Learning Paths")

## Firmware Engineering

Firmware Engineering involves working with microntrollers. These are typically 32-Bit CPUs (like ARM Cortex-M, RISC-V RV32 etc) with focus on power saving. Engineers tend to either write `bare metal` code or use an `RTOS` (like FreeRTOS, Zephys, ThreadX etc) if there is a need to handle complicated state machines.

Having a good understanding of what the CPU does as the result of the C code is a skill that will put you in the top 1% of the entry level Firmware engineers. Being able to understand a senior and co-operate to write the code is more than enough. Notice that the `C language` and `C Pointers` course will exactly help you become this. The `C Language` course is all about insights and based on the RISC-V CPU. So not only do you learn C the way it should be (by being able to reason down to the CPU) but also you learn programmers model and assembly for the RISC-V CPU. Double win!

The ARM Cortex-M 101/102 Introduces the ARM-M Architecture and focuses on booting and programming the CPU in Assembly. You will write a secheduler in assembly as part of these courses, this is deliberate and makes way for understanding FreeRTOS which follows. Going through these courses, you will notice how similar the RISC-V and ARM-M architectures are. By the end of the ARM courses, you will be having the skills of a senior firmware engineer.

The FreeRTOS course is laser focused on tearing down and reasoning about the scheduler and the OS primitives (mutex, semaphores etc). There are many engineers who work with FreeRTOS on a daily basis but don't understand the internals and thus, hit a glass-roof in their career. Being able to reason about OS constructs like mutex, semaphore, spinlocks etc is important. You will also learn the rare skill of porting FreeRTOS from scratch on a new ARM-M target!!

To grow up the ladder you will need to master the CPU's programmer model, architecture and be able to use the toolchain (gcc, ld, as, ar, gdb etc) to place the code/data in the memory, debug the solution and write build automation help.

Senior or Staff level engineers worry about details like power, performance, stability and fault tolerance of the firmware. Being an absolute master of C, CPU Architecture, Operating Systems and Debug tools is a must! If you notice, the courses are lined up to get you to becoming a master...

## Systems Engineering

Stellar Systems Software Engineers are firmware engineers who are working with Application Grade CPU (ARM Cortex-A, RISC-V RV64, AMD, Intel etc), Complex and interconnected system capable of running Higher Level Operating System (Linux, Mac-OS, Windows etc), Hypervisors and Virtualizer and Systems capable of running general applications like the chrome browsers.

The Application processors are complicated in their architecture and have layers privileges and modes. Systems Engineer need to have a good understanding of the CPUs to be able to reason about the systems level on-goings. They are involved in working with Bootloaders, hypervisors, OS Kernel (Linux, Windows etc) and need to be very thorough with the understanding of the Operating Systems.

The courses included focus on the ARM Cortex-A (aarch64) and RISC-V RV64 architectures. The introductory courses give a over all view of the given architecture. Once the architecture is understood, the next in line is the Linux Device Drivers. The 101 course, provides a deep insight into how the Linux Kernel Drivers work and the anatomy of a general character driver.

We focus on the ARM-A class CPUs just because they are very popular and used in Mobiles, Watches, Tablets, Desktops/Laptops and Servers! Investment into learning this architecture is to prepare for the future and bullet proof your career!

## General Skills

Honing technical skills is not enough. For these reasons we have included courses on general skills that a Firmware/Systems Software Engineer should have. When working in teams, collaboration is a big one and most semiconductor companies use tools like Git and Gerrit for source code management. Master these will enable you to be a reliable teammate!

`The ART of Interviewing` is a collection of special topics and interview experiences that will arm you with the knowledge and mindset to have a productive technical discussion with an interviewer (not to mention, become a better interviewer too)!

# More!

We will be adding more courses in the paths so eventually this becomes a robust and reliable path to take as to become a firmware or systems software engineer. The subscribers of course will get the updates for free :)

# Our Recommendation

Unless you are a student or an early professional who cannot afford the Yearly plan, our recommendation is to go for the Yearly Subscription to get the most bang for the buck.

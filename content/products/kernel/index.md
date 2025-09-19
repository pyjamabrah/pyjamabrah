---
layout: products

url: /kernel-from-scratch

aliases:
- /products/kernel-from-scratch/

title: "Build and Run Linux Kernel"
date: "2025-09-14T17:48:22+05:30"
tags:
  - bundle
description: "Learn how to compile and boot the Linux Kernel from the source code."
thumbnail: "/kernel-from-scratch/cover.png"
categories: courses
product: "kernel-from-scratch"

define: &enrolled 2000+
define: &lastupdated "19 September 2025"

param:
  image: "/kernel-from-scratch/cover.png"
  bundle:
    - course: "Build and Run Linux Kernel (from scratch)"
      subtitle: "`from the source to the prompt`"
      description: "Unlock the power of low-level system development with this hands-on video course, designed to guide you through the process of building a Linux kernel from source for the ARM64 architecture and running it on the QEMU virtual machine. Perfect for developers, system administrators, and enthusiasts eager to dive into kernel development, this course provides a step-by-step approach to compiling, configuring, and deploying a custom Linux kernel, using BusyBox to create a lightweight userspace environment."
      previewCover: "/kernel-from-scratch/cover.png"
      # previewVideo: "https://github.com/pyjamabrah/preview-videos/raw/refs/heads/main/C%20to%20Assembly.mp4"
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 5
      ratingCount:
      studentsCount: *enrolled
      message: ""
      courseCount:
      emulator: true
      hardware:
      workshops:
      newcontent:
      creators:
        - name: "Piyush Itankar"
          designation: "Embedded Engineer (L5), Google"
          contactLink: "https://x.com/pyjamabrah"
          photo: "https://avatars.githubusercontent.com/u/2120983?v=4"
          bio: "Electrical Engineer holding a Master’s degree in Embedded Systems, with a proven track record at industry giants. At Intel, contributed expertise to Navigation Firmware, Bluetooth Driver development, and RF validation software. Currently thriving as an Embedded Software Engineer at Google, drove innovation in Firmware development for the Power Management Sub-system on Tensor SoCs (Pixel Phones) and presently advancing system software for the Pixel Watch."
      lastUpdated: *lastupdated
      language: "English"
      lessons: 15
      length: "~ 3 Hours"
      files: 3
      quizzes:
      certificate: "/kernel-from-scratch/certificate.png"
      validity: 365 days
      projects: 1
      learning:
        - Understanding the Linux Kernel.
        - Setting Up the Development Environment.
        - Building the Linux Kernel.
        - Configuring BusyBox.
        - Running on QEMU.
        - Troubleshooting and Debugging.
        - Real-World Applications.
      sections:
        - section: "Build and Run Linux Kernel"
          id: "ldd-scratch"
          description: "Unlock the power of low-level system development with this hands-on video course, designed to guide you through the process of building a Linux kernel from source for the ARM64 architecture and running it on the QEMU virtual machine. Perfect for developers, system administrators, and enthusiasts eager to dive into kernel development, this course provides a step-by-step approach to compiling, configuring, and deploying a custom Linux kernel, using BusyBox to create a lightweight userspace environment."
          open: "open"
          chapters:
          - chapter: "here's a sneak-peak ..."
            preview: "sxxuAorWep4"
          - chapter: "Introduction"
            type: "title"
          - chapter: "Introduction"
            type: "video"
          - chapter: "Cheat sheet"
            type: "video"
          - chapter: "Environment and Plan"
            type: "video"
          - chapter: "Using docker to create a linux host machine"
            type: "video"
          - chapter: "Setup, Build and Run"
            type: "title"
          - chapter: "Installing the toolchain and utilities"
            type: "video"
          - chapter: "Compiling the kernel"
            type: "video"
          - chapter: "Ramdisk and busybox"
            type: "video"
          - chapter: "Getting and building busybox"
            type: "video"
          - chapter: "Creating the ramfs image"
            type: "video"
          - chapter: "Booting the kernel"
            type: "video"
          - chapter: "Trim the Kernel"
            type: "title"
          - chapter: "menuconfig and .config"
            type: "video"
          - chapter: "The trimmed Linux Kernel"
            type: "video"
          - chapter: "the .config file"
            type: "pdf"
          - chapter: "Recap and Conclusion"
            type: "title"
          - chapter: "Revisiting all the steps and the significance"
            type: "video"
          - chapter: "(Bonus) Device Tree"
            type: "video"
          - chapter: "Resources and Pointers"
            type: "pdf"
      requirements:
        - Basic familiarity with Linux command-line tools.
        - Understanding of C programming and system architecture concepts is helpful but not required.
        - A computer with a Linux distribution (e.g., Ubuntu) for development.
      audience:
        - Developers interested in Linux kernel development or embedded systems.
        - System administrators looking to understand low-level system operations.
        - Hobbyists and students eager to explore ARM64 architecture and virtualization.
        - Anyone curious about building and running a custom Linux kernel from scratch.
      reviewSectionTitle: "Reviews from the learners"
      reviewSectionDescription: "Because the course is brand new, we released some lectures on YouTube to get early feedback, and it has been a banger! You will not regret taking this course..."
      reviews:
        - reviewer: "Jim Nnamdi Samuel"
          date: "15/05/2025"
          rating: 5
          review: "very insightful"
        - reviewer: "Pulkit Singla"
          rating: 5
          review: "Fantastic explanation of the basic concepts. This course has helped me a lot in understanding the basics that I struggled with before."
          date: "21/05/2025"
        - reviewer: "Aditya Shidlyali"
          review: "Even though I know C language, after going through this series of lectures I was like wow, just amazing. Thank you so much Piyush and team making me learning embedded systems in joyful way and working on these kind of world was one of my dream and thanks for making me learning these things."
          date: "16/06/2025"
          rating: 5
      compare:
        - feature: "Basic C Syntax."
          us: true
          others: true
        - feature: "Data types, strings, pointers, operators and other basics."
          us: true
          others: true
        - feature: "Code development without IDE, like how the professionals do it."
          us: true
          others: false
        - feature: "Decomposition of C code into Assembly and conversion to machine code."
          us: true
          others: false
        - feature: "Mental models to aid thinking and reasoning."
          us: true
          others: false
        - feature: "A Bottom-Up Approach with the tinge of answering the `Whys`."
          us: true
          others: false
        - feature: "Mixing C with Assembly"
          us: true
          others: false
        - feature: "Real and applicable Case study and programming projects"
          us: true
          others: false
        - feature: "Project-Based Learning - Develop and learn with a simple yet effective project like C shell, memory allocator, etc."
          us: true
          others: false
        - feature: "Teach with insights at the CPU level."
          us: true
          others: false
        - feature: "Cover Assembly Language and Machine code."
          us: true
          others: false
        - feature: "Cover the toolchain utilities like compiler, assembler, linker and debug tools like GDB?"
          us: true
          others: false
      faqs:
        - q: "What is the difference between this course (paid) and the videos on YouTube?"
          a: "Only few initial videos are put on YouTube. The Full course has many more videos and is a paid offering. Learners will also have access to the notes, source code files and other resources."
          open: "open"
        - q: "Is this course good for beginners?"
          a: "Yes! The course is taught as if the learner has no idea about the C programming language."
          open: "open"
        - q: "Why is the course validity 365 days?"
          a: "We need to maintain the servers that host the courses. At the moment we have enough capital to keep the server afloat for another until. We are striving to make this a lifetime access course. As the funds trickle in, we will revisit the validity and might update it for all the enrolled learners."
          open: "open"
        - q: "Do I need a special machine configuration to take this course?"
          a: "No! All you will need is an internet connection and the Chrome browser. The hands-on examples and lab work is based on GitHub codespaces platform."
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
        - q: "How will the open-source contribution work?"
          a: "We will host few github repos under pyjamabrah with the skeleton code and details asks (in comments) about the subsequent tasks. You can add the code (with your details in the comment if you'd want), create PR (pull-request) and submit. We will review and merge your PR into main."
          open: "open"
        - q: "Will this course be added to `Firmware Engineer's Arsenal`?"
          a: "No! This is a separate offering and unrelated to my previous work at inpyjama.com. pyjamabrah is exclusively run by me and independent of continuous collaboration with my team."
          open: "open"
---

## Course Highlights:

- **Hands-On Approach**: Follow along with practical, real-time demonstrations of each step, from source code to a running system.
- **ARM64 Focus**: Target the ARM64 architecture, widely used in modern devices like servers, mobile devices, and embedded systems.
- **Minimalist Userspace with BusyBox**: Learn to create a compact and efficient userspace to complement your kernel.
- **QEMU Virtualization**: Harness the power of QEMU to test and experiment without needing physical hardware.
- **Expert Guidance**: Benefit from clear explanations and best practices for kernel development and system emulation.

## Who Should Take This Course:

By the end of this course, you’ll have the skills and confidence to build, configure, and run your own Linux kernel on an ARM64 QEMU virtual machine, complete with a BusyBox-based userspace. Start your journey into the heart of Linux today!

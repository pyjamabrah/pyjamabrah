---
layout: products

title: "The C Language"
date: "2025-01-08T17:48:22+05:30"
tags:
  - bundle
description: "Learn it from Scratch. Simple Explanation. Deep Insights!"
thumbnail: "/products/c-language/c-course.png"
categories: courses
product: "c"

define: &enrolled 131
define: &lastupdated "1 Mar' 2025"

param:
  image: "/products/c-language/c-course.png"
  note: "Claim the Discounted Prices while the course is being developed!"
  bundle:
    - course: "The C Language"
      subtitle: "Learn it from Scratch. Simple Explanation. Deep Insights!"
      description: "A foundational course taught in an unconventional way to get you the skills of a professionals. Taught by an industry expert, you will be able to code without an IDE, use all the tools involved in building the source code and reason about your program at the system level."
      previewCover: "/products/c-language/c-course.png"
      previewVideo: "https://github.com/pyjamabrah/preview-videos/raw/refs/heads/main/C%20to%20Assembly.mp4"
      bestSeller: "yes"
      beginner: "yes"
      intermediate: "yes"
      rating: 4.83
      ratingCount: 6
      studentsCount: *enrolled
      creators:
        - name: "Piyush Itankar"
          designation: "Embedded Engineer (L5), Google"
          contactLink: "https://x.com/pyjamabrah"
          photo: "https://avatars.githubusercontent.com/u/2120983?v=4"
          bio: "Electrical Engineer with a master's degree in Embedded Systems. Has worked at Intel on Navigation Firmware, Bluetooth Driver and RF validation software. Currently working as an Embedded Software Engineer at Google. Has been involved with Firmware development for the Power Management Sub-system on the Tensor SoCs (Pixel Phones) and Pixel Watch System Software."
      lastUpdated: *lastupdated
      language: "English"
      lessons: 42
      length: "~ 12 hr"
      files: 6
      quizzes: 29
      certificate: "/products/c-language/certificate.png"
      validity: 365 days
      learning:
        - Mental models to use when coding in C.
        - What is machine code.
        - Instruction Set Architecture and Assembly coding.
        - GNU toolchain utilities/programs (gcc, as, ld wtc).
        - GNU Debugger (GDB).
        - Automation using Makefiles.
        - How text is converted to 0s and 1s.
        - Syntax and Structure of C Programs.
        - Data types, variables, declaration/definition.
        - Arrays, Strings and Pointers.
        - Structs and Union.
        - arithmetic, logical, relational operators in C.
        - Functions and Modules/Libraries in C.
        - Pointers and how to use them in Design.
        - Types of pointers.
        - Bit fields and Bit manipulation.
        - Const and volatile type qualifiers
        - Controlling placement of code and data in memory.
        - Loops - for, while, do while.
        - Branching - if, if-else, switch, goto.
        - Mixing Assembly and C and the need for it.
        - Booting RISC-V CPU from scratch.
        - Cross compiling and what it means.
        - memory management - Stack vs. Heap.
        - Dynamic memory allocation (malloc, calloc, realloc, free).
        - Compiler optimizations (-O1, -O2, -O3, -Os, -Ofast).
      sections:
        - section: "C Language Tour"
          description: "The section focuses on the Roadmap, Mindset and the lense through which this course is to be pursued. We also dive into exploring a basic C program so you can learn to spot the patterns when exploring the code outside of the course. To further empower you, we will also look at the three work horse feature of this language."
          open: "open"
          sectionDuration: 1 hr 4 min
          chapters:
            - chapter: "The Roadmap and Mindset"
              preview: ""
              type: "video"
              meta: 06:54
              attachments: ""
            - chapter: "Sandbox Environment and Basic C Program"
              preview: ""
              type: "video"
              meta: 30:02
              attachments: ""
            - chapter: "Sandbox environment and basic C program."
              preview: ""
              type: "quiz"
              meta: "11"
              attachments: ""
            - chapter: "Hands on: Fix the Code."
              preview: ""
              type: "code"
              meta: ""
              attachments: ""
            - chapter: "Keep an Eye on Functions, Pointers and Structs"
              preview: ""
              type: "video"
              meta: 08:04
              attachments: ""
            - chapter: "Keep an Eye on Functions, Pointers and Structs"
              meta: "7"
              type: "quiz"
            - chapter: "Example of the RAW power - Functions, Struct and Pointers"
              preview: ""
              type: "video"
              meta: 19:50
              attachments: 3
            - chapter: "Example of the RAW power - Functions, Struct and Pointers"
              meta: "11"
              type: "quiz"
        - section: "Mental Models to Brain tattoo"
          open: "open"
          description: "In this section we will discuss the mental models that you can use to reason about the programs. In an attempt to doing this, we will explore the models of systems from 1970s. System composition and the CPU, Memory and Interactions with environment. This sets the foundation that will enable you to exactly predict the system behavior as a result of the C program that you write."
          sectionDuration: "44 min 11 Sec"
          chapters:
            - chapter: "Mental Model of the System"
              preview: ""
              type: "video"
              meta: 16:43
              attachments: 0
            - chapter: "The mental model of the CPU"
              preview: ""
              type: "video"
              meta: 11:41
              attachments: 0
            - chapter: "The mental model of the Memory"
              preview: ""
              type: "video"
              meta: 15:47
              attachments: 0
        - section: "From text to 0s and 1s"
          open: "open"
          description: "In this section, you will learn how the text gets transformed int 0s and 1s that represent the instructions in the memory."
          sectionDuration: "1 hr 36 min"
          chapters:
            - chapter: "Instruction Encoding and the rv32i ISA"
              preview: ""
              type: "video"
              meta: 25:52
              attachments: 0
            - chapter: "A tour of Toolchain, QEMU, GDB"
              preview: ""
              type: "video"
              meta: 16:23
              attachments: 0
            - chapter: "demo - Assembly to binary, QEMU and GDB"
              preview: ""
              type: "video"
              meta: 27:04
              attachments: 0
            - chapter: "Instruction Encoder Decoder, Makefile and GDB Dashboard"
              preview: ""
              type: "video"
              meta: 26:43
              attachments: 0
        - section: "Dwelling in the World of Assembly"
          open: "open"
          description: "Understanding what the system does as a result of the C program becomes very simple once we know how the C statements may be translated to the assembly code. We will thus spend time mastering the structure of the Assembly programs and the instructions available to us."
          sectionDuration: "1 hr 13 min"
          chapters:
            - chapter: "Anatomy of Assembly Program, writing code, debugging in GDB"
              preview: ""
              type: "video"
              meta: 26:59
              attachments: 0
            - chapter: "Decomposing C to Assembly and the relation"
              preview: ""
              type: "video"
              meta: 28:15
              attachments: 0
            - chapter: "Getting CPU from assembly to jump to C program"
              preview: ""
              type: "video"
              meta: 18:01
              attachments: 0
        - section: "C Keywords - Data types"
          open: "open"
          description: "In this section you will spend time internalizing each of the 32 keywords from the C Language and understand the assembly and system level implications."
          sectionDuration: "3 hr 30 min"
          chapters:
            - chapter: "Introducing the C Keywords"
              preview: ""
              type: "video"
              meta: 12:40
              attachments: 0
            - chapter: "Data types, Variables and Integers"
              preview: ""
              type: "video"
              meta: 12:47
              attachments: 0
            - chapter: "Data types - float and double"
              preview: ""
              type: "video"
              meta: 05:58
              attachments: 0
            - chapter: "Exploring sizes of data types and location in memory "
              preview: ""
              type: "video"
              meta: 37:11
              attachments: 0
            - chapter: "how integers are stored - 2s complement"
              preview: ""
              type: "video"
              meta: 19:36
              attachments: 0
            - chapter: "floating point number encoding and few examples"
              preview: ""
              type: "video"
              meta: 13:51
              attachments: 0
            - chapter: "more floating point - float and double"
              preview: ""
              type: "video"
              meta: 17:23
              attachments: 0
            - chapter: "signed and unsigned"
              preview: ""
              type: "video"
              meta: 9:56
              attachments: 0
            - chapter: "const and volatile"
              preview: ""
              type: "video"
              meta: 11:16
              attachments: 0
            - chapter: "demo - const and volatile"
              preview: ""
              type: "video"
              meta: 15:31
              attachments: 0
            - chapter: "void, c standard and gnu C manual"
              preview: ""
              type: "video"
              meta: 7:40
              attachments: 0
            - chapter: "typedef and sizeof"
              preview: ""
              type: "video"
              meta: 18:30
              attachments: 0
            - chapter: "structs and unions"
              preview: ""
              type: "video"
              meta: 30:26
              attachments: 0
            - chapter: "enums as named numbers"
              preview: ""
              type: "video"
              meta: 13:22
              attachments: 0
        - section: "C Keywords - Branching and Looping"
          open: "open"
          description: "In this section take a look at the keywords that relate to branching and looping"
          sectionDuration: "2 hr 30 min"
          chapters:
            - chapter: "if, else, switch, case, default, do, while, for, continue and break"
              preview: ""
              type: "video"
              meta: 35:20
              attachments: 0
            - chapter: "goto and return"
              preview: ""
              type: "video"
              meta: 9:04
              attachments: 0
            - chapter: "Demo - if, else if and else effects at assembly level"
              preview: ""
              type: "video"
              meta: 25:04
              attachments: 0
            - chapter: "Demo - switch case and effects at assembly level"
              preview: ""
              type: "video"
              meta: 11:27
              attachments: 0
            - chapter: "Demo - loops - for, do, while, continue and effects at assembly level"
              preview: ""
              type: "video"
              meta: 22:53
              attachments: 0
            - chapter: "Demo - goto and jumps across functions"
              preview: ""
              type: "video"
              meta: 10:20
              attachments: 0
            - chapter: "auto, register, extern and static"
              preview: ""
              type: "video"
              meta: 11:01
              attachments: 0
            - chapter: "Demo - auto keyword"
              preview: ""
              type: "video"
              meta: 6:33
              attachments: 0
            - chapter: "Demo - register keyword"
              preview: ""
              type: "video"
              meta: 7:32
              attachments: 0
            - chapter: "Demo - extern keyword"
              preview: ""
              type: "video"
              meta: 9:32
              attachments: 0
            - chapter: "Demo - static keyword"
              preview: ""
              type: "video"
              meta: 14:52
              attachments: 0
        - section: "Variables and Functions"
          open: "open"
          description: "We learn how to write C programs and what role variables and functions play in the context of C programs."
          sectionDuration: "27:44"
          chapters:
            - chapter: "Introduction to Variables and Functions"
              preview: ""
              type: "video"
              meta: 27:44
              attachments: 0
        - section: "Work in Progress"
          open: "open"
          description: "This course is being actively developed at the moment. More sections/Lectures and exercises are regularly added. Sections prior to this are complete and available for learner to pursue..."
          sectionDuration: ""
          chapters:
            - chapter: "Being recorded..."
              preview: ""
              type: "video"
              meta:
              attachments: 0
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
      reviewSectionTitle: "Early praise from YouTube Subscribers"
      reviewSectionDescription: "Because the course is brand new, we released some lectures on YouTube to get early feedback, and it has been a banger! You will not regret taking this course..."
      reviews:
        - reviewer: "@n.5s4584"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kwaiEov46AN__mYTLshOyDgJfnS9npGBzAYALfOGI=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "11/Feb/2025"
          rating: ""
          review: "I just wanted to take a moment to appreciate the amazing content you create! Your videos are not only engaging but also incredibly valuable. I’ve learned so much from your channel, and I always look forward to your uploads. Thank you for sharing your knowledge and insights—keep up the great work! Wishing you all the success you deserve."
        - reviewer: "@its_me_to-i4e"
          photo: "https://yt3.ggpht.com/ytc/AIdro_mj1PTnXtbKrudNYF6unc92tNmWG36cHOfo1udycpGb3U-7ha_eNbAtmaLVWjAoHsi59z0=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "11/Feb/2025"
          rating: ""
          review: "Your content is amazing! Last time, I bought the advanced C pointer course, and it was so helpful for embedded systems. Please consider making the course fees more affordable so that students like me can easily access them. Keep up the great work"
        - reviewer: "@sharifyy"
          photo: "https://yt3.ggpht.com/ytc/AIdro_mYvoZpJFyDpETsr-Nn2NhLTCwnNju7VLGDF1Bv0px-5A=s88-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "10/Feb/2025"
          rating: 5
          review: "your content is amazing, I give it 5 stars"
        - reviewer: "@techpartel9858"
          photo: "https://yt3.ggpht.com/rC37PHOuyl8VqqsWdEyVNKdRKgDoPutmfn-MWlL4iAYgwdlPqrjHjCDbrXtKWuv4qgybu_gY=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "2/Feb/2025"
          rating:
          review: "The flow of this course is Amazing. It covers a whole system overview of how your C code runs and how it's dumped in your hardware. Everything is excellent. Thank you, @piyush."
        - reviewer: "@EEShyama"
          photo: "https://yt3.ggpht.com/ytc/AIdro_lEZ-lojSo_TMLmbjtJocEMwGBz5u_W63aMWrcQJOs=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "2/Feb/2025"
          rating:
          review: "Loving these lectures!! Please keep them coming."
        - reviewer: "@Simi-bc8sb"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kyiEEZEs-Crzq8SJwJJ9aDaKqD04Ki4w4B0XhTr9o=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "1/Feb/2025"
          rating:
          review: "Great content. I really appreciate. Thank you"

        - reviewer: "@ElizabethGreene"
          photo: "https://yt3.ggpht.com/ytc/AIdro_lzSPNkz-qAuBGX37IqlrjwqU1aWC867oJ0TWJyIcw=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 5
          review: "Was there any reason why you preferred the RISCV32i chip over an x86 chip in QEMU?  I appreciate the lesson in cross compiling too, but was curious why. Thanks for making these. 10/10"

        - reviewer: "@RavindraBhandari-nf8vs"
          photo: "https://yt3.ggpht.com/ytc/AIdro_kgeb3tvIBGrdY-IdjHykSG-MSKpwcehWUAO3_O6TXPgadO46BAk4RkoG8qNgXDJBfHxg=s48-c-k-c0x00ffffff-no-rj"
          featured: ""
          date: "31/Jan/2025"
          rating: 4
          review: "I like your teaching method 🫡"

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

# The Design and Deliberation

There are many courses on the internet. I assure nothing comes close to this! C Language has been my daily driver at work for the past decade, and unlike the kernel developers, I used this language to program CPUs from scratch. This means, I have used the C language in its most RAW form - without any standard libraries. By the end of this course you will have first hand experience of that RAW power and will be able to use this language like a seasoned professional.

Over time, I have learnt that there are more C developers than meets the eye. The general public and students don't necessarily get to see it from where they are.

### Why I created this course?

I have had an interesting observations on repeat over the years - **Most engineers learn and use C the wrong way and this course attempts teach C the right way**. This course is a way to correct that. There is a way to look at the world using C, this course is an attempt to teach that skill.

I have had the wonderful opportunity to host **several interns**, lead **recent college graduates**, mentor **early career professionals** and **interview close to 100 working professionals** from the industry for different lower level positions in my team.

Over time, it dawned on me that although many used C on daily basis not everyone knew how to reason about their code at the System Level. For example, when I ask


> What does the `volatile` keyword in C do?


A common answer is

> It tells the compiler not to optimize out a variable.


While the answer is correct, very rarely people can explain what the implications are! A good answer to the question is -

> The variable is not cached in the CPU registers!

An answer at the CPU level hits very differently and confirms that the engineer has a very deep level of systems level understanding.

This course is very carefully designed to teach and reinforce such system level understanding!

# Learning Portal

The course is structured into Sections which have Chapters, Quizzes, Coding Challenges and Articles within them. Chapters also have a nice description to orient the learner as to what to expect, the Quizzes help reinforce the learnings from the Lectures.

![](portal.png "A Clean interface and neatly sectioned topics")

For the Lectures, you have the option to adjust the playback speed from `x0.25` to `x2` depending on what works best for you. The Code I write and explain is also shared as attachments.

# Lectures

I like the old school way of `chalk-and-board` when it comes to explaining the fundamental concepts. Doodles and Scribbling help drive the point home.

![](/products/c-language/course.gif "Screenshots from the lectures")

The lectures are more of us both sitting together and me explaining you on the paper how things work! I scribble on the screen, digital whiteboard and on the Code on the screen - This (trust me), I believe helps keep your focus on exactly the concept I want you to internalize.

The other thing that I use to ensure you don't struggle with the vocabulary of the language is - **Repeat critical things on repeat throughout the Course!**

# Hands on real world Skills

The course is based on `GitHub codespaces`, which means you will not need any special machine, just access to the internet and chrome browser. We set up the working environment on a Linux powered Cloud Virtual machine available to all GitHub users.

![](c-asm.png "We learn system level interaction by decomposing C to ASM.")

We will install all the toolchain and utilities required in `codespaces`, you personal machine stays untouched. Of course, if you want to setup everything on your machine there are steps for that too!

# The RISC-V ISA and Debugging

I have based the Course on the RISC-V Instruction set Architecture. This architecture has few instructions and helps us focus on learning and not be lost in the detailed nuances of the instructions. Further, there is a huge community out there, support and documentation is available easily.

![](gdb.png "We run the code")

We learn by converting the C code to Assembly and reasoning about what the system will do as a result. To be able to look into the system, we will use `gdb`.

# Coding Challenges and Reviews

After every important concept there is a coding test, where you fix a given code. Not only this ensures that you have internalized the concepts but also trains you to judge someone else's code (in this case mine). Code reviews at work and when contributing to Open-Source code is an important thing.

![](codingproblems.png "The course is scattered with hands-on coding challenges which reinforce the concepts.")

The code environment on the platform is set to enforce a delay between every run to ensure you get into the habit of thinking before acting. Once you have fixed the code, the platform will run checks on it and rate you based on the outcome.

# Quizzes and Reports

Quizzes are deliberately based on the content from the lectures. They will test you and force you to very carefully follow each word in the Lectures. These are a way to reinforce the vocabulary, concept and language used and delivered in the Lectures.

![](report.png "A sample quiz report")

As above, after every quiz, a detailed report is generated with a personalized feedback on how well you have done and what you should do or focus on next to master this language.

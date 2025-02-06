---
title: "The C Language"
date: "2025-01-08T17:48:22+05:30"
tags:
  - bundle
description: "Learn it from Scratch. Simple Explanation. Deep Insights!"
thumbnail: "/products/c-language/c-course.png"
categories: courses

layout: products

param:
  product: ""
  description: "Learn the C programming language from systems view. This course will provide you with insights that will enable you to confidently predict what the CPU will do given a line of C code. The course is hands-on and focused on developing intuition."
  image: "/products/c-language/course.gif"
  link: "pl_Pr8kvIvnjrP29w"
  note: "Claim the Discounted Prices while the course is being developed!"
  keyFeatures:
    - "**No background** and **no familiarity** assumed."
    - From Scratch, no IDE used!
    - "**19** recorded Lessons."
    - "**~ 6 hrs 16 mins** of Recording."
    - "**2** Downloadable resource"
    - Earn a certificate.
    - Taught by industry expert.
    - New content continuously added.
  bundle:
    - course: "The C Language"
      subtitle: "Learn it from Scratch. Simple Explanation. Deep Insights!"
      description: "A foundational course on C programming with a hands-on journey from Machine code to Design using C. Focused on exposing the system level mechanics that will enable you to reason clearly and be confident about how the system will behave as a result. The course takes a deliberate approach - starting with the models of systems, exploring instruction set architecture, assembly code, toolchain utilities, and finally making a case for the C language."
      bestSeller: "yes"
      rating: 4.8
      ratingCount: 5
      studentsCount: 37
      creators:
        - name: "Piyush Itankar"
          designation: "Embedded Engineer (L5), Google"
          contactLink: "https://www.linkedin.com/in/streetdogg/"
          photo: "https://pbs.twimg.com/profile_images/1884988463247978496/Y6HAdtXt_400x400.jpg"
          bio: "Electrical Engineer by Education, went on to pursue a master's degree in Embedded Systems. Has worked at Intel on Navigation Firmware, Bluetooth Driver and RF validation software. Currently working as an Embedded Software Engineer at Google. Has been involved with Firmware development for the Power Management Sub-system on the Tensor SoCs (Pixel Phones) and Pixel Watch System software."
      lastUpdated: "5 Feb' 2025"
      language: "English"
      lessons: 19
      length: "~ 6 hr 16 mins"
      files: 2
      quizzes: 0
      certificate: "/products/c-language/certificate.png"
      validity: 365 days
      learning:
        - Models of computation
        - Machine code
        - Instruction Set Architecture
        - Toolchain utilities
        - compiler (gcc)
        - assembler (as)
        - GNU Debugger (gdb)
        - Automation using Makefile
        - Basics of Assembly Language
        - How text is converted to 0s and 1s
        - C programming from scratch
        - Data types, variables, declarations.
        - Bit-Wise operators
        - Other operators of C (arithmetic, logical, relation, assignment )
        - The concept and idea of Functions in C
        - Pointers and casting
        - Types of pointers and how to use them
        - Structures and unions
        - Structure and bit fields
        - Structures and pointers
        - Const and volatile type qualifiers
        - Significance of volatile
        - const data, const pointer, cont volatile explanation with examples
        - Importance of const
        - Loops - for, while, do while
        - Mixing Assembly and C and the need for it
        - Booting RISC-V CPU from scratch
        - Introduction to Linker Scripting
        - Placement of variables, code in memory
        - Based on QEMU
        - Cross compiling and what it means
        - Build deep intuition about how computers work under the hood
        - Bottom-up approach
        - Write efficient, system-level code by truly understanding how the machine executes your programs.
        - memory management - Stack vs. Heap
        - Dynamic memory allocation (malloc, calloc, realloc, free)
        - Inline assembly for performance tuning
        - Compiler optimizations (-O1, -O2, -O3, -Os, -Ofast)
        - Standard C library
        - Writing your own small C library like wrapper
        - Working with Linux system calls
        - Developing a simple C shell
      sections:
        - section: "C Language Tour"
          description: "The section focuses on the Roadmap, Mindset and the lense through which this course is to be pursued. We also dive into exploring a basic C program so you can learn to spot the patterns when exploring the code outside of the course. To further empower you, we will also look at the three work horse feature of this language."
          open: "open"
          sectionDuration: 1 hr 4 min
          chapters:
            - chapter: "01: The Roadmap and Mindset"
              preview: ""
              type: "video"
              meta: 06:54
              attachments: ""
            - chapter: "02: Sandbox Environment and Basic C Program"
              preview: ""
              type: "video"
              meta: 30:02
              attachments: ""
            - chapter: "03: Keep an Eye on Functions, Pointers and Structs"
              preview: ""
              type: "video"
              meta: 08:04
              attachments: ""
            - chapter: "04: Example of the RAW power - Functions, Struct and Pointers"
              preview: "1-GXQFRaHZc"
              type: "video"
              meta: 19:50
              attachments: 2
        - section: "Mental Models to Brain tattoo"
          open: ""
          description: "In this section we will discuss the mental models that you can use to reason about the programs. In an attempt to doing this, we will explore the models of systems from 1970s. System composition and the CPU, Memory and Interactions with environment. This sets the foundation that will enable you to exactly predict the system behavior as a result of the C program that you write."
          sectionDuration: "44 min 11 Sec"
          chapters:
            - chapter: "05: Mental Model of the System"
              preview: "ZNgtPodbrxY"
              type: "video"
              meta: 16:43
              attachments: 0
            - chapter: "06: The mental model of the CPU"
              preview: ""
              type: "video"
              meta: 11:41
              attachments: 0
            - chapter: "07: The mental model of the Memory"
              preview: ""
              type: "video"
              meta: 15:47
              attachments: 0
        - section: "From text to 0s and 1s"
          open: ""
          description: "In this section, you will learn how the text gets transformed int 0s and 1s that represent the instructions in the memory."
          sectionDuration: "1 hr 36 min"
          chapters:
            - chapter: "08: Instruction Encoding and the rv32i ISA"
              preview: ""
              type: "video"
              meta: 25:52
              attachments: 0
            - chapter: "09: A tour of Toolchain, QEMU, GDB"
              preview: ""
              type: "video"
              meta: 16:23
              attachments: 0
            - chapter: "10: demo - Assembly to binary, QEMU and GDB"
              preview: ""
              type: "video"
              meta: 27:04
              attachments: 0
            - chapter: "11: Instruction Encoder Decoder, Makefile and GDB Dashboard"
              preview: ""
              type: "video"
              meta: 26:43
              attachments: 0
        - section: "Dwelling in the World of Assembly"
          open: ""
          description: "Understanding what the system does as a result of the C program becomes very simple once we know how the C statements may be translated to the assembly code. We will thus spend time mastering the structure of the Assembly programs and the instructions available to us."
          sectionDuration: "1 hr 13 min"
          chapters:
            - chapter: "12: Anatomy of Assembly Program, writing code, debugging in GDB"
              preview: "KNrqGRKsHRA"
              type: "video"
              meta: 26:59
              attachments: 0
            - chapter: "13: Decomposing C to Assembly and the relation"
              preview: ""
              type: "video"
              meta: 28:15
              attachments: 0
            - chapter: "14: Getting CPU from assembly to jump to C program"
              preview: ""
              type: "video"
              meta: 18:01
              attachments: 0
        - section: "C Keywords"
          open: ""
          description: "In this section you will spend time internalizing each of the 32 keywords from the C Language and understand the assembly and system level implications."
          sectionDuration: "1 hr 20 min"
          chapters:
            - chapter: "15: Introducing the C Keywords"
              preview: ""
              type: "video"
              meta: 12:40
              attachments: 0
            - chapter: "16: Data types, Variables and Integers"
              preview: ""
              type: "video"
              meta: 12:47
              attachments: 0
            - chapter: "17: Data types - float and double"
              preview: ""
              type: "video"
              meta: 05:58
              attachments: 0
            - chapter: "18: Exploring sizes of data types and location in memory "
              preview: ""
              type: "video"
              meta: 37:11
              attachments: 0
            - chapter: "19: how integers are stored - 2s complement"
              preview: ""
              type: "video"
              meta: 19:36
              attachments: 0

            - chapter: "Being recorded..."
              preview: ""
              type: "video"
              meta:
              attachments: 0
        - section: "Work in Progress"
          open: "open"
          description: "This course is being actively developed at the moment. More sections/Lectures and exercises are regularly added. Sections prior to this are complete and available for learner to pursue..."
          sectionDuration: ""
      requirements:
        - A GitHub account. This is to follow the labs.
        - An open and learning mindset.
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
        - Those seeking a job changing and preparing for interviews.
      reviewSectionTitle: "Early praise from YouTube Subscribers"
      reviewSectionDescription: "Because the course is brand new, we released some lectures on YouTube to get early feedback, and it has been a banger! You will not regret taking this course..."
      reviews:
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
        - feature: "Cover basic syntax of the language?"
          us: true
          others: true
        - feature: "A Bottom-Up Approach with the tinge of answering the `Whys`"
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
        - q: "Do I need a special machine configuration to take this course?"
          a: "No! All you will need is an internet connection and the Chrome browser. The hands-on examples and lab work is based on GitHub codespaces platform."
        - q: "Why is a GitHub account needed?"
          a: "The Experiments and Labs are based on the GitHub provided Codespaces virtual machine. Codespaces will enable a common work environment for all the learners and avoid the hassle of special setup."
        - q: "Can I change my email-id post purchase?"
          a: "As much as we'd like to support that, your account will be linked to your email-id post purchase."
        - q: "What name will be printed on the Certificate?"
          a: "The name you use on the platform will be printed as is on the Certificate when it is generated."
        - q: "Can I follow the steps on my own PC?"
          a: "Yes for the most part. Better yet would be if you have a linux machine."
        - q: "How will the open-source contribution work?"
          a: "We will host few github repos under pyjamabrah with the skeleton code and details asks (in comments) about the subsequent tasks. You can add the code (with your details in the comment if you'd want), create PR (pull-request) and submit. We will review and merge your PR into main."
        - q: "Will this course be added to `Firmware Engineer's Arsenal`?"
          a: "No! This is a separate offering and unrelated to my previous work at inpyjama.com. pyjamabrah is exclusively run by me and independent of continuous collaboration with my team."
---

## The Backstory of this Course

Following sections go into the details of why this course was created and why it follows the flow it does. Spoiler alert - **Most engineers learn and use C the wrong way and this course attempts teach C the right way**.

I personally use this language on a daily basis and have been for the past decade. Over time, I have learnt there are more C developers than meets the eye. The general public and students don't necessarily get to see it from where they are. I have worked on complex SoCs (System on Chip), tools and lower level software over the decade and had the opportunity to see the raw power of this language first hand!

![](/products/c-language/course.gif "Screenshots from the lectures")

### Why I created this course?

I have had the wonderful opportunity to host **several interns**, lead **recent college graduates**, mentor **early career professionals** and **interview close to 100 working professionals** from the industry for different lower level positions in my team.

Over time, it dawned on me that although many used C on daily basis not everyone knew how to reason about their code at the System Level. For example, when I ask

```
What does the `volatile` keyword in C do?
```

A common answer is
```
It tells the compiler not to optimize out a variable.
```

While the answer is correct, very rarely people can explain what the implications are! A good answer to the question is -

```
The variable is not cached in the CPU registers!
```

An answer at the CPU level hits very differently and confirms that the engineer has a very deep level of systems level understanding.

This course is very carefully designed to teach and reinforce such system level understanding!

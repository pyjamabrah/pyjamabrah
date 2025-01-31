---
title: "The C Language"
date: "2025-01-08T17:48:22+05:30"
tags:
  - bundle

categories: courses

layout: products

param:
  product: "The C Language"
  description: "A comprehensive course on C language that is focused on insights and use in industrial setting. You will start with mental models and end with the mastery of the C concepts in C."
  image: "/products/c-language/c.png"
  link: "https://pyjamabrah.com/posts/abstractions/c.png"
  bundle:
    - course: "C Language"
      subtitle: "Insights YOU should know but DON'T!!"
      description: "Foundation course on C programming with a hands on journey from Machine code to Design using C. Focused on exposing the system level mechanics that will enable you to reason clearly about the code you right and be confident about how the system will behave as a result. The course takes a deliberate approach - starting with the models of systems, exploring instruction set architecture, assembly code, toolchain utilities, and finally make a case for the C language."
      bestSeller: "true"
      rating: 1
      ratingCount: 1
      studentsCount: 1
      creators:
        - name: "Piyush Tulsidas Itankar"
          designation: "Senior Embedded Engineer (L5), Google"
          contactLink: "https://www.linkedin.com/in/streetdogg/"
          photo: "https://avatars.githubusercontent.com/u/2120983?v=4"
          bio: "Electrical Engineer by Education, went on to pursuing masters in Embedded Systems. Has worked at Intel on Navigation Firmware, Bluetooth Driver and RF validation software. Currently working as a Embedded Software Engineer at Google. Has been involved with Firmware development for the Power Management Sub-system on the Tensor SoCs (Pixel Phones) and Pixel Watch System software."
      lastUpdated: "1/1/2025"
      language: "English"
      lessons: 13
      length: "3 Hours 52 mins"
      files: 2
      quizzes: 0
      certificate: true
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
        - Bit manipulation techniques using bit-wise operators and examples
        - Bit extraction and working with memory mapped peripheral registers
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
      sections:
        - section: "C Language Tour"
          description: "The section focuses on the Roadmap, Mindset and the lense through which this course is to be pursued. We also dive into exploring a basic C program so you can learn to spot the patterns when exploring the code outside of the course. To further empower you, we will also look at the three work horse feature of this language."
          open: "open"
          sectionDuration: 1 Hour 4 Mins
          chapters:
            - chapter: "01: The Roadmap and Mindset"
              preview: "ZwqDd-WM4kk"
              type: "video"
              meta: 06:54
              attachments: ""
            - chapter: "02: Sandbox Environment and Basic C Program"
              preview: "3k4FGxUwXMk"
              type: "video"
              meta: 30:02
              attachments: ""
            - chapter: "03: Keep an Eye on Functions, Pointers and Structs"
              preview: "O-CZ8EvX-8Y"
              type: "video"
              meta: 08:04
              attachments: ""
            - chapter: "04: Example of the RAW power - Functions, Struct and Pointers"
              preview: "1-GXQFRaHZc"
              type: "video"
              meta: 19:50
              attachments: 2
        - section: "Mental Models to Brain tattoo"
          open: "open"
          description: "In this section we will discuss the mental models that you can use to reason about the programs. In an attempt to doing this, we will explore the models of systems from 1970s. System composition and the CPU, Memory and Interactions with environment. This sets the foundation that will enable you to exactly predict the system behavior as a result of the C program that you write."
          sectionDuration: "44 Mins 11 Sec"
          chapters:
            - chapter: "05: Mental Model of the System"
              preview: "ZNgtPodbrxY"
              type: "video"
              meta: 16:43
              attachments: 0
            - chapter: "06: The mental model of the CPU"
              preview: "ggWIlUo41io"
              type: "video"
              meta: 11:41
              attachments: 0
            - chapter: "07: The mental model of the Memory"
              preview: "Q7nHmAXwFEU"
              type: "video"
              meta: 15:47
              attachments: 0
        - section: "From text to 0s and 1s"
          open: "open"
          description: "In this section, you will learn how the text gets transformed int 0s and 1s that represent the instructions in the memory."
          sectionDuration: "1 Hour 36 Mins 2 Sec"
          chapters:
            - chapter: "08: Instruction Encoding and the rv32i ISA"
              preview: "K1uzo-Xy8iA"
              type: "video"
              meta: 25:52
              attachments: 0
            - chapter: "09: A tour of Toolchain, QEMU, GDB"
              preview: "uyjKrY5jNqk"
              type: "video"
              meta: 16:23
              attachments: 0
            - chapter: "10: demo - Assembly to binary, QEMU and GDB"
              preview: "GSgk7FBG3TQ"
              type: "video"
              meta: 27:04
              attachments: 0
            - chapter: "11: Instruction Encoder Decoder, Makefile and GDB Dashboard"
              preview: "PvIvhltDoII"
              type: "video"
              meta: 26:43
              attachments: 0
        - section: "Dwelling in the World of Assembly"
          open: ""
          description: "Understanding what the system does as a result of the C program becomes very simple once we know how the C statements may be translated to the assembly code. We will thus spend time mastering the structure of the Assembly programs and the instructions available to us."
          sectionDuration: "26 Mins 59 Sec"
          chapters:
            - chapter: "12: Anatomy of Assembly Program, writing code, debugging in GDB"
              preview: "KNrqGRKsHRA"
              type: "video"
              meta: 26:59
              attachments: 0
      requirements:
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
      reviews:
        - reviewer: "Pyjama Brah!"
          photo: "https://avatars.githubusercontent.com/u/193006162?s=200&v=4"
          featured: ""
          date: "2/1/2025"
          rating: 4.9
          review: "This course is hosted on our platform so as you can predict this is an awesome course. There are no second thoughts about it."
        - reviewer: "Piyush Itankar"
          photo: "https://avatars.githubusercontent.com/u/2120983?v=4"
          featured: ""
          date: "2/1/2025"
          rating: 4.9
          review: "I am the creator of the course so obviously this has to be the best course on this topic on the planet. I should also specify that my review is heavily biased."
        - reviewer: "Piyush Itankar"
          photo: "https://avatars.githubusercontent.com/u/2120983?v=4"
          featured: ""
          date: "2/1/2025"
          rating: 4.9
          review: "I am the creator of the course so obviously this has to be the best course on this topic on the planet. I should also specify that my review is heavily biased."
      faqs:
        - q: "Do I need a special configuration to pursue this course?"
          a: "No. You will need access to Chrome browser. The course and the labs can all be completed online."
          open: "open"
        - q: "Is this course good for begineers?"
          a: "Yes!"
        - q: "Do I need a special configuration to pursue this course?"
          a: "No. You will need access to Chrome browser. The course and the labs can all be completed online."
          open: ""
        - q: "Is this course good for begineers?"
          a: "Yes!"
      compare:
        - feature: "this is a sample feature. This feature is rather long. too long actually"
          us: true
          others: true
        - feature: "This another feature"
          us: true
          others: false
        - feature: "this is a sample feature. This feature is rather long. too long actually"
          us: true
          others: true
        - feature: "This another feature"
          us: true
          others: false
---

## Course Philosophy

The design of this course is very deliberate. We start with visit to 1970s and `no special knowledge of the subject is assumed`.

![](0.png "Preview of the Roadmap discussion.")

---
title: "tbd"
layout: unit
date: 2026-11-20
publication_date: 
toc: on
research-phase:
  - heuristics 
activities: 
  - searching 
mediatypes:
  - database
  - archive-document
authors:
  - Sarah Oberbichler
editors: 
  - sofia-papastamkou
reviewers:
- tbd
lang: en
unit_id: ai-literacy
link: /u/ai-literacy/
permalink: /u/ai-literacy/
audience: 
components:
  small: 
  medium:
cover:
  url: 
order: 
og:
  description: 
---

## Introduction
Access to the past is increasingly mediated by algorithms. Search engines and generative AI 
systems do not simply retrieve historical knowledge; they rank, filter, synthesise, and 
increasingly produce it, shaping which sources become visible, which narratives prevail, and 
which remain at the margins. This lesson examines these systems as active agents in the 
construction of historical narratives and public memory. Through hands-on exercises and case 
studies, you will explore how algorithms curate sources, how large language models generate 
historical text, and how training data and synthetic media reshape our relationship to the 
past. Along the way, you will develop the critical AI literacy needed to use and question 
these tools, and to situate your own practice within broader debates on digital history, 
algorithmic justice, and the future of historical knowledge production.

Learning Objectives: 

- Explain what AI literacy is, identify its core components (including data literacy), and explain how algorithms work.
- Critically analyze how search engines determine which sources are visible, accessible, and prioritized.
- Identify and interrogate the biases embedded in AI systems that affect the representation of historical events, peoples, and perspectives.
- Evaluate whose voices and narratives are amplified or silenced by algorithmic curation of historical content.
- Assess how training data limitations and biases in AI models perpetuate or challenge dominant historical narratives.
- Apply an intersectional lens to the analysis of digital technologies and explain why such technologies are not neutral.
- Understand and apply principles of responsible and ethical AI usage in historical research and teaching.
- Communicate findings from hands-on audits and case studies in written and oral form, to both academic and public audiences.


## 1 How Algorithms Work: Types, Risks, and Whose Perspective Counts 

*Computational and Ethical Literacy*

*Learning objectives:*
* Explain what an algorithm is, how different types of algorithms embed values, and why technology is never neutral.

Every time we search an archive portal, scroll through a news feed or ask an AI chatbot about the past, algorithms make decisions for us: which sources appear first, which remain hidden, how a text is translated, or what an image of a "CEO" or a "nurse" looks like. In its simplest form, an algorithm is a precise prescription of the steps and decisions needed to solve a problem. In computer science, the definition is stricter: according to Donald Knuth (1973), an algorithm must be finite, definite, have a clearly specified input and output, and be effective.

Yet algorithms are more than lines of code. Rob Kitchin (2017) argues that to think critically about algorithms, we need to understand them as part of wider socio-technical systems. They are often black-boxed, embedded in institutions and commercial interests, and they change and act differently depending on context. Scholars disagree on how algorithms and society relate. Some see them as neutral tools, others as forces that control our lives, as products of specific interests, or as co-produced with society. Some argue that the social and the technical can no longer be separated at all.

This matters for historians. When algorithms reproduce perceived cultural norms, they also reproduce biases. In this section, you will learn what an algorithm is, examine how algorithms and society shape each other, test AI tools for bias, and trace where that bias comes from.

### 1.a What is an algorithm?

In its simplest form, an algorithm is **a precise prescription of the steps and decisions needed to solve a problem**. A very simple algorithm is an instruction for how to make a sandwich: take two slices of bread, spread butter and jam on one slice, put the second slice on top and cut it in two halves. Watch the video below to see what happens when such instructions are followed exactly as written.

<iframe width="560" height="315" src="https://www.youtube.com/embed/eIOfbN7Hzpo" title="Exact Instructions Challenge" frameborder="0" allowfullscreen></iframe>

*Video: Exact Instructions Challenge, https://www.youtube.com/watch?v=eIOfbN7Hzpo*

As the video shows, every step has to be spelled out. What seems obvious to a human must be made explicit, and every instruction reflects a decision made by whoever wrote it.

In computer science, the definition is stricter. Donald Knuth (1973) defined five requirements that every algorithm must meet:

| Requirement | Meaning |
|---|---|
| **Finiteness** | It must end after a finite number of steps and cannot run forever or get stuck in an infinite loop. |
| **Definiteness** | Every step is precisely defined, with no room for interpretation or guesswork. This makes the algorithm consistent and predictable. |
| **Input** | It starts from clearly specified data, whose format and type are defined. |
| **Output** | There is a clear connection between what goes in and what comes out. |
| **Effectiveness** | Every step can be carried out in a finite amount of time, without excessive computational resources. |

In everyday language, however, the word "algorithm" is used much more broadly. The Cambridge Dictionary lists two meanings: a set of mathematical instructions or rules that help calculate an answer to a problem, and a set of instructions that a social media or news website uses to decide which content is shown to a particular user.

Algorithms in this second sense do more than calculate. They shape what we see, and through that, how the world looks. A well-known example is the interiors of fast-food restaurants, which have become more and more alike over the past decades. Algorithms define aesthetics by reproducing perceived cultural norms: what gets photographed, liked and recommended gets copied.

![McDonald's interiors in 1987, 1997, 2007 and 2026](IMAGE-PATH/mcdonalds-over-the-years.jpg)

*"Style is an algorithm": McDonald's interiors over the years. Source: https://www.reddit.com/r/generationology/comments/1vh642d/mcdonalds_over_the_years/*

**Task**

When we use a search engine or an AI chatbot, we only see what goes in (our question) and what comes out (the answer). The steps in between stay hidden: which data were used, which rules applied, and who decided them. Kitchin (2017) calls this the **black box**.

Pick a search engine and an AI chatbot, and ask both the same question about a historical topic of your choice. Then ask the same question again, in a new window or a new chat.

1. Did you get the same output both times? What changed?
2. Try to explain why each tool gave you this output. What can you actually see, and what can you only guess?
3. What would you need to know to understand how the output came about? Can you find this information, for example in the tool's documentation or help pages?

20 mins

### 1.b Algorithms and society

Read Kitchin (2017) and look at the five positions on how algorithms and society relate:

| Position | View |
|---|---|
| **Technological neutralism** | Algorithms exist outside society, with no relation to it. |
| **Determinism** | "Algorithms control our lives." |
| **Social determinism** | Algorithms are the product of people or companies with specific interests. |
| **Co-production** | Algorithms are shaped by social choices, and reshape society in turn. |
| **Socio-technical hybrids** | A clear distinction between the social and the algorithmic is no longer possible. |

Think back to the fast-food interiors in 1.a.

1. Which of the five positions best explains this development? Justify your choice.
2. Find one example from your own use of search engines, archive portals or social media for each of two different positions.
3. Kitchin describes algorithms as black-boxed and embedded in wider systems. What does this mean for a historian who wants to study them?

30 mins

### 1.c Algorithmic bias

**Part 1: Generating images.** Open two or three different AI chatbots (e.g. Gemini, ChatGPT, Copilot) and enter the following prompts:

- *Please create an image of a CEO of a big company.*
- *Please create an image of a nurse.*
- *Please create an image of a teacher.*

**Part 2: Translating.** Open DeepL and translate the following (grammatically incorrect) sentences into German or French:

- *The is a CEO.*
- *The is a nurse.*
- *The is a teacher.*
- *The is a doctor.*

Now reflect on the following:

1. What patterns do you see in gender, age, ethnicity and clothing? Do the tools differ from each other?
2. Which gender did DeepL assign to each profession? Why might that be?
3. Which cultural norms do these outputs reproduce?

**Part 3: Two cases.** Look at the following two cases.

![Gemini-generated images of German soldiers in 1943](IMAGE-PATH/gemini-1943-soldiers.jpg)

*In February 2024, Google paused Gemini's image generation of people after criticism of images like these. Source: The Guardian, 22 February 2024.*

![Tweets by Microsoft's chatbot Tay](IMAGE-PATH/microsoft-tay.jpg)

*In March 2016, Microsoft shut down its chatbot Tay within a day after users taught it to post Nazi content. Video: https://www.youtube.com/watch?v=Lr4yi9onykg

4. The Gemini images were the result of an attempt to make AI outputs more diverse. What does this case show about attempts to fix bias?
5. Tay learned from its conversations with users. What does this case show about where bias can come from?

30 mins

### 1.d Where was the bias created?

The biases you found in 1.c were not programmed in as explicit rules. They come from how AI systems are built. Large language models and image generators are trained in several stages:

**Huge corpus → Foundation model → Fine-tuned model → Aligned model**

First, a foundation model learns from a huge corpus of texts or images. That corpus reflects who has been written about, photographed and translated most often. The model is then fine-tuned on selected examples, and finally aligned through human feedback (RLHF). Bias can enter at each of these stages, and also through the people who use the system.

1. Look again at your results from 1.c, including the two cases. At which stage could each bias have been created? Give reasons.
2. Why are these questions particularly relevant for historians?

<details>
<summary>Need help? (click to expand)</summary>

The <strong>CEO, nurse and teacher images</strong> and the <strong>DeepL translations</strong> most likely come from the first stage, the <strong>training data</strong>. The huge corpus a model learns from overrepresents some people in some roles: more texts and images show men as CEOs and doctors, and women as nurses. The model learns these patterns as "normal" and reproduces them. Fine-tuning and human feedback can reinforce such patterns or soften them, depending on which examples and preferences were chosen.

The <strong>Gemini case</strong> shows bias created in the <strong>later stages</strong>, through fine-tuning, alignment and the instructions added to make outputs more diverse. These corrections were meant to counter the bias in the training data. Attempts to correct bias are themselves decisions built into the system, for example an instruction to show more diversity. Applied without historical context, such a correction can produce new distortions: in this case, ethnically diverse German soldiers of 1943.

The <strong>Tay case</strong> shows bias created <strong>after training, through users</strong>. Tay learned from its conversations with users on Twitter. Within hours, users deliberately fed it racist and antisemitic content, which it then repeated. Its bias was not in the original training data but came in through interaction after it was released, made possible by a design that let it learn from users without safeguards.
</details>

20 mins


### 1.a TITLE



### 1.b TITLE


### 1.c TITLE


### Reading/viewing suggestions  



## 2 TITLE

*Learning objectives:*
* [MAIN-LEARNING-OBJECTIVE-HERE]

2-3 paragraphs on the topic of section 2

### 2.a TITLE



### 2.b TITLE


### 2.c TITLE


### Reading/viewing suggestions  


## 3 TITLE

*Learning objectives:*
* [MAIN-LEARNING-OBJECTIVE-HERE]

2-3 paragraphs on the topic of section 3

### 3.a TITLE



### 3.b TITLE


### 3.c TITLE


### Reading/viewing suggestions  
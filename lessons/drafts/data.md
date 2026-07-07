---
authors: 
 - moritz-feichtinger
editors: 
 - sofia-papastamkou
 - aida-horaniet-ibanez 
date: 2025-05-08
title: Data criticism. Defining data
learning-objectives: 
 - Understand how digital data represent historical information through encoding systems and formats
 - Critically analyse how data models, schemas, and categories shape the representation of historical sources
 - Understand how relational databases structure and connect historical information 
---

This lesson is based on the assumption that data are not neutral givens, but structured representations shaped by cultural conventions, technical choices, and research purposes. It begins by exploring what “data” means and identifying its main characteristics before focusing on the specific nature of digital data.

Video animation of the lesson: https://vimeo.com/1198347738/9a759399ac

## 1 What is data?
*Learning outcomes* 

* *Understand that data are structured representations with specific characteristics* 
* *Recognise the role of formats, conventions and standards in data representation*
* *Reflect on the historical and cultural dimensions of data formats.*

The word “data” comes from Latin and means that which is given as in the French term *données*. In fact, what we call "data" – literally, "that which is given" – might be more accurately described as capta: "that which is taken," as Johanna Drucker (2011) argues. Data are not simply found in the world; they are actively constructed through assumptions and choices that are cultural, historical, political, and social (Drucker 2011, Loukissas 2019). Let's explore what "data" means and what its main characteristics are.

### 1.a Objects becoming data
Watch the video animation following Lea as she discovers and documents the objects left by her grandmother: books, postcards, tapes, floppy disks, videotapes, and photographs. 

1. Are all these objects “data”? 
2. What kinds of information do these objects contain? 
3. Which of the objects are directly readable by humans, and which ones require technical mediation — that is, a device or piece of software that translates the object's content into something a human can directly perceive (for example, a tape recorder for an audio cassette, or a floppy disk drive connected to a computer)?

When Lea makes photos of each object using her phone, several transformations take place. Consider: Does the photo capture everything about the object, or only some aspects of it? Could a future reader interpret the photo without ever having seen the original object? Could you tell from the photo alone whether the floppy disk still holds readable data? Do you think Lea constructs data at this stage? In what ways?


### 1.b Understanding the building blocks of data
Let's work with dates. Dates are one of the simplest and most familiar forms of data. We use them to identify specific moments in time by combining a limited set of symbols. 

Dates are important data for historians because they allow to contextualise a source - by the way, dating the objects is one of the tasks Lea gives to herself in the video to document her grandmother's holdings.  

A date such as `28-06-1914` already illustrates two essential characteristics of data: the symbols that represent data have to be finite and distinct.

“Finite” means that data are built from a limited number of possible symbols. In the decimal system, for example, we use only ten digits (0–9). Likewise, the alphabet consists of a finite number of letters. Although the number of symbols is limited, they can be combined and rearranged in countless ways. This is what makes data versatile and powerful.

“Distinct” means that each symbol must remain clearly distinguishable from the others. A 6 must always be recognizable as a 6, and not confused with a 5 or an 8. If symbols were not distinct, data could not be interpreted consistently by humans or machines.

Inspect these two dates: 

* `28-06-1914`
* `8.6.1914`


1. Which are the differences?
2. Could these formats create confusion? In what situations?

What have we learned so far? Data only makes sense if the symbols representing it are _distinct_ and _finite_.

### 1.c Understanding data as cultural constructions

Dates also remind us that data depend on cultural and technical norms of representation which can be loose [conventions](https://en.wikipedia.org/wiki/Convention_(norm)), e.g. socially agreed, or [normative](https://en.wikipedia.org/wiki/ISO_8601). The same day can be written differently depending on cultural or historical context. 

These expressions below all refer to the twenty-eighth day of June in the year 1914:

* 28-06-1914
* 06-28-1914
* XXVIII.VI.MCMXIV
* 4th of Sha'ban 1332

Inspect the above dates and answer the following questions - if necessary, you can do a little research on the web: 

1. Which date format is easiest for you to read? Why?
2. Which date format requires previous knowledge? What kind of knowledge?
3. What conventions can you decrypt to interpret each version?
4. What does this tell us about data? Tip: think in terms of given vs cultural embedded. 


<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
If we look at a date like June 28, 1914 (`28-06-1914`), we can see another important general feature of data: they are subject to established and shared conventions or standards. We need to agree on which digits represent the day and which represent the month. In US English, the form `MM-DD-YYYY` (month-day-year) is often used, whereas in Europe, the order `DD-MM-YYYY` (day-month-year) is more common. We also need to agree on which symbol system to use. After all, the date June 28, 1914 could also be written using Roman numerals:  `XXVIII.VI.MCMXIV`. Similarly, the date could be designated as the `4th of Sha'ban in the year 1332` according to the Islamic calendar, or as the `twentieth day of the tenth month in the Year of the Snake (4723)` according to the Chinese calendar. 
</details>

### Reading/viewing suggestions

Drucker, Johanna. Humanities Approaches to Graphical Display. *Digital Humanities Quarterly* 5 (1), 2011. https://doi.org/10.63744/r4ysrh7ae534.

Loukissas, Y. A. (2019). _All data are local: Thinking critically in a data-driven society_. The MIT Press

Rosenberg, D. (2013). Data before the Fact. In L. Gitelman (Ed.), “Raw Data” Is an Oxymoron (pp. 15–40). The MIT Press. https://doi.org/10.7551/mitpress/9302.003.0003 to be found [here](https://eswg.hsites.harvard.edu/sites/g/files/omnuum9476/files/eswg/files/rosenburg_-_rawdata.pdf)

## 2 Encoding and digital representation

*Learning outcomes*: Understand how encoding translates texts, images, and sounds into machine-readable digital data; recognise that digital representations depend on technical standards, formats, and encoding schemes; critically reflect on how encoding shapes the preservation, interpretation, and accessibility of historical sources.

How is reality translated into data? Encoding, the process of converting information from one format into another, lies at the heart of data recording. One of the simplest forms of encoding is a physical mark on a surface, such as a notch in wood or a punched hole in paper, used to represent a simple distinction like “yes” or “no”. Similar principles still appear today in tickets, gift cards, and punched cards.

<details>
<summary><strong>Punched train tickets as a form of encoding (click to expand)</strong></summary> 
Punched train tickets are a manual system for recording travel information using small holes made in a paper ticket. A hole isn’t random, as it registers something specific, for example validation of a ticket to prevent reuse by its holder.
</details>

The term “digital” originally meant numerical: data expressed through digits (Haigh 2023). Yet, digital does not necessarily mean electronic. Early telegraphy, for example, encoded letters and words through just two types of signal: short and long impulses in [Morse code](https://morsecode.world/international/translator.html).

Early computers followed similar principles. [Punch cards](https://www.si.edu/spotlight/punch-cards/punch-cards-data-processing) stored information through the presence or absence of holes in specific positions. IBM punch cards, widely used from the 1930s onward, encoded text, numbers, and commands using standardized hole patterns. These systems already relied on a central principle of digital data: complex information can be represented through combinations of a limited set of distinct symbols.

### 2.a Making sense of encoding with punch cards - 15 minutes 
Encoding serves to [transform human-readable to machine-readable information](https://en.wikipedia.org/wiki/Character_encoding). Computers can only digest numbers, and more precisely [binary numbers](https://en.wikipedia.org/wiki/Binary_number). In the binary system, [natural numbers](https://en.wikipedia.org/wiki/Natural_number) ([integers](https://en.wikipedia.org/wiki/Integer)) are represented only in `1`s and `0`s. You should have learned to convert decimal numbers into binary in school, but in case you've forgotten all of that, there are luckily many converters and explanations on the web, for example [this converter](https://www.rapidtables.com/convert/number/decimal-to-binary.html).

Let's see together how a computer would interpret the holes of punch cards. 

STEP 1
Please inspect carefully the image below: it represents an [IBM](https://fr.wikipedia.org/wiki/IBM) punch card. The respective holes represent characters (letters, numbers, special characters). Can you distinguish a zone in the card that is readable by humans? 
Tip: look on the top of the card! 

Now, think briefly: if you wanted to write your name and make it machine-readable, what knowledge would it take to be able to punch it using this card? (We will come back to this question but for the moment please follow the next step below). 

![IBM-EBCDIC punchcard](/assets/images/data-criticism/punchcard.jpg)

Caption:  An IBM 5081-style punched card showing the encoding of the 1964 EBCDIC Latin character set, including numerals 0-9, upper-case letters A-Z, and special characters. The contrast of the human-readable strip at the top of the card has been artificially enhanced.
Source: Wikimedia Commons contributors, "File:Blue-punch-card-front-horiz top-char-contrast-stretched.png," Wikimedia Commons, https://commons.wikimedia.org/w/index.php?title=File:Blue-punch-card-front-horiz_top-char-contrast-stretched.png&oldid=865403764

STEP 2
Now try this [beautiful emulator](https://masswerk.at/keypunch/) built by Austrian artist and web-designer Norbert Landsteiner. You can use the SYMBOLIC <!--because it uses EBCDIC--> configuration to type your name with help from a virtual [typewriter](https://en.wikipedia.org/wiki/Typewriter) and the emulator will punch the card for you. 

What is going on here? The emulator has integrated the knowledge that you (very probably) lacked in the previous exercise: an encoding scheme, i.e. the rules to follow to translate characters (or other data) as binary numbers or symbols. A scheme specifies which number represents which character, very much as the Morse code did, to get a digital, i.e. a both numerical and binary, representation of characters and text. 

The punch card of the above image, as well as the card you created using the emulator, use a scheme created by IBM in 1964: EBCDIC (for Extended Binary Coded Decimal Interchange Code), an [8-bit scheme](https://en.wikipedia.org/wiki/8-bit_computing) — meaning it represents information in chunks of 8 binary digits — that assigned numbers from 0 to 255 (the largest number you can represent in 8 bits) to some common characters and symbols. We can imagine this as a 16 x 16 grid, where each symbol or character is represented by a specific position on the coordinate grid, respectively its numerical value.

STEP 3
Now, use once more the emulator to enter a longer description of yourself or a person you know well. <!--1 minute-->

This should allow you to see that the punch cards could hold small datasets: technically, this would translate to a size of around 60 [bytes](https://en.wikipedia.org/wiki/Byte) (one byte is 8 bits long, one bit being either a `0` or a `1`). You can play around with punchcards and see for yourself what information you can fit onto one of them.  

STEP 4
Try to register text in a non-Latin alphabet (Cyrillic, Arabic, Greek, Chinese...). What do you observe? 

Finally, please write a small essay (up to 500 words) reflecting on: 
* What kind of historical information can/cannot fit in punch cards?
* What constraints does the medium impose? 

### 2.b Exploring text encoding

In 2.a you explored how punch cards translated characters into machine-readable information through an encoding scheme. As digital technologies evolved, new encoding systems were developed to represent increasingly complex forms of information such as texts, images, colours, and sounds.

Because long sequences of binary numbers are difficult for humans to read, programmers introduced more compact notations. One of these is the [hexadecimal system](https://en.wikipedia.org/wiki/Hexadecimal), which uses sixteen symbols (`0–9` and `A–F`) instead of only ten digits. Historians do not need to master hexadecimal calculations, but hexadecimal notation still appears regularly in digital environments, for example in colour codes, metadata, file signatures, and web design.

<details>
<summary><strong>HEX (click to expand)</strong></summary> 
Early in the history of information technology, programmers came up with the hexadecimal representation of binary numbers, because it's much more easy for humans to read. As a 16-base system, you basically count normally from 0 to 9, but continue with the letters A to F to represent the numbers from 10 to 15. For example, `A` = 10, `B` = 11, `C` = 12, and so on. The trick with hexadecimal numbers is that you need just two symbols to represent one byte (i.e. any number between 0 and 255).
</details>

Different encoding systems were also developed for text. [ASCII](https://fr.wikipedia.org/wiki/American_Standard_Code_for_Information_Interchange), one of the earliest standards, assigned numerical values to letters, numbers, and punctuation marks. However, ASCII mainly supported English and western alphabets. As computing became increasingly global, broader standards such as [UTF-8](https://en.wikipedia.org/wiki/UTF-8) emerged to represent non-Latin scripts, mathematical symbols, and emojis 😃.

<details>
<summary><strong>ASCII (click to expand)</strong></summary> 
ASCII uses only 7 bits and can therefore represent 128 different characters, 95 of which are used for the most common letters and special characters. Here, too, numbers are assigned to the letters, just as in the EBCDIC. Each letter or character is assigned a number between 0 and 127. For example, the letter **A** (capital) is assigned the number `65`. As you already know, we don't use the decimal system (0 to 9) to express numbers in bit encoding, but instead use the binary system, using just the two digits `0` and `1`. So the numerical value `65` of our letter **A** is expressed as the binary value `01000001` (or `41` in hexadecimal, if you prefer). Therefore, a longer text in ASCII encoding is ultimately a long chain of ones and zeros. The sentence "What are data?" is represented as a sequence of 1s and 0s in ASCII: `01010111 01101000 01100001 01110100 00100000 01100001 01110010 01100101 00100000 01100100 01100001 01110100 01100001 00111111`.
</details>


Use an online ASCII or Unicode converter. You can use [RapidTables](https://www.rapidtables.com/convert/number/ascii-to-binary.html), if you wish.  

1. Convert your first name into ASCII or Unicode.
2. Convert a short sentence — including at least one space and one punctuation mark — into ASCII. Which codes represent the space and the punctuation mark?
3. Enter accented characters or non-Latin scripts. Explore their representations in different encoding schemes, for example ASCII, ASCII/UTF-8, Unicode. 

Even if you do not fully understand what you see, such codes can be a source of technical problems — for example when collecting or publishing sources in web environments — but the same technical knowledge can also provide solutions to these problems. The variety of encoding systems is result of technical choices and cultural assumptions and can have an impact on collecting, analysing and preserving historical data (see 2.d). In other words, encoding has a role in what is visible and what is not. It is important to know this, even if you are not the one who would the technical work to fix such issues.   

### 2.c Images as encoded data

Encoding does not only apply to text: digital images are also encoded numerically. Imagine an image as a grid made of many tiny units called [pixels](https://en.wikipedia.org/wiki/Pixel). Each pixel receives a numerical value corresponding to its colour or brightness. In colour images, systems such as [RGB](https://www.rapidtables.com/web/color/RGB_Color.html) combine separate values for red, green, and blue to create millions of possible colour combinations; the same logic produces 8-bit grayscale, where each pixel simply holds one of 256 shades between black and white. The same grid-like principle extends to digital sound: a piece of music can be mapped onto a grid where one axis marks time and the other marks pitch, with each marked cell indicating which note sounds at which moment — [give it a try here!](https://8bitcomposer.com/)

The image below represents a simple circle on a 16 × 16 grid:

![Circle in 16 x 16 grid](/assets/images/data-criticism/16x16-circle-table.jpg)

Caption: simple representation of a circle in a 16x16 grid, author: M. Feichtinger

Each position in the grid can be identified numerically and assigned a RGB scheme colour value. Together, these encoded positions create the visual impression of a circle.

STEP 1 — Observing the grid

Inspect the image carefully and answer the following questions:

1. Can you recognize a circle in the image even though it is composed of individual squares?
2. What happens to the shape at the edges of the circle?
3. Why does the image appear simplified or “blocky”?

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
We have seen that in a simple 16 x 16 coordinate system, all 256 positions can be represented by a number. This number can be expressed as a binary value of 8 bits (one byte) in length. Using this idea, we can also map simple shapes. Imagine that we just specify each position that carries some colour. Now we can represent simple geometric shapes, like a circle. Again, we would specify the positions (or their numerical values, respectively) of the fields that are coloured, represented by red dots in the grid.
</details>


STEP 2 - Imagine increasing the grid from:

* 16 × 16 pixels
  to
* 100 × 100 pixels
  or even
* 1000 × 1000 pixels.

1. How would the image change?
2. What kinds of details could become visible?
3. What would be the advantages and disadvantages of higher resolution?


STEP 3 — Reflecting as a historian

Digital images are never exact copies of reality. They are encoded representations produced through technical choices such as resolution, colour depth, and compression.

Reflect on the following questions:

1. What problems could low-resolution digitisation create for historians working with:

   * manuscripts
   * maps
   * photographs
   * paintings
   * archival documents

2. Could important historical details disappear during digitisation?

3. Why might historians sometimes still need access to the original physical object?


### 2.d Why encoding schemes matter for historians

The choice of encoding scheme is not something we usually think much about when dealing with digital data and objects. However, it is important to keep in mind that it is a choice which determines what can be done with the data. Remember, ASCII excluded non-western characters and symbols (ASCII Imperialism). Storing and transmitting an image in a higher or lower resolution, in grayscale or RGB, can have effects on the accuracy of the representation of real-world objects. Consequently, the encoding scheme and its effects are something we should be critically aware of.

Digital representations, whether text or images (or sound) are therefore never exact copies of reality. They depend on technical standards, resolutions, formats, and encoding choices. These choices shape what can be preserved, displayed, searched, analysed, or shared.

For historians, encoding matters because digital sources are always mediated by technical systems. Some older formats become unreadable over time, some encoding systems exclude certain languages or symbols, and some digitisation processes may reduce or alter visual and sonic details. Understanding encoding therefore helps historians critically evaluate how digital sources are produced, transformed, and preserved.

> Although humans may find binary difficult to read, computers use it to represent and process all kinds of information. As we have seen, combinations of `0`and `1`s can encode texts, images, sounds, and many other forms of data. They can also represent instructions and logical operations such as “AND,” “OR,” and “NOT” — which means that binary digits are not only used to store information, but also to run algorithms and computer programs.


Return to Lea’s digital collection of her grandmother's holdings from the introductory animation. Note the scene 5 where Lea discusses with Ada about the floppy disk.  

1. Which technical problems could affect the preservation of her grandmother’s floppy disks, tapes, or digital photographs?
2. What kinds of information could be lost during digitisation?
3. Why is metadata important when recovering or interpreting digital sources?
4. Can digital reproductions ever fully replace original objects?


### Reading/viewing suggestions 

Haigh, Thomas. *Defining Digitalities I.* 2023. https://doi.org/10.25819/ubsi/10259.

The Punched Card | IBM. https://www.ibm.com/history/punched-card.

http://www.injosoft.se, Injosoft AB. The Beginner’s Guide to ASCII. https://www.ascii-code.com/articles/Beginners-Guide-to-ASCII.

Pargman, Daniel, and Jacob Palme. "ASCII Imperialism." In *Standards and Their Stories: How Quantifying, Classifying, and Formalizing Practices Shape Everyday Life*, edited by Susan Leigh Star and Martha Lampland, 177–199. Ithaca: Cornell University Press, 2009.


## 3 Creating models and datasets
Let us now explore how data are produced to describe and study the world around us. Texts, people, animals, places, or historical events can all be transformed into descriptive data. By creating such data, historians turn sources into structured representations that can be organised, searched, and analysed. This process is both conceptual — involving research choices and categories — and technical, relying on tools such as spreadsheets and databases, which also introduce their own constraints.

### 3.a Designing descriptive categories

Let's take a simple example: a wanted poster as you might know from western movies or comics (see figure below). Please observe carefully the poster and the information it provides. 

![Wanted Poster](/assets/images/data-criticism/Wanted_Poster_marx_new.jpg)

Then think of the poster as a simple table that focusses on a given person and lists a number of characteristics in different columns with the purpose to identify this person.

<!--
Person:
|Attributes|Values|
|:-:|:-:|
|Attribute 1|"..."|
|Attribute 2|"..."|
|Attribute 3|"..."|
|Attribute 4|"..."|
-->

Table Person

|Person ID|Attribute 1|Attribute 2|Attribute 3|Attribute 4|
|:---------|:---------|:--------|:-------|:--------|
|Person0001|Value1|Value2|Value3|Value4|

<!--
|P0002|"..."|"..."|"..."|"..."|
|P0003|"..."|"..."|"..."|"..."|
-->


[Link to editable table: Person](/assets/docs/data-criticism/person-table.docx)

STEP 1

Please fill the table: for the attributes (the characteristics listed in the column headers, such as "First Name:"), refer to the poster. For the values (the actual dates and information entered in the columns, such as "Karl"), use your critical skills and get help from the visual in the poster and from research on the web. 

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
In the above scaffold table, attribute 1 would be the first name of the person, attribute 2 would be the person's last name, attribute 3 would be the gender, attribute 4 the place of birth and so on (please refer to the poster). Such a table would now describe a person, Karl Marx.
</details> 

STEP 2

By selecting specific attributes, we create *descriptive categories*. Obviously, our selection of attributes would be different if we wanted to describe the same person in another context, for example as an author, or if we described something else, like a place, or a piece of art, or an animal, or a book. In other words, the selection of descriptive categories is subject to a finality. In the case of the wanted poster, the finality is identifying and catching a fugitive. For this reason, identifying, say, a person's favorite dessert might not be the most significant property, especially if we can only list a limited number of them on our wanted poster. 

Can you think of significant properties that would matter in this case but are not included in the poster? 

### 3.b Creating descriptive data

When we want to describe and compare several historical personalities, objects, or events, we can organise information in tables made of rows and columns. Each column represents a category or attribute — that is, a feature we want to record, such as a name, date, place, or other characteristic. The top row of the table usually contains headers identifying these categories. Each subsequent row contains the information describing one individual entry, while the recorded information itself is called a value. Organised in tables, these categories and values form data collections that can be searched, sorted, extended and analysed with the help of digital tools such as spreadsheets or databases.



<!--
If you imagine tilting our two-column table to the right, the attributes become column headers and we can add more rows to it, each one describing one person:
-->
We can now expand our table to list several historic persons by adding further records (=rows) to it:

|Person ID|first_name|last_name|year_of_birth|place_of_birth|author_of|gender|number_of_children|is_still_alive|
|:---------:|:--------:|:-------:|:--------:|:-------:|:--------:|:-----:|:---:|:---:|
|P0001|Karl|Value 2|Value 3| Value 4|Value 5|Value 6|Value 7|Value 8| 
|P0002|...|...|...|...|...|...|...|...|
|P0003|...|...|...|...|...|...|...|...|

[Link to editable table: Historical Persons](/assets/docs/data-criticism/historical-persons-table.docx)

The pre-defined list of properties you want to capture is commonly called a *data model*, and a collection of data following such a model is called a *data set*. The individual rows — for example, the historic persons in your table — are called *data records* or *entries*. The individual entries in the table are called *data points*, such as the value `Karl` for the attribute `first_name`.
We will not go further into data models here; if you want to explore how they are used to define relationships between different types of information, see the reading suggestions below.
 
Now fill the table to describe the following historic personalities (or at least two of them): 
* Karl Marx
* Wilhelm Marx
* Eleanor Marx 
* Groucho Marx

Now that you entered data, let's observe the different *types* of values and the issues they may raise. 
* Compare the first and the third rows after the ID: what types of values do you have in each?
<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
While the values for the first two descriptive columns are clearly textual (often called a "string" like a string of characters), the third would rather be a number (often called "an integer"). 
</details> 

* Observe the attribute in the third column: what additional values you should add if the attribute was "date" rather than "year"? How would you express these values based on what you learned in 1.c?

* What type of values you could enter in the fourth column? 
<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
The fourth column could be a string again, but it could also be a geo-coordinate, like a GPS location. In addition, it is unclear if this column refers to countries, cities, regions, villages, or even specific buildings.
</details> 

* What kind of issues could you encounter with the fifth column? 
<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
Our first historic person, Karl, was rather productive and was the author of many more than just one text. This is not a question of finality, but a structural problem: one person can be linked to many works — a *one-to-many relationship*. Squeezing several titles into a single cell (for example, separated by commas) might look like a solution, but it makes the data hard to search, sort, or count reliably. The proper solution is to give authored works their own table and link it back to the person — we will see exactly how to do this in Section 4.
</details> 

* Do you think that the sixth column could create specific questions as to the values you would enter? In what ways you think you could express these values (text, other)?

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
In this column, the values could be pre-defined: would you define two or more types of values? Whatever you decide, would these values be textual or integers? Think in terms of [coding data](https://en.wikipedia.org/wiki/Coding_(social_sciences)).
</details>

* What values can you enter in the eighth column? 

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
The eighth column can only hold "yes" or "no" as an answer (in most computational contexts, this is expressed in "Boolean" values: `true` or `false`).
</details>

What you've encountered here is called [data types](https://en.wikipedia.org/wiki/Data_type). Like the descriptive categories, that you should have selected before you begin collecting data, you also need to think of the appropriate data types for each of them.


### 3.c Creating datasets - 30 minutes

Historians do not record all possible information. The categories they choose depend on the questions they want to ask and the comparisons they want to make: thus, for different purposes, different attributes can be employed in data sets.

Remember, in the video animation Lea finds several objects in her grandmother's house. Let's imagine that she ends up having a collection like the one described in [this lesson](https://github.com/C2DH/ranketwo-submissions/blob/master/lessons/drafts/data-ethics.md#3c-bringing-it-all-together-evaluating-leas-choices). Note down the objects and put yourself into Lea's shoes: her purpose is to create an inventory. 

1. Imagine a table Object to describe each of the objects enumerated in the video (one object per row)
2. Which attributes you would create for each of the objects enumerated? (one attribute per column) 

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 

If your purpose is to create an *inventory* — quickly knowing what exists and where — a few basic attributes are enough:

| object_id | object_type | location_found | condition |
|---|---|---|---|
| 1 | floppy disk | grandmother's desk drawer | unreadable, rusted casing |

If your purpose is instead to *document* the object in detail — for example, to preserve or analyse it later — you need more attributes:

| object_id | object_type | material | dimensions | label_text | condition_notes | digitised |
|---|---|---|---|---|---|---|
| 1 | floppy disk | plastic, magnetic film | 3.5 inch | "Photos 1998" (handwritten) | rusted casing, label partially faded | no |

Notice how the same object requires a different data model depending on your purpose.
</details>

> Deciding what to record about Lea's grandmother's belongings — and what to leave out — is itself an ethical choice. To explore this further, check this lesson on [ethics and responsibilities](https://github.com/C2DH/ranketwo-submissions/blob/master/lessons/drafts/data-ethics.md).

### Reading/viewing suggestions

Lemercier, Claire, and Claire Zalc. 2019. *Quantitative Methods in the Humanities: An Introduction.* . Translated by Arthur Goldhammer. Charlottesville: University of Virginia Press.

Roberts, Spencer W.. Spreadsheets for Historians – Spencer W. Roberts. 12 août 2014. https://swroberts.ca/scholarship/spreadsheets-for-historians/.

Rogers, Jonathan. « LibGuides: Working with Quantitative Data: Home ». Consulté le 2 juin 2026. https://libguides.law.ucla.edu/data/home.


## 4 From sources to data: understanding the relational database

In 3.c, we created a single table to describe one type of object. But historical sources usually involve many different kinds of things at once — people, places, organisations, events — and we need a way to keep them connected without losing the bigger picture.

When historians work with a few sources, a spreadsheet is often sufficient. But when we need to analyse hundreds or thousands of documents, information quickly becomes repetitive and difficult to manage. Relational databases, based on [specific software](https://en.wikipedia.org/wiki/Database#Database_management_system), were designed to organise large amounts of information while preserving the connections between the described objects.   

### Instructions 

Look at the following source: Karl Marx. Whose Atrocities? *New York Daily Tribune*, April 10, 1857. [URL](https://www.marxists.org/archive/marx/works/1857/04/10.htm) <!--or via the Wayback Machine [here](https://web.archive.org/web/20260000000000*/https://www.marxists.org/archive/marx/works/1857/04/10.htm).--> 

![Source: "Whose Atrocities?"](/assets/images/data-criticism/source-full.jpg)

The exercises in 4.a, 4.b, 4.c, 4.d and 4.e use this source. Subpart 4.f illustrates a possible implementation of a database using a collection this source is part of. 

Before going further, let us note that we could treat this source on three different levels: On the one hand, we're dealing with a website. On a different level, it is an excerpt from an edited volume assembling Marx's writings for the New York Daily Tribune that was published in 1951. Finally, we could also treat it as an article that appeared in said newspaper on April 10, 1857. This is how these different types are displayed in [Zotero](https://www.zotero.org/), the popular software for managing bibliographical information. 

![zotero entries](/assets/images/data-criticism/zotero-entries.jpg)

The same source would look like this if captured in [Tropy](https://www.tropy.org/), the software specifically conceived to manage archive photos:
![tropy_screen](/assets/images/data-criticism/tropy-object.jpg)

### 4.a Conceiving a data model

Before information can be entered into a spreadsheet or a database, historians must decide what they want to record. A historical source contains far more information than can reasonably be captured as data. Researchers therefore select a limited number of categories that correspond to their research questions.

This selection of categories is called a data model.

A data model defines:

* Which types of information will be described
* Which attributes will be recorded for each type of information
* How the information is split and how the different parts relate to each other

Different research questions require different data models. A historian studying political networks may record offices and organisations, while a historian studying family history may focus on kinship relations and households.

Consider the source above.

Imagine you work on British political actors involved in the UK's policy in China in the 19th century. 

1. Which types of information you would record? Define relevant descriptive categories.  
2. What would be the essential information to extract for these categories? Define the attributes for each category.
3. Think ways in which the categories you defined relate to each other. Imagine arrows connecting them and try to find a verb for each arrow.
4. Think which information that is present in the article you can ignore.  

Use paper and pencil to draw your ideas. 

Now check the following image — this is what a data model for this source could look like. Make abstraction of technical details and focus on what you can understand.  

![Scheme and connections](/assets/images/data-criticism/database_scheme_simple.jpg)

1. Can you recognise types of information that constitute descriptive categories following the article you read?
2. Can you recognise what kind of information is considered important to retain based on the attributes of each category? 
3. Can you understand how the categories are related? How would you interpret the arrows connecting them?

Building a data model in practice raises further questions, such as how to handle a person known by several different names or titles (as with Palmerston in 4.c), or how to record that one person can be linked to several different works or roles (as with Karl's many publications in Section 3) — these are not flaws in your model, but design decisions every historian working with data has to make.


### 4.b Extracting information from sources

Before building a database, historians must identify the information they want to record. In this exercise, we are going to extract names, places, organisations, and events from our historical sources. We are actually going to perform a simplified form of [Named Entity Recognition (NER)](https://en.wikipedia.org/wiki/Named-entity_recognition).

Look at the source excerpt above.

* List all persons mentioned.
* List all places mentioned.
* List all organisations mentioned.
* List all events mentioned.

Which entities were easiest to identify? Which were more ambiguous?

![first paragraphs](/assets/images/data-criticism/source-zoom.jpg)


### 4.c Understanding the limits of spreadsheets

Imagine that you repeat the previous exercise for 500 newspaper articles. The same people, places, and organisations will appear again and again. If you store everything in a single spreadsheet, the information quickly becomes difficult to organise and maintain.

Suppose Lord Palmerston appears in fifty different newspaper articles.

* How would you record the different political roles he held during the period covered by Marx's articles?
* How would you handle the different titles used to refer to him?
* How would you group references such as "the Premier", "his Lordship", and "Lord Palmerston" so that they are all recognised as referring to the same person without ambiguity?

<details>
<summary><strong>Need help? (click to expand)</strong></summary>
These problems are not unique to spreadsheets — a carelessly designed database can suffer from exactly the same duplication and inconsistency. What a database really adds is not automatic prevention, but enforcement: once you decide that Palmerston is recorded once, as P002, the database will not let that rule be silently broken — a spreadsheet cannot guarantee that. The real advantages of a database over a spreadsheet show up as a project grows: it can handle far more data, answer complex questions across many tables at once, let several people work on it together, stay fast with large datasets, keep connections between tables automatically up to date, and offer proper backups.
</details>

Discuss why a spreadsheet can become difficult to manage when information is repeated, ambiguous, uncertain, or complex.

> A database only prevents duplicates if it is designed to. The technology itself doesn't know that "Lord Palmerston" and "the Premier" are the same person — that decision is made by whoever builds the data model. Once it is made, though, the database enforces it: Palmerston exists only once, as record P002, and every event, office, or source that refers to him simply stores that one identifier instead of repeating his name each time. If someone accidentally created a second row for him, the database would not catch that by itself — avoiding duplicates is a matter of careful design, not a guarantee that comes for free.
>
> **A note on scaling to many sources:** The table design shown above works well for a single article, where every Person, Place, and Organisation simply points back to the one Source they came from. But imagine building a database from a whole corpus — say, 500 newspaper articles about British foreign policy. Lord Palmerston would then be *mentioned in* many different sources, not *created by* one. Giving Person a single `source_id` column would force you to either duplicate Palmerston's row for every article he appears in (defeating the whole purpose of deduplication described above), or arbitrarily pick just one source to "own" him. The correct solution is a junction table — call it `Mention` — that records every time a person is named in a source, while the Person row itself stays unique.

#### Mention Table (junction table Person ↔ Source)

| mention_id | person_id | source_id |
|---|---|---|
| M001 | P002 | S001 |
| M002 | P002 | S045 |
| M003 | P002 | S078 |

Palmerston (`P002`) still exists only once in the Person table, but now appears in three rows of the Mention table — making this a many-to-many relationship between Person and Source.


### 4.d Building a relational database

*learning objective: Understand how relationships between tables are implemented with primary keys and foreign keys*


Relational databases rely on a few key principles. A relational database organises information into separate tables, where every row represents one specific object, place, or person.

**Primary keys.** How do you make sure each row can always be told apart from every other? Titles like "Earl of Clarendon" don't help on their own — this is a hereditary title, so different men held it at different points in history. The name alone doesn't tell you *which* Earl of Clarendon a source is talking about. A primary key solves this: it is a short code, invented once and never reused, that belongs to exactly one row, permanently. These identifiers should follow a consistent, systematic pattern — not just any random label. In our example, persons are coded P001, P002, P003… ; places would follow their own pattern (L001, L002…), events another (E001, E002…). A consistent scheme like this makes it immediately clear which table an identifier belongs to, and keeps the whole database manageable as it grows — imagine trying to track thousands of records with inconsistent, ad-hoc labels!

| person_id | name | source_id |
|---|---|---|
| P001 | Sir James Hogg | S001 |
| P002 | Lord Palmerston | S001 |
| P003 | Earl of Clarendon | S001 |

`P003` always means *this specific* Earl of Clarendon — the one described in our source — no matter how many other Earls of Clarendon existed before or after him.

**Foreign keys.** Once every row has its own permanent ID, tables can be linked without repeating information. A foreign key is simply a primary key from one table, copied into another table to point back to it. Instead of writing "Lord Palmerston, Premier of England" into every event he took part in, we just write `P002` — and the database follows that pointer back to the full Person record whenever it's needed.

| role_id | person_id | org_id | title |
|---|---|---|---|
| RO003 | P003 | O002 | Minister of Foreign Affairs |

Here, `person_id` and `org_id` are foreign keys: they don't describe the Role row itself, they point to where the full details live.

<details>
<summary><strong>Check your understanding (click to expand)</strong></summary>

Can you explain in your own words why `P003` in the Office table is a *foreign* key, not a primary key? What is the primary key of that Office row instead?

</details>


Some relationships can't be stored with a simple foreign key. Take the Lord Mayor's banquet (E002): both Palmerston (P002) and Clarendon (P003) took part in it. If you tried to add a person_id column to the Event table, you could only fit one person per event — there's no room for a second. If you instead tried adding an event_id column to the Person table, you'd run into the same wall from the other side: Palmerston alone appears at several events, not just one.
Junction tables solve this by giving the relationship itself its own table, with one row per pairing rather than per person or per event. A row like P002 – E002 simply states "Palmerston took part in the banquet"; a second row, P003 – E002, states "Clarendon took part in the banquet too" — both can exist side by side, without forcing either the Person or the Event table to hold more than one value per field. This is exactly what the Person–Event table does: every row links exactly one person to exactly one event, and as many rows as needed can share the same person_id or the same event_id.
Together with primary and foreign keys, junction tables let historians ask questions that cut across many sources at once — "who attended which events, and when?" — in ways a single spreadsheet, with its one-row-per-record limit, cannot represent.

![Junction table Person-Event](/assets/images/data-criticism/junction_table.jpg)

So far every relationship in our database has allowed at least one side to have several partners. But historians and archivists also regularly work with **authority records** — external, standardised identifiers for a specific person, held by an outside institution. [Wikidata](https://www.wikidata.org/), a free and open knowledge base, assigns exactly one unique identifier (a "QID", e.g. `Q193656`) to each distinct real-world entity it describes. Linking our Person table to Wikidata gives a genuine **one-to-one relationship**: each Person in our database corresponds to at most one Wikidata entry, and each Wikidata entry we link corresponds to exactly one Person — never several.

**Identifier** (new table)

| person_id | wikidata_qid |
|---|---|
| P002 | Q193656 |



1. Go to [wikidata.org](https://www.wikidata.org/) and use the search bar at the top of the page.
2. Search for "Lord Palmerston" (or one of the other persons from our source, e.g. "Earl of Clarendon").
3. Open the matching entry. The QID appears directly under the title, in the form `(Qxxxxxx)`, and also in the page's URL.
4. Add the QID as a new row to the Identifier table above.

Which persons from our source were easy to find on Wikidata? Were there any where you were unsure whether you had found the right entry?

### 4.e Extending the database

This exercise builds on what we did in 4.d. 

Karl Marx refers to the Arrow Incident.

Consult the [Wikipedia article on the Second Opium War](https://en.wikipedia.org/wiki/Second_Opium_War).

Add the event to the Events table.
Identify any additional persons, organisations, or places that should be included.
Do you need new tables? Why?

### 4.f Example database Sources

If we create tables for all the different types of information or entities, we could have four tables (five, if the source itself also gets one, here table 1): persons (table 2), roles (table 3), places (table 4), organisations (table 5). We would want to have another one for historic events, that contains all of the entries above. Now the magic happens in the junction tables which we need to store the relations (or connectors). Here, persons and organisations are related (as in our table 3) or persons and events (our table 7).


#### Table 1 — Source

| source_id | author | publication | date | url |
|---|---|---|---|---|
| S001 | Karl Marx | New York Daily Tribune | 1857-04-10 | https://www.marxists.org/archive/marx/works/1857/04/10.htm |

#### Table 2 — Person

| person_id | name | source_id |
|---|---|---|
| P001 | Sir James Hogg | S001 |
| P002 | Lord Palmerston | S001 |
| P003 | Earl of Clarendon | S001 |

In a relational database, Palmerston exists **exactly once** as row `P002`. Every event, every office, every source that mentions him simply stores `P002`. You can then ask questions that cut across all your sources at once: _"List every event involving persons who held office in the British Government, sorted by date."_ A spreadsheet cannot answer that. A relational database answers it in a single query, however many sources you have gathered.


_Note that we only see the first three entities here; further persons in the excerpt to be included in this table are: Harry Parkes (the Consul), Sir John Bowring, Admiral Seymour …_

#### Table 3 — Role

This table records genuine historical information: **which role a person held in which organisation, and for how long**. Each row also happens to name both a person and an organisation, which is what lets it double as the connector between the Person and Organisation tables — but unlike the Person-Event table below, it isn't a *real* junction table, since the role and dates are meaningful data in their own right, not just a link.

**A note on structuring dates.** Historical dates are rarely exact, and a plain text field like "ca. 1853" or "before 1857" can't be sorted, filtered, or compared by a computer — it's just a string of characters to the software. A more analysable approach splits the date into two parts: a **value** the software can actually read (a year, or a full date when known), and a **precision** label from a fixed, small vocabulary (`exact`, `circa`, `before`, `after`, `unknown`) that records how certain that value is. You lose nothing — the historical uncertainty is still fully recorded — but the value column now becomes something a database can genuinely work with. Historians working with larger or more uncertain date ranges may want to look at the [Extended Date/Time Format (EDTF)](https://www.loc.gov/standards/datetime/) standard, which offers a more complete vocabulary for exactly this problem.

| role_id | person_id | org_id | title | date_from_value | date_from_precision | date_to_value | date_to_precision |
|---|---|---|---|---|---|---|---|
| RO001 | P001 | O001 | Director | | unknown | | unknown |
| RO002 | P002 | O002 | Premier of England | 1857 | before | 1857 | after |
| RO003 | P003 | O002 | Minister of Foreign Affairs | 1857 | before | 1857 | after |

**A note on the `type` column.** A single field should always hold one clear, unambiguous value — the same principle that makes primary keys work also applies here. Writing "Region / Country" into one `type` cell bundles two separate facts together, which makes the column hard to filter or count reliably (should a query for "all countries" also return this row, or not?). A cleaner approach is to give each possible category its own column, with a simple yes/no (Boolean) value, so that a place can belong to several categories at once without ambiguity.

#### Table 4 — Place

| place_id | name | is_region | is_country | is_city | source_id |
|---|---|---|---|---|---|
| L001 | India | TRUE | TRUE | FALSE | S001 |
| L002 | England | FALSE | TRUE | FALSE | S001 |
| L003 | Canton | FALSE | FALSE | TRUE | S001 |

#### Table 5 — Organisation

| org_id | name | type | source_id |
|---|---|---|---|
| O001 | East India Company | Trading company | S001 |
| O002 | British Government | State authority | S001 |
| O003 | British Parliament | Legislative body | S001 |

#### Table 6 — Event

 The table Event is the connecting hub.

| event_id | name | date_value | date_precision | place_id | org_id | source_id |
|---|---|---|---|---|---|---|
| E001 | Exposure of torture system in India before Parliament | 1853 | circa | L001 | O003 | S001 |
| E002 | Lord Mayor's banquet — Palmerston's speech | 1857 | circa | L002 | O002 | S001 |
| E003 | Arrest of sailors aboard the *Arrow* | 1856-10-08 | exact | L003 | O001 | S001 |

#### Table 7 — Person–Event 

The table Person-Event is the junction table.

|compos_pers_ev_id | person_id | event_id | role_in_event              |
|---|-----------|----------|-------------------------------------------|
| PE001  | P002      | E002     | Speaker (as Premier)                 |
| PE002  | P001      | E001     | Director (respondent)           |
| PE003  | P003      | E002     | Attendee (as Minister of Foreign Affairs) |


Because one person can participate in many events and one event can involve many persons, this relationship is **many-to-many** — it cannot be stored in either the Persons or Events table alone. The junction table holds one row per person–event pairing. Both `person_id` and `event_id` are foreign keys; **together** they form the primary key of this table (a _composite_ primary key), because what is unique here is the _combination_ — the same person can appear in multiple events, and the same event can appear across multiple persons, but a specific person can only be linked to a specific event once.

A *query* is simply a question you ask the database in its own language — usually SQL, though the concept matters more here than the exact syntax. For example, you could ask: "Who was present at the Lord Mayor's banquet?" → the database would select all rows where `event_id = E002` → returning P002 and P003.

Now we have - a very basic - architecture of a database containing several different types of tables that are related to each other (much like hyperlinks in a web document, but more powerful and flexible). A visual represntation would look something like this:

> **Reading the diagram: cardinality and optionality.** Every relationship line carries two pieces of information at each end: *cardinality* (how many — a single bar means "one", a crow's foot means "many") and *optionality* (whether it's required — a bar means "must exist", an open circle means "zero is allowed"). Take Source–Person: the bar next to Source means every Person must belong to exactly one source (mandatory); the crow's foot next to Person means one source may be linked to many people — or, in principle, to none at all if a source names no individuals (optional). [Wikipedia](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model#Crow's_foot_notation) uses the same three symbols: ring = zero, dash = one, crow's foot = many.

![Scheme and connections](/assets/images/data-criticism/database_scheme_detail.jpg)


| Symbol | Meaning |
|---|---|
| `\|\|` | exactly one (mandatory: minimum 1, maximum 1) |
| `o\|` | zero or one (optional: minimum 0, maximum 1) |
| `\|<` | one or many (mandatory: minimum 1, maximum many) |
| `o<` | zero or many (optional: minimum 0, maximum many) |

*Reading rule: the symbol placed next to an entity's name describes **that entity's** multiplicity per one instance of the entity on the other end of the line. Example: `Source || ⋯ o< Person` reads as "one Source may be linked to zero-or-many Persons; every Person belongs to exactly one Source."*

#### Comprehensive relations-type overview

| Relation-type | Notation | Example |
|---|---|---|
| One-to-one, optional (0,1 – 1,1) | `Person o\| -- \|\| WikidataEntry` | Not every Person in our dataset has (yet) been linked to a Wikidata entry, but once linked, one Wikidata entry corresponds to exactly one Person. |
| One-to-many, optional many (1,1 – 0,N) | `Source \|\| -- o< Person` | One newspaper article may name zero, one, or several persons; every Person record belongs to exactly one Source. |
| One-to-many, mandatory many (1,1 – 1,N) | `Organisation \|\| -- \|< Office` | An Organisation only enters our database because at least one Office (a role held within it) was recorded; the same Organisation may have many recorded office holders. |
| Many-to-one (mirror view of the row above) | `Office o< -- \|\| Person` | Many Office records can point back to the same Person — Palmerston alone accounts for two (Foreign Secretary, then Prime Minister) — but every single Office record belongs to exactly one Person. |
| Many-to-many, optional both sides (0,N – 0,N) | `Person o< -- o< Event` | One person can take part in many events, and one event can involve many persons — captured by the Person-Event junction table. |


**One-to-many and many-to-one describe the same relationship from two directions.** Looking from Source to Person, one article can mention many people (*one-to-many*); looking from Person to Source, every person-record belongs to exactly one article (*many-to-one*). It is the same arrow, just read from opposite ends — which is why you will sometimes see the identical relationship labelled "1:N" in one textbook and "N:1" in another.

Of course, there are rules to follow when creating a database. Primary keys cannot be empty (null), for a start. Also, as we've already seen for other data sets, the entries (for each column) have to be of the same type. If you use a software to create a database (like the free [Libre Office Base](https://www.libreoffice.org/DISCOVER/BASE/)), you will have to specify the types. Also, the software <!-- which software? none was mentioned but anyway, I think that this level of details is perhaps too much without having before given specific explanation which however are not the aim of the lesson--> will ask you whether a column can hold foreign keys or not (you usually recognize them, because they are IDs, i.e. by their suffix `_id`).

But this lesson's aim is to raise awareness on what is behind a database; please consult the references in the reading suggestions to learn more (Julien 2024); and (Cosovschi 2024).   

![Types](/assets/images/data-criticism/odb.jpg) 

### What have we learned?
Databases are the main carrier for digital data. They can store a great variety of different types of data. But their true value comes from their ability to run queries over all of their content. This way, we can get very specific information, evaluate the magnitude or duration of phenomena and detect patterns in the data.

To make all of this possible, relational databases rely on a few key principles. Every record needs a **primary key** — a unique identifier that distinguishes it from all others, even if names or descriptions are identical across sources. **Foreign keys** allow tables to reference each other, so that a person, a place, or an organisation only needs to be described once and can then be linked to as many events or sources as needed. Where relationships are complex, for example if one person was involved in many events, and/ or we have to deal with one event involving many persons, **junction tables** store the connections without duplicating data. Together, these mechanisms allow historians to ask questions that cut across many sources at once, and to detect patterns that no single spreadsheet could reveal.


### Reading/viewing suggestions

Nodegoat. What Is a Relational Database?. Accessed 4 June 2026. https://nodegoat.net/blog.s/20/what-is-a-relational-database.

Cosovschi, Agustín. « From Sources to Data: Designing a Database for the Humanities and Social Sciences with Nodegoat ». Programming Historian, 29 février 2024. https://programminghistorian.org/en/lessons/designing-database-nodegoat.

Julien, Octave. Creating and using databases in medieval history: historiography, concepts and practice. Seminários do GIHM, April 2024, Porto, Portugal. ￿[halshs-04550456￿](https://shs.hal.science/halshs-04550456v1)

Robertson, Stephen. « THE PROPERTIES OF DIGITAL HISTORY ». *History and Theory* 61 (4) (2022): 86‑106. https://doi.org/10.1111/hith.12286.

Viale, Mattia. « From the Historical Source to a Database: A Short Story ». *Refashioning the Renaissance*, 21 November 2018. https://refashioningrenaissance.eu/from-the-historical-source-to-a-database/.



## 5 Converting data: the example of JSON format

Historians increasingly work with digital tools that require data in specific formats. A format represents the way data are encoded, stored, and displayed; it can be important for how data can be used, exchanged and shared. The format is reflected in the extension of the data file (for example, `.csv`).

When working with digital tools, structured formats make it easier to exchange data between information systems. Structured formats use standardized rules on the architecture and form of the data they contain, commonly called the data schema.

For example, in assignment 3, we worked with data in the form of a table. Tabular data are best stored, displayed, used and shared in [CSV (Comma-separated Values) format](https://en.wikipedia.org/wiki/Comma-separated_values). Tables are extremely useful, however, data often needs to be converted from one format to another.

Why is this useful?

- Different tools require different formats (for example, web applications)
- Some formats are more fit for storing and exchanging large volumes of data
- Some formats allow more complex structures than tables

One widely used format for this purpose is [JSON (JavaScript Object Notation)](https://www.json.org/json-en.html).

JSON is designed to:
- represent structured data in a way that computers can easily process  
- allow more flexible organisation of information (for example, nested data)

In this assignment, you will learn how to convert your tabular data into JSON and explore what this format makes possible.

### 5.a Recognising structure in JSON 

Look at the following dataset describing Karl Marx:

```json
{
   "firstName":"Karl Heinrich",
   "lastName":"Marx",
   "birth":{
      "date":"1818-05-05",
      "place":"Trier, Prussia (now Germany)"
   },
   "death":{
      "date":"1883-03-14",
      "place":"London, England"
   },
   "gender":"male",
   "nationality":"German",
   "occupations":[
      "Philosopher",
      "Economist",
      "Sociologist",
      "Historian",
      "Political Theorist"
   ],
   "knownFor":[
      {
         "title":"The Communist Manifesto",
         "year":1848,
         "coAuthor":"Friedrich Engels"
      },
      {
         "title":"Das Kapital",
         "year":1867,
         "volumes":3
      }
   ]
}
```

Now work with the following questions:

1. Identify different kinds of elements in the data:

* Where do you see text values?
* Where do you see numbers?
* Where do you see lists?

2. Compare this JSON data with your table:

* What information is the same?
* What is organised differently?

3. Look at the structure:

* Where do you see groups of information inside other groups?
* Why might this be useful for describing historical data?

Write down your observations before moving on.

If you need help, check below. 


| **Type**    | **What it means**                                          | **Example in JSON**                                            | **Formatting notes**                                                                                |
| ----------- | ---------------------------------------------------------- | -------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **string**  | A piece of text, always in double quotes.                  | `"firstName": "Karl"`                                          | Always use **double quotes `"..."`** for text (not single quotes).                                  |
| **integer** | A whole number (no quotes).                                | `"year": 1867`                                                 | No quotes around numbers.                                                                           |
| **number**  | A number that can have decimals.                           | `"rating": 4.5`                                                | Same rule: no quotes.                                                                               |
| **boolean** | A truth value: `true` or `false`.                          | `"isAlive": false`                                             | Must be lowercase (`true`, not `True`).                                                             |
| **null**    | No value (empty).                                          | `"middleName": null`                                           | Must be lowercase `null`.                                                                           |
| **object**  | A collection of key–value pairs inside curly braces `{ }`. | `"birth": { "date": "1818-05-05", "place": "Trier" }`          | Keys and values are separated by a colon `:`. Multiple entries are separated by commas.             |
| **array**   | A list of values inside square brackets `[ ]`.             | `"occupations": ["Philosopher", "Economist", "Revolutionary"]` | Values are separated by commas. Arrays can contain strings, numbers, objects, or even other arrays. |
 

### 5.b Understanding how JSON organises data

Based on what you observed, here are some key principles of JSON:

**Basic structure**

* Data is organised in key–value pairs
  * "firstName": "Karl Heinrich"

* Different containers (or "drawers" or "boxes") are used to structure data:
  * `{  }` (curly brackets) → objects (group related information)
  * `[  ]` (square brackets) → arrays (lists of values)
  * `" "` (quotes) → text values

**Syntax**

* Entries are separated by commas `,`
* Keys and text values must use double quotes
* Information can be organised hierarchically because, unlike tables, JSON allows nested structures
* Indentation is used to make nested structures easier to read by humans
* Commas must be placed correctly


### 5.c Creating your own JSON

Now convert your own table into JSON.

Use the table you created earlier in assignment 3.b. 

Rewrite this table in JSON using:
* key–value pairs
* at least one list (`[ ]`)
* at least one nested object (`{ }`)

If you need help, you can check the [JSON user documentation](https://json-schema.org/learn/getting-started-step-by-step).

Validate your JSON to check if your work is correctly formatted:

Paste your JSON into a validator: https://jsonchecker.com/

Try to identify and fix errors yourself before using automatic correction tools. 


Reflect on the following aspects: 

* What was difficult when converting your table into JSON?
* What kinds of errors did you make?
* In what situations might JSON be more useful than a table?
* What are the limits of JSON for historical data?


### 5.d Exploring JSON rules - 20 minutes
*This sub-assignment is of advanced difficulty for beginners*. 

Some JSON datasets follow more formal rules called a data schema, which define:
* What fields exist
* What kind of values they contain

Explore:

https://json-schema.org/learn


After reading [what is a schema](https://json-schema.org/understanding-json-schema/about), try to imagine in which case you might need to write your own schema and in which case you should better rely on the official JSON schema (or another schema used by a large community).

For historians and humanists it is wise to use a schema that is established by many others. However, you can of course write your own schema. For a comprehensive tutorial, see [here](https://json-schema.org/learn). If you're lazy, you might as well use one of the many online schema generators listed in the reading suggestions below.


### 5.e Critiquing data formats

In the previous exercises, you worked with different ways of structuring and representing data. This final step invites you to reflect more critically on the formats you use.


Consider the formats you have used in this assignment (JSON, CSV table).

1. Can this format be opened and edited with different software tools?
2. Would someone else easily be able to reuse your data?
3. What problems might arise if the software you used becomes unavailable?


As with encoding, the format of a data file is something we can think about critically.

- Some file formats are proprietary: they can only be opened or edited with specific software.
- Other formats are open: their structure is publicly documented and they can be used by many different tools.

Some formats are also easier to convert or exchange than others.

If you want your data to be easier to reuse and share, it is often advisable to use open formats.

Examples:
- Tables → comma-separated values (`.csv`)
- Text → Markdown (`.md`)
- Structured data → JSON (`.json`)

Reflect on the following:

- Why might historians prefer open formats?
- Are there situations where proprietary formats might still be useful?


You can find a list of open formats here:
https://en.wikipedia.org/wiki/List_of_open_file_formats


### What have we learned?

Across this lesson, we have seen that data are never simply "given": they are shaped by the symbols, conventions, and technical choices used to represent them (Section 1), and translated into machine-readable form through encoding systems whose scope and limitations — from punch cards to ASCII to RGB — determine what can and cannot be represented (Section 2). Turning historical sources into data requires deliberate choices about which descriptive categories and attributes to capture, choices that depend on the purpose of the research and are never neutral (Section 3). When the same entities recur across many sources, relational databases let us record each one only once and connect them through primary and foreign keys, making it possible to ask questions that a flat spreadsheet could not answer (Section 4). Finally, formats such as JSON show that even a finished dataset can be reorganised, nested, and exchanged in different ways — and that the choice of format, like the choice of encoding or data model, has consequences for who can reuse historical data and how (Section 5).

Together, these five steps trace the path from a historical source to structured, queryable data: from recognising what counts as data, through encoding and modelling it, to storing, connecting, and finally sharing it.


### Reading/viewing suggestions

*Online JSON schema generators*

JSON Forge. JSON Schema Generator https://www.jsonforge.com/tools/schema-generator

JSON Swiss https://jsonswiss.com/

Introducing JSON https://www.json.org/json-en.html

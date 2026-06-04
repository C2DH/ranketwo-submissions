---
authors: 
 - moritz-feichtinger
 
date: 2025-05-08
title: Defining data
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

The word “data” comes from Latin and means that which is given as in the French term *données*. Although we tend to think of data as being natural and universally “given”, this isn't really the case. In fact, **data are based on certain assumptions and include cultural, historical, political and social conventions in their structure and format** (Loukissas 2019). Let's explore what "data" means and what its main caracteristics are. <!--Sofia: not sure if you would like to add smth here about raw data, up to you--> 

### 1.a Objects becoming data  
Watch the video animation following Lea as she discovers and documents the objects left by her grandmother: books, postcards, tapes, floppy disks, videotapes, and photographs. 

1. Are all these objects “data”? 
2. What kinds of information do these objects contain? 
3. Which of the objects are directly readable by humans, and which ones require technical mediation, i.e. specific machines, software, etc.?

When Lea makes photos of each object using her phone, can you identify what transformation(s) take place? Do you think that Lea constructs data at this stage? In what ways?  

<!--The learning objective is to understand a) that data represent reality and make them concrete; b) media as careers of data; c) human/machine readability. The question on transformation is no doubt too open, can we give instructions towards specific directions? -->

### 1.b Understanding the finite and distinct nature of data  
Let's work with dates. Dates are one of the simplest and most familiar forms of data. We use them to identify specific moments in time by combining a limited set of symbols. 

Dates are important data for historians because they allow to contextualise a source - by the way, dating the objects is one of the tasks Lea gives to herself in the video to document her grandmother's holdings.  

A date such as `28-06-1914` already illustrates two essential characteristics of data: data are finite and distinct.

“Finite” means that data are built from a limited number of possible symbols. In the decimal system, for example, we use only ten digits (0–9). Likewise, the alphabet consists of a finite number of letters. Although the number of symbols is limited, they can be combined and rearranged in countless ways. This is what makes data versatile and powerful.

“Distinct” means that each symbol must remain clearly distinguishable from the others. A 6 must always be recognizable as a 6, and not confused with a 5 or an 8. If symbols were not distinct, data could not be interpreted consistently by humans or machines.

Inspect these two dates: 

* `28-06-1914`
* `08-06-1914`


1. Which symbols are finite in each example?
2. Could these formats create confusion? In what situations?

<!--
What have we learned so far? Data makes sense if the symbols are _distinct_ and _finite_, and if they adhere/correspond to a specific _schema_ or _data format_. -->

### 1.c Understanding data as cultural constructions

Dates also remind us that data depend on cultural and technical norms of representation which can be loose [conventions](https://en.wikipedia.org/wiki/Convention_(norm)), e.g. socially agreed, or [normative](https://en.wikipedia.org/wiki/ISO_8601). The same day can be written differently depending on cultural or historical context. 

These expressions below all refer to the twenty-eighth day of June in the year 1914:

* 28-06-1914
* 06-28-1914
* XXVIII.VI.MCMXIV
* 4th of Sha'ban 1332

Inspect the above dates and answher the following questions - if necessary, you can do a little research on the web: 

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

https://projects.iq.harvard.edu/files/eswg/files/rosenburg_-_rawdata.pdf => the link does not work and it is impossible to identify the publication <!--initial text snippet: [^0]: On the history and philosophy of the concept of "raw data," see: https://projects.iq.harvard.edu/files/eswg/files/rosenburg_-_rawdata.pdf This means that data can be both digital and non-digital. Just as there are non-digital calendars, there are also non-digital data. Let's start by understanding what "data" means and what its characteristics are. Then, we'll explore the specifics of digital data.-->

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
Now try this [beautiful emulator](https://masswerk.at/keypunch/) built by Austrian artist and web-designer Norbert Landsteiner. You can use the SYMBOLIC <!--because it uses EBCD--> configuration to type your name with help from a virtual [typewriter](https://en.wikipedia.org/wiki/Typewriter) and the emulator will punch the card for you. 

What is going on here? The emulator has integrated the knowledge that you (very probably) lacked in the previous exercice: an encoding scheme, i.e. the rules to follow to translate characters (or other data) as binary numbers or symbols. A scheme specifies which number represents which character, very much as the Morse code did, to get a digital, i.e. a both numerical and binary, representation of characters and text. 

The punch card of the above image, as well as the card you created using the emulator, use a scheme created by IBM in 1964: EBCDIC (for Extended Binary Coded Decimal Interchange Code), a [8-bit scheme](https://en.wikipedia.org/wiki/8-bit_computing) <!--explain: an architecture for representing information using chunks of 8 binary digits --> that assigned numbers from 0 to 255 (the largest number you can represent in 8 bits) to some common characters and symbols. We can imagine this as a 16 x 16 grid, where each symbol or character is represented by a specific position on the coordinate grid, respectively its numerical value. <!--If you want to see how exactly the EBCDIC character codes were mapped on the IBM punchcards, check out the insightful resources on punchcard history assembled by Douglas W. Jones: https://homepage.cs.uiowa.edu/~dwjones/ Two comments on this: 1) this resource is likely to not be accessible in 2 years time, however I made a copy on the internet archive, which guarantees a sustaineble URL 2) The page about punch cards is here: https://homepage.cs.uiowa.edu/~dwjones/cards/ and it would be important to suggest specific contents for the readers to check, first because otherwise they may be lost and second to give a concrete level to dig deeper in relation with what is presented above. However, all this may give more details than necessary-->  

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
2. Explore how the decimal number `188` 
3. Enter accented characters or non-Latin scripts. Explore their representations in different encoding schemes, for example ASCII, ASCII/UTF-8, Unicode. 

Even if you do not understand exactly what you see, such codes can be source of technical problems, for example for collecting or publishing source in web environments, or inversely solutions in the same configurations. The variety of encoding systems is result of technical choices and cultural assumptions and can have an impact on collecting, analysing and preserving historical data (see 2.d). In other words, encoding has a role in what is visible and what is not. It is important to know this, even if you are not the one who would the technical work to fix such issues.   


### 2.c Images as encoded data

Encoding does not only apply to text. Digital images are also encoded numerically. Images are composed of tiny units called pixels arranged in a grid. Each pixel receives numerical values corresponding to brightness or colour. In colour images, systems such as [RGB)(https://www.rapidtables.com/web/color/RGB_Color.html) combine values for red, green, and blue to create millions of colour combinations. The same principle applies to digital sound, which is represented through numerical samples recorded at regular intervals (Give it a try and explore [more here!](https://8bitcomposer.com/).

Now let's try to understand how images can also be encoded numerically. Imagine an image as a grid made of many tiny units called *[pixels](https://en.wikipedia.org/wiki/Pixel)*. Each pixel receives a numerical value corresponding to a colour or brightness.

The image below represents a simple circle on a 16 × 16 grid:

![Circle in 16 x 16 grid](/assets/images/data-criticism/16x16-circle-table.jpg)

Caption ???????????????? Mention of source (author?)

Each position in the grid can be identified numerically and assigned a RGB scheme colour value. Together, these encoded positions create the visual impression of a circle.

STEP 1 — Observing the grid

Inspect the image carefully and answer the following questions:

1. Can you recognize a circle in the image even though it is composed of individual squares?
2. What happens to the shape at the edges of the circle?
3. Why does the image appear simplified or “blocky”?

This is why this is happening. 
We have seen that in a simple 16 x 16 coordinate system, all 256 positions can be represented by a number. This number can be expressed as a binary value of 8 bits (one byte) in length. Using this idea, we can also map simple shapes. Imagine that we just specify each position that carries some colour. Now we can represent simple geometric shapes, like a circle. Again, we would specify the positions (or their numerical values, respectively) of the fields that are coloured, represented by red dots in the grid. 


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

> Although humans may find binary difficult to read, computers use it to represent and process all kinds of information. As we have seen, combinations of `0`and `1`s can encode texts, images, sounds, and many other forms of data. They can also represent instructions and logical operations <!--such as “AND”, “OR”, and “NOT”. This -->which means that binary digits are not only used to store information, but also to run algorithms and computer programs.


Return to Lea’s digital collection of her grandmother's holdings from the introductory animation. Note the scene 5 where Lea discusses with Ada about the floppy disk.  

1. Which technical problems could affect the preservation of her grandmother’s floppy disks, tapes, or digital photographs?
2. What kinds of information could be lost during digitisation?
3. Why is metadata important when recovering or interpreting digital sources?
4. Can digital reproductions ever fully replace original objects?



<!--
We have seen that in a simple 16 x 16 coordinate system, all 256 positions can be represented by a number. This number can be expressed as a binary value of 8 bits (one byte) in length. Using this idea, we can also map simple shapes. Imagine that we just specify each position that carries some colour. Now we can represent simple geometric shapes, like a circle. Again, we would specify the positions (or their numerical values, respectively) of the fields that are coloured, represented by red dots in the grid below:

![Circle in 16 x 16 grid](/assets/images/data-criticism/16x16-circle-table.jpg)

This principle of representing single pixels with numeric values is also how 8-bit grayscale works. In this scheme, there are 256 shades of grey between white and black. To implement this, just imagine that each field in our 16x16 grid has now the numerical code for a specific shade of gray assigned to it. Colors can also be represented in this way, using the 8-bit [RGB scheme](https://www.rapidtables.com/web/color/RGB_Color.html), which assigns 256 different intensity levels to each of the three primary colors red, green, and blue — resulting in over 16 million possible color combinations. Of course, the bigger our grid gets, the higher the resolution of our image will be!

But it's not just images that can be stored as digital data using bits (zeros and ones); music and sound recordings can too. Let's look at our 16x16 matrix again. This time, imagine that the x-axis divides a piece of music into 16 parts (i.e. time units, like seconds, for example), and the y-axis represents the sound frequency (0 for lowest, 16 for highest tone). The time period we apply to the x-axis (the sampling rate) and the subdivision of the frequency heights determine how many different sounds and tone sequences we can represent. Give it a [try!](https://8bitcomposer.com/) 

We humans might find the binary system difficult to understand, but for computers it is the perfect language because it lets them understand and express everything you can think of. As we have seen, zeros and ones can represent texts, images, sound, and any combination of these. They can be stored on punch cards, hard drives, CD-ROMs, USB drives, or any other storage available (but you can only interpret your data as long as you know the encoding). Binary digits can also represent the logical operators "AND," "NOT," "OR," and their combinations. In consequence, our chains of 0s and 1s can not only represent data of any kind, but also sequences of instructions and procedures, which can be used to represent logical circuits and combined to build complex switching systems. In other words: `0`s and `1`s can also represent [algorithms](https://www.geeksforgeeks.org/dsa/introduction-to-algorithms/) and [programs](https://www.geeksforgeeks.org/computer-organization-architecture/what-is-a-computer-program/)! 

We have seen that even an 8-bit encoding scheme can represent a wide variety of content and information as digital data. Modern computers can store more and more information and can process things more quickly, which, along with the rapid increase of communication speeds and bandwidth, makes our present digital world possible. But it all works on the same basic principles.

The choice of encoding scheme is not something we usually think much about when dealing with digital data and objects. However, it is important to keep in mind that it is a choice which determines what can be done with the data. Remember, ASCII excluded non-western characters and symbols (ASCII Imperialism). Storing and transmitting an image in a higher or lower resolution, in grayscale or RGB, can have effects on the accuracy of the representation of real-world objects. Consequently, the encoding scheme and its effects are something we should be critically aware of. 

What have we learned? Digital data can be used to create representations of text, image, sound, and so on. The specifics of their technical implementation ­- what resolution, 8-bit, 16-bit, 32-bit encoding, the schemes and code tables - are conventions that have emerged historically. If you (or your computer) know the encoding and have appropriate software to interpret any sequence of `0`s and `1`s, you can display and manipulate it. -->

### Reading/viewing suggestions 

Haigh, Thomas. *Defining Digitalities I.* 2023. https://doi.org/10.25819/ubsi/10259.

The Punched Card | IBM. https://www.ibm.com/history/punched-card.


http://www.injosoft.se, Injosoft AB. The Beginner’s Guide to ASCII. https://www.ascii-code.com/articles/Beginners-Guide-to-ASCII.


## 3 Creating models and datasets
Let us now explore how data are produced to describe and study the world around us. Texts, people, animals, places, or historical events can all be transformed into descriptive data. By creating such data, historians turn sources into structured representations that can be organised, searched, and analysed. This process is both conceptual — involving research choices and categories — and technical, relying on tools such as spreadsheets and databases, which also introduce their own constraints.

### 3.a Designing descriptive categories

Let's take a simple example: a wanted poster as you might know from western movies or comics (see figure below). Please observe carefully the poster and the information it provides. 

![Wanted Poster](/assets/images/data-criticism/wanted-poster.jpg)

Then think of the poster as a simple table that focusses on a given person and lists a number of characteristics in diffeent columns with the purpose to identify this person.

<!--
Person:
|Attributes|Value|
|:-:|:-:|
|Attribute 1|"..."|
|Attribute 2|"..."|
|Attribute 3|"..."|
|Attribute 4|"..."|
-->

Table Person

|Attribute 1|Attribute 2|Attribute 3|Attribute 4|
|:---------|:--------|:-------|:--------|
|"..."|"..."|"..."|"..."|
|"..."|"..."|"..."|"..."|
|"..."|"..."|"..."|"..."|


[Link to editable table: Person](/assets/docs/data-criticism/person-table.docx)

STEP 1

Please fill the table: for the attributes, refer to the poster. For the values, use your critical skills and get help from the visual in the poster and from research on the web. 

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
In the above scaffold table, attribute 1 would be the first name of the person, attribute 2 would be the person's last name, attribute 3 would be the gender, attribute 4 the place of birth and so on (please refer to the poster). Such a table would now describe a person, Karl Marx.
</details> 

STEP 2

By selecting specific attributs, we create *descriptive categories*. Obviously, our selection of attributes would be different if we wanted to describe the same person in another context, for example as an author, or if we described something else, like a place, or a piece of art, or an animal, or a book. In other words, the selection of descriptive categories is subject to a finality. In the case of the wanted poster, the finality is identifying and catching a fugitive. For this reason, identifying, say, a person's favorite dessert might not be the most significant property, especially if we can only list a limited number of them on our wanted poster. 

Can you think of significant properties that would matter in this case but are not included in the poster? 

### 3.b Creating descriptive data

When we want to describe and compare several historical personalities, objects, or events, we can organise information in tables made of rows and columns. Each column represents a category or attribute — that is, a feature we want to record, such as a name, date, place, or other characteristic. The top row of the table usually contains headers identifying these categories. Each subsequent row contains the information describing one individual entry, while the recorded information itself is called a value. Organised in tables, these categories and values form data collections that can be searched, sorted, extended and analysed with the help of digital tools such as spreadsheets or databases.

<!--Sofia: I think that the definition of data model below corresponds more to coding or categorizing data; the data model is mostly used to define relations, which is not the focus in this part of the lesson. Thus, I would suggest to not present it hastily here in a reductive way. Same for dataset, it is perhaps preferable to not assimilate the notion with the small tables above. We do not need to cover everything, and further exploration can be made by recommended lectures in the Reading suggestions section-->
*The pre-defined list of properties you want to capture on a given group of objects or phenomena is called the _data model_. The quality of any data model is determined by its usability for a given purpose: you want your data to be searchable, accessible, findable, and easy to process, present and communicate. We rarely, if ever, encounter data in the singular. Most of the time, we talk about a data set, like in the tables we have seen above. The individual entries in it are called data points, such as the numerical value that represents the letter "A" or the string that is the value for the attribute `first_name`. The individual rows of longer tables, for example the historic persons in your table, are commonly called _data records_ or _entries_. Several of them make a _data set_.* 

If you imagine tilting our two-column table to the right, the attributes become column headers and we can add more rows to it, each one describing one person:

|first_name|last_name|year_of_birth|place_of_birth|author_of|gender|number_of_children|is_still_alive|
|:---------|:--------|:-------|:--------|:-------|:--------|:-----|:---|
|Karl|Value 2|Value 3| Value 4|Value 5|Value 6|Value 7|Value 8| 
|...|...|...|...|...|...|...|...|
|...|...|...|...|...|...|...|...|

[Link to editable table: Historical Persons](/assets/docs/data-criticism/historical-persons-table.docx)

The individual entries in the table are called *data points*, such as the string that is the value for the attribute `first_name` (Karl). 
Now fill the table to describe the following historic personnalities (or at least two of them): 
* Karl Marx
* Wilhelm Marx
* Eleanor Marx 
* Groucho Marx

Now that you entered data, let's observe the different types of values and the issues they may raise. 
* Compare the first and the third rows: what types of values do you have in each?
<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
While the values for the first two columns are clearly textual (often called a "string" like a string of characters), the third column could also be a number ("an integer").
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
Our first historic person, Karl, was rather productive and was the author of many more than just one text. How could all this information fit in one row? Is the column fit to the other personnalities? If not, this would mean that the data model wan not conceived according to the finality - which would be a mistake you would rather avoid in a real research.   
</details> 

* Do you think that the sixth column could create specific questions as to the values you would enter? In what ways you think you could express these values (text, other)?

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
In this column, the values could be pre-defined: would you define two or more types of values? Whatever you decide, would these values be textual or integers? Think in terms of [coding data](https://en.wikipedia.org/wiki/Coding_(social_sciences)).
</details>

* What values can you enter in the eighth column? 

<details>
<summary><strong>Need help? (click to expand)</strong></summary> 
The eigth column 8 can only hold "yes" or "no" as an answer (in most computational contexts, this is expressed in "Boolean" values: `true` or `false`).
</details>

What you've encountered here is called [data types](https://en.wikipedia.org/wiki/Data_type). Like the descriptive categories, that you should have selected before you begin collecting data, you also need to think of the appropriate data types for each of them.

<!--The paragraphs below present redundancies with parts above and/or introduce new complex elements such as ontologies. They are parhaps a bit too abstract and not supported by exercises. Some stuff can be externalized in the sense that external bibliography can be recommended, for example on vocabularies and ontologies. The second phrase "If you create an inventory, capture only the most basic information that allows you to quickly search and find what you're looking for." can be the basis for building an exercice using the video and Lea's findings. Here? Create a 3.c (in which case the JSON exercice would be 3.d)? -->
<!--*For different purposes, you might want to employ different attributes in your data sets: if you need to transport or store your items, it makes sense to have information on weight and size. If you create an inventory, capture only the most basic information that allows you to quickly search and find what you're looking for. If you want to detect common elements and relations between different items, gather as much information as possible and carefully select attributes that are applicable to all of the objects you want to describe.* -->

<!--idea for an exercice: Watch the video and note down the objects Lea finds in her grandmother's house. Maybe we can use what Tugce proposes in her lesson here: https://github.com/C2DH/ranketwo-submissions/blob/master/lessons/drafts/data-ethics.md#3c-bringing-it-all-together-evaluating-leas-choices and ask the learners to think: what attributes they would create for each of the 3 types of objects proposed 1) if they were to create an inventory like Lea fdoes and 2) if they were to document the respective objects. We can prepare simple tables to provide in a Need help? section like above; -->


### 3.c Creating datasets - 30 minutes

Historians do not record all possible information. The categories they choose depend on the questions they want to ask and the comparisons they want to make: thus, for different purposes, different attributes can be employed in data sets.

Remember, in the video animation Lea finds several objects in her grandmother's house. Let's imagine that she ends up having a collection like the one described in [this lesson](https://github.com/C2DH/ranketwo-submissions/blob/master/lessons/drafts/data-ethics.md#3c-bringing-it-all-together-evaluating-leas-choices). Note down the objects and put yourself into Lea's shoes: her purpose is to create an inventory. 

1. Imagine a table Object to describe each of the objects enumerated in the video (one object per row)
2. Which attributes you would create for each of the objects enumerated? (one attribute per column) 

<!--We can prepare simple tables to provide in a Need help? section like above-->

> There are ethical considerations to take into account when we create data: to know more, check this lesson that will introduce you to [ethics and responsibilities](https://github.com/C2DH/ranketwo-submissions/blob/master/lessons/drafts/data-ethics.md) 

### Reading/viewing suggestions

Lemercier, Claire, and Claire Zalc. 2019. *Quantitative Methods in the Humanities: An Introduction.* . Translated by Arthur Goldhammer. Charlottesville: University of Virginia Press.

Roberts, Spencer W.. Spreadsheets for Historians – Spencer W. Roberts. 12 août 2014. https://swroberts.ca/scholarship/spreadsheets-for-historians/.

Rogers, Jonathan. « LibGuides: Working with Quantitative Data: Home ». Consulté le 2 juin 2026. https://libguides.law.ucla.edu/data/home.


## 4 From sources to data: understanding the relational database

When historians work with a few sources, a spreadsheet is often sufficient. But when we need to analyse hundreds or thousands of documents, information quickly becomes repetitive and difficult to manage. Relational databases, based on [specific software](https://en.wikipedia.org/wiki/Database#Database_management_system), were designed to organise large amounts of information while preserving the connections between the described objects.   

<!--In the previous part, we saw how we can store historical information in tables. The example of Lea's holdings in 3.c shows us that we can have many tables to describe different objects of a whole.-->  

### Instructions 


Look at the following source: Karl Marx. Whose Atrocities? *New York Daily Tribune*, April 10, 1857. [URL](https://www.marxists.org/archive/marx/works/1857/04/10.htm) <!--or via the Wayback Machine [here](https://web.archive.org/web/20260000000000*/https://www.marxists.org/archive/marx/works/1857/04/10.htm).--> 

![Source: "Whose Atrocities?"](/assets/images/data-criticism/source-full.jpg)

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

Now check the following image. Make abstraction of technical details and focus on what you can understand.  

![Scheme and connections](/assets/images/data-criticism/database_scheme.jpg)

1. Can you recognise types of information that constitute descriptive categories following the article you read?
2. Can you recognise what kind of information is considered important to retain based on the attrobutes of each category? 
3. Can you understand how the categories are related? How would you interprete the arrows connecting them?   


### 4.b Extracting information from sources

Before building a database, historians must identify the information they want to record. In this exercice, we are going to extract names, places, organisations, and events from our historical sources. We are actually goig to perform a simplified form of [Named Entity Recognition (NER)](https://en.wikipedia.org/wiki/Named-entity_recognition).

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

Every time Palmerston appears in a source, you may need to enter information about the same person again. As the number of sources grows, this can lead to hundreds of repeated entries, inconsistencies in spelling or naming, and difficulties updating information across the dataset.

</details>

Discuss why a spreadsheet can become difficult to manage when information is repeated, ambiguous, uncertain, or complex.

> Relational databases solve this problem by storing each entity only once and linking information through identifiers. In the relational database model introduced in 4.a, Palmerston exists only once, as record `P002`. Every event, office, or source that refers to him simply stores the identifier `P002`. This makes it possible to search, update, and analyse information across many sources without duplication.

### 4.d Building a relational database

*learning objective: Understand how relationships between tables are implemented with primary keys and foreign keys*

Relational databases rely on a few key principles. 

A relational database model organizes information into separate tables. Each table contains only unique rows, representing a specific object, place, or person... To guarantee this uniqueness, each row (record) requires a unique identifier ([primary key](https://www.w3schools.com/sql/sql_primarykey.asp)). 

Imagine two people are both named "John Smith" in your sources. A primary key (PK) solves this: it is a short code (in our example `P001`, `P002` …) that belongs to one and only one row, permanently. You invent it yourself when building the database, or the software you use assigns it automatically to each row/record.


For example: Table Person

| person_id | name | source_id |
|---|---|---|
| P001 | Sir James Hogg | S001 |
| P002 | Lord Palmerston | S001 |
| P003 | Earl of Clarendon | S001 |

The separate tables of a database are connected by relationships defined in the data model. To materialize these links without repeating all the attributes again, we use a [foreign key](https://www.w3schools.com/sql/sql_foreignkey.asp), which is a unique identifier (primary key) of one table inserted into another. 

Where relationships are complex, for example if one person was involved in many events, and/ or we have to deal with one event involving many persons, **junction tables** store the connections without duplicating data. Together, these mechanisms allow historians to ask questions that cut across many sources at once, and to detect patterns that no single spreadsheet could reveal. 

STEP 1 CREATE IDENTIFIERS

Using your list of entities:

* Assign a unique identifier to each person.
* Assign a unique identifier to each place.
* Assign a unique identifier to each event. 

STEP 2 CONNECTING INFORMATION

Examine the sample database tables below.

* Which table stores information about persons? Find and inspect this table. 
* Which table stores information about events? Find and inspect this table. 
* How can you identify all events involving Lord Palmerston? 
* Why is the Person–Event table necessary?

<details>
<summary><strong>Need help? (click to expand)</strong></summary>
The separate tables of a database are connected by relationships defined in the data model. To materialize these links without repeating all the attributes again, we use a [foreign key](https://www.w3schools.com/sql/sql_foreignkey.asp), which is a unique identifier (primary key) of one table inserted into another. 

Instead of writing "Lord Palmerston, Premier of England" into every event he is connected to, you write `P002` — and the database follows that pointer to the full Persons record instantly.

Where relationships are complex, for example if one person was involved in many events, and/ or we have to deal with one event involving many persons, **junction tables** store the connections without duplicating data. Together, these mechanisms allow historians to ask questions that cut across many sources at once, and to detect patterns that no single spreadsheet could reveal. 
</details>

### 4.e Extending the database

This exercice builds on what we did in 4.d. 

Karl Marx refers to the Arrow Incident.

Consult the [Wikipedia article on the Second Opium War](https://en.wikipedia.org/wiki/Second_Opium_War).

Add the event to the Events table.
Identify any additional persons, organisations, or places that should be included.
Do you need new tables? Why?

### 4.f Example database Sources

If we create tables for all the different types of information or entities, we could have four tables (five, if the source itself also gets one, here table 1): persons (table 2), functions (table 3), places (table 4), organisations (table 5). We would want to have another one for historic events, that contains all of the entries above. Now the magic happens in the junction tables which we need to store the relations (or connectors). Here, persons and organisations are related (as in our table 3) or persons and events (our table 7).

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

#### Table 3 — Office

This table records **which role a person held in which organisation, and when**. It is itself a junction table — it links Persons to Organisations and adds the historical detail of the relationship.

| office_id | person_id | org_id | title | date_from | date_to |
|---|---|---|---|---|---|
| OF001 | P001 | O001 | Director | _unknown_ | _unknown_ |
| OF002 | P002 | O002 | Premier of England | _before 1857_ | _after 1857_ |
| OF003 | P003 | O002 | Minister of Foreign Affairs | _before 1857_ | _after 1857_ |

#### Table 4 — Place

| place_id | name | type | source_id |
|---|---|---|---|
| L001 | India | Region / Country | S001 |
| L002 | England | Country | S001 |
| L003 | Canton | City | S001 |

#### Table 5 — Organisation

| org_id | name | type | source_id |
|---|---|---|---|
| O001 | East India Company | Trading company | S001 |
| O002 | British Government | State authority | S001 |
| O003 | British Parliament | Legislative body | S001 |

#### Table 6 — Event

 The table Event is the connecting hub.

| event_id | name | date | place_id | org_id | source_id |
|---|---|---|---|---|---|
| E001 | Exposure of torture system in India before Parliament | ca. 1853 | L001 | O003 | S001 |
| E002 | Lord Mayor's banquet — Palmerston's speech | early 1857 | L002 | O002 | S001 |
| E003 | Arrest of sailors aboard the _Arrow_ | 1856-10-08 | L003 | O001 | S001 |

#### Table 7 — Person–Event 

The table Person-Event is the junction table.

|compos_pers_ev_id | person_id | event_id | role_in_event                             |
|---|-----------|----------|-------------------------------------------|
| PE001  | P002      | E002     | Speaker (as Premier)                      |
| PE002  | P001      | E001     | Director (respondent)           |
| PE003  | P003      | E002     | Attendee (as Minister of Foreign Affairs) |


Because one person can participate in many events and one event can involve many persons, this relationship is **many-to-many** — it cannot be stored in either the Persons or Events table alone. The junction table holds one row per person–event pairing. Both `person_id` and `event_id` are foreign keys; **together** they form the primary key of this table (a _composite_ primary key), because what is unique here is the _combination_ — the same person can appear in multiple events, and the same event can appear across multiple persons, but a specific person can only be linked to a specific event once.

<!-- Not sure where the reader can make a query. Furthemore, what a query in a db is has not been explained and perhaps the fact that it comes from sql-->
_You can now query: "Who was present at the Lord Mayor's banquet?" → select all rows where `event_id = E002` → returns P002 and P003._

Now we have - a very basic - architecture of a database containing several different types of tables that are related to each other (much like hyperlinks in a web document, but more powerful and flexible). 
![Scheme and connections](/assets/images/data-criticism/database_scheme.jpg)

Of course, there are rules to follow when creating a database. Primary keys cannot be empty (null), for a start. Also, as we've already seen for other data sets, the entries (for each column) have to be of the same type. If you use a software to create a database (like the free [Libre Office Base](https://www.libreoffice.org/DISCOVER/BASE/)), you will have to specify the types. Also, the software <!-- which software? none was mentioned but anyway, I think that this level of details is perhaps too much without having before given specific explanation which however are not the aim of the lesson--> will ask you whether a column can hold foreign keys or not (you usually recognize them, because they are IDs, i.e. by their suffix `_id`).

But this lesson's aim is to raise awareness on what is behind a database; please consult the references in the reading suggestions to learn more (Julien 2024); and (Cosovschi 2024).   

![Types](/assets/images/data-criticism/odb.jpg) 

<!--
#### Keys and identifiers

For a relational database to work, it is indispensable that every row has a **unique identifier** - usually the first column - so the database can tell records (the rows) apart without ambiguity. Imagine two people are both named "John Smith" in your sources — or that Lord Palmerston is referred to as "the Premier", "his Lordship", and "Lord Palmerston" in three different paragraphs. A **primary key** (PK) solves this: it is a short code (`P001`, `P002` …) that belongs to one and only one row, permanently. You invent it yourself when building the database, or the software you use assigns it automatically to each row/record.

A **foreign key** (FK) is how one table points to another. Instead of writing "Lord Palmerston, Premier of England" into every event he is connected to, you write `P002` — and the database follows that pointer to the full Persons record instantly. Think of it like a footnote number: the number in the text is the foreign key; the full citation at the bottom is the primary key row in another table. By having several tables for different entities, you can refer to each of their entries via their identifier. 

If we create tables for all the different types of information or entities, we could have four tables (five, if the source itself also gets one, here table 1): persons (table 2), functions (table 3), places (table 4), organisations (table 5). We would want to have another one for historic events, that contains all of the entries above. Now the magic happens in the junction tables which we need to store the relations (or connectors). Here, persons and organisations are related (as in our table 3) or persons and events (our table 7).

#### Table 1 — Sources

| source_id | author | publication | date | url |
|---|---|---|---|---|
| S001 | Karl Marx | New York Daily Tribune | 1857-04-10 | https://www.marxists.org/archive/marx/works/1857/04/10.htm |

#### Table 2 — Persons

| person_id | name | source_id |
|---|---|---|
| P001 | Sir James Hogg | S001 |
| P002 | Lord Palmerston | S001 |
| P003 | Earl of Clarendon | S001 |

In a relational database, Palmerston exists **exactly once** as row `P002`. Every event, every office, every source that mentions him simply stores `P002`. You can then ask questions that cut across all your sources at once: _"List every event involving persons who held office in the British Government, sorted by date."_ A spreadsheet cannot answer that. A relational database answers it in a single query, however many sources you have gathered.

_Note that we only see the first three entities here; further persons in the excerpt to be included in this table are: Harry Parkes (the Consul), Sir John Bowring, Admiral Seymour …_

#### Table 3 — Offices / Functions

This table records **which role a person held in which organisation, and when**. It is itself a junction table — it links Persons to Organisations and adds the historical detail of the relationship.

| office_id | person_id | org_id | title | date_from | date_to |
|---|---|---|---|---|---|
| OF001 | P001 | O001 | Director | _unknown_ | _unknown_ |
| OF002 | P002 | O002 | Premier of England | _before 1857_ | _after 1857_ |
| OF003 | P003 | O002 | Minister of Foreign Affairs | _before 1857_ | _after 1857_ |

#### Table 4 — Places

| place_id | name | type | source_id |
|---|---|---|---|
| L001 | India | Region / Country | S001 |
| L002 | England | Country | S001 |
| L003 | Canton | City | S001 |

#### Table 5 — Organisations

| org_id | name | type | source_id |
|---|---|---|---|
| O001 | East India Company | Trading company | S001 |
| O002 | British Government | State authority | S001 |
| O003 | British Parliament | Legislative body | S001 |

#### Table 6 — Events _(the connecting hub)_

| event_id | name | date | place_id | org_id | source_id |
|---|---|---|---|---|---|
| E001 | Exposure of torture system in India before Parliament | ca. 1853 | L001 | O003 | S001 |
| E002 | Lord Mayor's banquet — Palmerston's speech | early 1857 | L002 | O002 | S001 |
| E003 | Arrest of sailors aboard the _Arrow_ | 1856-10-08 | L003 | O001 | S001 |

#### Table 7 — Person–Event _(the junction table)_

|compos_pers_ev_id | person_id | event_id | role_in_event                             |
|---|-----------|----------|-------------------------------------------|
| PE001  | P002      | E002     | Speaker (as Premier)                      |
| PE002  | P001      | E001     | Director (respondent)           |
| PE003  | P003      | E002     | Attendee (as Minister of Foreign Affairs) |


Because one person can participate in many events and one event can involve many persons, this relationship is **many-to-many** — it cannot be stored in either the Persons or Events table alone. The junction table holds one row per person–event pairing. Both `person_id` and `event_id` are foreign keys; **together** they form the primary key of this table (a _composite_ primary key), because what is unique here is the _combination_ — the same person can appear in multiple events, and the same event can appear across multiple persons, but a specific person can only be linked to a specific event once.

_You can now query: "Who was present at the Lord Mayor's banquet?" → select all rows where `event_id = E002` → returns P002 and P003._

Now we have a database containing several different types of entities and tables that are related to each other (much like hyperlinks in a web document, but more powerful and flexible):
![Scheme and connections](/assets/images/data-criticism/database_scheme.jpg)

Of course, there are rules to follow when creating a database. Primary keys cannot be empty (null), for a start. Also, as we've already seen for other data sets, the entries (for each column) have to be of the same type. If you use a software to create a database (like the free [Libre Office Base](https://www.libreoffice.org/DISCOVER/BASE/)), you will have to specify the types. Also, the software will ask you whether a column can hold foreign keys or not (you usually recognize them, because they are IDs, i.e. by their suffix `_id`).

![Types](/assets/images/data-criticism/odb.jpg) 

#### Assignment
You see that Karl mentions an incident that happened on a ship, the Arrow. Head over to the respective [Wikipedia entry](https://en.wikipedia.org/wiki/Second_Opium_War) to get details. Now update the tables, specifically the "events" table. Do we need more tables for this?

---

### What have we learned?
Databases are the main carrier for digital data. They can store a great variety of different types of data. But their true value comes from their ability to run queries over all of their content. This way, we can get very specific information, evaluate the magnitude or duration of phenomena and detect patterns in the data.

To make all of this possible, relational databases rely on a few key principles. Every record needs a **primary key** — a unique identifier that distinguishes it from all others, even if names or descriptions are identical across sources. **Foreign keys** allow tables to reference each other, so that a person, a place, or an organisation only needs to be described once and can then be linked to as many events or sources as needed. Where relationships are complex, for example if one person was involved in many events, and/ or we have to deal with one event involving many persons, **junction tables** store the connections without duplicating data. Together, these mechanisms allow historians to ask questions that cut across many sources at once, and to detect patterns that no single spreadsheet could reveal.

First of all, we notice that we could obviously treat this source on three different levels: On the one hand, we're dealing with a website. On a different level, it is an excerpt from an edited volume assembling Marx's writings for the New York Daily Tribune that was published in 1951. Finally, we could also treat it as an article that appeared in said newspaper on April 10, 1857. This is how these different types are displayed in [Zotero](https://www.zotero.org/), the popular software for managing bibliographical information. 

![zotero entries](/assets/images/data-criticism/zotero-entries.jpg)

The same source would look like this if captured in [Tropy](https://www.tropy.org/), the software specifically conceived to manage archive photos:
![tropy_screen](/assets/images/data-criticism/tropy-object.jpg) -->


### Reading/viewing suggestions

Nodegoat. What Is a Relational Database?. Accessed 4 June 2026. https://nodegoat.net/blog.s/20/what-is-a-relational-database.

Cosovschi, Agustín. « From Sources to Data: Designing a Database for the Humanities and Social Sciences with Nodegoat ». Programming Historian, 29 février 2024. https://programminghistorian.org/en/lessons/designing-database-nodegoat.

Julien, Octave. Creating and using databases in medieval history: historiography, concepts and practice. Seminários do GIHM, April 2024, Porto, Portugal. ￿halshs-04550456￿

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
* at least one list (`[ ]``)
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


After reading [what is a schema](https://json-schema.org/understanding-json-schema/about), try to imagine in which case you might need to write your own schema and in which case you should better rely on the official JSON schema (or another schema used by a large community. 

For historians and humanists it is wise to use a schema that is established by many others. However, you can of course write your own schema. For a comprehensive tutorial, see [here](https://json-schema.org/learn). If you're lazy, you might as well use one of the many 


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


### Reading/viewing suggestions

*Online JSON schema generators*

JSON Forge. JSON Schema Generator https://www.jsonforge.com/tools/schema-generator

JSON Swiss https://jsonswiss.com/

Introducing JSON https://www.json.org/json-en.html 




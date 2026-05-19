---
authors: 
 - moritz-feichtinger
 
date: 2025-05-08
title: Defining data
learning-objectives: 
 - Understand the basic concept of "data" as an abstract representation
 - Understand that choices of attributes is motivated by purpose of data 
---

### What are data?
The word "data" comes from Latin. The verb "dare" means "to give," so "datum" means "that which is given" as in the French term "données."[^0] Apart from the meaning of data in the digital realm, we still use the term to refer to specific days, months, and years.

[^0]: On the history and philosophy of the concept of "raw data," see: https://projects.iq.harvard.edu/files/eswg/files/rosenburg_-_rawdata.pdf This means that data can be both digital and non-digital. Just as there are non-digital calendars, there are also non-digital data. Let's start by understanding what "data" means and what its characteristics are. Then, we'll explore the specifics of digital data.

The date used to mark a specific day already has the characteristics of data: It consists of unique (distinct) symbols from a limited (finite) number of such symbols. 
"Distinct" means that each symbol has exactly one meaning: a six is a six, not a five or a seven. "Finite" means that there are a limited number of possible characters. We know this from the alphabet, which also has only a limited number of characters. But this limitation also leads to a much larger number of combinations and rearrangements of these characters. This is what makes distinct symbols so versatile and powerful.

If we look at a date like June 28, 1914 (`28-06-1914`), we can see another important general feature of data: they are subject to established and shared conventions or standards. We need to agree on which digits represent the day and which represent the month. In US English, the form `MM-DD-YYYY` (month-day-year) is often used, whereas in Europe, the order `DD-MM-YYYY` (day-month-year) is more common. We also need to agree on which symbol system to use. After all, the date June 28, 1914 could also be written using Roman numerals:  `XXVIII.VI.MCMXIV`. Similarly, the date could be designated as the `4th of Sha'ban in the year 1332` according to the Islamic calendar, or as the `twentieth day of the tenth month in the Year of the Snake (4723)` according to the Chinese calendar. Although we tend to think of data as being natural and universally "given," this isn't really the case. In fact, **data are based on certain assumptions and include cultural, historical, political and social conventions in their structure and format**.[^2]

What have we learned so far? Data only makes sense if the symbols are _distinct_ and _finite_, and if they adhere/correspond to a specific _schema_ or _data format_. 

### Digital data and encoding
The simplest form of data entry we could think of is some kind of mark on a carrier medium, like a cut on a stick or a hole or the absence of a hole on a piece of paper or cardboard (representing "yes" or "no"). A further very simple form of data storage would be numerical, i.e., the number of holes representing a number, or a hole being punched in the field of a preprinted number (or other value). We can find lots of examples of this simple data storage method in everyday life. It is used on many different types of cards, such as travel and admission tickets, gift cards and more. 

The term "digital" in "digital data" originally just means numerical, meaning the data is printed in digits [^3]. Digital does not have to mean electronic. Historically, electronic communication technologies such as the telegraph, telephone and radio were not digital. Telegraphy, the earliest form of electronic communication, however, used only two types of signal to represent letters and the words and sentences made up of them: [short signal or long signal](https://morsecode.world/international/translator.html).
At the dawn of the computer age, letters were also represented by just two symbols: a hole or no hole on a punch card, or at a specific position on the card. Text could be displayed by combining holes in different positions. IBM's punch card, the most widely used worldwide, had twelve rows and 80 columns and has been used to process information since the 1930s. IBM's own EBCDIC 8-bit encoding format could display 64 of the most common textual characters on the punch card (as well as some special characters, control commands and special expressions). 

Here is an IBM punchcard with the respective holes for all the characters printed on the top according to the EBCDIC encoding. Would you know how to punch your name?

![IBM-EBCDIC punchcard](/assets/images/data-criticism/punchcard.jpg)

As you see, the punchcard can't hold much information, something around 60 bytes (one byte is 8 bits long, one bit being either a `0` or a `1`). You can play around with punchcards and see for yourself what information you can fit onto one of them. 

#### Assignment
The Austrian artist and web-designer Norbert Landsteiner has built a [beautiful emulator](https://masswerk.at/keypunch/) to further explore this medium. Give it a try, punch a short data-set describing yourself or a person you know well.

---

But how would a computer interpret the holes then? Computers can only digest numbers, more precisely: binary numbers. In the binary system, natural numbers ("integers") are represented only in `1`s and `0`s. You should have learned to convert decimal numbers into binary in school, but in case you've forgotten all of that, there are luckily many converters and explanations on the web, for example [here](https://www.rapidtables.com/convert/number/decimal-to-binary.html).
To get a digital (= numerical and binary) representation of characters and text, we need to agree on a scheme (=encoding) that specifies which number represents which character, very much as the Morse code did. EBCDIC was one such scheme. It assigned numbers from 0 to 255 (the largest number you can represent in 8 bits) to some common characters and symbols. We can imagine this as a 16 x 16 grid, where each symbol or character is represented by a specific position on the coordinate grid, respectively its numerical value.[^4]

[^2]: Loukissas, Y. A. (2019). _All data are local: Thinking critically in a data-driven society_. The MIT Press.
[^4]: If you want to see how exactly the EBCDIC character codes were mapped on the IBM punchcards, check out the insightful resources on punchcard history assembled by Douglas W. Jones: https://homepage.cs.uiowa.edu/~dwjones/ 

[^1b]: For example, the decimal number 188 can be written as `BC` in hexadecimal, and 123 as `7B`. You can convert between decimal, binary, and hexadecimal using any online converter.

Early in the history of information technology, programmers came up with the hexadecimal representation of binary numbers, because it's much more easy for humans to read. As a 16-base system, you basically count normally from 0 to 9, but continue with the letters A to F to represent the numbers from 10 to 15. For example, `A` = 10, `B` = 11, `C` = 12, and so on. The trick with hexadecimal numbers is that you need just two symbols to represent one byte (i.e. any number between 0 and 255).[^1b]

Another very old way to represent text is the ASCII encoding. ASCII uses only 7 bits and can therefore represent 128 different characters, 95 of which are used for the most common letters and special characters. Here, too, numbers are assigned to the letters, just as in the EBCDIC. Each letter or character is assigned a number between 0 and 127. For example, the letter **A** (capital) is assigned the number `65`. As you already know, we don't use the decimal system (0 to 9) to express numbers in bit encoding, but instead use the binary system, using just the two digits `0` and `1`. So the numerical value `65` of our letter **A** is expressed as the binary value `01000001` (or `41` in hexadecimal, if you prefer). Therefore, a longer text in ASCII encoding is ultimately a long chain of ones and zeros. The sentence "What are data?" is represented as a sequence of 1s and 0s in ASCII: `01010111 01101000 01100001 01110100 00100000 01100001 01110010 01100101 00100000 01100100 01100001 01110100 01100001 00111111`.[^5]

Nowadays, most texts are represented in UTF-8 and similar encoding schemes, because ASCII worked only for Latin-based, western languages. UTF-8 and similar unicode systems are also 8-bit encoding schemes, but capable of expressing non-western languages and also mathematical symbols and even emojis! 😃 

[^3]: Haigh, T. (2023). _Defining Digitalities I: What’s Digital about Digits?_  <https://doi.org/10.25819/ubsi/10259>
[^5]: Many web-based converters allow you to switch from ASCII to binary and back, for example this one: https://www.rapidtables.com/convert/number/ascii-to-binary.html

We have seen that in a simple 16 x 16 coordinate system, all 256 positions can be represented by a number. This number can be expressed as a binary value of 8 bits (one byte) in length. Using this idea, we can also map simple shapes. Imagine that we just specify each position that carries some colour. Now we can represent simple geometric shapes, like a circle. Again, we would specify the positions (or their numerical values, respectively) of the fields that are coloured, represented by red dots in the grid below:

![Circle in 16 x 16 grid](/assets/images/data-criticism/16x16Circle_table.jpg)

This principle of representing single pixels with numeric values is also how 8-bit grayscale works. In this scheme, there are 256 shades of grey between white and black. To implement this, just imagine that each field in our 16x16 grid has now the numerical code for a specific shade of gray assigned to it. Colors can also be represented in this way, using the 8-bit [RGB scheme](https://www.rapidtables.com/web/color/RGB_Color.html), which assigns 256 different intensity levels to each of the three primary colors red, green, and blue — resulting in over 16 million possible color combinations. Of course, the bigger our grid gets, the higher the resolution of our image will be!

But it's not just images that can be stored as digital data using bits (zeros and ones); music and sound recordings can too. Let's look at our 16x16 matrix again. This time, imagine that the x-axis divides a piece of music into 16 parts (i.e. time units, like seconds, for example), and the y-axis represents the sound frequency (0 for lowest, 16 for highest tone). The time period we apply to the x-axis (the sampling rate) and the subdivision of the frequency heights determine how many different sounds and tone sequences we can represent. Give it a [try!](https://8bitcomposer.com/) 

We humans might find the binary system difficult to understand, but for computers it is the perfect language because it lets them understand and express everything you can think of. As we have seen, zeros and ones can represent texts, images, sound, and any combination of these. They can be stored on punch cards, hard drives, CD-ROMs, USB drives, or any other storage available (but you can only interpret your data as long as you know the encoding). Binary digits can also represent the logical operators "AND," "NOT," "OR," and their combinations. In consequence, our chains of 0s and 1s can not only represent data of any kind, but also sequences of instructions and procedures, which can be used to represent logical circuits and combined to build complex switching systems. In other words: `0`s and `1`s can also represent [algorithms](https://www.geeksforgeeks.org/dsa/introduction-to-algorithms/) and [programs](https://www.geeksforgeeks.org/computer-organization-architecture/what-is-a-computer-program/)! 

We have seen that even an 8-bit encoding scheme can represent a wide variety of content and information as digital data. Modern computers can store more and more information and can process things more quickly, which, along with the rapid increase of communication speeds and bandwidth, makes our present digital world possible. But it all works on the same basic principles.

The choice of encoding scheme is not something we usually think much about when dealing with digital data and objects. However, it is important to keep in mind that it is a choice which determines what can be done with the data. Remember, ASCII excluded non-western characters and symbols (ASCII Imperialism). Storing and transmitting an image in a higher or lower resolution, in grayscale or RGB, can have effects on the accuracy of the representation of real-world objects. Consequently, the encoding scheme and its effects are something we should be critically aware of.  

What have we learned? Digital data can be used to create representations of text, image, sound, and so on. The specifics of their technical implementation ­- what resolution, 8-bit, 16-bit, 32-bit encoding, the schemes and code tables - are conventions that have emerged historically. If you (or your computer) know the encoding and have appropriate software to interpret any sequence of `0`s and `1`s, you can display and manipulate it. 

### Data-sets
Having understood how computers store and represent information at the most basic level, we can now look at how data is used to _describe_ the world around us.

In addition to directly representing a certain information object digitally in a bitstream, like a digital version of a given text or an image, data are also used to describe objects (because most phenomena in our world cannot be directly digitized). For example, next to the text itself, we could annotate it with further information such as the language of the text, the name of its author, and so on. Or think of entities like animals, people or historic events: there is no way to represent them in a bitstream, but we can describe them in a text or take a picture of them (or both) and digitize these descriptions. To illustrate descriptive data, think of a wanted poster as you might know from western movies or comics, which is basically just a simple table listing a number of attributes to identify a given person:

![Wanted Poster](/assets/images/data-criticism/wanted-poster.jpg)

Person:
|Attributes|Value|
|:-:|:-:|
|Attribute 1|"..."|
|Attribute 2|"..."|
|Attribute 3|"..."|
|Attribute 4|"..."|

This table now describes a person, listing some of the attributes and the corresponding values we might consider useful for identifying it. Obviously, our choice of attributes would be different if we wanted to describe something else, like a place, or a piece of art, or an animal, or a book. This selection is often called _descriptive categories_, because, for identifying a fugitive criminal, for example, her or his favorite dessert might not be the most significant identifier, especially if we can list only a limited number of them on our wanted poster. 

But what would we do, if we wanted to collect information on several historic persons? If you imagine tilting our two-column table to the right, the attributes become column headers and we can add more rows to it, each one describing one person:

|first_name|last_name|year_of_birth|place_of_birth|author_of|gender|number_of_children|is_still_alive|
|:---|:---|:---|:---|:---|:---|:---|:---|
|Karl|Value 2|Value 3| Value 4|Value 5|Value 6|Value 7|Value 8| 
|...|...|...|...|...|...|...|...|
|...|...|...|...|...|...|...|...|

All kinds of properties can be recorded as data and can be used to describe any phenomena or objects. To put it simply, we can picture data collections of any kind as tables and spreadsheets. The features that we want to record form the attributes or categories in the header and the respective values are entered below row by row for each individual object. The pre-defined list of properties you want to capture on a given group of objects or phenomena is called the _data model_. The quality of any data model is determined by its usability for a given purpose: you want your data to be searchable, accessible, findable, and easy to process, present and communicate.
We rarely, if ever, encounter data in the singular. Most of the time, we talk about a data set, like in the tables we have seen above. The individual entries in it are called data points, such as the numerical value that represents the letter "A" or the string that is the value for the attribute `first_name`. The individual rows of longer tables, for example the historic persons in your table, are commonly called _data records_ or _entries_. Several of them make a _data set_. 

#### Assignment
You've certainly recognized the person on our wanted poster! Now fill in all the information in his row and do the same thing for two more historic persons of your choice.

---

You might have observed that for the various attributes in our table of historic persons, there are different types of values: While the values for the first two columns are clearly textual (often called a "string" like a string of characters), the third column could also be a number ("an integer"). As we only asked for the year, it cannot contain more detailed information like day and month. The fourth column could be a string again, but it could also be a geo-coordinate, like a GPS location. In addition, it is unclear if this column refers to countries, cities, regions, villages, or even specific buildings. In column 5, authorship, you might also have run into trouble, because our first historic person, Karl, was rather productive and was the author of many more than just one text. Column 6 could be a matter of debate: what values would you accept? Just two, or more? While column 7 again takes an integer, column 8 can only hold "yes" or "no" as an answer (in most computational contexts, this is expressed in "Boolean" values: `true` or `false`). What you've encountered here is called _"data types"_. Like the _descriptive categories_ that you should have selected before you begin collecting data, you also need to think of the appropriate data types for each of them.

For different purposes, you might want to employ different attributes in your data sets: if you need to transport or store your items, it makes sense to have information on weight and size. If you create an inventory, capture only the most basic information that allows you to quickly search and find what you're looking for. If you want to detect common elements and relations between different items, gather as much information as possible and carefully select attributes that are applicable to all of the objects you want to describe. 

If you want to share your data with others, you have to make sure that your attributes and categories adhere to common types. However, if you want to sort your data and search for comparable features and connections, you will need to make sure that your data entries also follow pre-defined rules in terms of capitalization, spelling, and so on. These rules are commonly called the **data schema**. There are quite a lot of different schemas out there, each one tailored for the description of specific objects and phenomena and for specific purposes. What they do have in common, however, is that their schema has to be specified in what is called an "ontology" or "vocabulary". These basically list all the attributes you can use. 

A very common data format is JSON (Java Script Object Notation). Below you see a listing of the data types it can store:
| **Type**    | **What it means**                                          | **Example in JSON**                                            | **Formatting notes**                                                                                |
| ----------- | ---------------------------------------------------------- | -------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **string**  | A piece of text, always in double quotes.                  | `"firstName": "Karl"`                                          | Always use **double quotes `"..."`** for text (not single quotes).                                  |
| **integer** | A whole number (no quotes).                                | `"year": 1867`                                                 | No quotes around numbers.                                                                           |
| **number**  | A number that can have decimals.                           | `"rating": 4.5`                                                | Same rule: no quotes.                                                                               |
| **boolean** | A truth value: `true` or `false`.                          | `"isAlive": false`                                             | Must be lowercase (`true`, not `True`).                                                             |
| **null**    | No value (empty).                                          | `"middleName": null`                                           | Must be lowercase `null`.                                                                           |
| **object**  | A collection of key–value pairs inside curly braces `{ }`. | `"birth": { "date": "1818-05-05", "place": "Trier" }`          | Keys and values are separated by a colon `:`. Multiple entries are separated by commas.             |
| **array**   | A list of values inside square brackets `[ ]`.             | `"occupations": ["Philosopher", "Economist", "Revolutionary"]` | Values are separated by commas. Arrays can contain strings, numbers, objects, or even other arrays. |

JSON is widely used for annotation and transfer in the humanities because it is easily readable and customizable. It can be used to describe all sorts of objects/entities, including historic persons. Below is a short dataset describing our old friend Karl in JSON:
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
You see that it is in some way the same as our table above, only that it presents our data in sequential form (because, as you know now, computers store all data that way) and it allows "nested" structures for the entries. You also see that it uses quite a lot of different containers (or "drawers" or "boxes") to store data points: quotes `" "`, curly brackets `{  }` and square brackets `[  ]`. In addition, the entries are separated by commas `,` and the lines are indented so that the data sets are nested into each other. The formatting rules of JSON are quite strict; if you mess up a comma or indentation of a line, it cannot be processed. JSON is used for a wide range of different data, each having a specified data schema. For historians and humanists it is wise to use a schema that is established by many others. However, you can of course write your own schema. For a comprehensive tutorial, see [here](https://json-schema.org/learn). If you're lazy, you might as well use one of the many online schema generators, like [this one](https://www.jsonforge.com/tools/schema-generator) or [this one](https://jsonswiss.com/). 

#### Assignment
Above, you've created a small table describing a historic person. Let's see if you can do this in well-formed JSON!
But how do you know if you produced valid and pretty JSON? Just copy it and paste it into one of the many online checkers, like [this one](https://jsonchecker.com/). There are many others out there that help you correct your errors, but before you use [one of them](https://jsonformatter.curiousconcept.com/), try to spot your error yourself!

---
You've seen that JSON goes way beyond just the encoding (which usually is UTF-8). In addition, it consists of very concise and strict rules on the structure and form of all data contents. Finally, if you store your JSON data, you will append `.json` to the name of your file. JSON is a format. Other than encoding, formats specify also things such as the visual depiction of data, which software can do what with it, how it will be stored on your computer, and so on. As with encoding, the format of a given data file is something that we can think of critically: some file formats are proprietary, they can only be read and manipulated with a certain software. Some formats are more easily convertible, or allow interchange more easily than others. If you want your data to be _interoperable_, that is, if you want to enable others to work with them, you need to format them in open formats. So for tables and spreadsheets, for example, use the _comma-separated values format_ (`.csv`), for text use _markdown_ (`.md`), and so on. You can find a list of open and interoperable file formats [here.](https://en.wikipedia.org/wiki/List_of_open_file_formats)

What have we learned? Data can be used to describe all kinds of objects and phenomena. To do so effectively, we need to select the right _descriptive categories_ (=attributes), choose appropriate _data types_ for each, and make sure everything conforms to a _data schema_ and file format — like JSON.

### Databases
We have seen that we can store all kinds of information in tables. For a comprehensive and critical analysis, we want to capture and study our sources from many different angles, collecting a great variety of information. However, coherence and clarity would get lost if we stuffed everything into one single table. But if we create many tables, how can we discover relations then? Because, after all, we're interested in discovering connections, patterns, and correlations. Relational databases allow us to do precisely that! They are capable of storing a great variety of different data and their respective database management systems (DBMS) enable us to perform the basic sorting, filtering and searching operations that build the foundation of research and analysis.

#### From sources to databases
To gather our research data, we will first have to extract it from the primary sources. 
Let's look at the following source as an example, an article written by Karl Marx for the New York Daily Tribune, published in 1857. You can find it on the web [here](https://www.marxists.org/archive/marx/works/1857/04/10.htm) or via the Wayback Machine [here](https://web.archive.org/web/20260000000000*/https://www.marxists.org/archive/marx/works/1857/04/10.htm). 

![Source: "Whose Atrocities?"](/assets/images/data-criticism/source_full.jpg)

First of all, we notice that we could obviously treat this source on three different levels: On the one hand, we're dealing with a website. On a different level, it is an excerpt from an edited volume assembling Marx's writings for the New York Daily Tribune that was published in 1951. Finally, we could also treat it as an article that appeared in said newspaper on April 10, 1857. This is how these different types are displayed in Zotero[^6]:

![zotero entries](/assets/images/data-criticism/zotero_entries.jpg)

The same source would look like this if captured in Tropy[^7]:
![tropy_screen](/assets/images/data-criticism/tropy-object.jpg)

[^6]: Zotero is a very useful and popular software for managing bibliographic information, basically a database. It can import and export all of the most common data formats for bibliographic data. (If you do not yet use Zotero, head to its [webpage](https://www.zotero.org/) and download the appropriate version for your system.) You can see that Zotero lets you enter additional information on your source, depending on how you want to treat (and further analyse) it: website, chapter in an edited volume, or newspaper article. You can also attach keywords ("tags") that will make it easier to create collections of sources on similar subjects.

[^7]: [Tropy](https://www.tropy.org/) is a similarly useful software, designed to help you organize your research findings, particularly photos. It is enormously helpful if you work in an archive and take pictures of historical records and documents that you want to analyze and sort later on.

Our job here is to capture all names of people, places, dates, and events in this source. This process can be automated to a certain extent and is called "Named Entity Recognition" (NER). We do it by hand. Of course we could store the entities in the paragraph just in one spreadsheet, but let's imagine we will extract information from many different sources or an entire corpus (for example all of Marx's writings, or all English newspaper articles on China concerning the Opium Wars). If we just have a look at the first few sentences, we encounter already a lot of information.

![first paragraphs](/assets/images/data-criticism/source_zoom.jpg)

We find several names, each with an office or title, the respective institutions, as well as references to historical events yet to be clarified. In addition, we could look up all these entities and acquire additional information on dates and times and various places. This is a lot of information already. If we wanted to cram all that information into a single table, it would become huge and difficult to work with. That's why we want a relational database.

A single, well-kept spreadsheet is perfectly fine for one source. But the moment you start working across multiple sources — ten newspaper articles, a set of parliamentary reports, diplomatic correspondence — a spreadsheet becomes a liability. Every time Palmerston appears in a new row, you retype his name, role, and dates. One inconsistent spelling ("Palmerstoon") makes him invisible to a search. Correcting his title means hunting through hundreds of rows manually.

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

### Reading/viewing suggestions
- Octave Julien. Creating and using databases in medieval history: historiography, concepts and practice. Seminários do GIHM, Apr 2024, Porto, Portugal. ￿halshs-04550456￿
- Stephen Robertson. "The properties of digital history".     [https://doi.org/10.1111/hith.12286]( https://doi.org/10.1111/hith.12286)
- Mattia Viale. "From the historical source to a database: a short story". 21 November 2018. [https://refashioningrenaissance.eu/from-the-historical-source-to-a-database/](https://refashioningrenaissance.eu/from-the-historical-source-to-a-database/)
- [Agustín Cosovschi, From Sources to Data: Designing a Database for the Humanities and Social Sciences with nodegoat](https://programminghistorian.org/en/lessons/designing-database-nodegoat)

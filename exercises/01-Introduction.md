# Introduction exercise
## date: 2021-01-08

## 1. Turn on a timer

Remember that I want us all to keep track of our time!


## 2. Find a text on [archive.org] or hathi with the following characteristics

a) has something to do with your interests, but is not _the_ principal source that you want to work on this semester 
b) has a messy, auto-recognized plain text version
c) contains some sort of list or table that you will be able to treat as "tabular" (i.e. spreadsheet) data


## 3. Copy that text into Sublime Text (or some other text editor)

You can find the plain text version various ways, including by selecting text on a pdf. When you paste it into Sublime text, all of the hidden codes that something like Microsoft Word contains will be stripped out. Then you can proceed to manipulate the text for research purposes, using regular expressions and the like

Plain text is a format that works in all kinds of applications. It can be opened in word processors, for example.

Typical extensions on plain text files is .txt, .csv, .tsv. CSV and TSV (Comma and Tab separated values) can be read in spreadsheet programs, as well as in Sublime Text.


## 4. Do some cleaning with Regex

This is purely experimental. But if you find junk (empty pages, page headings, etc) you can recognize and remove it.


## 5. Paste the big plain text file into Voyant, and use its tools to "diagnose" the content of your text.

Voyant treats the text as a "bag of words," paying no attention to syntax or meaning. It offers you metrics to characterize and navigate this undifferentiated bag of words.


## 6. Work with the list or table that you've found, in order to get it into Palladio

This is probably the most difficult part of the exercise. In order to make your list or table digestable, you have to parse the plain text into columns. In plain text documents, it's usually most convenient to differentiate those columns with tabs. Then that columned data can be pasted into Palladio and manipulated.

Here's a simple example. Say you had a list of names like this: `John Doe, Jane Doe, Joey Doughy`.

If you replace every `, ` (comma space) with a line break (`\n` is the regular expression), then replace every space (i.e. between first and last name) with a tab (`\t`) you will have something like this:

```
John	Doe
Jane	Doe
Joey	Doughy
```

This is a table that you can then paste into Palladio. Then, use palladio to explore the list.

Programming historian has a great introduction to regular expression work of this sort: Laura Turner O'Hara, "[Cleaning OCR’d text with Regular Expressions](https://programminghistorian.org/en/lessons/cleaning-ocrd-text-with-regular-expressions)," The Programming Historian 2 (2013), https://doi.org/10.46430/phen0024.


## 7. Summarize what you've found (and how you got there) in a one-page document, with screenshots of tables or the like if appropriate, and send it to me by Tuesday night.

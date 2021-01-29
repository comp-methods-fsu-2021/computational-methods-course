## Exercise 4: Cleaning

This week we're going to begin to cleaning our files to prepare them for manipulation.

Think about cleaning on three levels:

### 1. File
At the level of the file, aim to identify the most useable unit. For some of you, this will be a volume. For others, volumes should be broken into issues. For some, it will be a single poem. Whatever the case, make sure that your filename has an extension, and that there are no white spaces in the file name.

Whether your metadata is listed in the file header or in a separate tabular file, make sure that you record as much information as you can about each file:
- source facimile
- url
- author
- date
- page count

### 2. Line
Think carefully about how your text file should be structured. For some of you, each line in the file should be a line on the printed page. For others, a line in the file should be a paragraph on the printed page. Imagine that your lines correspond to lines you'd like to see in a spreadsheet for quantitative analysis.

To do this work, use regular expressions to find line breaks that you want to eliminate or introduce.

For example, to remove mid-sentence line breaks, try a case-sensitive search for `([a-z]) ?\n(?=[a-z])` and replace it with `$1 `. There will certainly be errors and mis-steps. Use them to learn more about the patterns in your text.

Sublime Text lets you apply find and replace to all of the files in a folder in one go using "Find in Files" under the Files menu. Be careful not to make 10,000 mistakes! Try your find and replace on a sample first. 

### 3. Intermediate divisions
The most challenging and useful part of this exercise is to discover intermediate divisions within your file and to isolate and identify them with unambiguous tags. Are separate articles introduced with a pattern, such as a double line break or a headline in ALL CAPS? How are page headers formatted? Where are the page numbers? Find them and mark them with unambiguous codes that you can find again.

### Documentation
In a separate file, keep a record of the expressions that you used to clean your text. You will want to find them again in the future!

Also, begin to map the structure of your text's intermediate divisions.

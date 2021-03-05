# Computational Methods in the Humanities
## Will Hanley, whanley@fsu.edu
### HIS 6934-0003, Wednesday 9-12

This course is a practical introduction to computational research methods. It trains graduate students in digital analysis of the kinds of primary materials used in history, literature, religion, classics, and related fields. Students will learn to transform closed textual materials (such as PDFs and microfilms) into open formats, then experiment with methods to analyse and enrich those materials. Students are encouraged to work with primary materials from their own specialized fields of research focus. We will also do some limited reading of theoretical work related to the methods we learn. Prior knowledge of computational methods is not required.

## Course Objectives
By the end of this course, students will have

- gained practical experience with dozens of tools (both simple and complex) that deploy computational research methods, and be able to articulate opinions on the virtues and limitations of these tools
- practiced conceiving of the data potential of certain primary sources in their field, and experimenting with that potential
- learned different formats for the presentation and visualization of data, and to articulate critique of data presentations appearing in the secondary literature
- developed confidence to follow tutorials and ask questions related to their computational research needs
- produced a web presence (including a website) showcasing the products of their research

### Note on graduate tracking:
This is a methods course, but for the purposes of graduate tracking, it can instead be assigned to a regional or topical field if your work focuses around content in that field. To do so, satisfy these conditions: a) in week 2, choose a source rich in content from the field, b) produce a website ably deploying that source in its rich context, and c) secure the permission of the appropriate member of your committee (with whom I will be happy to communicate, if you ask).

## Required Materials
### In hard copy:
- Claire Lemercier and Claire Zalc, [*Quantitative Methods in the Humanities: An Introduction*](https://www.upress.virginia.edu/title/5168) (University of Virginia Press, 2019). [companion website](https://quanthum.hypotheses.org/) [FSU libraries ebook](https://ebookcentral-proquest-com.proxy.lib.fsu.edu/lib/fsu/detail.action?docID=5662549)
- Ted Underwood, [*Distant Horizons: Digital Evidence and Literary Change*](https://press.uchicago.edu/ucp/books/book/chicago/D/bo35853783.html) (University of Chicago Press, 2019). [FSU libraries ebook](https://www-degruyter-com.proxy.lib.fsu.edu/chicago/view/title/559905?tab_body=toc)
- Kieran Healy, [*Data Visualization: A Practical Introduction*](https://press.princeton.edu/books/hardcover/9780691181615/data-visualization) (Princeton University Press, 2019). [companion website](https://socviz.co/)

### Online:
- Ruth Ahnert, Sebastian E. Ahnert, Catherine Nicole Coleman, and Scott B. Weingart, [*The Network Turn*](https://www.cambridge.org/core/elements/network-turn/CC38F2EA9F51A6D1AFCB7E005218BBE5/core-reader) (Cambridge, 2020).
- Catherine D’Ignazio and Lauren Klein, [*Data Feminism*](https://data-feminism.mitpress.mit.edu/) (MIT Press, 2020).
- [*The Programming Historian*](https://programminghistorian.org/)

## Grading
**Weekly exercises (5% per week) 70%**

Each week's meeting will begin with a review of the previous week's exercise. You will submit the deliverable by midnight on the night before class. You will document your work process (including a precise accounting of the time you spent on each step), and offer a brief assessment of the research potential and problems you see in the exercise, as well the next steps you might pursue. These exercises will be graded on a completion basis. Satisfactory work receives full marks. Unsatisfactory work can be resubmitted until it is satisfactory.

**Website 30%**

Every student will produce a website containing her or his transformed and enriched primary material, analysis, and documentation. This is a cumulative, standalone, public project; it is not an amalgam of the weekly exercises. It is a showcase of the skills you build and the research sensibilities you bring to your work. It will include discussion, where appropriate, of secondary literature on computational methods (including material we read in class). The website will be due at the end of the semester, and will be given a letter grade (i.e., it will not be graded on a completion basis).

## Schedule

### Jan. 6: Introduction

**Exercise:** Find a text of interest to you already in rough digital form, e.g. from [archive.org](https://archive.org/); perform quick transformations, using simple web-based tools. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/01-Introduction.md)

**Suggested tutorial** (ignore for now the second half of the lesson, which uses the Python programming language): Laura Turner O'Hara, "Cleaning OCR’d text with Regular Expressions," The Programming Historian 2 (2013), https://doi.org/10.46430/phen0024.

**Quick Tool:** [Sublime Text](https://www.sublimetext.com/), [Regexr](https://regexr.com/), [Voyant](https://voyant-tools.org/), [Palladio](http://hdlab.stanford.edu/palladio/)

---

### Jan. 13: Corpora

**Exercise:** Identify a texual primary source in closed format and transform it into plain text. Students are encouraged to identify a source from their own field of interest that includes quantitative as well as qualitative material (ideally in the form of lists). A great example of a data-rich source with broad coverage is the [*Almanach de Gotha*](https://catalog.hathitrust.org/Record/001597627) (1763-1944), in French and German. English language equivalents, for those interested in names lists, include [*Burke's Peerage*](https://catalog.hathitrust.org/Record/000056027) (UK, from 1826) and [*Social Register*](https://catalog.hathitrust.org/Search/Home?lookfor=social%20register&searchtype=title&ft=ft&setft=true) (US, from the 1880s). [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/02-corpus.md)

**Reading:** Lemercier and Zalc, Introduction, Chs. 1 & 2.

**Quick Tools:** Adobe Acrobat, Google Docs

---

### Jan. 20: Infrastructure
**Exercise:** Sign up for various computational services, and post material from last week's source to Github and Wikipedia. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/03-services.md)

**Reading:** Lemercier and Zalc, Ch. 3.

**Slow Tools:** Github, Stack Overflow, Wikipedia, Zenodo, Wikidata

---

### Jan. 27: Cleaning I
**Exercise:** Post a cleaned open format version of your primary source, regularized using regular expressions. Post a file documenting the cleaning process. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/04-cleaning.md)

**Reading:**
- Ryan Cordell, “‘Q i-Jtb the Raven’: Taking Dirty OCR Seriously.” Book History 20, no. 1 (October 25, 2017): 188–225. https://doi.org/10.1353/bh.2017.0006.
- Katie Rawson and Trevor Muñoz, "Against Cleaning" (2016). http://curatingmenus.org/articles/against-cleaning/

**Suggested tutorial:** Dennis Tenen and Grant Wythoff, "Sustainable Authorship in Plain Text using Pandoc and Markdown," The Programming Historian 3 (2014), https://doi.org/10.46430/phen0041.

**Quick Tool:** [Regular expressions](https://regexr.com)

---

### Feb. 3: Open Format Data I
**Exercise:** Post a cleaned, regularized set of tabular data derived from a transformation of your primary source. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/05-tab-data.md)

**Reading:**
- Lemercier and Zalc, Ch. 4.

**Quick Tool:** Google Sheets, Microsoft Excel, [Breve](http://hdlab.stanford.edu/breve/)
**Slow Tool:** [Open Refine](https://openrefine.org/)

---

### Feb. 10: Visualization I
**Exercise:** Share a range of visualizations of your primary source. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/06-visualiztion.md)

**Reading:** Healy, Preface, Ch. 1.

**Quick Tool:** [Raw Graphs](https://app.rawgraphs.io/)
**Slow Tool:** [Tableau](https://public.tableau.com/en-us/s/), [Google Data Studio](https://datastudio.google.com/overview)

---

### Feb. 17: Quantification I
**Exercise:** Share an R workbook visualizing material from your primary source.

**Reading:** Healy, Chs. 2-3.

**Slow Tool:** [R Studio](https://rstudio.com/), its [Cheatsheets](https://rstudio.com/resources/cheatsheets/)

---

### Feb. 24: Sharing I
**Exercise:** Make a preliminary version of your Hugo or Jekyll website live. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/08-website.md) [Instructions addendum (Hugo)](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/08-01-hugo-website-osx.md)

**Reading:** Amanda Visconti, "[Building a static website with Jekyll and GitHub Pages](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages)," _Programming Historian_.

**Slow Tool:** [Hugo](https://gohugo.io/) or [Jekyll](https://jekyllrb.com/)

---

### Mar. 3: Text Mining
**Exercise:** Produce word frequency comparison between your primary source and appropriate reference sources. [Instructions](https://github.com/comp-methods-fsu-2021/computational-methods-course/blob/master/exercises/09-mining.md)

**Reading:** Underwood, Preface, Chs. 1 & 2, Appendices A & B

**Quick Tool:** [Voyant](https://voyant-tools.org/), [TopicModelingTool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)

---

### Mar. 10: Categorization
**Exercise:** Upload some data byproducts to Wikidata.

**Reading:** D’Ignazio and Klein, Introduction, Chs. 1-4; Underwood, Ch. 4.

**Slow Tools:** SPARQL, Wikidata

---

### Mar. 17: Open Formats II
**Exercise:** Enriched, cleaned primary source posted to website.

**Reading:** D’Ignazio and Klein, Chs. 5-7; Underwood, Ch. 3; Ahnert et al., Introduction and Part I.

---

### Mar. 24: Quantification II
**Exercise:** Enriched, cleaned data tables derived from primary source posted to website.

**Reading:** Healy, Chs. 4-5; Underwood, Ch. 5.

---

### Mar. 31: Cleaning II
**Exercise:** Documentation posted to website.

**Reading:** Ahnert et al., Parts II and III, epilogue.

---

### Apr. 7: Visualization II
**Exercise:** Data visualizations and workbooks posted to website.

**Reading:** Healy, Chs. 7-8.

---

### Apr. 14: Sharing II
**Exercise:** No weekly exercise is due following this class. The final version of websites will be due at the end of the following week (April 23).

## Policies:

### 1. Attendance Policy:
Attendance will be taken at each meeting, and every missed class is counted in the participation grade. University attendance policy: excused absences include documented illness, deaths in the family and other documented crises, call to active military duty or jury duty, religious holy days, and official University activities. These absences will be accommodated in a way that does not arbitrarily penalize students who have a valid excuse. Consideration will also be given to students whose dependent children experience serious illness.

According to FSU policy, you must be present on the first day of class or you will be automatically dropped from the course. If you miss a class, you are responsible for getting the material. I will answer specific questions, but I will not re-teach any lecture or give the notes for it.

### 2. Missed Assignment Deadlines or Meetings:
Late work loses ten percent per day. In the case of a personal or family emergency, you must contact the Dean of Students at 644-2428. I will receive official notification from them if your absence is to be excused. For missed deadlines, if the instructor deems the excuse valid, you will receive up to one week to complete the assignment. Missed assignments due to unacceptable reasons will result in a failure for that exam or assignment.

** Students in difficulty can find help from:** Dean of Students (https://dos.fsu.edu/; 644-2428), University Counseling Center (https://counseling.fsu.edu/; 644-2003), University Health Services (https://uhs.fsu.edu/; 644-6230), Victim Advocate Program (https://dos.fsu.edu/vap/; 644-7161).

### 3. Academic Honor Policy              
With all assignments at FSU, the Academic Honor Code applies. You are expected to be familiar and abide by the University’s Academic Honor Code, found at http://fda.fsu.edu/Academics/Academic-Honor-Policy. The Florida State University Academic Honor Policy outlines the University’s expectations for the integrity of students’ academic work, the procedures for resolving alleged violations of those expectations, and the rights and responsibilities of students and faculty members throughout the process. Students are responsible for reading the Academic Honor Policy and for living up to their pledge to “. . . be honest and truthful and . . . [to] strive for personal and institutional integrity at Florida State University.” Failure to abide by the Honor Code could result in a “0” for the assignment, an “F” for this course, and/or possible dismissal or suspension from the University.

### 4. Sexual Discrimination and Misconduct              
"No person in the United States, shall, on the basis of sex, be excluded from participation in, be denied the benefits of, or be subjected to discrimination under any education program or activity receiving Federal financial assistance." Title IX of the Education Amendments of 1972, and its implementing regulation at 34 C.F.R. Part 106 (Title IX).
As a recipient of Federal financial assistance for education activities, FSU is required by Title IX to ensure that all of its education programs and activities are free from discrimination on the basis of sex. Additionally, the Florida Educational Equity Act prohibits discrimination in schools based on race, ethnicity, national origin, gender, disability, or marital status. FLA. § 1000.05 (2012). Furthermore, this commitment is reaffirmed in FSU's Equal Opportunity and Non-Discrimination Statement and the Title IX Statement, which are applicable to all faculty, staff, students, visitors, applicants, and contractors. Sexual discrimination includes sexual misconduct (sexual violence, stalking, intimate partner violence, gender based animosity and gender based stereotyping). If you have questions about Title IX or wish to file a Title IX complaint, please visit the FSU Title IX website: www.titleix.fsu.edu or call Jennifer Broomfield, Title IX Director 850-644-6271.  Please note that as Responsible Employees, all faculty are required to report any incidents of sexual misconduct to the Title IX Office.

The Victim Advocate Program at FSU has a confidential advocate on call twenty-four hours a day to respond to FSU students, faculty, and staff who are victimized, or any other person who is victimized on our campus, or by an FSU student. Daytime Phone: 850.644.7161, 850.644.2277, or 850.645.0086. Nights, Weekends & Holidays 850.644.1234 (FSUPD) Ask to speak to the on-call advocate.  

### 5. Americans with Disabilities Act:              
Students with disabilities needing academic accommodation should:
1. register with and provide documentation to the Student Disability Resource Center; and
2. bring a letter to the instructor indicating the need for accommodation and what type.

Please note that instructors are not allowed to provide classroom accommodation to a student until appropriate verification from the Student Disability Resource Center has been provided.   

This syllabus and other class materials are available in alternative format upon request.
For more information about services available to FSU students with disabilities, contact the Student Disability Resource Center, 874 Traditions Way, 108 Student Services Building
Florida State University, Tallahassee, FL 32306-4167. Telephone: (850) 644-9566 (voice); (850) 644-8504 (TDD). Email: sdrc@admin.fsu.edu Website: http://www.disabilitycenter.fsu.edu/

### 6. Syllabus Changes:
Except for changes that substantially affect implementation of the evaluation (grading) statement, this syllabus is a guide for the course and is subject to change with advance notice. The instructor reserves the right to make changes to this syllabus, including the schedule of assignments, lectures, and the selected readings. The syllabus posted on GitHub will be updated to reflect changes, and it is the schedule of record.

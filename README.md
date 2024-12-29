# Design Detailed Document

- This document has a description of my work in this software project focused on developing a website, the problems that I encountered while I was making it, and the conclusions or personal thinkings of this project.

## Description

- The website follows a basic structure that begins with the index page and gives access to the other 6 pages.

- In the index.html page I began with a basic structure that I had from activity III and activity IV. This structure divides the page in a header that contains the title page, links to other pages of the website and to my university website; a container called content-about, display flex for the main content that I used to very briefly describe the website; and a menu section where I included a footer section and some links to my GitHub repository and to my LinkedIn. This basic structure has been used for all the pages in the website.

- In the degree.html page, I investigated my own degree and asked myself why I'm studying it and which is the objective of the University for this degree. Later, I looked at the way my degree is made; for this, I looked at the subjects in the UFV website and the goals of each subject. With this information I made a table with the goals of the subjects that I have in the different years and semesters. To make this possible, I created a table-row with four cells for the years, inside each cell I created another table with two cells for the semesters, and I also created a new row in each year with two cells to make a list for the different subjects under the different semesters.

- For the FCE.html page, I made a deeper investigation of the subject "Fundamentals of Computer Engineering" looking at the UFV subject pages, the canvas of the subject and my personal opinion. Afterwards, I wrote the main contents of the course that are divided into theorical and practical contents, and I also wrote about the goals that it has, the learnings this subject gives to the students, and the activities done in the class. I made it with headings, paragraphs and lists configured by CSS file.

- In the about.html page, I described myself, talked about some of my interests and carachteristics, included a photo through a root to the images folder and shaped its size with a class in CSS file. Afterwards I made my own curriculum vitae in a container built in the CSS file with flex display and a row flex direction to divide the curriculum in two parts. The container of the curriculum is made by two containers controlled by the CSS file, one with my photo configured with certain radius with a class in the CSS file, work situation and some ways to contact me. And the other part with my studies, skills, languages, certifications and some volunteering where I worked.

- In the net.html page I created a table whose borders aren't visible since the border color is equal to the background color, each row of the table has a link to one of my classmates websites.

- For the contact.html page I created a form for the name, email and the message of the person who wants to get in touch with me. I configured the form in order to have some information display and space for the input text with certain font-size configured by different classes in the CSS file. Besides, I created a button but it doesn't send any information.

- Topic.html file has my investigation about "Mus" like how it is played, its history and some terms or signals. All the information is  diplayed in the main content area through headings, paragraphs and unordered lists. There are some photos that show the mus plays and the mus signals for a better understanding of the game.

## Problems during the development

- At the moment of doing the header, I had a problem to make the UFV logo and the header title be at the same heigth, the reason was that I wanted the title in the center of the header and the logo in the right part of the header. To resolve this, I justified the header content with space-between and moved the title to the center with a left margin in the header title container. 
- The second problem I encountered was the position of the point in unordered lists. The problem was that they appeared on the left part of the container where they were positioned. To resolve this, I searched in internet pages like ENIUN and found an easy command to resolve it.
- The third problem came when I was doing the different tables of the degree page. Due to the border of the tables, the design was ugly, but I resolved it with the border-collapse.
- Another problem I discovered appeared when I didn't have enough content in a page to use all the screen height. The height that I didn't use didn't have any class and is a white space. To resolve this, I tried things like putting html height at 100%, but this solution changed the magnitude of other elements getting the website worse. So I decided to leave this space.
- There was other problems that I solved in an easy way with the use of the command ctrl+mays+i in the webpage. For example, at the moment of centering the titles of the header, I used this command to know how many margin I needed to center them in a quick way


## Conclusions

- When I began this project I realised that I didn't have a lot of knowledge about html and CSS. However, after this activity, I consider that I have gained a good control in CSS and html, but I should still improve many things.
- After spending many hours with this project, I have got a taste for software development for webpages and learnt a lot. For this reason, I think that this project is a very good idea for beginners on the software development area. Even though this project has frustrated me more than once, after completing the whole project I feel that it can help me a lot in the future.
# Movie-Theater-Website-Project
<h2> Introduction </h2>
<p>This is a project that I have worked on during my time at The Tech Academy. It is a website for a sample Movie Theater Client using MVC/MVVM Web Application in C#, along with Bootstrap and Entity Frameworks. It was a great opportunity to work on both the back and front end of a project. I was able to jump into a project that had already been started and pick up/improve upon some things that needed tweaking. Whether it was working on styling pages or adding CRUD (Create, Read, Update, Delete) functionality, this was a challenging yet rewarding project. I utilized tools like Visual Studio 2019, Azure Devops, and Github, while also communicating with my team through Discord with daily standups and weekly code reviews. I have included some snippets of my work below.</p>
<h2>Front End Development</h2>
Here is my code for the styling of the "About Page" of the theater:<br>

![](/AboutPage.PNG)

<br>
As well as the CSS Styling: <br>

![](/AboutCSS.PNG)
<h2>Back End Development</h2>
Here is a gif of the Rental class with three options for selecting a rental with CRUD functionality. It is a main rental option with two inherited classes: Rental Equipment and Rental Room. There is also the created controller to manage Create, Read, Update, and Delete funcionality. <br>

![](/rentalcontrollergif.gif)

<br>
Additonally, I used some Bootstrap to create and index page that seperates the three components, Rentals, Rental Equipment, and Rental Room, to highlight details about each one for easy user viewing. Users can click on each item to see details, edit them, or delete them. They can also create a new item at the top of the screen:<br>

![](/indexgif.gif)
<br>

Another work item was to edit the "create" page to be able to select which section of option the user would be creating in a Rental, whether it be a rental room or rental equipment. I added dropdown functionality and used Javascript so that only the properties of the selected inherited class would show as an option:<br>

![](/createpage.gif)
<br>


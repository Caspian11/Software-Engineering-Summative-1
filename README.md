# **Software-Engineering-Summative-1**

## **Currency Converter Web App using HTML, CSS and JavaScript**

This project is regarding building a web app currency converter using HTML, CSS and JavaScript code. 
The project has been planned using a hybrid of agile and waterfall modern planning techniques. Using a hybrid approached helped me to complete stages of the project in a linear sequential order but allowing for adaptive planning and improvements on the design.
The project was broken into serveral iterations, accomodating adaptive planning and continuous improvement of the product. A GitHub project planner was used to keep track of the project requirments and progress, assign responsibilities and link with the project.
To allow for accurate tracking of stages in the project, the stages were raised as issues in GitHub and linked to the project.


![GitHub Project Planning Tool](https://user-images.githubusercontent.com/91996898/213866503-cb385aa3-91e5-472d-8143-77793a8e45a2.JPG)

The first step was to decide the web app to be built, as this is my first time in building a web app and using HTML, CSS and JavaScript, i decided to build a currency converter as there are many resources available on this topic.
The second step was to decide which visual design tool to use, i chose to use Figma as i like the simplicity of Figma and the areas of CSS code it offers and Figmas is a free alternative to Jira.
The third step was to create an account and design a simple currency converter outline in Figma. Keep the design simple, so i can move on to the coding of the product. Below is a screenshot of the initial currency converter design in Figma.


![First Figma Design](https://user-images.githubusercontent.com/91996898/213887177-de915e21-35d5-4f1b-ab3c-957eed06a2de.JPG)

Once the initial design was ready, i used Visual Studio Code to write the HTML and CSS code, JavaScript was added at a later date as JavaScript is the functionality and i did not need this to build the visual design of the currency converter. This allowed the project to move forward more quickly as i did not need to build the app end to end before any progress could be viewed.

Figma records the CSS code assigned to each part of design so the CSS code can be reused when coding the web app, this ensures the product coding is the same as the product design in Figma. Unfortunately, figma does not include all of the CSS code or the developer may want to specify an extra feature, this must be written directly into the CSS codespace separetely. The images showing the comparison in codes are included in the GitHub project file list and a pull request was used to perform this. 

### Coding the Currency Converter
Using Visual Studio, i create a HTML file and a CSS file. I documented the link between the HTML file and the CSS file so the design elements could be coded in the CSS file but fed back through to the HTML file. HTML is used to define the structure of a web page, text included in the <body> section of the HTML code will be displayed on the web page, such as where the container should be placed, if there is going to be a header and a date and if the date is placed above or below the header, on the web page. HTML also allows the developer to add in different classes such as the use of a button or boxes requiring user input. 
The CSS file is used to specify the visual design and presentation of the web page, each class in the CSS file is related back to the HTML file, if there isnt a link, there will be no output and the CSS code is useless. The majority of the CSS code can be copied from design tools such as Figma, but the appearance may not be the excat same and will need to be adapted by the developer. After the design elements were coded in Visual Studio i coded the functionality using JavaScript, the initial code was found on https://www.youtube.com/watch?v=6Dk4OEU4oGc&t=417s
The functionality allows the user to select the currency they are converting from and to such as GBP (Great British Pounds) to JPY (Japanese Yen). The JavaScript code is assigned to an API which contains the abbreviations and the full names of all currencies(https://api.frankfurter.app/currencies) and also an API for conversion rates (api.frankfurter.app). The use of JavaScript also requires to be linked back through to the HTML file using <script src="index.js"></script>. JavaScript interacts with HTML and requests the return of requested information. JavaScript is also able to add event handlers to specified elements, the event handlers are fired when the specified action occurrs such as a 'click'. 


### TESTING
I used test driven development by viewing the output of the code on the live server before deciding if the code was correct and how i wanted the design to look. If the design was not correct, i would change the code until the output was correct. I also tested the conversion between currencies viewed in the web app and the conversion between currencies viewed in the

![Caspian Currency Conversion GBP - EUR](https://user-images.githubusercontent.com/91996898/213887962-25d60585-b4a3-45e8-8143-03753ec7b7ad.JPG)


![gGoogle Currency Conversion GBP - EUR](https://user-images.githubusercontent.com/91996898/213887978-d91d3091-26e1-403e-8455-9f51abdcc7f3.JPG)



### Evaluation
The design of my currency converter web app is simplistic in appearance but it does what it is supposed to do which is to supply a conversion rate. The conversion rate is correct as found during test driven development and the helpful feature of the host API (application programming interface). The appearance of the web app could be more responsive and have layers, this would be an enhancement of the current web app. The appearance can be changed by adapting the CSS code and the HTML code. Only the CSS code needs to be adapted if there are no extra visual features to include. If extra conmtainers are to be included, this will need to be reflected in the HTML code. The JavaScript code can be adpated if extra functionality is required.
Coding in HMTL and CSS is not as difficult as i thought it would be, the use of CSS seems to simplify the complexity of HTML, but this is only a small project. However, i believe this is a good foundation to build upon. JavaScript is not my favourite language but i have found it to be very useful in achieving the functionality in the Caspian currency converter.
By using GitHub as my primary project tool, it helped to stay organised and ensure i had completed the tasks required.

  
#### Bibliography
  
  


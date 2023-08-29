# Tailwind1
Hosted link of my project:
for steps of my project please refer:

let me introduce u to Tailwind css:

Tailwind CSS is a Utility first framework that helps us in styling the HTML pages without leaving the HTML file. 
This means you can simply add some utility classes in your HTML tags to design your pages swiftly.
Tailwind CSS is an extraordinary framework that will completely change the way you write CSS in your programs. One major reason for the popularity of Tailwind CSS is its feasible workflow, as it eliminates the need of mapping the CSS to your HTML file. Nowadays, Tailwind CSS is evolving at a very fast pace. Let’s begin setting up Tailwind CSS-
Installation

First of all, we will install some important programs which will be required throughout our Tailwind Journey-

●        Install VS code: You can easily download the VS code by clicking here.
Moreover, Install the live server extension in VS code as it allows us to visualize our static page by opening the page with a live server.

●        Adding Tailwind CSS: To add tailwind CSS to your file, simply visit the official documentation by clicking here. After that, From the play CDN section, just copy the script and add it to the “<head>” of your HTML file. Hence, we can now use Tailwind CSS in our HTML file.

●        Install Node Js: You can Download Nodejs by clicking here. Select your OS and click on next, and your Nodejs will be installed.

●        Installing ‘Tailwind CSS IntelliSense’ extension: This extension provides some advanced features such as autocomplete, syntax highlighting, and linting.
Creating a Landing page

A landing page is a standalone page on a website designed to enable a specific action. The steps to create a landing page with the help of Tailwind CSS are mentioned below:-

    Have a Reference:- First of all, You have to surf through google to draw inspiration from the designs of other landing pages. 
    Create an HTML file:- After having the reference, Create an HTML file( for example- a landing.html file) and jot down the title and description of your landing page. In the below example, the title has been set as “Best Used Phones in Lucknow- Grab the deal now”.
    Add Tailwind CDN:- To begin using Tailwind CSS in your HTML file, you have to add the script of Tailwind CDN inside the <head> tag.

Advantages of using Tailwind CSS

1. Eliminate the Need of reinventing class name

 By using Tailwind CSS, One can easily obliterate the requirement of reinventing the class name. In the case of writing Traditional CSS, one has to add a large number of class names while creating a single component. For example: While creating a section, a number of classes such as section-heading, section-para, etc are created.

 

2. No Risk of Breaking the existing template

While using Tailwind CSS, you can easily style the elements by applying pre-existing utility classes directly in your HTML. The biggest advantage of the Utility first approach is that all your components become independent. Thus, It eliminates the risk of providing the same class to two different components. For example: While creating a Header and Footer, A person can unintentionally provide the same class to both components and thus hampering the development.

 

3. Faster CSS Styling Process

Tailwind CSS is one of the fastest frameworks for styling HTML. As a result, one can effortlessly create stunning layouts by styling elements directly. 

You can try to create a landing page with the help of Traditional CSS and Tailwind CSS to experience the efficient process of using the Tailwind CSS.

 

4. Responsiveness

In Tailwind CSS, a variety of breakpoints helps in constructing responsive designs. This simply means that you can easily change the CSS at a particular breakpoint. Thus, You can comfortably add the different classes for the different devices in the same element.
Setting Up Tailwind CSS for Production

You might know the procedure of setting up Tailwind CSS for development with the help of Play CDN. However, there is a slight difference in the process of setting Tailwind CSS for production. Let’s discuss it out!


To set up Tailwind CSS for production, you have to execute the below set of commands:

npm init -y

This command will initialize the directory as a NodeJS project.

npm install -D tailwindcss postcss autoprefixer vite

This command will install the required packages.

npx tailwindcss init-p

The execution of this command will generate the configure file of Tailwind CSS.

 

    Create an “Input.css” file
    Add below text to your HTML and edit it with the below piece of content:

@tailwind base;

@tailwind components;

@tailwind utilities; 

    In the tailwind.config.js file, You have to replace “content: []” with “content: [“*”]”.
    Moreover, You have to add “start”: “vite” to your scripts in package.json.
    Finally, you have to run the npm run start command to start a dev server.
    he Document Object Model (DOM) is a programming interface for HTML(HyperText Markup Language) and XML(Extensible markup language) documents. It defines the logical structure of documents and the way a document is accessed and manipulated.

Note: It is called a Logical structure because DOM doesn’t specify any relationship between objects. 

DOM is a way to represent the webpage in a structured hierarchical way so that it will become easier for programmers and users to glide through the document. 
With DOM, we can easily access and manipulate tags, IDs, classes, Attributes, or Elements of HTML using commands or methods provided by the Document object. Using DOM, the JavaScript gets access to HTML as well as CSS of the web page and can also add behavior to the HTML elements. so basically Document Object Model is an API that represents and interacts with HTML or XML documents.

Why DOM is required?

HTML is used to structure the web pages and Javascript is used to add behavior to our web pages. When an HTML file is loaded into the browser, the javascript can not understand the HTML document directly. So, a corresponding document is created(DOM). DOM is basically the representation of the same HTML document but in a different format with the use of objects. Javascript interprets DOM easily i.e javascript can not understand the tags(<h1>H</h1>) in HTML document but can understand object h1 in DOM. Now, Javascript can access each of the objects (h1, p, etc) by using different functions.

Structure of DOM: DOM can be thought of as a Tree or Forest(more than one tree). The term structure model is sometimes used to describe the tree-like representation of a document.  Each branch of the tree ends in a node, and each node contains objects  Event listeners can be added to nodes and triggered on an occurrence of a given event. One important property of DOM structure models is structural isomorphism: if any two DOM implementations are used to create a representation of the same document, they will create the same structure model, with precisely the same objects and relationships.

Why called an Object Model?
Documents are modeled using objects, and the model includes not only the structure of a document but also the behavior of a document and the objects of which it is composed like tag elements with attributes in HTML.
 
Creating the Navbar

Eventually, to create a navbar, you have to define the <nav> tag inside the body section of the landing.html. After that, You can add the list items like ‘Home’, ‘Contact Us’, ‘About’ and ‘Catalogue’ with the help of <li tag> in the form of an unordered list. As a result, the defined items will be shown in the Navigation bar.
Enhancing the Navbar

Furthermore, you have to use the flex property in the parent container to lay the collection of list items in one horizontal direction.   

In addition to this, You can use the Tailwind Utility for controlling the space between child elements. Moreover, you can add a justify-end property to move all the items to the top right end. Lastly, You can add the desired background color to the navbar. Here’s the code and result of a navbar created by following the above procedure:

 
Adding Logo - In Navbar

To add a logo in the navbar, you have to simply add the URL of your desired image in the "src" attribute. After that, You can enhance the position and size of your logo according to your need. For example:-

 


 

Explanation:- In this case, the image has been properly aligned by setting the height as 12 and assigning the padding in the top and x-direction.
Moreover, the image has been made rounded to give it an elegant look. You can also use the cursor pointer property to specify the type of cursor at a specific instance.
Adding Title - In Navbar

Alternatively, you can add a title to the navbar instead of adding the Logo. To add the title, You have to simply remove the image and add the title text inside the <span> tag. Additionally, you can enhance the text by using the margin, font bold, text colour and many more properties.
Creating the Content Section

To add the content section to your landing page, follow the steps mentioned below:-

    Create a Container: You can create a new div container and assign the proper value of height and width to the created container.
    Add Background: You can easily add the background colour of your choice to the div container.
    Add Heading/paragraph Text: You can add text to the content section by creating another div container and assigning the text size.
    Add buttons: To add the buttons, simply use the <button></button> tag and add the desired text and properties such as background colour, text colour, hover text, hover background, margin and so on. 
    Adding a Picture: Eventually, You can add an image to the content section of the landing page with the help of the ‘Imgsrc’ attribute and flexbox. Moreover, to align the image properly, you can use the item-centre property of the flexbox.
    Add Padding: Finally, you can add padding to each container with the help of the hit and trial method.
   

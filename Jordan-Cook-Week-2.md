### Javascript Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. How do you link a css file to your html page?

 //Your Answer
 <link href="link.css/>"


 //Googled Answer
  <link rel="stylesheet" href="styles.css">


 #### 2. What is a css class? How do you use declare one in html? How do you use it in css?


 //Your Answer
 a css class is something that allows you to style a group of things that fall uder that class. <h1 class=Style>. in css you would use .Stlye to make changes.

 //Googled Answer
 the .class selector selects elements with a specific class attribute.
 <p class="center large">This paragraph refers to two classes.</p>
 .class {
     css declarations;
 }

#### 3. The class "heading-box" exists in our html file - write the css code that would:
##### 1) align this box to the center of its container : ,
##### 2) give it a black border that is 5px wide,
##### 3) make its text appear in the center of the box
.heading-box{text-align; center,
    boarder-color: black,
    boarder: 5px,
    margin: 50%
    }

#### 4. What is Bootstrap? Explain a few reasons that you might choose to use it in a project?


 //Your Answer: Bootstrap is a website that offers already coded elements that you can incorporate into your own code. It is helpful for when you know you need something fast since the code is already written. It is also useful to add more visually appealing features to the page.


 //Googled Answer:Bootstrap is a free front-end framework for faster and easier web development
Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins
Bootstrap also gives you the ability to easily create responsive designs



#### 5. Name 4 semantic html tags. <header></header>, <div></div>, <p></p>, <h1></h1>,<footer></footer>

#### 6. What is block scope that became available in ES6? Include how it differs from local and global scope, and what variables are block scoped.

 //Your Answer: Block scope is similar to local scope but uses the let and const variables to assign its value. It limits those elements to the scope.


 //Googled Answer:While there are many issues that trip up developers coming from other languages, variable scoping may be number one. The fundamental problem is that many expect variables to be scoped to a particular block (like a for loop), but in JavaScript variables declared with var are scoped to the nearest parent function.

 #### 7. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

 //Your Answer: front end is what is seen on the web page. CSS and HTML is what is used to style how the page looks.


 //Googled Answer: Front end developers use HTML, CSS, and JavaScript to code the website and web app designs created by web designers. The code they write runs inside the user’s browser.


 #### 8. Choose one of the new ES6 concepts we learned about this week (namely: block scope, classes, and string interpolation) and write example code that demonstrates the concept, with comments to explain what is going on.
//line 71 is using the class concept that gives App its own properties but uses properties from Component//
class App extends Component{
    //now inside the class i would be give a value a state at that time on the webpage//
    constructor (props){
        super(props){
            this.state
        }
    }
}

 #### 9. What is the difference between a div and a span?


 //Your Answer: a div is an html element that has other elements nested inside.


 //Googled Answer: The <div> tag is nothing more than a container unit that encapsulates other page elements and divides the HTML document into sections.
 The <span> tag is used to group inline-elements in a document.



#### 10. How would you explain the idea of "inheritance" in object oriented programming?


 //Your Answer: inheritance is a class or object that has its own properties but it also inherits properties from the parent object.

 //Googled Answer:In object-oriented programming, inheritance enables new objects to take on the properties of existing objects.

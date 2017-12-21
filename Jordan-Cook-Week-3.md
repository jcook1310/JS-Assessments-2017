### Javascript Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:


- React is a modern, efficient answer to complex UI applications
- React is a full stack framework for modern web applications


 #### 2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.


 //Your Answer : smart components are functions that run certain aspects of the page.  dumb components are the simple parts like css and html


 //Googled Answer : smart components handle the state of the page. dumb components just displays what the state is.


#### 3. Write a simple component that simply prints "I am a dumb component" to the screen. Be sure to include all necessary imports, expots, etc...
import React,{Component} from 'react'

class Simple extends Component {
    render(){
        return(I am a dumb component)
    }
    }
export default Simple
#### 4. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?


 //Your Answer : yarn add ... will install a library that allows you to use pre-made code on your new page.  This will automatically update the package.JSON file.


 //Googled Answer : yarn add package-name installs the “latest” version of the package. This will also update your package.json and your yarn.lock


#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    import React, { Component } from 'react';

    class Recipes {
      constructor(props){
        super(props)
        this.state = {
          recipes:
            name: 'Meatballs',
            name: 'Mac & Cheese'

        }
      }

      render() {

        return (

          let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{recipe.name}</li>
            )
          })

          <ul>
            {this.state.recipes}
          </ul>
        );
      }
    }

    export default Recipes;

#### 6. Name three input types. (NOTE: text is the default type - so it doesn't count in this case)

 //Your Answer: image, number, button


 //Googled Answer: type, name, value


 #### 7. How would you explain state to a friend who doesn't know code?

 //Your Answer: state describes what the current state of the page is in.  for example, if you create a post on facebook the current state is right when you create it.  once someone likes the post the state changes to show the one like symbol.


 //Googled Answer: The heart of every React component is its “state”, an object that determines how that component renders & behaves. In other words, “state” is what allows you to create components that are dynamic and interactive. ... You've interacted with state-based systems your entire life — you just haven't realized it!


 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 -Props are what is being created at the beginning of a react app. State changes how the props are when the page is being used.

 #### 9. Name three benefits of testing and TDD:


 //Your Answer: Testing allows you to check your code to make sure it works before it is in a fully functioning app. It also helps the user understand what you are trying to accomplish. Finally it makes your code easier to read for people reading it so they understand what is going on.


 //Googled Answer:
 Cut development costs.
Shorten the development Time to Market.
Increase the programmer's productivity.


#### 10. List two helpful testing matchers and two helpful enzyme simulators that we can use when writing our tests:


 //Your Answer: testing matchers: expect() and toEqual()


 //Googled Answer:
Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.

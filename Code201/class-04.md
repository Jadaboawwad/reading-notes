# HTML Links, JS Functions, and Intro to CSS Layout

## 1.Link Element

        in this part we will discuss the following points

- There are 4 ways for dealing with Links in HTML we will list them.

<br/>

                           The beginning of Part One 

### 1.1 : Linking to Other Sites

we use :
                                
```html
    <ol>
    <a href="http://www.Jehadabuawwad.coffeecup.com">Empire</a>
    </ol>
```

### 1.2 : Email Links

we use :
                                
```html
    <ol>
    <a href="mailto:jehadabuawwad@outlook.org">Email Jon</a>
    </ol>
```

### 1.3 : Opening Article Links in a New Window

we use :
                                
```html
    <ol>
    <a href="http://www.Jehadabuawwad.coffeecup.com" target="_blank">
    </ol>
```


### 1.4 : Linking to a Specific Part of the Same Page

we use :
                                
```html
    <ol>
    <a href="#arc_shot">Arc Shot</a><br />
    <p>A shot in which the subject is photographed by an encircling or moving camera</p>
    </ol>
```

                           The End of Part One


## 2.Layout

        in this part we will discuss the following points

- How CSS and HTML treats with elements when it displays it. 
- How we contain elements inside others.
- How the browsers display each element.
- How do we floating elements.
- How we can deal with Screen Sizes.
- What are the Grids.

<br/>

                           The beginning of Part Tow 

### 2.1 : CSS and HTML treats with elements when it displays it as the following:

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

### 2.2 : We contain elements inside others as the following:

- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- div elements are often used as containing elements
to group together sections of a page.

### 2.3 : The browsers display each elementas as the following:

- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
    - Relative: Relative positioning moves an element in relation to where it would have been in normal flow.
    - Absolute:When the position property is given a value of absolute , the box is taken out of normal flow and no longer affects the position of other elements on the page.
    - Fixed:Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed .

### 2.4 : We float elements as the following:

- The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

### 2.5 : We can deal with Screen Sizesas the following:

- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide,and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

### 2.6 : What the Grids are.
- Grids set consistent proportions and spaces between items which helps to create a professional looking design.

- Grids help create professional and flexible designs.


                           The End of Part Tow

## 3.Functions, Methods, and Objects
        in this part we will discuss the following points

-What are the functions.
-How we can declare a function.
-How we can call a function and if we want to call it immediately how?
- What is the variable Scope and what are the type of it.


                           The beginning of Part Three 

### 3.1 : The Functions are:


- Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than rep eating the same set of st atements)

- Functions allow you to group a set of related statements together that represent a single task.

- Functions can take parameters (informatiorJ required
to do their job) and may return a value.

### 3.2 : We declare a function as the following:

![Declaring a Function](https://jehadabuawwad.github.io/reading-notes/images/class-04-photos/1.png)

### 3.3 : We can call a function as the following:
![Calling a Function](https://jehadabuawwad.github.io/reading-notes/images/class-04-photos/2.png)

- This is how we call it immediately:
```javascript

    var area = (function(){
    var width = 3;
    var height = 2 ;
    return width * height;
    }()) ;
```

### 3.4 : The Variable scope is:

- The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope.

- type of variable scope is:
    - Local variable : When a variable is created inside a function using the var keyword, it can only be used in that function. It is called a local variable or function-level variable.
    - Global variable : If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope.




                           The End of Part Three



### 3.5 Six Reasons for Pair Programming:
                
                           The beginning of Part Four 
                            
    1.Greater efficiency
    2.Engaged collaboration
    3.Learning from fellow students
    4.Social skills
    5.Job interview readiness
    6.Work environment readiness 

                            The End of Part Four



                                                        
<br/>

## 5. Pair Programming

the  pair programming process started by decideing which part is the Navigator


**Ashjan** is the **Navigator**

**Jehad** is the **Driver** 

 is the Navigator :female-judge::skin-tone-2:
and
Fatima is the Driver :female-technologist::skin-tone-2:

<br/>     

                            The beginning of Part Five 

## Jehad's side:

### 1- Ashjan will create the repo on GitHub (she's the owner of the repo) and send me the link of her repo (She can add in the README that she's the navigator and I'm the driver)

### 2- I will go to Ashjan's repo on GitHub and fork it (Click on Fork)

## 3- I will now have a version of her repo in my GitHub repositories

### 4- I will open it, and click on code button and copy the link

### 5- I will go to Ubuntu and clone (git clone) the repo
### 6- I will open VSCode and Ashjan will tell me what to add/update/delete in code, I will also add in the README that I'm the driver and Ashjan is the navigator

### 7- After finishing the code, I will do A-C-P (add, commit, push)

### 8- I will go back to my GitHub and open the forked repo
(You might see a message that says Create a pull request, click on it and go to step 10/ if not, go to step 9)

### 9- I will go to Pull Request

### 10- I will click on New pull request  (compare: main  base:main)

### 11- I will create a pull request (this pull request will go from my main to Ashjan's main) --> Head Repository: My repo  ___ Base Repository: Ashjan's repo

### 12- (I will find the title already added, I can change it for example: "changes made by Jehad", and add a description)

### 13- I will click on Create a pull request

### 14- I will copy the URL (link) above and save it in a note: I was the driver on this (link)

## Ashjan's side:

### 1- She will go to her GitHub and open the repo

### 2- She will click on Pull Requests

### 3- She will open the pull request that is sent from me ("changes made by Fatima")

### 4- She will click on Merge pull request

### 5- She will click on Confirm Merge

### 6- She will copy the URL (link) and save it in a note: I was the navigator on this (link)

### 7- When she goes back to her code, she should first do on Ubuntu: git pull to take the new changes I made on the repo

<br/>

                            The End of Part Five

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

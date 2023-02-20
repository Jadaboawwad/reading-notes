# HTML Images; CSS Color & Text


## 1.Images Elements

        in this part we will discuss the following points

- What is the Image element we use in HTML.
- What are the attribute carried by this element.
- Where to Place Images in Your Code

<br/>

                           The beginning of Part One 

### 1.1 : The Image elements we use in HTML is

##### 1.1.1 img 
   - img element is used to add images to a web page.
    - is an empty element (which means there is no closing tag).


we use :
                                
```html
<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial that is similar in size to the domestic cat." />
```

#### 1.1.2 : figure and figcaption
we use :

```html
<figure>
    <img src="images/otters.jpg" alt="Photograph of
			 two sea otters floating in water">
    <br />
    <figcaption>
        Sea otters hold hands when they sleep so they don't drift away 
        from each other.
    </figcaption>
</figure>
```
 
### 1.2 : the attribute carried by this element are:

- src : This tells the browser where it can find the image file.    
- alt : This provides a text description of the image which describes the image if you cannot see it.
- title : You can also use the title attribute with the img element to provide additional information about the image
- height : This specifies the height of the image in pixels
- width : This specifies the width of the image in pixels.
### 1.3 : The Place of Images in Your Code is

- **before a paragraph**: The paragraph starts on a new line after the image.
- **inside the start of a paragraph**: The first row of text aligns with the bottom of the image.
- **in the middle of a paragraph**: The image is placed between the words of the paragraph that it appears in.
 
                           The End of Part One




## 2 : Colors
        in this part we will discuss the following points

- What is the color property we use in HTML.
- What are the ways of specifing color in HTML.


<br/>

                           The beginning of Part Tow 


### 2.1 : The color property we use in HTML is
- The color property allows you to specify the color of text inside an element. You can specify any

### 2.2 :The ways of specifing color in HTML are:

- RGB values :Values for red, green, and blue are expressed as numbers between 0 and 255.
- Hex codes : Hex values represent values for red, green, and blue in hexadecimal code.
- Color names :Colors are represented by predefined names. However, they are very limited in number.
-HSL Colors: consist of 
    - **Hue**: is the colloquial idea of color. In HSL colors, hue is often represented as a color circle here the angle represents the color, although it may also be shown as a slider with values from 0 to 360.
    -**Saturation** : Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.
    - **Lightness** : is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.
    - **alpha** :This is expressed as a number between 0 and 1.0 . For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.
 
 ___
                           The End of Part Tow

## 3 : Text
        in this part we will discuss the following points


- What are 13 property and element for text.
- Give a summirize.

<br/>

                           The beginning of Part Three 


### 3.1 :  13 property and element for text are:

#### 3.1.1: For font family we use :   

```css
body {font-family: Georgia, Times, serif;}
```
#### 3.1.2: For font Size we use :   

```css
body {font-size: 12px;}
```

#### 3.1.3 : For font weight we use

```css
body {font-weight:: 12px;}
```

#### 3.1.4 : for UpperCase & LowerCase we use

```css
h1 {text-transform: uppercase;}
```
#### 3.1.5 :for Underline & Article we use :

```css
a {text-decoration: none;}
```

#### 3.1.6 : for leading we use :


```css
p {line-height: 1.4em;}
```

#### 3.1.7 :  for Letter & Word Spacing 


```css
h1, h2 {
text-transform: uppercase;
letter-spacing: 0.2em;}
.credits {
font-weight: bold;
word-spacing: 1em;}

```

#### 3.1.8 : for Alignment  


```css
h1 {
text-align: left;}
p {
text-align: justify;}
.credits {
text-align: right;}
```



#### 3.1.9 : for Virtical Alignment  


```css
h1 {
#six-months {
vertical-align: text-top;}
#one-year {
vertical-align: baseline;}
#two-years {
vertical-align: text-bottom;}
```



#### 3.1.10 : for Indenting Text 


```css
h1 {
h1 {
background-image: url("images/logo.gif");
background-repeat: no-repeat;
text-indent: -9999px;}
.credits {
text-indent: 20px;}
```

#### 3.1.11 : for First Letter or Line


```css
h1 {
p.one {
background-color: #eeeeee;
color: #666666;
text-shadow: 1px 1px 0px #000000;}
```

#### 3.1.12 : for Drop shadow


```css
p.intro:first-letter {
font-size: 200%;}
p.intro:first-line {
font-weight: bold;}
```



#### 3.1.12 : for Styling link


```css
a:link {
color: deeppink;
text-decoration: none;}
a:visited {
color: black;}
a:hover {
color: deeppink;
text-decoration: underline;}
a:active {
color: darkcyan;}
```

#### 3.1.13 : for Responding to Users

```css
input {
padding: 6px 12px 6px 12px;
border: 1px solid #665544;
color: #ffffff;}
input.submit:hover {
background-color: #665544;}
input.submit:active {
background-color: chocolate;}
input.text {
color: #cccccc;}
input.text:focus {
color: #665544;}
```



### 3.2 :  A summery:

- There are properties to control the choice of font, size,
weight, style, and spacing.
There is a limited choice of fonts that you can assume
most people will have installed.

- If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.

- You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.

- You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.



                           The End of Part Three


## 4. Dealing with Branches

<br/>

                            The beginning of Part Four 



#### 1- You will go to this repo: https://github.com/LTUC/amman-201d32-lab5

#### 2- Fork it

#### 3- Clone it on your machine (from Code green button, copy the link)

#### 4- In Ubuntu, git clone the-link-you-copied

#### 5- You are now in the main branch, you can see Repo-Name[main]$, inside square brackets you have the branch name and here you have the main branch

#### 6- type git checkout -b problem1 to create a new branch for problem 1

#### 7- code .

#### 8- Solve problem 1

#### 9- Go live (Open live server)

#### 10- Right click

#### 11- Inspect

#### 12- Go to Console tab

#### 13- Check if the test passed or not, if not go back to the code and solve it, if yes go to step 14

#### 14- Go to your terminal (Ubuntu) and do A-C-P (add, commit, push) (when you do git push, you will do it on the branch name that is inside the square brackets git push origin problem1 )

#### 15- Go to to your repo on GitHub and you will see a message "Compare & pull request", click on it (If you didn't find the message, go to Pull Requests and click on New pull request)

#### 16- Make sure that Head and Base are your repo NOT LTUC's repo, also make sure that the branches are from problem1 branch to main branch (base: main  compare:problem1)
#### Head: Your repo   base:main   <-  Base: Your repo   compare:problem1

#### 17- Merge pull request

#### 18- When you go back to the main branch on GitHub you will see it's updated and has the solution of problem 1

#### 19- Go back to Ubuntu

#### 20- type git checkout main (to go back to the main branch)

#### 21- type git pull origin main (to get the new changes that are done on the main which are solving problem 1 and merging it to the main)

#### 22- Now type git checkout -b problem2 to create a new branch for problem 2

#### 23- Do the rest of the steps as mentioned before (starting from 8 )

#### ...

#### 24- Now after you're done with all of the problems

#### 25- Go to Pull requests in GitHub and click on New pull request

#### 26- NOW PAY A GOOD ATTENTION

#### Here you will have the merging like this

#### Base: LTUC repo  base:main   <-  Head: Your repo   compare:main

#### 27- Click on Create a pull request

#### 28- You will NOT be able to merge in this steps

#### 29- Copy the URL (link that is in the above) and submit it to Canvas

<br/>

                           The End of Part Tow

<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

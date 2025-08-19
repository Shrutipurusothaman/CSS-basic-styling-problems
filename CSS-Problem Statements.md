## CSS-Problem Statements

### Date:19/08/2025



#### ***Basic Styling:***



##### **1. Change Text Color and Font**

##### Style a <p> tag to have blue text and a custom font like Arial.



###### **HTML:**

<!DOCTYPE html>

<html>

<head>

&nbsp; <title>My first basic styling</title>

&nbsp; <link rel="stylesheet" href="./style.css">

</head>

<body>

&nbsp;  <h1>Welcome to the page of innovations</h1>

&nbsp;  <p>Hi I am shruti here, now let's change the colour of this <p> tag into blue color with a custom font like Arial</p>

</body>

</html>



###### 

###### **CSS Solution:**



&nbsp;   **p{**

        

        **color:blue;**

        **font-family:Arial;**

     

     **}**





##### 

##### **2. Center Align Text**

##### Center the content of a heading tag (<h1> or <h2>) using CSS



###### **HTML:**

<!DOCTYPE html>

<html>

<head>

&nbsp; <title>My Second basic styling</title>

&nbsp; <link rel="stylesheet" href="./style.css">

</head>

<body>

&nbsp;   <h1>Welcome to the page of innovations</h1>

&nbsp;   <p>Now let's center the content of heading tag using css</p>

</body>

</html>





###### **CSS Solution:**

   

    **h1{**

        

       **text-align:center;**

     

      **}**

   

    **p{**

       

      **text-align:center;**

    

    **}**





##### 

##### **3. Set Background Color**

##### Apply a light gray background to the entire page (body)





###### **HTML:**

<DOCTYPE html>

<html>

<head>

&nbsp; <title> My Third basic styling</title>

&nbsp; <link rel="stylesheet" href="./style.css">

</head>

<body>

&nbsp;  <h1>Welcome to my Third styling page</h1>

&nbsp;  <p>Now let's change the background of the entire page into light gray</p>

</body>

</html>



###### 

###### **CSS Solution:**

    

     **body{**

          

          **background-color:lightgray; or #D3D3D3;**

     

      **}**





##### 

##### **4. Style Multiple Elements**

##### Give all <h1> and <p> tags a margin of 20px using a group selector.





###### **HTML:**

<DOCTYPE html>

<html>

<head>

  <title> My fourth basic styling</title>

&nbsp; <link rel="stylesheet" href="./style.css">

</head>

<body>

   <h1>Welcome to my Fourth styling page</h1>

   <p>Now let's give all <h1> and <p> tags a margin of 20px using a group selector.</p>

</body>

</html>



###### **CSS solution:**

    

      **h1,p{**

          

          **margin:20px;**

        

      **}**



##### 

##### **5. Apply Box Shadow to a Div**

##### Add a subtle shadow to a card-like <div> element.





###### **HTML:**

<DOCTYPE html>

<html>

<head>

&nbsp;   <title> My fifth basic styling</title>

&nbsp;   <link rel="stylesheet" href="./style.css">

</head>

<body>

 <h1>Welcome to my Fifth styling page</h1>

 <p>Now let's add a subtle shadow to a card-like element.</p>

&nbsp; <div id="cs-card">

&nbsp;  <img src="https://www.google.com/imgres?q=computer%20science\&imgurl=https%3A%2F%2Fimages.squarespace-cdn.com%2Fcontent%2Fv1%2F5fce63270356d927d7eecdbd%    2F033e9988-2ac8-4cb9-8b9f-5bf05fb22dcb%2Fgff.jpg\&imgrefurl=https%3A%2F%2Fwww.jietjodhpur.ac.in%2Fblog%2Fcomputer-science-engineering-vs-artificial-intelligence\&docid=icWJ88\_PT-CBGM\&tbnid=T8nxrT0kBJKG0M\&vet=12ahUKEwjujbXoz5aPAxX92DgGHe7bJAkQM3oECBIQAA..i\&w=1000\&h=633\&hcb=2\&ved=2ahUKEwjujbXoz5aPAxX92DgGHe7bJAkQM3oECBIQAA" alt="Computer Science image">

&nbsp;  <p>I am a CS student</p>

&nbsp;  </div>

</body>

</html>





###### **CSS solution:**

   

        **#cs-card{**

   

            **border:1px solid ;**

            **padding:10px;**

            **box-shadow:5px 10px grey;**

     

      **}**































































































&nbsp;       


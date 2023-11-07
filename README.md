This project was actually our 4th assignment given to us in the Introduction to Web Development Course 
but I edited and made some changes to it, because when it was previously submitted I received feedback 
saying it had minor alignment issues but now i have made sure to fix them, the only challenging aspects
of the code was adding the hamburger icon to the page when it is shrunk or minimized replacing the 
navigation bar, all that remains is the javascript to make the hamburger icon resposinve.
In the head tag is where all the meta tags, links to stylesheets and title of the webpage go.
```
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="author" content="Nifemi Leye">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
        integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <meta name="description" content="Nifemi Leye: Web Developer">
    <meta name="keywords" content="web developer, web, developer, 
    front-end, html, css, javascript, react, sql">
    <title>Project 1</title>
    <link rel="icon" href="./assets/img/faviconratio.jpg" type="image/x-icon">
    <link rel="stylesheet" href="./assets/style/index.css" media="all">
    <link rel="stylesheet" href="./assets/style/reset.css" media="all">
</head>
```

In the header is where the navigation bar for the webpage is made,
including the hamburger icon which appears when webpage is shrunk.
```
<header>
    <div class="container">
        <h1>Project 1</h1>

        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
        <div class="collapse nav icon">
            <i class="fa-solid fa-bars"></i>
        </div>
    </div>        
</header>
```
![Header](assets/img/Header.png)

The css involving the styling of the header is shown below, the background colour used and how the items where aligned.
```
header {
    height: 60px;
    background-color: #682cc0;
    overflow: hidden;
}

header > div {
    display: flex;
}

header div h1 {
    font-size: 20px;
}

header h1 {
    margin-left: 30px;
    height: 60px;
    line-height: 50px;
    color: #fff;
    width: 40%;
    font-size: 18px;
}

header nav {
    width: 100%;
    text-align: right;
}

header nav ul {
    list-style: none;
    font-size: 0px;
}

header nav ul li {
    line-height: 50px;
    font-size: 18px;
    display: inline;
}
```


The main also resides in the body where the table itself is made.
Below is the css involved for the structure of the table, also showing how it was centered. 

```
.center {
    margin-left: auto;
    margin-right: auto;
    place-items: center;
}

table {
    height: 52vh;
    margin-top: 100px;
    width: 65%;
    border-collapse: separate;
    border-radius: 10px;
}

th {
    color: #888d97;
    font-size: 14px;    
    padding: 2px;
}

td {
    padding: 8px;
    border-bottom: 1px solid #ddd;
    background-color: #fff;
    text-align: center;
}

div {
    border-radius: 50%;
    padding: 10px 2px;
}
```
![Table](/Project%201/assets/img/Table.png)

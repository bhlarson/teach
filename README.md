# teach
Simple lessons to teach web programming to children

Step 0:
1) clone the tutorial
in the search bar, type cmd
> mkdir c:/git
> cd c:/git
> git clone https://github.com/bhlarson/teach.git
2) In chrome, install the web server for chrome extension https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en
3) Start the web server by creating a new chrome tab -> Apps -> Web server
4) On Choose folder, choose C:\git\teach\public
5) On a chrome tab, enter "http://127.0.0.1:8887"
6) press ctl+shift+i to open the developer tools
7) Drag and drop C:\git\teach\public from a windows explorer and allow full access
8) On sources, open (index)



Step 1: Basic HTML layout:
Copy and paste the following into index.html 
<!DOCTYPE html>
<html>
<head>
</head>
<body>

</body>
</html>

1) What is "!DOCTYPE" https://www.w3schools.com/tags/tag_doctype.asp
2) What happens if "!DOCTYPE" is removed?
3) Find matching html keys beginning with <something> and ending with </something> 
4) Add basic HTML tags from https://www.w3schools.com/html/html_basic.asp
5) press F5 to refresh and the browser and dispay the changes

Step 2: Add javascript and cascade style sheet files
Change index.html to the following:
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <link href="css/style.css" rel="stylesheet" />
</head>

<body>
    <script src="js/index.js"></script>
</body>
</html>

1) Reload the browser




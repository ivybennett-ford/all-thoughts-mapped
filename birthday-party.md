The following code is taken from a codecademy project designed to teach the user how to git-control a one-page website.

```html
<!DOCTYPE html>

<html>

<head>

<title>Kay's Birthday Party</title>

</head>

<body>

<!-- Changed the font-size -->
<h1 style="font-style: 72px">Kay's Birthday Party</h1>

<h2>Friday, November 13, 2015, from 7 - 11 pm</h2>

<h3>At Roof Garden Cafe, in the Met </h3>

  
<!-- Updated the description as an unorderd list -->
<p><ul>

<li>Join Kay in celebrating their 29th birthday with free food and beverages</li>

<li>karaoke and a special appearance by Willy Nelson</li>

<li>explore the Met museum before or after you stop by!</li>

<li>Birthday presents optional</li>

</ul></p>

<p>For more information: contact Kay at 101-000-0101</p>

  

</body>

</html>
```


Have not tested the page as listed above, but you could!

Git commands practiced today:
```c
# basic committing workflow
git add <filename>
git commit -m "message"
git push --set-upstream origin <branchname>
# git push (if you've set an upstream)
git co main
# if you want to merge from the CLI:
git merge origin <branchname>
# removing a branch from CLI
git branch -D <branchname>
```


#code #git #engineering #user-guide  #computer-science #html
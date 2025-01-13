# Question 15
You can import fonts via downloading a trf file or simply using a service such as Google Fonts. 


In Google Fonts, you can import then use the imported fonts via classes.
!["Question 15 screenshot"](/images/questions/question-15.png)

<br>
<br>
<br>

You will need to place the following code into your stylesheet:
```CSS
@import url('https://fonts.googleapis.com/css2?family=Jersey+15&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
```

<br>
<br>
<br>

Then, you will also need to write the following code:
```CSS
.jersey-15-regular {
  font-family: "Jersey 15", serif;
  font-weight: 400;
  font-style: normal;
}
```

<br>
<br>
<br>

With both set of scripts written, you can then use `jersey-15-regular` as a class value.

Try it out then later attempt to import other different fonts on your own.
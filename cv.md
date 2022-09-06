
##Atavaliev Timur

###Contacts
####E-mail: tatavaliev@gmail.com
####Telegram : @konferansie
[LinkedIn]("LinkedIn")

###Bio
I'm 35 y.o, I live in Kyrgyzstan, Bishkek.
I managed to work in different companies, but they were all related to IT.
My first job was as operator of customer support in cellular company.
I worked there for more than a year, after that I got a job in an Internet provider company as an installer.
A year later, I moved to the department of customer support. I worked in this position for about 3 months.
After that, I returned to the cellular company, but to another department, to the technical support department.
There were also several other interesting places where I managed to work where I received new knowledge and skills.

###Skills
After I started working in the field of programming, I acquired many useful skills here are some of them.
* HTML5
* CCS3, SASS, SCSS, Gulp
* JQuery
* JS, ReactJS
* CMS (WordPress, Joomla)
* WebStorm, PhpStorm
* Photoshop, Figma
* Git, Github
* Php Basics

####Code Examples
#####Your mission:
#####Write a function called checkCoupon which verifies that a coupon code is valid and not expired.
#####A coupon is no more valid on the day AFTER the expiration date. All dates will be passed as strings in this format: "MONTH DATE, YEAR".
#### Solution:
```
function checkCoupon(enteredCode, correctCode, currentDate, expirationDate){
    return enteredCode === correctCode && Date.parse(currentDate) <= Date.parse(expirationDate) ? true : false
}
```

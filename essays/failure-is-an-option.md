---
layout: essay
type: essay
title: Failure is an option
# All dates must be YYYY-MM-DD format!
date: 2018-01-17
labels:
  - Interests
  - IOT
  - Goals
---
<p>

&emsp;

This past thursday was our first official WOD for my ics 314 class. I was fairly confident that I would do well. I did well in the practice

WODs, but I guess I should have done them a few more times. Because every WOD I practiced on I would always get some sort of syntax error.

For example when we did the problem.

<br>

Create a function that converts a number from Farenheit to Celsius.

</p>

</br>
function changeTemp(tempType,Temp){ // function that takes in the paramaters of type being taken in, and the degree of tempurature
</br>
let finalTemp = 0; // initialize final temp
</br>
if(tempType=="f"){
</br>
finalTemp= (Temp)(9/5)-32;}
</br>
if(tempType=="c"){
</br>
finalTemp= (Temp)(5/9)-32;}
</br>
else{
</br>
return "incorrect input"}
</br>
return finalTemp;}
</br>
console.log("f",212); // should come out to 100
</br>
}


</br>
</br>

&emsp;As soon as we got this I began to work on it and for two days straight I kept getting one sort of error or another. Errors such as "function expected" or other syntax errors. My biggest issue was with double equals, and that would later come back to haunt me.

</br></br> 

&emsp;We get to the day of the WOD and it was that morning at the library where I finally got my code to work. I have no idea how but it gave me a false sense of confidence. We got into the WOD and it was an easy problem. I could have done this code in 10 minutes tops, but for some reason, I felt my chest tightening up, my hands forgot how to type, and as soon as he said go, I forgot how to code.

</br>

The code was something like this

</br>

Make a function that prints out numbers from 1 to 100. If this it's a multiple of 4, print "Jabby", for multiples of 6 print "Wabby", and for mutiples of both "JabbyWabby". My code was SUPPOSED to look like this

</br></br> 

function JabbyWabby(num){

</br>

for(let i = 0; i<=num;i++){

</br> 

&emsp; if(i%2==0){

</br>

&emsp;console.log("Jabby");}

</br>

&emsp;if(i%4==0){

</br>

&emsp;if(i%4==0){

</br>

&emsp;console.log("Wabby");}

</br>

&emsp;if(i%2==0&&i%4==0){

</br> 

&emsp;console.log("JabbyWabby");}

</br>

&emsp;else{

</br>

&emsp;console.log(i);

</br>

}

</br>

console.log(100);

</br></br>

&emsp;Do you remember that double equals issue I had earlier? It came full force for this WOD. I even forgot to initialize i in the for loop. Then to top it off. For final statement I put:

</br>

else{

</br>

&emsp; console.log(num);} which only called 100 for every iteration of i

</br></br>  



&emsp; I psyched myself out, and ended up not finishing because you can't turn in code that doesn't run. Because as much as I wanted it to be done, you can't turn in something that doesn't work and call it finished. It was embarassing. I didn't finish what could be the easiest WOD of the semester. In fact it still hurts a little while writing this essay. But I'll be sure that I get the next one, and hopefully I don't choke up like I did. I'm not sure how easy it is to maintain an A if you fail the first two WODs. Overall though I like javascript it's a little easier than java and allows you to be a bit more general. I'm excited for what I will learn from this class, and hope that I can calm down during the WODs. This will be challenging, but at the same time I'm stoked to even get this far, as I honestly didn't think I would have done so well in ANY of the computer science classes. Yet here I am, typing about how coding made me look stupid. Though it's fair to say coding will definitely make a fool out of me again.

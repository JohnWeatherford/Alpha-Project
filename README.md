# Alpha-Project
First Web Dev project

User story
As a new web developer who is creating websites for the first time.
I want to show case old projects and see waht I can realy do.
So that I can pass this class and come back with a new skill and have a new favorit skill.

Wireframe: https://github.com/JohnWeatherford/Alpha-Project/blob/main/docs/images/wireframe.jpeg.

js
'''
document.addEventListener("DOMContentLoaded", () => {
  console.log("document succesfully loaded, baby");

  document.getElementById('btnClicky').addEventListener('click', btnClicky);
}
);

function btnClicky() {
  console.log('in btnClicky event');
  document.getElementById('btnClicky').style.transform = 'rotate(90deg)'
  console.log('after rotation');
}
'''

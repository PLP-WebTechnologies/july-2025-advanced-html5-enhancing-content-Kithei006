[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ew7e64j9)
# 📘 Assignment: Enhancing HTML5 Content & Mastering Forms

## Overview

This assignment focuses on elevating your HTML5 skills by working with advanced content elements and mastering the creation, structure, and validation of web forms. You will practice using lists, tables, and media to enrich page content, and then dive deep into building dynamic, user-friendly forms powered by native HTML5 features.

## Objectives

You are expected to demonstrate the ability to:

* Use lists and tables effectively to organize content for clarity and accessibility.
* Embed media content such as images, audio, or video using semantic HTML5 elements.
* Build structured HTML5 forms that are both usable and visually intuitive.
* Apply various HTML5 form attributes to improve user interaction.
* Use built-in validation techniques to minimize incorrect data input without relying on JavaScript.

## Instructions

Design a simple multi-section web page that showcases the use of lists, tables, and media, followed by a complete HTML5 form. The page should reflect thoughtful structure, usability, and clarity.

Your form should include various input types, make use of labels and fieldsets for accessibility, and apply HTML5 validation rules through attributes like `required`, `type`, `minlength`, `pattern`, and others.

Avoid using JavaScript for validation—rely solely on native HTML5 capabilities.

## Deliverables

Submit a single HTML file named `enhanced-form.html`. It should include:

* Well-structured content using lists, tables, and media.
* A complete HTML5 form including a variety of input fields.
* Correct use of form attributes such as `placeholder`, `required`, `autocomplete`, and `readonly`.
* HTML5 validation features implemented correctly across all relevant fields.
* A clear, accessible layout using semantic tags.

## Tips

* Proper and meaningful use of lists, tables, and media.
* Clarity and accessibility of form structure.
* Correct use of form elements and attributes.
* Effective application of native HTML5 validat[Uploading enhanced-form.html…]()
ion.
* Clean, well-indented, and maintainable HTML code.

<!DOCTYPE html>
<html lang = "en">
  <head>
    <title>Week 2 Assignment </title>
  </head>
<body>
  <h1> Ordered Lists</h1>
  <ol>
    <li> Monday</li>
    <li> Tuesday</li>
    <li> Wednesday</li>
  </ol>
  <h2> Un-ordered lists</h2>
  <ul> 
    <li> Thursday</li>
    <li> Friday</li>
  </ul>
  <h2> Definition Lists</h2>
  <dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language- a language for creating webpages</dd>
  </dl>
  <h2> Nested Lists</h2>
  <ol>
    <li> Frontend languages</li>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Javascript</li>
    </ul>
    <li> Backend Languages</li>
    <ul>
      <li>Ruby</li>
      <li>Python</li>
      <li>Java</li>
    </ul>
  </ol>
  <h2>Images</h2>  
  <img src="https://images.pexels.com/photos/33245188/pexels-photo-33245188.jpeg?cs=srgb&dl=pexels-anchau-1663967297-33245188.jpg&fm=jpg&_gl=1*11yzgwe*_ga*MTYyMzQ3MjA5MS4xNzU0MjkzMjE0*_ga_8JE65Q40S6*czE3NTQyOTMyMTMkbzEkZzEkdDE3NTQyOTM0NjEkajU5JGwwJGgw"
  alt="Picture of a woman"
  width="500"
  height="300" 
  <h2> Tables</h2>
  <table border="1">
    <thead>
      <tr>
        <th>name</th>
        <th>Gender</th>
        <th>country</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Edith</td>
        <td>female</td>
        <td>Kenya</td>
      </tr>
      <tr>
        <td>Onyancha</td>
        <td>male</td>
        <td>Uganda</td>
      </tr>
      <tr>
        <td>Shaz</td>
        <td>female</td>
        <td>Rwanda</td>
      </tr>
    </tbody>
  </table>
  <h2>Embedding Videos & audio</h2>
  <video width="500" height="300" controls>
    <source src="https://www.pexels.com/video/person-shaking-the-glass-of-wine-5045649/" type="video/mp4">
    Your browser does not support the videos
  </video>
  <audio>
    <source src="c:\Users\HP\OneDrive\Desktop\songs" type=" audio/mpeg">
    Your Browser does not support audio playback
  </audio>
  <h2>Forms</h2>
  <form action="location" methods="">
    <label for="Name"> Name: </label>
    <input type=" text" id="Name" placeholder=" enter your name Here...">
    <label for="email">email:</label>
    <input type=" email" id="email" placeholder=" enter your email Here...">
    <br><br/>
    <label for="age">age:</label>
    <input type=" number" name="age" id="age" max="30" min="18" placeholder=" enter your age Here...">
    <br><br/>
    <label for="dob">Date of Birth</label>
    <input type="date" name="dob" id="dob"> 
    <br><br/>
    <label for="Gender">Gender:</label>
    <input type=" radio" name="gender" value="Male"> Male
    <input type="radio" name="gender" value="Female"> Female
    <br /><br />
    <label for="cv">Upload CV</label>
    <input type="file" name="cv" id="cv">
    <br><br/>
    <label for="bio">Bio:</label>
    <textarea name="bio" id="bio" cols="30" rows=" 10" placeholder="Write your bio here..."></textarea>
    <br /><br />
    <input type="Submit">value="Submit">
    

  </form>
</body>
</html>


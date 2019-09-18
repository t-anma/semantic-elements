# semantic-elements
## Lesson 1 Assignment for UW's Introduction to Git & HTML online class
### In the index.html file, you will find my completed 15 Elements
### In the semantic elements paragraph.docx file, you will find my paragraph on Semantic Elements
#### by Angela Martin, angelalmartin98@gmail.com

## 15 Elements Code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>semantic-elements</title>
  </head>
  <body>
    <div style="background-color:lightblue">
    <h1>Welcome!</h1>
    </div>
    <section>
      <h2>This is a website created for the <em>semantic-elements</em> assignment.</h2>
      <h3>This assignment was given in the <strong>University of Washington's online HTML course!</strong></h3>
      <h4>In this assignment, we are to showcase at <em>least</em> 15 different HTML elements.</h4>
      <h5>So that I may demonstrate using blockquote and a line break, here  is the exact assignment given:</h5>
    </section>
    <br> <!--this is a comment and I am not sure it counts towards the 15 elements. To be safe, I will assume not.-->
    <blockquote>
    <ul>
      <li>Create a new git repository on your computer. Name it semantic-elements.</li>
      <li>Inside the repo, code an HTML document. Name it index.html.</li>
      <li>Use at least 15 different types of HTML elements (correctly!)  We didn't cover 15 elements in the lesson. You'll need to use some information from the articles. Test your code using the validator we discussed in this lesson.</li>
      <li>View your document in a browser to ensure it displays as you expect.</li>
      <li>Push your code to GitHub as a new repository.</li>
      </ul>
    </blockquote>
    <br>
    <mark>To recap, here are the 15+ elements <s>(plus the comment element which I was unsure counted because it is not a visual element which appears on the page)</s> used in this document:</mark>
    <ol>
      <li>Doctype</li>
      <li>html lang-"en"</li>
      <li>head</li>
      <li>meta</li>
      <li>title</li>
      <li>h1, h2, h3, h4, h5, h6</li>
      <li>br (linebreak)</li>
      <li>blockquote</li>
      <li>P (paragraph)</li>
      <li>ol and li (ordered list)</li>
      <li>ul and li (unordered list)</li>
      <li>mark (highlight)</li>
      <li>s (strikethrough)</li>
      <li>div</li>
      <li>section</li>
      <li>address</li>
      <li>footer</li>
      <li>!--...--! (comment)</li>
    </ol>
    <div style="background-color:lightblue">
      <h4> Contact/Connect with me! </h4>
        email:<address>angelalmartin98@gmail.com</address>
        <p> View my <a href= "https://angelamartin.myportfolio.com">portfolio here</a></p>
    </div>
    <footer>
      <p> Thanks for viewing my page! </p>
      <h6> and have a wonderful day :) </h6>
    </footer>
  </body>
  </html>
  
  ## Paragraph on Semantic Elements
  	A semantic element in HTML is an element which clearly describes its meaning and use to both the browser reading it (such as Chrome, Edge, Firefox, Safari, etc.) and to the human developer. For example, the element “<footer>” would be considered a semantic element because it is clearly identifiable as the start of the “footer” section of the HTML coded document. Alternatively, “<span>” is not a semantic element because it is difficult to identify what the element does by the developer reading it. Clearly, it is more helpful to the developers reading the documents to use semantic elements over non-semantic elements because it makes the developer's visualization of the code much easier. Of course, it wouldn’t make much of a difference to the browser reading the code. Although, some semantic elements have become obsolete or deprecated over time such as “basefont” and should always been looked out for.

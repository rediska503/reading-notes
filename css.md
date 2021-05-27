+CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

+CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
    color: red;
    font-size: 5em;
}


+Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Example
Inline styles are defined within the "style" attribute of the relevant element:

<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>


+Multiple Style Sheets
If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 

Assume that an external style sheet has the following style for the <h1> element:

h1 {
  color: navy;

  [back to main page](README.md)
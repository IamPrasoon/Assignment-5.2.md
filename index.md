1. index.html


<!DOCTYPE html>
<html>
<head>
    <title>CSS Selectors</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>CSS Selectors Practice</h1>
    <div id="special" class="card">
        <h2>About Me</h2>
        <p>I am Prasoon Anand.</p>
    </div>
    <div class="card">
        <h2>My Skills</h2>
        <p>HTML, CSS, JavaScript</p>
    </div>
</body>
</html>

2. style.css


* {
    box-sizing: border-box;
}
body {
    background: lightblue;
}
p {
    color: black;
}
.card {
    background: white;
    padding: 15px;
    margin: 10px;
}
#special {
    background: lightyellow;
}
h1, h2 {
    color: navy;
}
.card {
    background: lightgreen;
}

Short Explanation:

Element selector: p styles paragraphs.

Class selector: .card styles multiple sections.

ID selector: #special styles one section.

Universal selector: * applies to all elements.

Grouping selector: h1, h2 styles both headings.

Cascade & Specificity: The second .card rule overrides the first, but #special has higher specificity, so its background remains light yellow.

Submission: Submit index.html, style.css, and the short explanation above.
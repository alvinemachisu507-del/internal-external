
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Home is the best</title>

<!-- External CSS simulated in same file -->
<style>
/* External CSS: general page styling */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #eef2f7;
    margin: 0;
    padding: 0;
    color: #333;
}

section {
    max-width: 900px;
    margin: 50px auto;
    background-color: #fff;
    padding: 40px 50px;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    transition: transform 0.3s, box-shadow 0.3s;
}

section:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 25px rgba(0,0,0,0.25);
}

h2 {
    text-align: center;
    color: #2c3e50;
    margin-bottom: 30px;
    font-size: 2em;
    letter-spacing: 1px;
}

/* Paragraph styling */
p {
    line-height: 1.7;
    margin-bottom: 20px;
    font-size: 1.1em;
    transition: color 0.3s;
}

p:hover {
    color: #2980b9; /* subtle hover color */
}

/* Internal CSS for special styling */
.underline {
    text-decoration: underline;
    color: #2c3e50;
}

.italic {
    font-style: italic;
    color: #e74c3c; /* red-ish for emphasis */
}
</style>
</head>

<body>

<section>
<h2>Professional Styled Paragraphs</h2>

<p class="italic">I like chapati with Meat.</p>
<p class="underline">I like chapati with Meat..</p>
<p class="underline">I like chapati with Meat..</p>
<p>I like chapati with Meat..</p>
<p>I like chapati with Meat..</p>

</section>

</body>
</html>

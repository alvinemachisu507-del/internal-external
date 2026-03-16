<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Styled Paragraphs with Internal & External CSS</title>

<!-- Simulated External CSS (placed in <style> for one file) -->
<style>
/* External CSS part - general page styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 20px;
}

section {
    max-width: 800px;
    margin: auto;
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.1);
}

p {
    line-height: 1.6;
    margin-bottom: 20px;
    font-size: 1.1em;
}
</style>

<!-- Internal CSS for special paragraph styling -->
<style>
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
<h2>Example of Styled Paragraphs</h2>

<p class="italic">This paragraph is slanted (italic) using internal CSS.</p>
<p class="underline">This paragraph is underlined using internal CSS.</p>
<p class="underline">This paragraph is also underlined for emphasis.</p>
<p>This paragraph is normal, styled by the simulated external CSS.</p>
<p>This paragraph is also normal, just standard styling.</p>

</section>

</body>
</html>

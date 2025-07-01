## code

<!DOCTYPE html>

<html lang="en">

<head>
  
  <meta charset="UTF-8">
  
  <title>Inline vs Block Elements</title>
  
  <style>
   
   body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    .block {
      background-color: #6fc4cf;
      border: 2px solid #0c2666;
      padding: 10px;
      margin-bottom: 10px;
    }

    .inline {
      background-color: #fce4ec;
      border: 1px solid #b61e20;
      padding: 2px 6px;
    }

    .example {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <h1>Inline and Block Elements</h1>

  <div class="example block">
    <h2>Block Element: &lt;div&gt;</h2>
    <div>This is a block-level element. It takes up the full width available and starts on a new line.</div>
  </div>

  <div class="example block">
    <h2>Inline Element: &lt;span&gt;</h2>
    <p>
      This is an example of an inline element:
      <span class="inline">I am a span</span> inside a sentence. Notice how I don't break onto a new line.
    </p>
  </div>

  <div class="example block">
    <h2>More Block Elements</h2>
    <p>&lt;p&gt; - Paragraph tag (block)</p>
    <ul>
      <li>&lt;ul&gt; and &lt;li&gt; - List items (block)</li>
      <li>&lt;h1&gt; to &lt;h6&gt; - Headings (block)</li>
    </ul>
  </div>

  <div class="example block">
    <h2>More Inline Elements</h2>
    <p>
      <strong>&lt;strong&gt;</strong> and <em>&lt;em&gt;</em> are inline elements too.<br>
      Example: This is <strong class="inline">strong</strong> and <em class="inline">emphasized</em> text inline within the same paragraph.
    </p>
  </div>

  <div class="example block">
    <h2>Comparison Summary</h2>
    <p><strong>&lt;div&gt;</strong> is used to group large sections and is a block-level element.</p>
    <p><strong>&lt;span&gt;</strong> is used to style or mark inline portions of text and does not break lines.</p>
  </div>

</body>
</html>

## output
![alt text](<Screenshot 2025-07-01 125624.png>)!
[alt text](<Screenshot 2025-07-01 131553.png>)
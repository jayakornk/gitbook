# Segment

### **Shortcode Example:**

```markup
[segment tag="section" style="1" spacing="medium" id="segment-id" class="custom-class"]
[row]
[column span="12"]
<h1>Hello World!</h1>
[/column]
[/row]
[/segment]
```

### **Produced:**

```markup
<section id="segment-id" class="segment1 custom-class space-medium">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <h1>Hello World!</h1>
            </div>
        </div>
    </div>
</section>
```

### Usage:

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Attributes</b>
      </th>
      <th style="text-align:left"><b>Description</b>
      </th>
      <th style="text-align:left"><b>Options</b>
      </th>
      <th style="text-align:left"><b>Code</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Render Html Tag</b>
      </td>
      <td style="text-align:left">Element tag that is going to be produced from shortcode.</td>
      <td style="text-align:left"><em>section</em>
      </td>
      <td style="text-align:left"><code>&lt;section ...&gt;&lt;/section&gt;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"><em>div</em>
      </td>
      <td style="text-align:left"><code>&lt;div ...&gt;&lt;/div&gt;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"><em>article</em>
      </td>
      <td style="text-align:left"><code>&lt;article ...&gt;&lt;/article&gt;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Segment Style</b>
      </td>
      <td style="text-align:left">Style of each segment, defined in <b>Customize</b>.</td>
      <td style="text-align:left"><em>[1-5]</em>
      </td>
      <td style="text-align:left"><code>&lt;element class=&quot;segment[1-5] ...&quot;&gt;&lt;/element&gt;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Background Color</b>
      </td>
      <td style="text-align:left">Define segment background color. (<b>override</b> Segment Style)</td>
      <td
      style="text-align:left"><code>#hex</code>
        </td>
        <td style="text-align:left"><code>style=&quot;background-color: #hex;&quot;</code>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Background Image URL</b>
      </td>
      <td style="text-align:left">Define segment background image.</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Background Repeat</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Disable background-repeat</td>
      <td style="text-align:left"><em>no-repeat</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-repeat: no-repeat;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Repeat background only on x-axis</td>
      <td style="text-align:left"><em>repeat-x</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-repeat: repeat-x;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Repeat background only on y-axis</td>
      <td style="text-align:left"><em>repeat-y</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-repeat: repeat-y;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Repeat background only on both axis</td>
      <td style="text-align:left"><em>repeat</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-repeat: repeat;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Background Position</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">
        <p>Set origin of background image in x, y order respectively.</p>
        <p>eg. <code>top left</code>, <code>center center</code>
        </p>
      </td>
      <td style="text-align:left"><em>top, left, bottom, right, center</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-position: top left;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Background Attachment</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Scroll background normally</td>
      <td style="text-align:left"><em>scroll</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-attachment: scroll;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Prevent background to scroll (often use to create <b>Parallax</b> effect)</td>
      <td
      style="text-align:left"><em>fixed</em>
        </td>
        <td style="text-align:left"><code>style=&quot;background-attachment: fixed;&quot;</code>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Background Size</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">The background image is displayed in its original size.</td>
      <td style="text-align:left"><em>auto</em>
      </td>
      <td style="text-align:left"><code>style=&quot;background-size: auto;&quot;</code>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Resize the background image to cover the entire container, even if it
        has to stretch the image or cut a little bit off one of the edges.</td>
      <td
      style="text-align:left"><em>cover</em>
        </td>
        <td style="text-align:left"><code>style=&quot;background-size: cover;&quot;</code>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Resize the background image to make sure the image is fully visible.</td>
      <td
      style="text-align:left"><em>contain</em>
        </td>
        <td style="text-align:left"><code>style=&quot;background-size: contain;&quot;</code>
        </td>
    </tr>
  </tbody>
</table>


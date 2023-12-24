<h1>CSS Practice</h1>
<h2>Selectors</h2>
<ul>
  <li><b>Universal- </b>*</li>
  <li><b>Pseudo Classes- </b>:active, :checked, :first, :first-child, :hover, :nth-child(), :nth-of-type()</li>
  <li><b>Pseudo Elements- </b>::after, ::before, ::first-letter, ::first-line, ::selection</li>
</ul>
<h2>Styling Concepts</h2>
<ul>
  <li><b>CSS Cascade- </b>order of style declaration</li>
  <li><b>Specificity- </b>Inline-styles---------ID--------Class/Attribute--------Element</li>
  <li><b>!important- </b>most important + No calculation</li>
  <li><b>Inheritance- </b>auto + manual<i>(eg. color: inherit)</i></li>
</ul>
<h2>day_01: Position</h2>
<h5>Element is positioned according to the normal flow of the document</h5>
<ul>
  <li>
    <b>Static- </b>
    <ul>
      <li>Every element by default is position static.</li>
      <li>The top, left, right, bottom & z-index have no effect</li>
    </ul>
  </li>
  <li><b>Relative- </b>Offset relative to itself based on values of top, left, right, bottom</li>
  <li>
    <b>Sticky- </b>
    <ul>
      <li>Offset relative to its nearest scrolling block-level ancestor based on t/l/r/b values.</li>
      <li>Not fixed(start) ---> Fixed(later)</li>
    </ul>
  </li>
</ul>
<h5>Element is removed from the normal flow of the document</h5>
<ul>
  <li>
    <b>Absolute- </b>
    <ul>
      <li>No space is created for the element in the page layout i.e. it doesn't take any space in the document and is removed from the flow.</li>
      <li>Is positioned relative to its <b><i>closest positioned ancestor(which has position set to anything other static)</i></b> or to the initial containing block</li>
      <li>Final position is determined by the values of t/l/r/b</li>
    </ul>
  </li>
  <li>
    <b>Fixed- </b>
    <ul>
      <li>Is positioned relative to its initial containing block(which is the <b>viewport</b>) with exceptions.</li>
      <li>Nothing to do with any parent element or etc.</li>
      <li>It <b>stays there</b> in its position, always offset from its initial containing block</li>
    </ul>
  </li>
</ul>
<h2>day_02: Image: object-fit</h2>
<p><b>object-fit: </b> this property sets how the content of a replaced element like &ltimg&gt or &ltvideo&gt, should be resized to fit its container. Setting up &ltimg&gt's width and height set the dimension for image container not the image itself. The actual image can be scaled in different ways using this property to fit into &ltimg&gt's container(or content box).
<br>
  <b>By default: "fill"</b>
</p>
<ul>
  <li><b>contain- </b>maintains image's aspect ratio while fitting it into the container</li>
  <li><b>fill- </b>image will completely fill the container. If aspect ratio doesn't match, the image will be stretched to fit</li>
  <li><b>cover- </b>image again fills the container completely but maintians its aspect ratio by clipping itself to fit</li>
</ul>
<h2>day_03: Display: block, inline, inline-block</h2>
<p>
  - display property sets an element's inner and outer display types
</p>
<b>&ltdisplay-outside&gt</b>
<ul>
  <li><b>block</b></li>
  <li><b>inline- </b>have no effect of height, width, vertical-margins and more</li>
  <li><b>inline-block</b></li>
</ul>
<h2>day_04: Transition & Transform</h2>
<b>Transition</b><br>
shorthand for-
<ul>
  <li>transition-property</li>
  <li>transition-duration</li>
  <li>
    transition-timing-function
    <ul>
      <li>easing</li>
      <li>subic-bezier</li>
    </ul>
  </li>
  <li>transition-delay</li>
</ul>
<b><u>Syntax:</u></b><br>
transition: &ltproperty&gt &ltduration&gt &lttiming-function&gt &ltdelay&gt;
<br><br>
<b>Transform- </b>lets you rotate, scale, skew, or translate an element.

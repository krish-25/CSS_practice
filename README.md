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
  <li><b>Inheritance</b></li>
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


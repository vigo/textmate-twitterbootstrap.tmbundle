# TextMate Html Bundle for Twitter's Bootstrap
This is un-offical bundle for [Twitter's Bootstrap][bootstrap].
README.md file is not finished yet...

Well, this bundle helps you to use great features of Twitter's Bootstrap
Html/CSS framework easily.

You can check out [CHANGELOG.md][changelog] for history.

## Download & Installation
To install via Git:

    cd "~/Library/Application Support/TextMate/Bundles"
    git clone git://github.com/vigo/textmate-twitterbootstrap.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'


## TAB Triggers

### layout
There are two types of layout; Fixed and Fluid:
	
	<!-- Fixed -->
	<div class="container">
	    <div class="content">
			Content
	    </div>
	</div>

	<!-- Fluid -->
	<div class="container-fluid">
		<div class="sidebar">
			Sidebar
	    </div>
	    <div class="content">
			Content
	    </div>
	</div>

### row
Creates a `div` with a `.row` class:

	<div class="row">
		Content 
	</div>

There are also other `row` variants which includes `span` in it.
**Row > 33% [3 Spans]**

	<div class="row">
	    <div class="span-one-third">
			<p>1/3</p>
		</div>
	    <div class="span-one-third">
			<p>1/3</p>
		</div>
	    <div class="span-one-third">
			<p>1/3</p>
		</div>
	</div>

### span
Creates a `div` with a `.span` class between **1-16** Simple `span`:

	<div class="span16">
		Span
	</div>

**Span 1/3**:

	<div class="span-one-third">
		Span 1/3
	</div>

**Span 2/3**:

	<div class="span-two-thirds">
		Span 2/3
	</div>

### section, footer, container
Section and Footer creates `<section>` and `<footer>` wrappers.

	<!-- section -->
	<section id="about">
		Content
	</section>
	
	<!-- footer -->
	<footer>
		Content
	</footer>

Container creates a `div` with in a `container` class. (*Like layout*)

	<div class="container">
		Content
	</div>

### h1, h2, h3, h4, h5, h6
Creates headings with sub header text.

	<h1>Hello <small>world</small></h1>

### header
Creates page header.

	<div class="page-header">
		<h1>Hello <small>world</small></h1>
	</div>
	

### abbr
Creates abbreviation tag in single letter constrain.

	<abbr title="Phone Number">P</abbr>
	
### ady
Creates address tag in two different style.

	<address>
		<strong>Company Name</strong><br/>
		Line 1<br/>
		Line 2<br/>
		<abbr title="Phone">P:</abbr> 123-45-67
	</address>$0
	

### quo
Creates nice quotting style.

	<blockquote>
		<p>Text</p>
		<small>By Foo Bar</small>
	</blockquote>

### code, pre
Creates `<code>` and `<pre>` wrappers

### dl, dd, dt
Creates definition list and `<dd>` and `<dt>` wrappers.
	
	<!-- dl -->
	<dl>
		<dt>List</dt>
		<dd>Description</dd>$0
	</dl>

### ul, ol, li
UL has to different style: Default and Unstyled. OL creates `<ol>` and LI
creates `<li>` wrappers. 

	<ul class="unstyled">
		<li>List Item</li>
	</ul>

### table, tr, td, thead, tbody, tfoot
There are 4 different table styles available.

1. Default
2. Condensed
3. Bordered
4. Zebra

``` html
<table class="condensed-table">
    <thead>
        <tr>
            <th>#</th>
            <th>A</th>
            <th>B</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Item</td>
            <td>Item</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Item</td>
            <td>Item</td>
        </tr>
    </tbody>
</table>
```

### label


### mgrid

Creates media grid in seven different style.

	<ul class="media-grid">
		<li><a href="#"><img alt="#" src="http://placehold.it/210x90" class="thumbnail"></a></li>
		<li><a href="#"><img alt="#" src="http://placehold.it/210x90" class="thumbnail"></a></li>
		<li><a href="#"><img alt="#" src="http://placehold.it/210x90" class="thumbnail"></a></li>
		<li><a href="#"><img alt="#" src="http://placehold.it/210x90" class="thumbnail"></a></li>
	</ul>

### tabs, pills, bread, paging


### alert


### btn

[bootstrap]: http://twitter.github.com/bootstrap/
[changelog]: https://github.com/vigo/textmate-twitterbootstrap.tmbundle/blob/master/CHANGELOG.md

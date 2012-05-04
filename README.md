#flex
CSS grid that is flexible in options (including the option to make the grid flexible)

##Grid
The grid is made up of 12 columns, each 60px in size and having 10px margin on either side. This creates a 20px gutter between columns and 10px on either end.

###Core
There are 3 core pieces to the grid: .container, .row, and .columnXX
 - .container determines the size/flex of the grid and is the parent to .row
 - .row is a vertical break - each .row is stacked on top of one another
 - .columnXX is a horizontal block that can span 1-12 column(s) and is the parent of content on the page

###Basic 2 column example
A basic layout split 50/50 on the grid looks like this:

	<div class="container">
		<div class="row">
			<div class="column06">I'm the left side.</div>
			<div class="column06">I'm the right side.</div>
		</div>
	</div>
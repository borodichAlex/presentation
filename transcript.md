# 1 slide 
	Hi, I want to talk about CSS Grid Layout. This is most powerful layout system available in CSS.
# 2 slide (What is a grid?)
	Grid Layout is a new layout model for CSS that has powerful abilities to control the sizing and positioning of boxes and their contents. Unlike Flexible Box Layout, which is single-axis–oriented, Grid Layout is optimized for 2-dimensional layouts: those in which alignment of content is desired in both dimensions. Grid Layout gives us a method of creating grid structures that are described in CSS and not in HTML. It helps us to create layouts that can be redefined using Media Queries and adapt to different contexts.
# 3 slide (features grid)
	CSS grid layout has the following features:
* **Fixed and flexible track sizes.**
	You can create a grid with fixed track sizes – using pixels for example. This sets the grid to the specified pixel which fits to the layout you desire. You can also create a grid using flexible sizes with percentages or with the new fr unit designed for this purpose.
* **Item placement.** 
	You can place items into a precise location on the grid using line numbers, names or by targeting an area of the grid. Grid also contains an algorithm to control the placement of items not given an explicit position on the grid.
* **Creation of additional tracks to hold content.**
	You can define an explicit grid with grid layout. The Grid Layout specification is flexible enough to add additional rows and columns when needed. Features such as adding “as many columns that will fit into a container” are included.
* **Alignment control.**
	Grid contains alignment features so we can control how the items align once placed into a grid area, and how the entire grid is aligned. 
* **Control of overlapping content.** 
		More than one item can be placed into a grid cell or area and, they can partially overlap each other. This layering may then be controlled with the z-index property.
# 4 slide (browser support)
	Full support for all major browsers and 93.77% global usage.
# 5 slide (terminology)
	A Grid always has two axes: the Inline Axis runs in the direction that words are laid out on the page and the Block Axis in the direction that blocks are laid out.
1. subslide (grid container)
	>The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
2. subslide (gird item)
	>The children of the grid container. Here the item elements are grid items, but sub-item isn’t.
3. subslide (grid line)
	>The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.
4. subslide (grid cell)
	>The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. Here’s the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.
5. subslide (grid track)
	> The space between two adjacent grid lines. You can think of them like the columns or rows of the grid. Here’s the grid track between the second and third row grid lines.
6. subslide (grid area)
	> The total space surrounded by four grid lines. A grid area may be composed of any number of grid cells. Here’s the grid area between row grid lines 1 and 3, and column grid lines 1 and 3.
7. subslide (gutters)
	> Gutters or alleys between grid cells can be created using the column-gap and row-gap properties, or the shorthand gap.

# 6 slide (Resources)
	That's all. There is much more to CSS Grid Layout than this quick overview has shared, and the resources below will help you to learn the grid. Bye.

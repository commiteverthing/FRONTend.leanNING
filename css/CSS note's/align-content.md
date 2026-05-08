The CSS align-content property sets the distribution of space between and around content items along a flexbox's cross axis, or a grid or block-level element's block axis.

This property has no effect on single line flex containers (i.e., ones with flex-wrap: nowrap).

The interactive example below uses grid layout to demonstrate some of the values of this property.

In this article
Try it
Syntax
Formal definition
Formal syntax
Examples
Specifications
Browser compatibility
See also
Hetzner
Cloud Server in Singapore!
Starting at US$ 7.59 per month.
Try now!
Ad
Try it
CSS Demo: align-content

Reset
align-content: start;
align-content: center;
align-content: space-between;
align-content: space-around;

Syntax
css

Copy
/* Normal alignment */
align-content: normal;

/* Basic positional alignment */
/* align-content does not take left and right values */
align-content: start;
align-content: center;
align-content: end;
align-content: flex-start;
align-content: flex-end;

/* Baseline alignment */
align-content: baseline;
align-content: first baseline;
align-content: last baseline;

/* Distributed alignment */
align-content: space-between;
align-content: space-around;
align-content: space-evenly;
align-content: stretch;

/* Overflow alignment */
align-content: safe center;
align-content: unsafe center;

/* Global values */
align-content: inherit;
align-content: initial;
align-content: revert;
align-content: revert-layer;
align-content: unset;
Values
normal
The items are packed in their default position as if no align-content value was set.

start
The items are packed flush to each other against the start edge of the alignment container in the cross axis.

center
The items are packed flush to each other in the center of the alignment container along the cross axis.

end
The items are packed flush to each other against the end edge of the alignment container in the cross axis.

flex-start
The items are packed flush to each other against the edge of the alignment container depending on the flex container's cross-start side. This only applies to flex layout items. For items that are not children of a flex container, this value is treated like start.

flex-end
The items are packed flush to each other against the edge of the alignment container depending on the flex container's cross-end side. This only applies to flex layout items. For items that are not children of a flex container, this value is treated like end.

baseline, first baseline, last baseline
Specifies participation in first- or last-baseline alignment: aligns the alignment baseline of the box's first or last baseline set with the corresponding baseline in the shared first or last baseline set of all the boxes in its baseline-sharing group.

the baseline is the line upon which most letters "sit" and below which descenders extend.

The fallback alignment for first baseline is start, the one for last baseline is end.

space-between
The items are evenly distributed within the alignment container along the cross axis. The spacing between each pair of adjacent items is the same. The first item is flush with the start edge of the alignment container in the cross axis, and the last item is flush with the end edge of the alignment container in the cross axis.

space-around
The items are evenly distributed within the alignment container along the cross axis. The spacing between each pair of adjacent items is the same. The empty space before the first and after the last item equals half of the space between each pair of adjacent items.

space-evenly
The items are evenly distributed within the alignment container along the cross axis. The spacing between each pair of adjacent items, the start edge and the first item, and the end edge and the last item, are all exactly the same.

stretch
If the combined size of the items along the cross axis is less than the size of the alignment container, any auto-sized items have their size increased equally (not proportionally), while still respecting the constraints imposed by max-height/max-width (or equivalent functionality), so that the combined size exactly fills the alignment container along the cross axis.

safe
Used alongside an alignment keyword. If the chosen keyword means that the item overflows the alignment container causing data loss, the item is instead aligned as if the alignment mode were start.

unsafe
Used alongside an alignment keyword. Regardless of the relative sizes of the item and alignment container and whether overflow which causes data loss might happen, the given alignment value is honored.

Note: The <content-distribution> values (space-between, space-around, space-evenly, and stretch) have no effect in block layout as all the content in that block is treated as a single alignment-subject.

Formal definition
Initial value	normal
Applies to	Block-containers, multi-column containers, flex containers
Inherited	no
Computed value	as specified
Animation type	discrete
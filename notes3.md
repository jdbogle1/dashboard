# layouts

1. Cannot limit width easily on inline elements
2. Block level elements allow width BUT
> Text can exceed the boundaries of its container
> This is due to the default value of `overflow: visible'
3. Understanding `overflow` and the need for it due to markup/css behaviour is important
4. To make something `resize:`, `overflow` must be set too.
5. Remember to stick to one mindset, if you are using `float` then all participant `div`s need this set, otherwise they cannot horizontally stack. Alternative approaches are flexbox and cssgrid.
5. `clear` can be used to ensure an element does not have anything to its side e.g. `clear: left` would make it drop to the next line, even if it has `float: left`


# Approach 1

Just using the `resize` property, but ony works on bottom right corner.

# Approach 2

Make the divider into a `div` itself so that it occupies its own space, and gives the option to add a resize curor symbol across the full vertical length.
TAAdaptiveSpaceItem
===================

An NSToolbarItem subclass which creates a space that will center the next toolbar item.

This class is useful when you need to center an item in a NSToolbar. For example, you may wish to have some items on the left hand side, a search bar on the right hand side and a segmented control centered in the middle.

Using a Flexible Space toolbar item on each side of the centered item doesn't work since the total width of the items on the left and right hand sides is unlikely to be the same. Instead, you can insert a TAAdaptiveSpaceItem just before the item to be centered, and a Flexible Space item afterwards.

Usage
-----

Add the .m and .h files for TAAdaptiveSpaceItem and TAAdaptiveSpaceItemView to your project.

If you're using Interface Builder add an "Image Toolbar Item" to your toolbar and set it's class to be TAAdaptiveSpaceItem. Move it so that it's placed just before the item to be centered.





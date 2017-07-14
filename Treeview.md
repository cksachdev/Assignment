## Problem statement
Making YUI2 treeview accessible.

#### Goal
You should be able to navigate on treeview using just Keyboard and listening to Screenreader instructions. Here is an example http://oaa-accessibility.org/example/42/

#### Treeview documentation
http://yui.github.io/yui2/docs/yui_2.9.0_full/treeview/

#### Treeview API documentation
http://yui.github.io/yui2/docs/yui_2.9.0_full/docs/module_treeview.html

#### Example usage:
* http://yui.github.io/yui2/docs/yui_2.9.0_full/examples/treeview/tv_highlight.html
* http://www.libraryinformationsystem.org/yui2/examples/treeview/tv_markup.html

#### Sample JSON for testing and creating treeview
You can use any treeview json, below is a sample just for your reference.
```
[{"expanded":true,"type":"TextNode","children":[{"type":"TextNode","children":[{"type":"TextNode","label":"label-0-0-0"},{"type":"TextNode","label":"label-0-0-1"}],"label":"label-0-0"},{"type":"TextNode","children":[{"type":"TextNode","label":"label-0-1-0"}],"label":"label-0-1"},{"expanded":true,"type":"TextNode","children":[{"type":"TextNode","label":"label-0-2-0"},{"expanded":true,"type":"TextNode","label":"label-0-2-1"}],"label":"label-0-2"},{"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-0-3-0"},{"type":"TextNode","label":"label-0-3-1"}],"label":"label-0-3"}],"label":"label-0"},{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-1-0-0"}],"label":"label-1-0"}],"label":"label-1"},{"type":"TextNode","children":[{"expanded":true,"type":"TextNode","children":[{"type":"TextNode","label":"label-2-0-0"}],"label":"label-2-0"},{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-2-1-0"}],"label":"label-2-1"}],"label":"label-2"},{"type":"TextNode","children":[{"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-3-0-0"},{"type":"TextNode","label":"label-3-0-1"}],"label":"label-3-0"},{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-3-1-0"}],"label":"label-3-1"},{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-3-2-0"},{"expanded":true,"type":"TextNode","label":"label-3-2-1"}],"label":"label-3-2"},{"type":"TextNode","children":[{"type":"TextNode","label":"label-3-3-0"}],"label":"label-3-3"}],"label":"label-3"},{"type":"TextNode","children":[{"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-4-0-0"},{"expanded":true,"type":"TextNode","label":"label-4-0-1"}],"label":"label-4-0"}],"label":"label-4"},{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","children":[{"expanded":true,"type":"TextNode","label":"label-5-0-0"},{"type":"TextNode","label":"label-5-0-1"}],"label":"label-5-0"},{"type":"TextNode","children":[{"type":"TextNode","label":"label-5-1-0"}],"label":"label-5-1"},{"expanded":true,"type":"TextNode","children":[{"type":"TextNode","label":"label-5-2-0"}],"label":"label-5-2"}],"label":"label-5"}]
```

### About ARIA attributes for treeview component
You should have an understanding of following aria attributes after going through the links below:
1. aria-level
2. aria-posinset
3. aria-setsize
4. aria-owns
5. aria-selected
6. aria-label
7. aria-expanded
7. role
8. state
9. name

* https://www.w3.org/TR/wai-aria-practices-1.1/#TreeView 
* http://oaa-accessibility.org/example/42/



### Reference
http://ydn-javascript.yahoogroups.narkive.com/71xGuZ5M/aria-and-the-yui-treeview

### Testing
Download JAWS on a Windows machine and test
http://www.freedomscientific.com/Products/Blindness/JAWS







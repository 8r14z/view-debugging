# view-debugging

### Prerequisites
Setting debug mode to Objective-C by this cmd
```
(lldb) settings set target.language objective-c
```
Later then, setting it back to Swift
```
(lldb) settings set target.language swift
```

### Commands
- **\-\[UIView recursiveDescription]**: method to print view hierarchy of current view and its subviews

- **\-\[UIView \_parentDescription]**: method to print view hierarchy of current view and its parents

- **+\[UIViewController \_printHierarchy]** (class method):  get view hierarchy of all view controllers and their states

- **(lldb) e dump(T)** for Swift | **\-[UIView \_ivardescription]** for Objective-C

To print state of an object

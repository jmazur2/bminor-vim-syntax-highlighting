# Bminor syntax highlighting in vim

Simple syntax highlighter written in vimscript for the [Bminor language](https://www3.nd.edu/~dthain/courses/cse40243/fall2019/bminor.html).
This is a bit too little, too late as the course recently ended a few weeks ago. I had wanted to make this during the semester to
make reading and writing Bminor code a bit easier, but didn't find the time. I figured I might as well make it now that I have time over winter
break so I can at least learn some more vimscript.

## How to use it

You must have the `syntax` and 	`ftdetect` folders in the top level of your `~/.vim/` folder. `syntax` defines keywords and regular
expressions to match things like strings, operators, numbers, etc., and highlight them appropriately. `ftdetect` just checks a file's
extension, this case `*.bminor`, and uses the appropriate highlighting.

## Example

![](https://yld.me/raw/W3u.png)


## todo

- multiline C-style comments not being caught in regex
- multiply and divide operators conflict with C-style comments
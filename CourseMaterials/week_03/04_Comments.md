# Comments
Comments in code allow developers to leave information that is for other human developers only. Computers and processors ignore comments in code. 

I am sure you can think of a number of reasons why you may want to include comments in code?

Let’s go over a few reasons why you may want to include comments in your code.

1. First and foremost, comments convey information about code. 
	- Typically, this means _why_ some code was written in a certain way. 
	- This may also point out information to other developers who may be collaborating on code together. 
2. Comments can be used to remind you want you are working on. You may make notes to yourself about the goal of your work or how you think you may go about solving a problem.
3. Comments can be used to remind you what _else_ you have to do. A very common use of comments is to place “`TODO: `“ within your code along with what it is you still need to _todo_. There are even packages from editors, such as Atom, that can [show you a list of your remaining TODO’s](https://atom.io/packages/todo-show) in a project or simply [highlight your TODO’s for you to easily see](https://github.com/atom/language-todo). 
4. **They are a way for you to communicate intention and thought to the instructors grading your homework this semester!!!**

## Comments in HTML
Comments are designated slightly different in every language. In HTML however, as with everything else, they are designated using a tag. Anything placed within this tag will be ignored by the browser. (NOTE: comments are not hidden from other _people_. Comments, if included in your deployment code, will be available for the whole world to see.)
```html
<!-- This is an HTML comment -->
<!-- Everything placed between the 'dashes' is part of the comment. -->

<!-- comments should not span multiple lines in HTML.
		sometimes this can cause issues for a browser's processor. 

		This comment is considered as bad styel -->

<!-- Instead, -->
<!-- You should place each line of a multi-line comment within a comment tag -->
<!-- That would be considered proper style -->
```
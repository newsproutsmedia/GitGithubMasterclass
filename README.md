## SUPER BASIC WEB PAGE FOR PURPOSE OF IMPROVING GIT SKILLS

There's literally nothing to this code. I'm purely using it as a canvas to practice git concepts.


# For example... here's a _bunch_ of **markdown**:

# Header 1 is made with a single pound
## Other, smaller headers
### Can be made
#### By adding more
##### Pound
###### Signs (up to six)

## Lists and Text Formatting

Like this unordered list:
- As you just saw, you can add _italics_ by using _single_ underscore or asterisks.
- **Bold**, however, uses **double** underscore or asterisks.
- If you want **_bold and italic_** you just combine the two!
- Now, if you've made a ~~Merstake~~ mistake, you can strikeout text with a double-tilda.

If you want to add another list, you have to remember to add spacing between the previous bulleted item and the non-bullet text.

+ You can also use plus signs or asterisks
+ For unordered lists

If you want to have multiple lists, just use the different symbols back to back (to back)
+ Here's the first
+ set of list items
- and the second
- set of list items
* and here's
* the third

And, obviously, you can do numbered lists:
1. All you have to do
2. Is add the number
3. At the front of the line

Sublists can be accomplished by offsetting the sub lists using 3 spaces
1. Spacing, however, is platform-independent
   - GitHub requires 3 spaces
   - But other platforms
   - Can use different spacing
2. You can mix different types of sublists (bullet and number -- or roman numeral)
3. And you can create sub-sublists, too
   * Just do a second level of offsetting lines
   * Keep indenting
      1. To add more
         * Sublists
            1. Like this
      
1. You can have a number on top
   * Followed by a bullet
      
Or...
* You can have a bullet
   1. Followed by a roman numeral
      
1. Or a number
   1. Followed by a number
      1. Followed by a letter
         * Followed by something else

## Tasks

You can make tasks through the simple use of brackets:
- [ ] Here's a task
- [X] This one is completed already

## Tables

Creating tables is easy

Column Header | Another one
--- | ---
The previous line | needs at least three dashes
for each | column

Header 1                         | Header 2     | And here's a really long header
-------------------------------- | ------------ | -------------------------------
you can also                     | align things | in the code editor
so it looks better while editing | but it's     | not necessary
it makes no difference           | to the       | output

You can align | columns | through use of colons
:------------ | :-----: | --------------------:
left aligned  | centered | right aligned

## Links

Adding | Links
:--- | :---
[My Site](http://newsproutsmedia.com) | [Another Site](http://www.natewalters.info)

Links don't have to be displayed in a table.
You can also add links [like this](https://www.linkedin.com/in/nbwalters/)

## Images

### You can add images from external sources

Linux Icon | MacOS Icon | Windows Icon
--- | --- | ---
![](http://www.myiconfinder.com/uploads/iconsets/256-256-75e6bbae408b4149f47496c4e60af903.png) | ![](http://www.myiconfinder.com/uploads/iconsets/256-256-8b8258a1b7427a1deb3617406a1b4d01.png) | ![](http://www.myiconfinder.com/uploads/iconsets/256-256-e0ded59725330fc9e9d623d8325499b4.png)

### Or you can add them from your own GitHub account

Apple Icon | Android Icon | Ubuntu Icon
--- | --- | ---
![](/images/apple_logo.png) | ![](/images/android_logo.png) | ![](/images/ubuntu_logo.png)

## Videos

You can even link to a video! Click on the image below to watch on Vimeo:

[![Gerber ExtensiveHA Promo Video](/images/Gerber_ExtensiveHA.png)](https://vimeo.com/391046251)

## Displaying Code

Here's a developer's favorite section. To display code...

To display code inline `<a class="your-code">Use the accent character</a>`.

To display a code block, use three accents before and after:

``` html
<html>
   <head>
      <title>Adding a code block</title>
   </head>
   <body>
      <div class="container">
         <h1>Adding code to a code block</h1>
         <p>It's really easy to add code to a code block. Just use three accents before and after the block.</p>
         <h3>Make it language-specific</h3>
         <p>Add the tag for the language you want after the first accents. In this case "html".</p>
      </div>
   </body>
</html>
```

Markdown allows code blocks in a variety of languages
``` java

class MarkdownDemo {

   private String exampleText = "Here's an example using Java";

   private void javaExample() {
      System.out.println(exampleText);
   }

}

```

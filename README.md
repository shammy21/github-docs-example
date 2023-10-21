# Writing Good Documantation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to __copy, paste, and share__ code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Becasue it allows other to copy and paste their code to replicate or research an issue.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confussed with quotation (')


```
# Define a Person Class
Class Person
  #  Constructor
def initialize(name, age)
  @name = name  #  Instance variable for the person's name
  @age  =  age  #  Instance variable for the peerson's age
end

#  Instance method to return a greeting
def greeting
  "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

-  When you can you should attempt to apply syntax highlighting to your codeblocks

  ```ruby
# Define a Person Class
Class Person
  #  Constructor
def initialize(name, age)
  @name = name  #  Instance variable for the person's name
  @age  =  age  #  Instance variable for the peerson's age
end

#  Instance method to return a greeting
def greeting
  "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

-  Make note of where the backtick button is located. It should appear above the tab key
-  But it may vary based on your keyboard layout

<img width="200" src="https://github.com/shammy21/github-docs-example/assets/28939511/c0866d0c-e17a-4608-b9b0-9c703a696b3e" />

Good Cloud Engineers use codeblocks for Code and Errors that appear in the console.

```bash
Traceback (most recent last call):
        2: from /usr/bin/irb:23:in `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

>Here is an example of using a codeblock for an error that appears in bash.

##  Step 3 Use Github Flavored Makrdown Task List

Github extends Markdown to have a list where you can check off items [<sup>[3]</sup>](#external-references)

-  [X]  Finish Step 1
-  [ ]  Finish Step 2
-  [ ]  Finish Step 3

##  Step 4 Use Github Flavored Makrdown Use Emoji 
Github Flovered markdown (GFM) supports emoji shortcodes. [<sup>[4]</sup>](#external-references)

Here are some examples:

| Name | Code | Emoji |
| ---- | ---- | ----- |
| cloud with lighting and rain  | `:cloud_with_lightning_and_rain:`  | ⛈️    |
| wind face | `:wind_face:`  | :wind_face:   |
| tornado  | `:tornado:`  |🌪️   |

##  Step 5 How to create a table 

You can use the following markdown format to create tables: 

```md
| Name | Code | Emoji |
| ---- | ---- | ----- |
| cloud with lighting and rain  | `:cloud_with_lightning_and_rain:`  | ⛈️    |
| wind face | `:wind_face:`  | :wind_face:   |
| tornado  | `:tornado:`  |🌪️   |
```

Github extends the functionality of Markdown Tables to provide more aligment and table cell formatting options. [<sup>[5]</sup>](#external-references)



##  External References
-  [Github Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[1]</sup>
-  [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>[2]</sup>
-  [GFM - Task List ](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists) <sup>[3]</sup>
-  [GFM - Emoji CheatSheet ](https://github.com/ikatyang/emoji-cheat-sheet) <sup>[4]</sup>
-  [GFM - Tables (with extensions) ](https://github.github.com/gfm/#tables-extension-) <sup>[5]</sup>


# Writing Good Documentation
- basic lists are good by prepending (-) to a statement
- 
## Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, & share code**.
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy paste code to replicate or research the issue

If you use sinlge quotes instead of back ticks, it will not look right.
'''
an example of using quotes
'''


(this is upper left on the keyboard, below the Escape key, these are 3 back ticks)
```
# an example of using back ticks
# Create an empty list to store the values
value_array = []

# Input the first value from the user
value1 = input("Enter the first value: ")

# Input the second value from the user
value2 = input("Enter the second value: ")

# Append the values to the array
value_array.append(value1)
value_array.append(value2)

# Print the array to verify the values are stored
print("Array with input values:", value_array)
```
If you add color to the syntax to make it readable, append the language to the top line with the 3 (`)
```Python
# an example of using back ticks
# Create an empty list to store the values
value_array = []

# Input the first value from the user
value1 = input("Enter the first value: ")

# Input the second value from the user
value2 = input("Enter the second value: ")

# Append the values to the array
value_array.append(value1)
value_array.append(value2)

# Print the array to verify the values are stored
print("Array with input values:", value_array)
```
## Adding a picture 
Adding a picture is also helpful
the format is 
```
![<Alt Text>](<PathToImage>)
# or once it's been put in place you can use a reference
![<Alt Text>](reference)
```
![terraform](assets/terraform_iac_hotpot-ai.png)

If you want, you can use the normal html method to put the image into your document and even change the size of it.

<img width ="200px" src="https://github.com/LabminMe/github-docs-example/blob/main/terraform_iac_hotpot-ai.png">

## Showing Errors
Good Cloud Engineers show errors that show up in code blocks with 'bash' identified in it for reference when trying to alert or get help from others.
```bash
# Attempting to divide by zero, which will raise an error
result = 10 / 0

# This line will not be executed because of the error
print("This line will not be printed due to the error.")
```

> This quoted segment is an example of a bash notated error of Python

When you can, copy errors and put them into code blocks. If you cannot or need the picture as well, use a screenshot. Phones are not the best at taking this action.
## Step 1 - How to take screenshots
A screenshot is when you capture part of the screen using an utility, and is not a photo of your screen with a camera or your phone. 
**Good Screenshot[^1]**

![Good Picture](assets/GoodScreenshot.png)

**Bad Screenshot**

![Bad Picture](assets/BadScreenshot.png)

### How to take screenshots
**Windows:**

Using PrtScn (Print Screen) key:

Press the PrtScn key on your keyboard to capture the entire screen.
Press Alt + PrtScn to capture only the active window.
The screenshot is copied to your clipboard, and you can paste it into an image editor (like Paint) or any other application (e.g., Word).
Snipping Tool (Windows 7, 8, 10):

Search for "Snipping Tool" in the Start menu.
Open the Snipping Tool application.
Click on "New" and select the area of the screen you want to capture.
Save or copy the captured screenshot.
Snip & Sketch (Windows 10):

Press Win + Shift + S to open the Snip & Sketch tool.
Select the area you want to capture.
The screenshot is copied to your clipboard.
**macOS (OS X):**

Using Keyboard Shortcuts:

Press Shift + Command + 3 to capture the entire screen. The screenshot is saved on your desktop.
Press Shift + Command + 4 to capture a selected portion of the screen. You'll be prompted to select the area.
Press Shift + Command + 4, followed by Space, to capture a specific window. Click on the window you want to capture.
Using Grab (preinstalled):

Search for "Grab" in the Applications > Utilities folder.
Open Grab and select "Capture" from the menu to take screenshots with more options.
**Ubuntu (Linux):**

Using GNOME Screenshot (default):

Press PrtScn to capture the entire screen.
Press Alt + PrtScn to capture only the active window.
The screenshots are saved in your Pictures folder.
Using Shutter (installable):

If not already installed, you can install Shutter using the package manager.
Open Shutter, and you can capture screenshots with advanced options and editing capabilities.

## Step 3 - Use GitHub Flavoured Markdown Task Lists
Github extends Markdown to have a list where you can check off items.[<sup>[1]</sup>](#references)
- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Using emojis!
GitHub Flavoured Markdown (GFM) support emoji shortcodes [<sup>[2]</sup>](#references)

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud w/Lightning | `:cloud_with_lightning:`  | 🌩️ |
|  |  |  |

## Step 5 - Building a table
GFM has options for creating tables! [<sup>[3]</sup>](#referenes)
Here is a codeblock of the previously created table of emojis
```md
| Name | Shortcode | Emoji |
| Cloud | `:cloud:` | ☁️ |
| Cloud w/Lightning | `:cloud_with_lightning:`  | 🌩️ |
|  |  |  |

```



## Citing our Sources by creating References
- [GitHub Flavored Markdown Spec](https://github.com/gfm) 
- [Basic Writing & Formating (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/) <sup>[2]</sup>
- [GFM - Tables w/Extensions](https://github.github.com/gfm/#tables-extension-) <sup>[3]</sup>

## Foot Notes ##
[^1]: Good Screenshot

# Prettify your JSON files in Sublime Text

## What is it for?

Kinda bored with how my .json files appear in Sublime Text. I found a solution from this page, https://github.com/shaunakv1/twilight-tmTheme-better-json-highlight

I copied few lines from his xml code that is used for updating the colors of a json object. I wasn't sure if it was going to work because I was using a different theme, AfterGlow. Fortunately, it worked and I'm happy to share it with you!

I thought I'd document it in case I'll build a new development machine as well as help other developers looking for similar solution. It took me a while yesterday finding a solution.

## Updating your theme

To get your .json files rendered nicely in Sublime Text, you will need to add the codes from attributes-for-json.xml file into your theme file. And yes, you're right, I had the same question, where can I find the theme file.

First you have to know which theme you installed and which one is currently active. In my case, I installed AfterGlow and it's the active theme but this was way back before I finally decided that my json should have colors. So I've been using AfterGlow for quite sometime.

Anyways, on SublimeText's menu on top, click Preferences -> Browse Packages. When I did this, it opened the Packages window containing different folders. Click on User -> then click on Color Higlighter -> then finally click on themes folder. I have 2 files, Afterflow.tmTheme and Monokai(SL).tmTheme

Open the appropriate theme file. It's an example. It's an xml file so better not ruin it when you paste the code from our attributes-for-json.xml. I just put mine before `</array>` then I saved it. Right after saving it, the json file was beautified. :)

## JSON before the changes
![Image of Before Changes](/before.png)

## JSON after changes
![Image of Before Changes](/after.png)


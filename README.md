# README template-2020
## How to use

Look closely at the files in this repository. 

You will see a number of files are named with the .md file extension. That is: **index.md**, **page2.md** … **page5.md**. 

### .md files explained

.md stands for MarkDown. You don't need to use the markdown language, and we don't introduce it here. But, there are many features and advantages of these .md files:

* .md files are automatically converted to HTML files when you publish them.

* When you edit the .md files, you are only editing the content for the BODY part of your pages. The system will automatically insert the content of your md files into the HTML of your pages.

* You still need to use HTML tags in your .md files, but only the tags you use in the body of the document. E.G.: `<h1>`, `<h2>`, `<p>`, `<hr>`, `<img>`, `<video>`, `<iframe>` etc..

* The big advantage of .md files is that editing these won't affect the architecture and structure of your main HTML template. However, it's important to be aware of renaming these files. 

### Other essential files

1. **HTML Template** : The HTML template file of your site is named **default.html** and is located in the **&#95;layouts** folder. You will only need to edit this slightly to name the labels of your navigation bar.  Apart from that, you won't need to edit the HTML template at all.

1. **Stylesheet** : In the folder **assets/css**, you will find the **style.scss** file. .scss is a varient of css and works in the same way. You can edit this file to create custom styles for your site. For example, you will be able to change the colours of your banner, and make any other style adjustments you choose.

1. **images** : This is the directory to store your image files. Inside the images folder you can find a **readme.md** file explaining how to use this directory.

1. **Config file** : Finally, the **&#95;config.yml** file is a configuration file, where you modify the settings for your site. You also use this file to set the mappings for your pages to the navigation bar.

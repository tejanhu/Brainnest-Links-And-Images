# Assignment(Links & Images):
# a. Create a new directory named links-and-images
# b. Within that directory, create a new file named index.html
# c. Fill in the usual HTML boilerplate
# d. Set the title to “Links & Images”
# e. Finally, add the following h1 to the body: `<h1>Homepage</h1>`
# f. Create another HTML file named about.html
# g. Back in the index page, add the following anchor element below the `<h1>` element: `<a href=”https://theuselessweb.com/”>``click me</a>``<a href="about.html">About</a>`

# h. Open the index file in a browser and click on the About link to make sure it is all wired together correctly. Clicking the link should go to the empty about page you just created (you can fill it in if you like)

# i. Create a directory named pages within the links-and-images directory and move the about.html file into this new directory. Refresh the index page in the browser and then click on the about link. It will now be broken. This is because the location of the About page file has changed. To fix this, you just need to update the about link href value to include the pages directory since that is the new location of the about file relative to the index file. `<a href="./pages/about.html">About</a>`

# j. In many cases, this will work just fine; however, you can still run into unexpected issues with this approach. Prepending ./ before the link will in most cases prevent such issues. By adding ./ you are specifying to your code that it should start looking for the file/directory relative to the current directory. You can also add a link to get back from the About page to your homepage

# k. To use images on your own websites, you can use a relative path:

# i. Create a new directory named images within the links-and-images project
# ii. Next, download any image .jpg/.png and move it into the images directory you just created
# iii. Rename the image to first-img.jpg/.png
# iv. Add the image to the index.html file: `<img src="images/first-img.jpg">`
# v. Save the index.html file and open it in a browser to view your image in all its glory. Remember to use ./ before the images/first-img.jpg if your image isn’t loading

# l. As a bit of practice, add an alt attribute to the first-img you added to the links-and-images project.
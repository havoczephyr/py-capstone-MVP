# Soul Level Eight

Hello My name is Giovanni D'Amico, I'm a Python student here at DevMountain and Im here to introduce you to my project, Soul Level Eight!

**Twitch** is a streaming service with as of 2021, over 2 million concurrent viewers. it's a multi billion dollar industry and a fast growing service in the current age. Not that it was specifically the reason I wanted to build this project, because I do think streaming can be a heck of lot of fun. 

In that light, I wanted to develop a blog that would allow for greater interactivity with viewers. a data-driven web page providing stats and details of the run for viewers to read through and immerse themselves into the runner's stream.

And thus was born Soul Level Eight.

Soul Level Eight is a streaming blog for the Twitch User Havoc Zephyr for the all time classic video game "Dark Souls". In "Dark Souls" difficutly is challenging and its beautiful grim dark fantasy world holds many surprises for the player. additionally the player can also customize their character in various ways to face the challenges ahead of them.

Normally most Dark Souls streamers usually suffice with a "death counter" which, in most circumstances is a "Tally System" where pressing a button just increases a number by one. By utilizing a very potent piece of injection software called "Cheat Engine", I can show alot more data, and with far greater accuracy.

"Cheat Engine" allows me to view the in memory variable data inside of the memory addresses of a piece of running software. utlizing customized "Cheat Tables" I can see exactly what each variable means and extract XML tables from the software by Copying the data from its generated system.

Soul Level Eight then allows you to convert that XML data into "timeline entries" that show much more then just how many deaths the player had, Soul Level, what Attributes they have, armor, weapons, their playtime in milliseconds. graphs showing variation between runs and even maps showing current bonfire locations!

Additionally SL8 Staff can post announcements of coming events and recent news on the home page.

Login Policies prevent any registered user from accessing those parts of the site without the necessary permissions. So Timeline Entries and Announcements are only submittable by SL8 Staff

Soul Level Eight was built in Python, utilizing the Flask Microframework. Alongside Flask, Bcrypt and Flask Login was used to generate a functioning login system, WTForms provide the library for forms and validation, MatPlotLib was used to generate the graphs and customized images, Pillow for the ability to customize user profile pictures, Sqlite as the database structure for the site and SQLAlchemy as the ORM framework, with its very powerful Model system.

There were many challenges I had to face building this project, between the various ORM queries I had to perform, learning how to make graphs, Jinja's fantastic systems, Bootstrap for CSS, but I hope you share my joy in seeing this project come to fruition. Thank you, and Take care!
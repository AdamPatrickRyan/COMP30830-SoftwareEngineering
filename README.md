# COMP30830-SoftwareEngineering
 
Howdy! If you're reading this, you've probably ended up here because you're studying an MSc in Computer Science in UCD, and are looking for some tips on how to go about the Software Engineering project.

Unfortunately while I don't have pictures of the end result or a setup guide for this app (although it hopefully should be fairly intuitive to follow), a few helpful suggestions I'd make for this which I found very helpful:

1. This Repo contains an Import File for our Team's Confluence: https://www.atlassian.com/software. You can use Confluence to automatically export a full PDF report of documentation for the project if you've maintained it. I highly recommend Jira and Confluence for managing aspects of the project. Checkout the PDF report if you want to see what our structure was like for the management section; you can always import it for the layout/nesting structure and fill it in yourself appropriately. This should hopefully help give an idea of how we managed our documentation which is worth as much as the application itself!

2. Definitely(!) make sure you model the data first. A key problem you might encounter fairly early on is that as you pull station data, you'll notice that what appears to be duplicates come in (hint: my view is they're not - the data just hasn't changed at the station). Find a way to note when your scrapers run. This will also be very valuable because you'll be pulling weather data as well. You need some way to join the weather you pulled at a certain time to the bike data at that time. Data modelling can really help you understand how the data components of your app will fit together, and makes it much easier later on as it helps you avoid some overcomplicated code.

3. I found it really useful to timebox my work on the project; there's five other modules in the semester, and while this one takes a lot (and is a lot of fun) try to stop it from taking all of your time and devote some time to other modules too.

4. We went with an sql.py heavy approach instead of a models.py approach largely because I find it much quicker to write and work with SQL, but don't feel you need to do it this way!

5. The database we collected and the scrapers we used with our structure is available in this repo; feel free to import it into MySQL if you want to see how we connected everything (or check out our Confluence Report) or you want to get data for March-June(ish) 2021 for weather and bike data.

6. Don't plagiarise.

Any questions, feel free to reach out!
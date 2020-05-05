![BQ logo][bqlogo]

# Coding challenge

Greetings iOS lover!

If you have made it so far, that means that it's time to show your coding skills to us.

As you probably already know, BQ is a company known for working on really different kind of projects: backend-based apps, IoT, robotics, 3D printing, camera, eBooks, etc.

For this challenge we want you to put in practice daily knowledge related to iOS development with freedom to pick you own architecture, stack of libs that you usually used and event design decisions regarding UI. Actually, we want to see them as well as why you took them. So please write a `README` containing your development decisions within your repository in Markdown style.

The **only requisite is to use Swift** as the programming language: we try to avoid as much as possible the old grandpa-C.

So, now that we are ready to go, let's start!

# Marvel Popularity Contest

Do you like Marvel characters? Do you know who of them is the most famous? Some suprises could be hidden behid so much attention due to the movies...

For that reason, we want you to build an app to create a ranking of Marvel characters by battling them using their popularity as their only weapon.

All the information that you need to build it can be found in the [Marvel Developer Portal by using its public API](https://developer.marvel.com/).

The app should have the following screens:
- **Search**: a way to search characters by `name` with a list showing the results. By clicking in any of the resulted items, the app should navigate to the *Character profile*.
- **Character profile**: a detailed view in which the `thumbnail` of the character, along with his/her/its `name` and `description`.
- **Arena**: this screen should allow the user to search and pick 2 characters to battle them. The power level will be determined by the total issues in which the character has appeared. The result of the combat should be shown to the user by using a popup with a button to navigate to the *Ranking*. Both characters involved in the battle will be saved to be shown in the *Ranking*.
- **Ranking**: this screen should show a list of characters that have had already a battle. The list will be sorted by their power which should be equal to the of total `available` issues (comics) featuring this character. The list should be available offline. Again, if one of the character items is clicked, the app should navigate to the *Character profile*. 

Ready to battle?

# Extra points

Apart from developing the app, we would positively value if you can implement a set of basic tests via **XCTest** and/or **XCUITest**. Some examples could be:
- Check that without Internet connection an alert is shown to the user when searching for characters.
- Check that without Internet the *Ranking* shows previous characters invovled in battles.


---

# Attribution

Data provided by Marvel. © 2014 Marvel

[bqlogo]:https://storage.googleapis.com/bqcom15.statics.bq.com/bqcom/static/Pressroom/logos/logoandsymbol/BQlogosymbol200x200.jpg


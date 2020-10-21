# birthdaycard
A simple birthday card made in HTML, CSS and JavaScript, utilising the typed.js library.<br>
Made by [geneva](https://github.com/geenva) and [Lake The Eevee](https://github.com/LakeTheEevee). Well, mostly [geneva](https://github.com/geenva).<br>
Thanks to [Vixen](https://github.com/Vxxen) for the help with typed.js. 

[Take a look at the demo here](https://birthdaycard.marcuscodes.me)

## How do I use this?
Fork this repository. Edit the <em>(person)</em> part in `index.html` to your intended audience. Next, edit `wishes.html`, and edit this from:
```
    var typed = new Typed('.typed', {
        strings: [
            "We hope you have a great day...",
            "a long life...",
            "always pretty...",
            "healthy...",
            "happy...",
            "and most importantly,",
            "lovely."
        		       ],

```
<br>
...to something like this.<br>

```
    var typed = new Typed('.typed', {
        strings: [
    "You're a nice person.",
    "You are wonderful."
        ],
```

<br>

Lastly, edit `love.html`. Replace the name `Marcus` with your name.

<br>

NOW THIS IS THE IMPORTANT PART. Go to the Settings part of your repository, scroll down to the GitHub Pages section, and for source, <b>select the main branch, and for the directory, select "/".</b>. <br><br>Click Save. Don't choose anything for themes - leave it there. <br><br> You should see something like 
"Your site is published at site." That's it. Wait for a few minutes, and click on the link. You should see it deployed there. Enjoy!

### To Do

* [ ] Allow input via URL to state the person who this is sent to (e.g. https://geenva.github.io/birthdaycard/?name=John/)

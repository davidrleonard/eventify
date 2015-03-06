An event screen thingy
======

This is a simple event screen. Pass it a few url parameters and you'll get a pretty, color-changing display you can put up at events

# Use it on the web

Open up a new browser and point it [at this url](http://davidleonard.me/eventify/):
```
http://davidleonard.me/eventify/
```

To set the text, just pass in some url parameters for `name` and `description` [like this](http://davidleonard.me/eventify/?name=Your%20Event&description=What%20a%20great%20event):
```
http://davidleonard.me/eventify/?name=Your%20Event&description=What%20a%20great%20event
```

Make sure you throw `%20` in to replace spaces.

# Use it on your computer

```
git clone [repo-link]
cd eventify
python -m SimpleHTTPServer
```

Open a browser window and point it at the url and port printed out by Python in your terminal.
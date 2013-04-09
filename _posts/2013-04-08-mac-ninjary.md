---

title: Mac Ninjary 101
layout: video
categories: morning-sessions
tags: productivity mac
video-id: 63657814

---

In case you haven't noticed, the Scholars' Academy has a lot of computers. In addition, a fair number of those computers run Mac OS X (the most popular operating system in the school is iOS, in case you were wondering). It's worth getting comfortable with Mac OS X. You can do a lot of really cool stuff with it. More importantly, if you are going to be stuck in front of it for the next few years, you might as well be able to work quickly and efficiently with it.

## What We're Going to Cover

* About This Mac
* Finding Stuff with the Finder
* The Elusive Nature of the Menu Bar
* The Finer Points of the Dock
* The Bat Signal: Spotlight
* Learning and Loving Keyboard Shortcuts
* When All Else Fails: Force Quitting and Restarting
* Right-Clicking in a One-Button World
* Proxy Moxie: Getting the Proxies Working
* How to Take a Screenshot

## Common Misconceptions

* Most of the time, the amount of data you have on your hard drive will not slow down your computer (unless you have less than like 5% of the space left, then it will actually bring your computer to a screeching halt).

## About This Mac

Sometimes, bad things happen to good people. Sometimes bad things happen to mediocre people. I'm not here to make a judgement call on what kind of person you are. But, when something goes awry with your Mac, the people trying to help might have some questions for you.

A lot of these questions can be answered by visiting the `Apple Menu` and clicking on `About This Mac...`. If you click on the version number, it will also show you the serial number for the computer as well as a lot of other things. This kind of information goes a long way when you're trying to explain something.

![About This Mac](/img/2013-04-09-about-this-mac.png)

## The Finder

Finder is an application built into Mac OS X. He's that blue little guy at the left end of your dock and his job is to help you find stuff. He's been around since 1984. We're the same age, actually.

Some things you can do with the Finder:

* Eject disks
* Add stuff to the side bar
* Take a whole bunch of files and move them into a new folder
* Renaming files

If you want to rename a file. Click on the title of the file or just click on the file and press `Return`.

If you want to select more than one file, hold `Command` and click on the files.

If you want to take a whole bunch of random files and move them to a common folder. Select the files and go to `File > New Folder with Selection`.

## The Menu Bar

The menu bar changes depending on what application you're in. Also: closing all of the windows in an application doesn't necessarily exit the application. This may seem annoying until you realize you can close that monsterous iTunes window and the music will keep playing.

Also: Mac OS X is really smart about memory management, so stop fretting over how many applications you have open. In Lion and Mountain Lion, Mac OS X will actually quit applications you're not using for you. So relax.

## The Dock

![The Dock](/img/2013-04-09-dock.png)

The Dock contains the following things:

* Finder (whether you like it or not)
* Commonly-used applications that were either put there by default or by you
* Currently open applications (identified by a light underneath)
* Minimized windows
* Commonly-used folders or documents that were either put there by default or by you
* The Trash Can (whether you like it or not)

You can resize the Dock by clicking on the median. Or, you can right-click it for a whole bunch of other obnoxious options.Personally, I keep my Dock on the left as I have more horizontal space than vertical space. But, that's just me.

## Right-Clicking

* You can always hold control and click.
* If you have a Mighty Mouse, you can go into `Apple Menu > System Preferences > Mouse` and just activate the right click.
* On a trackpad, you can just tap with two fingers.

## Using the Force (Quit)

Sometimes things get hung up. If so, kill them.

* You can right click on the icon on the Dock. If Mac OS X knows it's frozen, then it will allow you to select `Force Quit`. If it doesn't, then you can hold down `Option` to force it's hand.
* You can hit `Command-Option-Escape` to bring up a list of applications to brutally murder. It's like `Control-Alt-Delete` in Windows.

## Keyboard Shortcuts

Next to many menu items, there is a keyboard shortcut. Below are some common ones.

* `Command-Q` quits an application.
* `Command-S` saves your document.
* `Command-T` opens a new tab in Safari or Chrome.
* `Command-Tab` allows you to switch between applications.

My advice: If you find yourself doing the same task over and over. Spend a minute or two to learn how to do it with a keyboard shortcut. It seems small, but this stuff just really adds up if you learn them one at a time.

## Managing the Chaos

Mac OS X gives you some great tools for managing a ton of Windows.

* Mission Control
* Show Desktop
* Show Application Windows

## Spotlight

Spotlight is your friend. Basically, Mac OS X has a super-powerful search engine built right into it. Not only does Spotlight look at file names, it also scans the contents of the file when you are searching. So, even if you named your file something stupid, Spotlight can still help.

Spotlight lives in that little magnifying glass in the upper-right corner of the screen. For more advanced options, you can select `Show All in Finder` and it will pop open a new Finder window that allows you to specify file types, sort by date, and other fun miscellany.

### Using Spotlight to Open Applications

One of my favorite ways to use Spotlight is as an application launcher. Instead of overloading my Dock or manually going through the applications folder, I can just hit `Command-Space` and start typing the name of the application I want to open. As soon as I have found something I like, I just hit enter. Boom.

### Towards Better Disorganization

I don't sort my files into folders. It's a waste of time and I have better things to do. Instead, consider just naming your files real well (e.g. "Comments on Eighth Grade Humanities PBAs, April 2013") and just letting Spotlight do the heavy lifting.

## How to Take a Screenshot

Good tutorials have lots of pictures. Your tutorial should not be an exception. So, how do you take a screenshot? It's _really_ easy on a Mac.

* To take a screenshot of your entire screen, press `Command-Shift-3`.
* To take a screenshot of a certain area of your screen, press `Command-Shift-4`. This will give you some crosshairs. Click and drag and your Mac will take a shot of the area you have selected.
* To take a screenshot of one window, press `Command-Shift-4`. You'll get the crosshairs. Now, press `space`.

## How to Record a Screencast

What if a still picture won't cut it? Well, then you can record your screen. It's magic. Let's [let a younger version of myself explain the process with a screencast][vimeo] (crazy, right?).

[vimeo]: https://vimeo.com/26682644

{% for post in site.tags.screencasting %}
* [{{post.title}}]({{post.url}})
{% endfor %}

## Proxies

The fabulous folks at DIIT have decided that if you want to access the web (ports 80 and 443), then you need to go through them as a proxy so they can make sure you're not trying to pull and educational video from YouTube or anything like that. Sometimes, kids delete those settings. Don't call me. Just head over to `Apple Menu > System Preferences > Network > Advanced > Proxies`. That seems like a lot, but you'll get the hang of it. Trust me.

Then, click on `Automatic Proxy Configuration` and input `http://proxy.nycboe.org/proxy.pac` and you should be good to go. Just make sure you select `Apply` in the main dialogue.

![Proxy Settings](/img/2013-04-09-proxy.png)

## Resources

Here are some links to point you in the right direction. That said, the smart student will take a close look at the keyboard shortcuts and poke around in System Preferences in order to uncover some hidden gems.

* [30 Fantastic Geeky Tricks to Get the Most From Your Mac][1]
* [14 Must Know Tips and Tricks for Mac OS X][2]
* [80 Handy OS X Lion Tips and Tricks][3]
* [Some Mountain Lion Tips and Tricks][4]
* [Fifteen Tips and Tricks for Mac OS X Mountain Lion][5]

[1]: http://mac.appstorm.net/roundups/30-fantastic-geeky-tricks-to-get-the-most-from-your-mac/
[2]: http://osxdaily.com/2012/06/08/14-must-know-tips-tricks-for-mac-os-x/
[3]: http://www.techradar.com/us/news/software/operating-systems/80-handy-os-x-lion-tips-and-tricks-1044374
[4]: http://9to5mac.com/2012/07/30/some-mountain-lion-tips-and-tricks/
[5]: http://miami.cbslocal.com/2012/08/11/fifteen-tips-and-tricks-for-mac-os-x-mountain-lion/

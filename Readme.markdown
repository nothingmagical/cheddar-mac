# Cheddar for Mac

[Cheddar for Mac](http://cheddarapp.com/apps) is the Mac application for [Cheddar](http://cheddarapp.com), a simple & instant task manager.

**Note:** I haven't had time to setup good tools for third-party developers to hack on Cheddar for Mac yet. I need to spend time and implement the web flow since only official apps can use the username and password OAuth flow. Also, the [sparkle branch](https://github.com/nothingmagical/cheddar-mac/tree/sparkle) has a lot of differences than master. I want to merge it back in and #ifdef all of the Sparkle stuff so it's easy to keep doing betas.


## Getting Started

Run the following commands to get start:

    $ git clone https://github.com/nothingmagical/cheddar-mac.git
    $ cd cheddar-mac
    $ rake setup

Now open the Xcode project and build. You will see one error telling you to fill in your API credentials. If you don't already have API credentials, head over to the [Cheddar developer site](http://cheddarapp.com/developer).


## Why is this open source?

This is open source since the app is free already. It is intended to be a source of sample code for everyone to benefit from. You can make cool apps that use Cheddar and I hopefully get more users because you built something awesome.

Also, if you want to help out and fix some bugs, I'll love you forever. Maybe you'll even get a shirt or something :)


## License

Cheddar for Mac is released under the [Simplified BSD License](https://github.com/nothingmagical/cheddar-mac/blob/master/LICENSE).

While it is not strictly forbidden by the license, I would greatly appreciate it if you didn't redistribute this app exactly the way it is in the App Store. There's nothing stopping you, but don't please be a jerk.


## Contributing

If you want to fix bugs, I'll love you forever! If you want to add some features, I may not merge it. I'm sure it will be awesome, but defending Cheddar's simplicity is my upmost duty. If you're feeling like implementing a feature, check out the [issues](https://github.com/nothingmagical/cheddar-mac/issues) for things tagged with "feature".

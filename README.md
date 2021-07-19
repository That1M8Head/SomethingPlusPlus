# ![Something++](https://raw.githubusercontent.com/That1M8Head/SomethingPlusPlus/main/something-plusplus-logo.png) Something++
Something++ is a satirical command line shell for macOS, GNU/Linux, BSD and whatever other OSes I missed out. Something++ includes amazing features such as a password system, and the ability to make the user say "What am I doing with my life?".

### Usability? Who gives a crap about usability? We're onto SOMETHING! And we're going to INCREMENT!

## How the flip to use it

If you understand how other shells work, you should be far from home with this shell! Commands like `cd` and `ls` don't do as expected!

## How the flip to get it

Just `git clone` or download and extract the repo and compile it using the built in shell script `build.sh`.

 Then `cp` it to`/usr/local/bin` or whatever.

You need `g++` to build it, but that's about it.

### Michaelsoft Binbows ![Binbows](https://raw.githubusercontent.com/That1M8Head/SomethingPlusPlus/main/michaelsoft.png)

On Windows, you should either install MinGW or compile Something++ in WSL. (WSL is preferred since it can actually be set as a shell)

If compiling with MinGW, run `build.bat` rather than `build.sh`.

## How the flip to start it

If you've installed it, type `something`. If not, and you're still in the build directory, type `./something`.

### Dependencies

Nope. None. No deps. Just `g++` with a standard `gcc` installation.

## How the flip to set it as default

Don't. Just don't.

### I make poor life decisions

Add `something` to `/etc/shells`.

```
echo /path/to/something >> /etc/shells
```

#### :warning: WARNING: VERY BAD STUPID IDIOT IDEA :warning:
Then set it as your default shell.

```
chsh -s /path/to/something
```

If you followed exact instructions earlier, then `/path/to/something` is `/usr/local/bin/something`.

Then log out and log in again.

I take no responsibility for anything that goes wrong when using Something++. Your fault is your fault.


# Coursera Machine Learning Class Notes and Examples

The following are my notes and completed examples for the Coursera Machine Learning class

## Installing Octave on Mac

The instructions I found on the web appeared to be out of date, and were a bit more complicated than required. I use Homebrew on my Mac, and unfortunately, there are two versions of Octave available for installation, one through regular brew (`brew install octave`) and a cask version (`brew cask install octave`).

*ADVICE*: Do not use the Homebrew cask version of Octave. It'll probably work, but it's outdated. Instead, just use the following commmand, which should get you up and running. I already have Java installed, hence the `--without-java` option.

````bash
brew install octave --without-java --with-gui --with-qt
````

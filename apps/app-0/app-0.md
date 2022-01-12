# App 0: Environment Setup

Discuss this app & get help on [Piazza](https://piazza.com/upenn/spring2022/srs_cis1952012022a).
Please leave feedback by creating a GitHub issue or by posting on Piazza.

**Expected Duration:** 10-15 minutes of engagement. 1+ hours of installing & updating software if required.


**Deadline:** Mondayy, January 24th at **5:00pm** 🤖

- - - -

**PLEASE READ THROUGH THE ENTIRE ASSIGNMENT BEFORE POSITING ON PIAZZA ‼️**

- - - -

## Objectives
* Learn some vocabulary.
* Ensure your Xcode is set up correctly.
* Make sure you can run apps using the virtual iPhone simulator.
* Meet the _Playground_ — a “scratch pad“ to quickly experiment with Swift

## Vocab
* **iPhone** — a smartphone produced by Apple that runs the **iOS operating system**.
* **iOS** —  the operating system that runs all iPhones and iPads. It’s responsible for downloading and running apps, making calls, taking photos, and pretty much everything else.
* **Swift** — Apple’s modern programming language. It is the language used to make apps for iOS, watchOS, MacOS, and all other Apple platforms. The language is relatively new, so new versions (with different syntax!) come out frequently. For this reason, you should search **Swift 5** (the current version) whenever searching StackOverflow or Google.
* **UIKit** — Apple’s user interface development kit, used on iOS. This is how you **interact** on the code level with iOS. You’ll spend most of this class learning UIKit development.
* **Xcode** — an IDE (integrated development environment) provided by Apple. This is the iOS equivalent of Java’s Eclipse editor. It allows you to write and compile Swift, and also provides a lot of niceties (autocompletion! type checking!).
* **Xcode Simulator** — a full iPhone simulator built into Xcode. We’ll use this to quickly test iOS apps without needing an actual iPhone (although if you have an iPhone, you can use that too!).

## Install Xcode
1. Make sure you are running at least **macOS 11.3 Big Sur** or later. You can check this by clicking on the Apple icon > About this Mac. sIf you are not, you can update your OS from the Mac App Store (keep in mind this will take additional time so plan ahead). This version is required for the most recent Xcode release currently available on the App Store (Xcode 13). Not all Macs can run this version, check that yours can [with this list]("https://support.apple.com/kb/sp833?locale=en_US")
2. Go to the Mac App Store and install Xcode. If you have Xcode already, make sure it is updated to the latest version **13.2**.
3. Launch Xcode and accept any permission dialogues. You may have to put in your password. Xcode might also ask to “Install Additional Required Components” — click yes if so.

If you made it this far, your environment should be set up for the semester. Next, we’ll get started with Xcode playgrounds!

## Important Notes
* **Downloading Xcode and updating your Macbook will take up a SIGNIFICANT amount of storage.** Even while Xcode itself may only take ~8-12 GBs, it might require extra space while downloading. If you are running into issues while downloading indicating that you do not have enough storage, you may have to clear additional space up to ~20-30 GBs. There are lots of strategies available online for clearing additional space; here are a few that you can try if necessary:
    * Clear caches and delete downloaded files
    * Go to Finder and organize all of your files by size; see if there's any large files that can be deleted
    * Delete any unnecessary Applications that are taking up singificant space
    * Download a third-party app to help optimize storage space (e.g. AVG Cleaner)
* If you do not have access to a device capable of running macOS, you are responsible for identifying an alternative method for obtaining one for the purposes of this class; if this applies to you (or should you find yourself unable to download on your current device), here are a few alternative options available:
    * Van Pelt offers Macbook rentals through the [Penn Libraries Webiste]("https://www.library.upenn.edu/using-libraries/tech-equipment/equipment/macbook")
    * MacInCloud provides somewhat reasonably priced remote Mac servers to run XCode on; you can look into this option [here]("https://www.macincloud.com/") if interested
    * If you are still struggling to find a way to access a macOS device, please email me ASAP so we can make necessary arrangements

## Xcode Playgrounds
> “Playground - noun: a place where people can play”  

Playgrounds are miniature testing environments for the Swift language. They allow you to quickly try out code and see results — without making a full app! Some of our tutorials will use Playgrounds.

#### Do the following:
- Make a new folder for this course. Make sub-folders named `tutorials` and `apps`.
- Open Xcode.
- Go to File > New > Palyground
- Name the new playground `app0_lastname_firstname` and save it in your new `apps` folder.

Great! You should now see a Playgrounds file with some boilerplate code:
![](/apps/app-0/assets/fig3.png?raw=true)
1. This is the code editor. Code goes here! Click the **play** button to compile and run code.
2. This is a “status panel” — a feature unique to Playgrounds. When you initialize a variable, it will show you the value of that variable. This will also show you useful debugging info, like how many times each line of code is run. This is a feature of Playgrounds that we won't have when developing full apps.
3. This is the output console — errors and print statements are sent here.

#### Do the following:
- Erase the line beginning with `var str = "Hello...`
- Write a comment: `// App 0`
- Make constants for your name, favorite emoji, and penn id (replace the <...>):
```
let name = "<YOUR NAME>"
let emoji = "<EMOJI>"
let pennId = <PENNID>
```
- Add a line to print out your constants:
```
print("Hello World \(emoji) My name is \(name) and my pennId is \(pennId)")
```
- Click the play button to compile and run.

Congrats! You just ran your first line of Swift 🎉🎉🎉

**DON’T FORGET:** Submit `app0_lastname_firstname.playground` on Canvas before the next class.



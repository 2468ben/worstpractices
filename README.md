# worstpractices
WorstPractices.js -- A library to cause all the problems you didn't know you had

I know the repo should have a hyphen if I wanted to refer to it as WorstPractices and not Worstpractices, but that would be a best practice.

**MISSION**

Does your app have dependencies? Do you worry about them causing problems?

What if you could make those problems happen now?

Introducing WorstPractices.js, a library that will try its best to **reversibly** break your app.

Inspired by [Netflix's Simian Army](https://github.com/Netflix/SimianArmy) and finally motivated by [this delightful chain of events](https://github.com/azer/left-pad/issues/4), this library will gradually add some JS and NPM-related scripts that can ideally raise weaknesses or vulnerabilities in your code/build. When you feel like testing the resiliency of your app, you can either try a specific script to see the damage, or let WorstPractices choose a random one for you.

Also, if I see an opportunity for this repo to update in a way that can highlight weaknesses (other than unpublishing the repo), I'll do that and mention it in the changelog or release notes. So lock your version number or [get ready for a Wild Ride](http://knowyourmeme.com/memes/mr-bones-wild-ride).

**CONTRIBUTION**

Since there are countless unknown ways your app might screw up (and I'm only one person), I'm hoping to build this library with the help of the JS & Node community. 

Here are the only rules I currently have for contributions:
* They must not cause any irreversible damage to an app's code or build (no rm -rf, except maybe inside ```/node_modules```)
* They must highlight a weakness or vulnerability that is worth finding (leave the style linting to the linters)
* They try to follow the [Node Contribution Guidelines](https://github.com/nodejs/node/blob/master/CONTRIBUTING.md). This library is already designed to be frustrating, so we might as well keep the community around it as light-hearted as possible.
## Pimp my rect ( ͡° ͜ʖ ͡°)
_a simple JS app for xfive.co_

This is a specification for a Xfive test JavaScript project. Use any technology of your preference. It’s perfectly OK to use vanilla JS or any front-end frameworks or libraries.

Here’s what it should look like:

* The app should consist of 3 parts/sections: **Editor**, **Output**, **Gallery**. Editor should live-update the Output. It’s up to you if you show Gallery on the same page or under e.g. localhost:xxxx/gallery. What’s crucial: the gallery’s state persists after the browser restarts. To obtain this goal, you’re allowed to use any technology you feel comfortable with (i.e. WS + IndexedDB, Firebase, Node+MongoDB, LocalStorage).
* **Output**: simple rectangular `<div>`
* **Editor**: it should have a set of inputs to adjust Output’s:
  * background colour (colour picker)
  * size (input which you think is the most suitable here)
  * border radius (please use a range picker)
  * A save button
* **Gallery**: a list of saved Output divs with preserved styling. It should be possible to:
  * remove Outputs from the list
  * [optional but very welcome] some animations or sorting/filtering options
* It should work well in the newest browsers (mobile Chrome and Safari included!).
* All third party dependencies (if there will be any) should be installed using either Yarn or NPM.
* The whole thing should be split into modules.
* The layout is up to you! Feel free to use tools such as http://getbootstrap.com/ or https://www.muicss.com/. In case you’d like to roll your own CSS you’re more than welcome to do so.

**Project deadline**: Try to deliver the test within 1 week time. If we don't see any activity in your test repository after 1 week (at least initial commits), we will automatically withdraw your application.

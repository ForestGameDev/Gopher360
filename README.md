Why I modified Gopher?
======

The original Gopher version didn't work well in my laptop, I was not able to make small movements to select options in small menus, etc. I confirmed the problem was with my laptop (Lenovo, Windows 7). Also the 3 speed modes caused me a little confusion to know in which mode I was, so I changed them to only 2.

One of my two speed modes is much slower than the original slow speed. The other is about 20% faster than the original fast mode.

I made a small change in the operation to calculate the movement in order to increase the speed more in relation with the amount of the left stick's movement (multiplied delta by 5), so the slow mode can go from very slow to medium speed, and the fast mode can be slow enough to select big components and fast enough to move between multiple screens.

I use Gopher for my daily office work :), it had helped me a lot for the wrist pain, so thanks Tylemagne and other contributors!


About Gopher
======

Gopher is a utility for couch-oriented PC users that wish to entirely control their PC from the couch with a controller. Gopher works by transforming Xbox (or PlayStation, if using DS3Tool) controller input into traditional keyboard and mouse input that many applications and games still completely rely on with no controller-based alternative input options. The analog sticks move the mouse, the buttons click - it's very simple. Gopher completely skips this requirement and brings controller compatibility to ALL your applications and MOST of your games. Games like Runescape will be just fine. Crysis? Maybe not so much. It all depends on what amount of traditional input the game requires. Gopher is an excellent tool for PC gaming from the couch, as it's fully capable of web browsing, playing mouse-based games, controlling media players, and launching emulators. Don't stand up and waste calories, just download Gopher!

Gopher separates itself from the competition by being efficient, small, portable, free, and fully open. Competitors like XPadder and Joy2Key have their place, but Gopher really gives them a run for their money, even at its initial beta release.


Video Demonstration
======

https://vine.co/v/MYadBgWXuWY


Download Instructions
======
Check out the 'releases' link at the top for executables or source code downloads. I recommend you copy it somewhere outside of the ZIP and make a shortcut to it. Adding it to your startup folder in your HTPC can make bootups a lot more convenient!

Controls
======

**Start**: Windows Start.

**A**: Click.

**X**: Right-click.

**B**: Enter.

**D-pad**: Arrow keys.

**Right Analog**: Scroll up/down

**Left Analog**: Mouse.

**Left Analog Click**: Middle mouse click (for scrolling web pages).

**Back**: Toggle. Useful for when you launch emulators or open Steam Big Picture mode. Press again to re-enable.

**LBumper**: Cycle speed (x3)

(planned)**RBumper**: Cycle master volume (x8)

TODO
======
Call GetState once per frame - thanks for catching that!

Allow adjustment of sensitivilty & volume via top L / R buttons. Text/beep feedback.

Easter egg that plays Ice Caves when you hold down LTrigger :D:D:D



Port Progress
======
Linux: Not started.

Windows: Initial port complete.

OSX: Not started.



License
======
Gopher free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.

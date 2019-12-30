# prakAI-perspicacious

EXPLORATORY PROJECT that is looking at ways to produce a fully interactive overlay on a computer screen that can display a blurred version of everyday content to children being rehabilitated after sight restoration. 

Inspired by newly-sighted children, experiments were run with AI that have revealed a possibility that humans who are exposed to blurry images when sight is given later in life after initial brain development might have improved rehabilitative outcomes. We are looking for ways to produce a controllably blurry filter for children to use as they learn to use a computer through blurry eyes first to improve their eventual acuity at the end of their rehab process. 

If you have ideas about how to accomplish this goal, please get in touch with [Project Prakash](https://www.projectprakash.org)!

- [prakAI-perspicacious](#prakai-perspicacious)
	- [Ideas so far](#ideas-so-far)
		- [Electron - status: promising, but slow](#electron---status-promising-but-slow)

## Ideas so far

### Electron - status: promising, but slow

We have started experimenting with an Electron app that has a window that is alwaysontop, fullscreen, and clickthrough. The window would be on a loop taking screen captures, blurring them, and displaying them on the screen. The `prakAI-perspicacious` directory has an electron app that has screenshots rendered every second with complete click through behavior and always on top. It is tested on windows, but it is literally just a proof-of-concept that this is possible.
The goal is to create a smart computer assitant that can save
movement and efforts by learning from posture, gaze and eye-tracking.

# Goal Features
	- Precise eye-tracking ()
	- Function in low-light
	- Warp cursor to gaze position
	- Suggest quick actions to the user, much like predictive typing

# Details

- Features
	- Predict where the user is looking
	- Warp mouse to where the user is looking  where you are looking
	- Switch between windows and workspaces with eyesight.
	- Scroll comfortably when looking towards bottom or top of the screen
	- Recognize patterns of cause and effect
	- High-level pattern recognition intelligence
	- Starts out rough, but refines with every click

* Recognize user states from:
	- Hands crossed
	- Typing
	- Moving mouse
	- Reaching for mouse
	- Reaching for keyboard
	* Stretching
	* Scratching

- Recognize AI state from:
	- User state
	- Window applications
	- Window geometry

- Strong OCR
	- Detect what the user is reading

- Bubble-UI and Gaze-Completion
	- UI bubbles appear around the user's gaze and can be controlled by sight.
	- For example
		- Opening a link in Firefox
		- Clicking a button on the screen
		- Switching between windows

	- Recognizes sequences of events and offer quick shortcuts:
		- Navigating to a directory
		- Switching to an application
		- Opening a new application
		- Switching to a different user state
		- Open a terminal
		- Enter command

- Recognizing a list of those things being done over and over again
- Suggesting a quick shortcut to do those chains of events
- Gaze-completion, bubble-based ui

# Pattern

A pattern is a sequence of identities.

e.g.:
* AB
* AA
* ABC
* ABBCC

The pattern can also encode time between the identities.

# Pattern AI

Features:
	- LOD
	- Temporal neuron

# Relevant ideas

- Look at video-encoding

# Questions

- How does visual recognition work in the human brain?
- Can existing NN techniques be applied succesfully?
- How is it related to pattern recognition? How about musical patterns?
- How can we use culling techniques to optimize the network's performance?
	- LOD: spend less time on areas of low relevance
		- Moving objects
		- User annotation
	- Gaze prediction: prioritize details I'm looking at


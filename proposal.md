# Spade For After Effects

## Repository
https://github.com/johnnyy18/spade

## Description
Spade is an intuitive UI-based extension that automates repetitive actions inside After Effects. Spade streamlines inefficient workflows, allowing Motion Designers to build compositions faster.

## Features
- New Layer Shortcuts
  - Various buttons are easily accessible straight from the UI panel. Upon clicking the designated layer type, a new layer will be automatically created in your timeline.
- Auto-trim
  - If you are currently selecting a layer, newly created layers will be trimmed to its size. This is only executed if an existing layer is selected.
- Auto-parent
  - If you create an empty null, it will be automatically parented to a selected layer. This is only executed for null objects and if an existing layer is selected.
- Layer Sequencing
  - Selecting multiple layers and executing this command will automatically sequence layers based on an operation (Those being top-to-bottom or bottom-to-top)

## Challenges
- For this project specifically, because Python does not natively control After Effects, I will most likely have to use JavaScript or alternative libraries like PySide6 and PyAutoGUI for the interactive elements.
- Depending on the route taken, I will need to use ExtendScript, Adobe CEP, HTML, and JavaScript.

## Outcomes
Ideal Outcome:

### Ideal Outcome
- Execute all commands quickly and more efficiently than navigating through the window menus
- All commands do not break

### Minimal Viable Outcome
- New Layer shortcuts work without the auto trim function or the auto parenting features
- Layer Sequencing works without the operation-based direction

## Milestones

### Week 1
- Complete the basic logic structure
- Start UI building and user interaction

### Week 2
- Complete the structure for the user interface
- Complete the layer modification and After Effects communication

### Week 3 (Final)
- Final Test
- Troubleshooting and bug fixing

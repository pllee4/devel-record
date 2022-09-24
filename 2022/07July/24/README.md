# 24/7

## Update
- Finally done restructured previous app of searching algorithm to follow Model View Controller design.
- Although in the end, the output is the same but in term of architecture and code structure, it is much more cleaner and efficient.
- Previously the code just followed the ui framework and was directly written on the rendering loop without considering respective functionality.
- The responsibility of each component is now reflected on model, view and controller and has becomes clearer and more extensible.
- Approximately 450 lines of codes have been refactored to 750 lines of code.
- Previously even for the same value, computation happens unnecessarily in the rendering loop, now the program is now more towards event handling.

![model-view-controller](https://user-images.githubusercontent.com/42335542/180603695-f2d6f11f-b8c8-431f-8f72-33239f6a7229.png)
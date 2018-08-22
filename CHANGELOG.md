## Release History
* **0.3.4**
    * `BUGFIX` The function `MicroModal.close(id)` now properly accepts an ID
    * `FEATURE` Allow opening a modal with a data-* trigger and then closing it programmatically and vice versa 
* **0.3.3**
    * `FEATURE` A `micromodal-open` class is now added to the body element whenever a modal is open
* **0.3.2**
    * `BUGFIX` Fixed bundling for es and umd builds
* **0.3.1**
    * `FEATURE` **Breaking** Renamed `hasAnimation` to `awaitCloseAnimation`
    * `BUGFIX` Updated correct version of modal in dist
* **0.3.0**
    * `FEATURE` **Breaking** Added flag to await close animation end before destroying modal
    * `FEATURE` Added flag to disable focus on first element
    * `FEATURE` Added ability to pass custom data-attributes for open and close
    * `BUGFIX` Fixed modal not working without animations
    * `BUGFIX` Not focusing on last element in modal in case of file inputs
* **0.2.0**
    * `FEATURE` Added api to programmatically close modal
    * `FEATURE` Added abilty to disable scroll on modal open
    * `FEATURE` Added hooks for open/close animations
    * `FEATURE` Added flag for toggling debug logs in console
    * `ENHANCEMENT` Added ability to pass config to `show` method
    * `ENHANCEMENT` Cleaned up `aria` tags for accessibilty
    * `ENHANCEMENT` Added test suite for browser tests
    * `BUGFIX` Fixed native form events not firing in modal
    * `BUGFIX` Fixed modal blocking custom event listeners
* **0.1.1**
    * `BUGFIX` Fixed issue where validation was not firing
* **0.1.0**
    * `CHANGE` Released first minor version 😊

Immutability requires several changes in order to make sure nothing in a class can be changed after it is created.

* The class should be final.
* Instance fields should be final.
* There should be no setters.
* Getters should use defensive copying where appropriate.

This is an alternative implementation of the *dining philosophers* problem, where eating is controlled by a host. A philosopher is allowed to eat when the following criteria are fulfilled:

* The maximum number of parallelly eating philosophers has not yet been reached.
* The philosopher is not already eating, do not exceed the number of allowed dinners and there's enough time elapsed since the philosopher's last dinner.
* Both chopsticks corresponding to the philosopher's seat are free.

Note: seats are randomized.
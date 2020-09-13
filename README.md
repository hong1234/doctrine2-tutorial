# doctrine2-tutorial

# Links: 
https://www.doctrine-project.org/projects/doctrine-orm/en/current/tutorials/getting-started.html#queries-for-application-use-cases

# An Example Model: Bug Tracker

# we can extract the requirements:

- A Bug has a description, creation date, status, reporter and engineer
- A Bug can occur on different Products (platforms)
- A Product has a name.
- Bug reporters and engineers are both Users of the system.
- A User can create new Bugs.
- The assigned engineer can close a Bug.
- A User can see all their reported or assigned Bugs.
- Bugs can be paginated through a list-view.


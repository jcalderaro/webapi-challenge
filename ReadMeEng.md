
## Minimum Viable Product

- [ ] Configure an _npm script_ named _"server"_ that will execute your code using _nodemon_. Make _nodemon_ be a development time dependency only, it shouldn't be deployed to production.
- [ ] Configure an _npm script_ named _"start"_ that will execute your code using _node_.

Design and build the necessary endpoints to:

- [ ] Perform CRUD operations on _projects_ and _actions_. When adding an action, make sure the `project_id` provided belongs to an existing `project`. If you try to add an action with an `id` of 3 and there is no project with that `id` the database will return an error.
- [ ] Retrieve the list of actions for a project.

## Translates To 

Top Half 

- Make a script named Server that will run your code using "nodemon"

- Make a script named Start that will execute the code using "node" 

- Make "nodemon" a time depency only 
    => this should be a DEVELOPMENT only dependency.

Bottom Half

- The application should have the ability to create (post) an action
- The application should have the ability to update (put) an exisisting project with the newly created action from #1.
- The application should have the ability to retrieve (get) a project and all of its actions.


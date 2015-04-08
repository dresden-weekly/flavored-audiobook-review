# flavored-audiobook-review
Single page audiobook review/rating website app based on [Ember](http://emberjs.com/) or maybe [ReactJS](http://facebook.github.io/react/index.html) or [Polymer](https://www.polymer-project.org) to gather some experience with one (or more) of these frameworks.

Additionally it would be interesting to think about whether/how *flavored* ratings could be realized with some simple logic in a database-backend. *Flavored* in the sense of "rated by appreciated people" or "rated by people with similar preferences".

The choice of possible ratings should include negative values. Instead of giving the users the choice of *good*, *great*, and *best ever* they should be allowed to express that something really *sucks*.

### Models

- User
- Audiobook
- Rating (of an audiobook)
- UserRating (or maybe just an n:m "User -> appreciates -> User's ratings")

### Relations

- User 1:n Rating
- Rating n:1 Audiobook
- User 1:n UserRating
- UserRating n:1 User

#### State of the project

Draft of a draft.

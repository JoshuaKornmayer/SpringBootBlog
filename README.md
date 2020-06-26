# Tech Talent Blog

### What makes a blog post

Main attributes:

- Id (primary key)
- Title
- Author
- Entry

### Why learn how to make a blog?

- Basic CRUD app that's easy to understand
- Lots of optional features we could use to teach ourselves
- Once you know how to make a blog, it becomes apparent how much of the internet uses the same basic functionality

## Edit Button

On it's face, adding the ability to edit a blog post doesn't seem like a big deal. However once you start pulling on that thread you realize there are two big things we have to figure out how to do to make this work.

1. How do we retrieve a single record of our entity?
2. How do we save over the previous record instead of just creating duplicates?

###PathVariables

PathVariables is essentially a way for us to "store" data we need in a url.

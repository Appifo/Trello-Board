[00:04] Trello is a popular project management tool that you might already be familiar with. 
It uses a Kanban style board in order to keep up with the progress of different tasks

[00:16] You can add new columns to the board. Reorder them as you see fit. Rename them. And add new tasks to them.

[00:42] In this course, we're going to build a much simplified version of this Trello board. It's going to look something like this.

[00:51] It has the same columns in here where you can add new ones. Rename existing ones. Delete columns. Reorder them. Add new tasks.

[01:19] And drag tasks between different columns. While of course, we won't be building out all of the awesome features of Trello,

[01:28] At the end of the course, you will walk away with a pretty functional and nice Kanban or Trello board. 
The library that's gonna power a lot of this functionality

[01:40] is called Vue Draggable. It exposes a draggable component that allows us to easily perform drag and drop functionality. 
You can do things like reorder items in a list

[01:54] or have multiple lists and drag items between them. You can also clone items between different lists. 
As well as enable nice transitions between the different positions.

[02:16] Under the hood Vue Draggable is powered by Sortable.js. In this course, we'll be working
with the Vue Draggable API, as well as some APIs

[02:26] that are directly passed from Vue Draggable onto Sortable.js. Both of these libraries
are really very powerful and are going to make working with drag and drop a breeze.

[02:39] Finally, we'll utilize a couple of different composables from the popular VueUse library to enable things
like some keyboard shortcuts, being able to option drag in order to clone tasks within our board,

[02:53] as well as persist our tasks and columns to local storage. Oh, and I almost forgot. We'll also be using Tailwind CSS
in order to rapidly style our application.

[03:08] Alright, I hope you're as excited as I am for this very hands-on and very practical course. Let's start building in the next lesson.

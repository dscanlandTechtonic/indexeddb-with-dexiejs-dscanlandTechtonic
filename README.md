# indexedDB-with-DexieJs-assignment

For this assignment we will be creating a client-side data storage mechanism to store/cache some book-like objects from a local `JSON` file.

We will be utilizing [DexieJS](https://dexie.org/), a minimalistic wrapper (read framework) for [IndexedDb](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) to perform **CRUD** operations on this local data store.  

To get started, open up `/js/indexedDB.js` to see how the local data store is initialized, and what it holds.

After you've familiarized yourself with the local "database", open up `/js/app.js` and start working in the `onDatabaseReady` function.  

We are going to write a few functions, which perform basic **CRUD** operations on our "library_database"

### Delete Book
Write a function which deletes a single book by it's primary key (title in this case) from the local data-store

### Add Book
Add a single book to the "library_database".  Make sure to validate the schema before the book is added and handle updating the UI once the book has been added.

### Edit Book
Write a function which updates a record in the local data-store.  Again, make sure to update the UI

### Bonus
Start working through the addititional BONUS instructions (#4) in `app.js`

Once you've completed the assignment, `commit` and `push` your changes and then submit your repository to the completed assignments roster.

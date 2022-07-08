# library
Project: Library from TheOdinProject

This is the seventh project assigned by The Odin Project. We are to create a simple library web app that creates new book objects with an object constructor which will then be appended into an array. This app allows users to create, view, update, and delete books. In a way it's kind of like a CRUD app but without the use of a database or any back-end. This is the most fun project I've worked on so far as I used my own bookshelf as an inspiration for the UI design. Frankly, it took me 3 days to "finish" this because I kept adding features that were outside of the requirements.

Some of the extra features that I added are a table that lists all the book objects from the array. Book objects can be viewed, updated, and deleted from the table and from its individual modal. Since I haven't learned how to extract form values from the back-end, I prevented the form value's from being sent but still allowed it to do client-side validation. Values are only extracted (from front-end side) if the submit button of the form is a success. I learned how to create "pop-up windows" that generates different kinds of information, custom checkboxes that updates a book object's value, and store the book array data in cache. So next time the users load the page, it'll keep the book array from their last visit.

A problem that I have yet to solve is making this website responsive for mobile devices.
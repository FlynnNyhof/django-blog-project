# Django Blog Project Work Log
### 15/06/2026
- Found a good tutorial online to follow for a Django blog project
- Installed Django and set up the development environment
- Defined the Category, Post, and Comment models

### 22/06/2026
- Created a migration and created the database
- Began using the Django Admin Site to register the models I created
- Fixed basic shortcomings with the text representations of the models
- Created the blog_index(), blog_category(), and blog_detail() views

### 28/06/2026
- Created HTML templates for all of the relevant views
- Created a URLs file for hooking up routes between each view
- Created a Base template HTML file for controlling global styling options
- Added an external CSS framework to implement some basic styling

### 01/07/2026
- Created a comment form for allowing users to add comments to posts (with fields 'author' and 'body')
- Modified the blog_detail view to accommodate for the comment form
- Updated the detail template to include leaving and viewing comments
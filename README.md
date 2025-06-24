# Picdump automator

![Screenshots of “picdump” articles in the “Global Nerdy” and “Accordion Guy” blogs](./docs/images/picdump%20articles.jpg)

Every week, I post a regular “picdump” article made up of the photos, images, comics, and memes I found interesting that week on my blogs:

- One with pictures related to technology, programming, and work on Saturdays on _Global Nerdy_, and
- One with general pictures (think of it as a sort of editorial) on Sundays on the _Accordion Guy_ blog.

I used to make these posts manually, but decided that it would save a lot of time if I automated the process. So I created a Jupyter Notebook to do just that. Given the following...

- Wordpress username and application passwords stored in a `.env` file
- A directory of images to be posted

...this notebook creates a picdump post with the appropriate date, uploads the images from the specified directory, and saves the post as a draft for review. This notebook’s a real time-saver, and you might get some good ideas from its code.
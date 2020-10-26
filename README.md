What functionalities your project has now?

Website: - Generate graph - Search and filter country list - Select countries - Select data type - Select graph type - View about us page - View blog posts

Backend: - Generate graphs - Convert graph to HTML string - Upload CSV file to database - Blog posts saved to database


What functionalities need unit tests?

Website: - Search and filter country list

Backend: - Upload CSV file to database - Convert graph to HTML string (my test in test.py) - Blog posts saved to database - Generate graphs


What functionalities do not need unit tests?

Website: - Generate graph - Select countries - Select data type - Select graph type - View about us page - View blog posts


My unit tests

I was originally assigned with creating a unit test to check chart type. Line chart is currently default.

We decided a lot of the visual functionalities are somewhat redundant or pointless to test, such as this one, so we are exploring new functionalities that we can create unit tests for.

I have spent most of my time trying to familiarize myself with unit tests and python. I plan to do more in the future as my current test is more of a "dummy" test.

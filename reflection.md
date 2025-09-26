# IT373 Week 1 Setup Reflection
## Challenges During Setup and Solutions

Setting up the Django development environment in Week 1 of IT373 came with several hurdles, but each difficulty ultimately improved my understanding of web development practices.

**Virtual Environment Setup:**
One of my initial challenges was properly activating the virtual environment. The main confusion was ensuring that Django was installed inside the isolated environment rather than globally on my system. I resolved this by using python -m venv .venv, activating it, and then installing the dependencies. This experience highlighted the importance of environment isolation in preventing project conflicts.

**Learning Template Inheritance:**
Django’s template inheritance was another area of difficulty, particularly in understanding how {% block %} tags function and how child templates extend a base template. Through experimenting with layouts and reviewing class examples, I learned that inheritance provides a way to maintain consistent designs while still allowing customization in specific sections.

**Working with URL Routing:**
I also encountered issues while connecting URLs to views, such as duplicate paths and incorrect imports. Solving these mistakes helped me realize the importance of assigning unique names to URLs and carefully following Django’s URL dispatcher structure.

**Using Git for Version Control:**
Integrating Git into the project took some practice as well. I had to figure out how to manage commits effectively and set up a .gitignore file to exclude unnecessary files like those from the virtual environment. This process showed me how version control makes projects more organized and easier to manage.

Overall, these challenges not only strengthened my problem-solving abilities but also gave me hands-on experience with Django’s MVT framework.
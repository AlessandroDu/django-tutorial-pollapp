### Learning Django
In this tutorial I learned some new stuff in Django, I already worked with it leading a Django project but not build it myself.

This tutorial taught me interesting DRY principles in Django, using OOP, which I personally liked.

I also really liked how Django simplifies so much of the development process, really taking away most of the tedious stuff, allowing you to build an app really fast without thinking of all the underlying logic behind it.

### What It Is
This is a Poll application, you can create Questions and choices in the admin site, and users can vote on them, view all polls, and view a detail poll.

### How To Run It
You can issue `python manage.py runserver` in the terminal, making sure you are in the root directory.

### Url Endpoints
If you want to test it out:
polls/  - view all polls
polls/<int:pk>/  - view a single poll in detail
polls/<int:pk>/results/  - view vote results
polls/<int:question_id>/vote/  - vote on a poll, get redirected to results

# Django Tutorial
Done for coursework @MakeSchool.
Completed by Nolan Kovacik.
See `LICENSE.md` for more information.

## Run Locally
1. Fork or clone this project from GitHub.
1. `cd` into the downloaded project root directory.
1. Run `python manage.py runserver`.

## Update Database Structure
1. Run `python manage.py migrate`.
1. Make your changes to the database models.
	- These can usually be found in a `models.py` file.
1. Run `python manage.py makemigrations <app>`
	- One example of `<app>` is `polls`.
1. Run `python manage.py migrate` again.

**\*NOTE**: If you are going to make changes to the database more than once, step 1 may be superfluous.

### Remembering Commands
If you have trouble remembering which command does what, this tidbit from Stack Overflow may help you&hellip;
- `python manage.py makemigrations <app>`: Create the migrations (generate the SQL commands).
- `python manage.py migrate`: Run the migrations (execute the SQL commands).



## Credits
Many thanks to the Django team, their [tutorial], and their great documentation.
Thanks also to @Dani from Make School, and her team.


[tutorial]: https://docs.djangoproject.com/en/3.0/intro/tutorial01/

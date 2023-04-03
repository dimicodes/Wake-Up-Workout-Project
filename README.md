# Wake-Up-Workout-Landing-Page

This is a basic landing page with a mailchimp form integrated. The captured emails will connect to the python program.

The Python program uses MailChimp's API key to pull emails that have subscribed via the landing page.

The program then adds those subscribed emails to the list titled 'emails', generates a unique workout program, logs into Gmail via smptlib, and emails subscribers the generated workout.

This program is hosted to automatically run on PythonAnywhere, everyday at 4am (EST), so subscribers will automatically receive a brand new and unique workout emailed to them every morning.

There are over 225 unique beginner workouts, 270 unique intermediate workouts, and 1944 unique advanced workouts that can be generated.

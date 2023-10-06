# Wake Up, Workout

**Wake Up, Workout** is a project that combines a landing page with a Mailchimp form and a Python program to deliver daily bodyweight workouts to subscribers via email. The landing page collects email addresses from users interested in receiving daily workouts, and the Python program, hosted on PythonAnywhere, uses the Mailchimp API to fetch subscriber emails, generate unique workout programs, and send them via email every morning at 4 AM (EST).

## Features

- Landing page with Mailchimp integration.
- Automatic generation of unique daily bodyweight workouts.
- Daily email delivery of workouts to subscribers.
- Segmented workouts for beginners, intermediates, and advanced users.
- Unsubscribe link included in emails.
- Extensive collection of workout variations.

## Technologies Used

- Python
- Mailchimp API
- SMTP for email delivery
- HTML/CSS for the landing page
- Bootstrap for styling

## How to Use

1. Clone the repository to your local machine.

2. Customize the landing page (HTML/CSS) to match your branding if needed.

3. Set up a Mailchimp account and obtain an API key.

4. Replace `ENTER_API_KEY_HERE`, `ENTER_YOUR_SERVER_HERE`, `ENTER_YOUR_LIST_ID_HERE`, `ENTER_YOUR_GMAIL_HERE`, and `ENTER_YOUR_GMAIL_APP_KEY_HERE` with your Mailchimp API key, server information, list ID, Gmail credentials, and an unsubscribe link URL in the Python script.

5. Install the required Python libraries using `pip install mailchimp-marketing` and `pip install datetime` if not already installed.

6. Host the Python script on a server, such as PythonAnywhere, to automate the daily email delivery.

7. Launch the landing page to collect email addresses from interested users.

8. Users who subscribe will receive a daily workout email every morning.

## Customization

You can customize this project by:

- Modifying the landing page to match your branding and design preferences.
- Adding more workout variations to the `generate_workout` function.
- Adjusting the timing of the email delivery in the Python script.
- Implementing additional features or integrations as desired.

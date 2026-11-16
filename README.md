# IPL Ticket Booking – Activity 3

A simple IPL ticket booking website created using HTML5, CSS and a small amount of JavaScript for a client-side demo confirmation.

## Files
- `index.html` – Home page with a link to the booking form.
- `booking.html` – Ticket booking form with HTML5 validation.

## Form fields and validation
- Full name: `required`, `minlength`, `maxlength`, and `pattern`.
- Email: `type="email"` and `required`.
- Phone: `type="tel"`, `pattern`, `minlength`, and `maxlength`.
- Match and stand: required dropdown menus.
- Ticket quantity: `type="number"`, `min="1"`, and `max="10"`.
- Booking preference: radio buttons.
- Confirmation: required checkbox.
- Submit and reset buttons.

The browser displays its built-in validation prompts when required or invalid values are entered. A successful submission displays a demo confirmation message. This is a front-end activity only; it does not store bookings or process payments.

## Run in VS Code
1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open `index.html` with Live Server, or open it directly in a browser.
4. Click **Book IPL Tickets** to open the form.
5. Try submitting the empty form, an invalid email, an invalid phone number, and a ticket quantity outside 1–10. The browser should block invalid submissions.
6. Enter valid details and submit to see the demo confirmation.

## Screenshot evidence
Open the form in a browser and capture:
1. The booking form with its fields visible.
2. A browser validation prompt after attempting an invalid submission.
3. The successful demo confirmation after entering valid details.

Save the screenshots in this repository (for example, in a folder named `screenshots`) and commit them if your instructor requires screenshot files in GitHub.

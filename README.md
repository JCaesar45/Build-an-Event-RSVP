```
# Event RSVP Form

A simple, accessible React application for event RSVP submission. This project provides a user-friendly form that collects essential attendee information and validates inputs before confirming the RSVP — all without page reloads.

---

## Features

* **Controlled form inputs** for real-time state management.
* **Validation** for required fields: name, email, and number of attendees.
* **Email format checking** using regex for proper validation.
* **Number input validation** ensures at least one attendee.
* **Optional dietary preferences** field.
* **Checkbox** to indicate bringing additional guests.
* **Submission confirmation** that displays all submitted details.
* Prevents page reload on form submission for smooth user experience.

---

## User Stories Fulfilled

* Text input for attendee’s **name** (required).
* Email input for attendee’s **email** (required and validated).
* Number input for **number of attendees** (required, min 1).
* Text input for **dietary preferences** (optional).
* Checkbox to indicate **bringing additional guests**.
* Submit button that handles form submission without refreshing the page.
* Display of a confirmation message with the RSVP details after successful submission.

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/event-rsvp-form.git
   ``

2. Navigate into the project directory:

   ```bash
   cd event-rsvp-form
   ``

3. Install dependencies:

   ```bash
   npm install
   ``

4. Start the development server:

   ```bash
   npm start
   ``

5. Open your browser and go to `http://localhost:3000` to use the RSVP form.

---

## Usage

Fill in your name, email, and the number of attendees. Optionally, specify any dietary preferences and check the box if you’re bringing additional guests. Click **Submit RSVP** to see a confirmation message below the form with all your provided details.

---

## Code Overview

* **React Functional Component** with hooks (`useState`) for state management.
* Form input elements include two text inputs, one email input, one number input, and one checkbox input.
* Form submission is handled with client-side validation.
* Confirmation display is conditionally rendered based on form submission state.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements or new features.

---

## License

This project is licensed under the MIT License.

---

## Contact

For questions or feedback, reach out to jordanleturgez@gmail.com.

---

*Thank you for using the Event RSVP Form project!*

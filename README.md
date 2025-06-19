# Medicine Suggestor

## Overview

Medicine Suggestor is a web-based application designed to help users find the right medicines based on their symptoms. It allows users to input their symptoms and receive a list of suggested medicines, along with detailed information about each medicine including description, side effects, usage instructions, and price. The platform also offers health tips, a feedback form, and options to find doctors or buy medicines.

## Features

- **Symptom-Based Medicine Suggestion:** Enter your symptoms (e.g., "Fever, Headache") and get a list of suitable medicines.
- **Medicine Information Lookup:** Search for a medicine by name to view its description, side effects, instructions, and price.
- **Health Tips:** Get random health and care tips to promote wellness.
- **Doctor Finder:** Find recommended doctors in your city.
- **User Authentication:** Sign up and log in to get personalized access.
- **Feedback System:** Submit feedback through a simple form.
- **Buy Medicines:** Browse a list of common medicines and proceed to purchase.

## How It Works

1. **Symptom Input:**
   - On the home page, enter your symptoms separated by commas.
   - The application queries its database and suggests medicines that match the symptoms.

2. **Medicine Search:**
   - Use the "About the Medicine" section to search by medicine name and get detailed information.

3. **Health Tips:**
   - Click the "Get a Tip" button to display a random health tip.

4. **Find Doctors:**
   - Enter your city to find the best doctors nearby.

5. **Buy Medicines:**
   - View a list of available medicines with images and prices. Click "Show More" to proceed to the shop (implementation required).

6. **Feedback:**
   - Fill in your name, email, and feedback message to help improve the application.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sharanyasinghal/Medicine_Suggestor.git
   cd Medicine_Suggestor
   ```

2. **Set Up the Database:**
   - Create a MySQL database named `medicine_login`.
   - Set up the required tables: `users`, `Medicines`, `Symptoms`, `Symptom_Medicine_Map`, and `feedback1`.
   - Configure your database credentials in the PHP files.

3. **Run the Application:**
   - Deploy the files on a local or remote PHP server (e.g., XAMPP, WAMP).
   - Access `index.php` or `index.html` via your browser.

## File Structure

- `index.php` / `index.html` – Main web interface
- `about.php` – Medicine info lookup by name
- `get_medicine.php` – Backend for symptom-to-medicine mapping
- `login.php` / `sign.php` – User authentication scripts
- `feedback.php` – Feedback form handler
- `style.css` – Stylesheet (not shown here)
- `login.html` – Login and signup page

## Contributing

Feel free to submit issues or pull requests if you'd like to improve this project!

## License

This project is for educational purposes. Please contact the author for any other usage.

---

**Made by Sharanya Singhal.**

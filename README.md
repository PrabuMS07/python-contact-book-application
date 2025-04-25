

# 📖 Simple Command-Line Contact Book

This is a basic command-line application written in Python for managing personal contacts. It allows users to add, view, search, update, and delete contact information stored in memory during the application's runtime.

## ✨ Features

*   **Add Contacts:** Add new contacts with name, phone number, email, and address.
*   **View Contacts:** Display a list of all saved contacts (shows name and phone number).
*   **Search Contacts:** Find contacts by searching for their name or phone number.
*   **Update Contacts:** Modify the phone number, email, or address of an existing contact.
*   **Delete Contacts:** Remove a contact from the book by name.
*   **Interactive Menu:** Provides a simple numbered menu for easy navigation.
*   **In-Memory Storage:** Contact data is stored in a Python dictionary while the application is running. **Note:** Data is *not* saved permanently and will be lost when the application closes.

## ⚙️ Technology

*   **Language:** Python 3.x
*   **Libraries:** Uses only standard Python libraries (no external dependencies).

## 🛠️ Setup

1.  **Download:** Save the Python script (e.g., `contact_book.py`).
2.  **Python:** Ensure you have Python 3 installed on your system. You can download it from [python.org](https://www.python.org/).

## ▶️ Usage

1.  **Navigate:** Open your terminal or command prompt and navigate to the directory where you saved the `contact_book.py` file.
2.  **Run the Script:** Execute the script using the Python interpreter:
    ```bash
    python contact_book.py
    ```
3.  **Follow Menu Prompts:** The application will display a menu with options:
    ```
    --- Contact Book ---
    1. Add Contact
    2. View Contacts
    3. Search Contact
    4. Update Contact
    5. Delete Contact
    6. Exit
    ```
4.  **Interact:**
    *   Enter the number corresponding to the action you want to perform (e.g., `1` to add).
    *   Follow the on-screen prompts to enter contact details (name, phone, email, address) or search terms.
    *   Enter `6` to quit the application.

## 💡 Potential Future Improvements

*   **Data Persistence:** Implement saving and loading contacts to/from a file (e.g., CSV, JSON, or a simple text file) so data persists between sessions.
*   **Input Validation:** Add validation for inputs like phone number format or email format.
*   **Error Handling:** Improve handling of potential errors (e.g., incorrect input types).
*   **Case-Insensitive Search:** Make the search function ignore case differences.
*   **View Full Details:** Add an option to view all details (phone, email, address) for a specific contact, not just the summarized list.
*   **Duplicate Handling:** More flexible handling of duplicate names or phone numbers (e.g., allow update confirmation).


# Book Recommendation System
A graphical user interface (GUI) application for book recommendations, built with Python's Tkinter library. This application allows users to search for books through the Google Books API, view book details, and add or remove books from their favorites list. It also includes a feature to view all saved favorites in a scrollable layout.

# Features
Book Search: Users can search for books by title.
Book Details Display: Each search result displays book details, including title, author(s), publication date, and cover image.
Favorites Management: Users can add books to a favorites list and remove them if desired.
Scrollable View: Search results and favorites are displayed in a grid format with vertical scrolling to accommodate a large number of entries.
Requirements
Python 3.x
Tkinter: Standard library in Python for GUI development
Pillow: Imaging library for displaying book cover images
Requests: For making HTTP requests to Google Books API
Setup
Clone the Repository:

git clone https://github.com/yourusername/book-recommendation-system.git
cd book-recommendation-system
Install Dependencies: Make sure you have Pillow and Requests installed.

pip install pillow requests
Run the Application: Execute the following command to start the application:

python main.py
Usage
Search for Books:

Enter a book title in the search bar.
Click the "Search" button to fetch book details using the Google Books API.
Results are displayed in a grid format with book title, author, publication date, and cover image (if available).
Add to Favorites:

Click on "Add to Favorites" under any book result to save it to your favorites list.
A message will confirm that the book was added.
Show Favorites:

Click "Show Favorites" to view all saved books.
Each favorite displays its details along with a "Remove from Favorites" option.
Remove from Favorites:

Click "Remove from Favorites" under any book in the favorites list to delete it.
A message will confirm the removal.
Google Books API Integration
The app uses the Google Books API to retrieve book details. To enable this, the app sends HTTP requests to fetch data such as title, authors, publication date, and cover images. Ensure your internet connection is active when using the search feature.

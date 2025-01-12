# Social Media API - Task 1: Proof of Concept

This branch (`task1-proof-of-concept`) implements the initial core endpoints for the Social Media API:

*   **Users:**
    *   `POST /api/users/`: Create a new user.
    *   `GET /api/users/{username}/`: Retrieve a user's profile. 
*   **Posts:**
    *   `POST /api/posts/`: Create a new post.
    *   `GET /api/users/{username}/posts/`: Retrieve all posts by a specific user.

**Key Features:**

*   **Django Models:** Defines `User` and `Post` models using Django ORM.
*   **Django REST Framework:** Utilizes DRF `ModelViewSet` for API endpoints.
*   **Basic Testing:** Includes basic `curl` commands for testing the implemented endpoints.

**To Run:**

1.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt 
    ```

2.  **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

**Testing:**

*   Refer to the `curl` commands provided in this README for basic testing.
*   Further testing can be performed using tools like Postman.

**Next Steps:**

*   Implement user authentication.
*   Add error handling and appropriate HTTP status codes.
*   Write unit tests for the implemented endpoints.

**Note:**

This is a basic implementation for Task 1. Refer to the project requirements and the detailed task descriptions for further guidance and enhancements.

---

**Remember to:**

*   Replace placeholders (e.g., `requirements.txt`, specific URLs) with the actual file names and URLs in your project.
*   Update the `README.md` file with any changes you make during development.
*   Consider adding screenshots of Postman requests/responses or other relevant visuals to enhance the documentation.

This `README.md` provides a clear and concise overview of the work done in this task, making it easier for you and others to understand the code and its functionality.

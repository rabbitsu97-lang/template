# Frost CMS Standalone Project

This is the structure for a standalone CMS built using Laravel for the backend and Vue.js for the frontend.

## Directory Structure:

- backend/  (Laravel)
    - app/
        - Http/
            - Controllers/
                - UserController.php
                - PostController.php
        - Models/
            - User.php
            - Post.php
    - config/
        - app.php
    - .env
    - routes/
        - api.php
- frontend/ (Vue.js)
    - src/
        - components/
        - pages/
            - Home.vue
            - Login.vue
        - App.vue
        - main.js
    - public/
        - index.html

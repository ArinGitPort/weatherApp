# weatherApp

## Contributing to the Codebase

1. **Create a new branch (use a descriptive name, e.g., `feature/Add-file`):**
   ```sh
   git checkout -b feature/Add-file
   ```

2. **Make your changes.**


3. **Stage your changes:**
   ```sh
   git add .
   ```

4. **Commit your changes (use a clear, imperative message, e.g., `Add feature: user login`):**
   ```sh
   git commit -m "Add feature: user login"
   ```

5. **Push your changes to the remote repository:**
   ```sh
   git push -u origin feature/Add-file
   ```

6. **Create a Pull Request on GitHub.**


If Git keeps tracking changes to a file like `database.php` even after adding it to `.gitignore`, follow these steps:

1. Add the file to `.gitignore` (if not already):
   ```
   database.php
   ```

2. Remove it from the Git index without deleting it locally:
   ```bash
   git rm --cached database.php
   ```

3. Commit the change:
   ```bash
   git commit -m "Stop tracking database.php"
   ```

4. Push the change:
   ```bash
   git push
   ```

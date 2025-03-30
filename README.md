# My Obsidian Template

This repository provides a template for using Obsidian with Git Large File Storage (LFS) and GitHub. It is designed to help you manage your notes and attachments efficiently while leveraging version control.

## Getting Started

1. **Clone the Repository**
   To get started, clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/yourusername/my-obsidian-template.git
   ```

2. **Install Git LFS**
   Make sure you have Git LFS installed. You can download it from [git-lfs.github.com](https://git-lfs.github.com/). After installation, run:
   ```
   git lfs install
   ```

3. **Configure Git LFS for Attachments**
   To track large files in the `attachments` directory with Git LFS, run the following command:
   ```
   git lfs track "vault/attachments/*"
   ```

4. **Add Your Notes**
   You can start adding your notes in the `vault/notes.md` file. Use the `attachments` directory to store any media files you want to include in your notes.

5. **Commit Your Changes**
   After making changes, remember to commit your changes using:
   ```
   git add .
   git commit -m "Your commit message"
   ```

6. **Push to GitHub**
   Finally, push your changes to GitHub:
   ```
   git push origin main
   ```

## Using Obsidian

Open the `my-obsidian-template` folder in Obsidian to start using your vault. You can customize your notes and settings as needed.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
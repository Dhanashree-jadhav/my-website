# Interview Questions on GitHub Pages and Web Development

## Questions
1. What is GitHub Pages, and how does it work?
2. Can you host dynamic applications on GitHub Pages?
3. What are the limitations of GitHub Pages?
4. How do you update a website hosted on GitHub Pages?
5. What happens if you delete the repository hosting a GitHub Pages site?
6. How do you add custom CSS to a GitHub Pages site?
7. What is the default file that loads on a GitHub Pages site?

## Answers
1. **What is GitHub Pages, and how does it work?**  
   GitHub Pages is a free service to host static websites directly from a GitHub repository. It works by serving HTML, CSS, and JavaScript files from a specified branch (e.g., `main`) and folder (e.g., root). You enable it in the repository’s Settings > Pages, and GitHub provides a URL like `username.github.io/repo-name`.

2. **Can you host dynamic applications on GitHub Pages?**  
   No, GitHub Pages is limited to static content (HTML, CSS, JavaScript). Dynamic apps requiring server-side processing (e.g., PHP, Node.js) or databases need platforms like Heroku or AWS.

3. **What are the limitations of GitHub Pages?**  
   - 1 GB storage per repo.
   - 100 GB bandwidth per month.
   - 10 builds per hour limit.
   - No server-side code or databases.
   - Individual files max 100 MB.

4. **How do you update a website hosted on GitHub Pages?**  
   Edit files locally (e.g., `index.html`), commit changes with `git commit -m "Update content"`, and push with `git push origin main`. The site updates automatically within a minute.

5. **What happens if you delete the repository hosting a GitHub Pages site?**  
   The site becomes inaccessible, returning a 404 error. The URL stops working, and any custom domain link breaks unless reassigned.

6. **How do you add custom CSS to a GitHub Pages site?**  
   Create a CSS file (e.g., `styles.css`), link it in `index.html` with `<link rel="stylesheet" href="styles.css">`, and push both files to the repo. Ensure the file path matches.

7. **What is the default file that loads on a GitHub Pages site?**  
   The default file is `index.html`. GitHub serves it automatically from the root or specified folder if present.
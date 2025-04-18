# **Interactive Prompt Archive Sheet**

This is a simple, single-page HTML application that functions as an interactive sheet for archiving your prompts. It allows you to add prompts with colored tags, filter and search through them, and copy prompts to your clipboard. Data is stored directly in your browser's local storage.

## **Features**

* **Add Prompts:** Easily add new prompts and assign comma-separated tags.  
* **Colored Tags:** Tags are automatically assigned consistent, visually distinct colors.  
* **Filter by Tags:** Click on tags to filter the displayed prompts.  
* **Search:** Search prompts by text content or tags.  
* **Copy to Clipboard:** Quickly copy the full text of any archived prompt.  
* **Local Storage:** Your prompts and tag colors are saved directly in your browser, persisting between sessions.

## **How to Use**

1. Save the provided code as an index.html file on your computer.  
2. Open the index.html file in your web browser.

The application will load, and you can start adding prompts. Your data will be saved automatically in your browser's local storage.

## **How to Host**

This is a static HTML application, making it very easy to host.

1. Save the code as index.html.  
2. Create a new repository on a Git hosting service like [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), or [Bitbucket](https://bitbucket.org/).  
3. Upload your index.html file to the repository.  
4. You can then use a service like [Netlify](https://www.netlify.com/) or [GitHub Pages](https://pages.github.com/) to deploy your site directly from the repository.

For Netlify, the process typically involves linking your Git repository, and Netlify automatically detects and deploys the static site.

## **Data Storage**

Please note that all your data is stored in your browser's **Local Storage**. This means:

* Your data is only accessible in the browser you used to create it.  
* Clearing your browser's cache or local storage will delete your saved prompts.  
* This is not a cloud-based solution, so your data is not synced across devices or browsers.

If you need a more robust or collaborative solution, a backend database would be required.

## **Contributing**

If you'd like to contribute to this simple project, feel free to fork the repository and submit pull requests.

## **License**

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

# Always active 🟩 🟩 🟩 🟩

GitHub Actions Auto-Commit Workflow
Automate your GitHub commits to keep your tiles green and active! This GitHub Actions workflow allows you to make automatic commits to your repository, adding a touch of green to your contributions graph.

Getting Started
Follow these steps to set up the auto-commit workflow in your repository:

Create your own repository on GitHub if you haven't already.

Copy the following files to your repository:

.github/workflows/autocommit.yml
LAST_UPDATED
Customize the email and name information in the autocommit.yml file:

Replace "your-email@example.com" with your GitHub-associated email address.
Replace "Your Name" with your GitHub username.
Adjust the scheduling time in the autocommit.yml file (Line 9). You can use Crontab.guru to create a cron schedule string that fits your desired schedule.

For example, to run the workflow every hour, you can set the schedule to "0 * * * *".

Note: The first time you set up the workflow and make any commit, it will run immediately. After the initial setup, it will adhere to the specified schedule.

That's it! The auto-commit workflow is now set up in your repository.

Usage
With this auto-commit workflow, your repository will automatically receive commits, ensuring that your contribution graph is active and green.

Customization
You can customize the commit messages and the schedule to meet your specific requirements. Feel free to modify the .github/workflows/autocommit.yml file to adjust the commit messages or the timing of the auto-commits.

License
This GitHub Actions Auto-Commit Workflow is open-source and available under the MIT License.

Happy coding! 🌿🟩



[Check it out in action!](https://github.com/WysockiD/auto-commits/actions)

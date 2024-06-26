## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Creating a new project
- To create a Next.js app, open your terminal, cd into the folder you'd like to keep your project, and run the following command:

```bash
npx create-next-app@latest nextjs-dashboard --use-npm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"
```
- This command uses ``create-next-app``, a Command Line Interface (CLI) tool that sets up a Next.js application for you
- In the command above, you're also using the --example flag with the starter example for this course

## Exploring the project
- Unlike tutorials that have you write code from scratch, much of the code for this course is already written for you. This better reflects real-world development, where you'll likely be working with existing codebases.

- Our goal is to help you focus on learning the main features of Next.js, without having to write all the application code.

- After installation, open the project in your code editor and navigate to nextjs-dashboard.

```bash
cd nextjs-dashboard
```
Let's spend some time exploring the project.

### Folder structure
- You'll notice that the project has the following folder structure:
	- ``/app:`` Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
	- ``/app/lib:`` Contains functions used in your application, such as reusable utility functions and data fetching functions.
	- ``/app/ui:`` Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
	- ``/public:`` Contains all the static assets for your application, such as images.
	- ``/scripts:`` Contains a seeding script that you'll use to populate your database in a later chapter.
Config Files: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.



# PSYC341OER
## Table of Contents
* [Introduction](https://github.com/bobsthinktank/PSYC341OER/blob/master/README.md#introduction)
* [Contributors](https://github.com/bobsthinktank/PSYC341OER/blob/master/README.md#contributors)
* [Become a Contributor](https://github.com/bobsthinktank/PSYC341OER/blob/master/README.md#become-a-contributor)
* [Navigating the Repository](https://github.com/bobsthinktank/PSYC341OER/blob/master/README.md#Navigating-the-Repository)
* [Making Changes](https://github.com/bobsthinktank/PSYC341OER/blob/master/README.md#making-changes)

# Introduction

The primary goal of project is to provide an open-source, ever-expanding body of information for undergraduate classes in Cognitive Psychology. These materials were initially compiled for [PSYC341: Introduction to Memory and Cognition](https://app.testudo.umd.edu/soc/202101/PSYC/PSYC341) at the [University of Maryland, College Park](https://umd.edu/), with support from a [2020 Faculty OER Mini-Grant](http://www.oer-maryland.org/support-sustain/most-oer-grant-program/) from the [Maryland Open Source Textbook Initiative](https://www.oer-maryland.org/). 

This site is hosted via Github, allowing many users to contribute to the main site or to make their own variations. Ideally/eventually, this site will provide a mix of written and multimedia information to encourage learning through several mediums. 

This site material itself falls in the Public Domain - i.e., licensed under a [Creative Commons Zero v1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/deed.en), however note that content in most sections is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US).

# Contributors
* [Bob Slevc](https://github.com/bobsthinktank)
* Camille Burns
* Sam Santomartino
* Ren Salig

# Become a Contributor

See something wrong or want to add something? There are several ways you can do so: 

- Edit directly in your web browser. Best for smaller edits. See below for step-by-step instructions. 
- For feedback without direct edits, you can open a GitHub Issue (Issues tab → New Issue) and describe your suggested change(s).
- If you plan to make many/larger edits and are Git savvy, consider the 'standard' Fork + Pull Request workflow. 

## How to suggest edits in your browser: 

This method lets you propose changes to any file without needing special permissions. Your suggestion will be sent for review before anything changes on the live site.

### What you'll need
- A free [GitHub account](https://github.com/signup)

### Step-by-step

1. **Go to the repository**
   Visit: [https://github.com/bobsthinktank/PSYC341OER](https://github.com/bobsthinktank/PSYC341OER)

2. **Find the file you want to edit**
   Browse the folders to find the relevant chapter or page. Most content files end in `.md` (Markdown).

3. **Open the file and click the edit icon**
   Click the file name to open it, then click the **pencil icon** (✏️) near the top-right corner of the file content. If you see a tooltip that says *"Fork this repository and edit the file"*, that's exactly what you want — click it.

4. **Make your edits**
   You'll see the file's text, which you can edit directly in the browser. The content uses **Markdown** formatting — see the section on [making changes](#making-changes) below.

6. **Describe your changes**
   Scroll to the bottom of the page. Under **"Propose changes"**, enter a short summary of what you changed and why (e.g., *"Fixed typo in Chapter intro"* or *"Clarified definition of working memory"*). The more detail the better!

7. **Submit your proposal**
   Click **"Propose changes"**, then on the next screen click **"Create pull request"**. Add any additional notes if helpful, then click **"Create pull request"** one more time.

That's it! The repository owner will receive a notification, review your suggestion, and either merge it (accept), ask follow-up questions, or let you know if they'd suggest a different approach. You'll get an email notification when there's a response.

## Tips for Good Edits

- **One topic per suggestion** — if you have changes for two different chapters, submit them separately. This makes review much easier.
- **Explain your reasoning** — especially for content changes, a brief note about *why* helps the repository owner evaluate the suggestion.
- **Small and focused is better** — a tightly scoped suggestion is more likely to be accepted quickly than a large overhaul.
- **Ask first when unsure** — for major structural changes, consider opening a GitHub **Issue** (via the Issues tab) to discuss the idea before writing it all out.


# Navigating the Repository

The repository is organized (sometimes not very well) into several folders on the main page:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 11.49.38 AM.png" style="width:20%">
</figure>

* **_data** holds the .nav page, which creates the sidebar of links
* **_pages** holds the multiple pages for each subject and is divided by subject
* **_sass** holds the _variables page, which dictages fonts and format
* **images** holds every image used on the site; it is necessary to upload images here before they can be used

Additionally, there are several lone pages:
* **.gitignore and Gemfile** have information about the current theme
* **LICENSE** has more information about Creative Commons Zero v1.0 Universa
* **README.md** is this!
* **_config.yml** has information on the theme and layout
* **index.md** is the main page of the website

# Making Changes

## Editing in Markdown

Pages that end with **.md** can be edited using Markdown, an easy way of editing Github pages. Editing in markdown is simple; [this page](https://guides.github.com/features/mastering-markdown/) outlines the basics.

## Changing the Sidebar

If you want to add or delete a page from the sidebar, follow these steps:

**1)** Add a page to the **_pages** folder, or delete the selected page by clicking the trashcan icon in the top right corner:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.23.31 PM.png" style="width:20%">
</figure>

**2)** In **_data**, go to navigation.yml. 

Each sidebar is organized in the same format:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/sidebarreadme.png" style="width:20%">
</figure>

For example, here is the beginning of the sidebar for the Sensation and Perception pages:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.30.39 PM.png" style="width:20%">
</figure>

Which, when published, leads to this:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.31.19 PM.png" style="width:20%">
</figure>

Therefore, when adding or deleting a page, you must also add or delete the code for that page in the sidebar. 

**3)** If your page is referenced in the Table of Contents on the **index.md** page, you must add or delete it there. 

## Adding Images

To add images to your .md page, follow these steps:

**1)** Upload your image to the **images** folder.

**2)** Insert your image using the following format:

<figure>
    <img src="https://bobsthinktank.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.41.50 PM.png" style="width:20%">
</figure>

* The **figure style** can be edited to change the alignment, margins, and size of the photo
* The **img src** is the URL, linking to the uploaded photo in the **images** folder
* The **fig caption** refers to the text underneath the photo

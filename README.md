## **Prompt**
Classify a collection of social media posts into categories based on the content using keywords rules.

## **Problem**
Social media feeds can become unmanageable due to things like excessive marketing/spam, offensive comments, or unwanted posts.

## **MVP**
A tool/application that classifies social media posts into predefined categories using keyword-based rules. The tool accepts a list of posts as input and evaluates their content to determine whether they fall into one or more categories such as “ad,” “rude,” “political,” or “ok.”

After processing, the system generates a report that lists each post (or article title) along with its assigned category tags. This provides a simple, rules-based way to organize and moderate social media content.

Key MVP Components:
* Command-line interface (CLI) application
* Input: list of social media posts
* Rule-based keyword classification system
* Categories: “ad,” “rude,” “political,” “ok”
* Output: report listing each post/article title with assigned category tags

## **Beyond MVP**
* Take HTML page with posts and remove all the “political” posts producing a new html page.
* Hide show/images on the page by classifying the alt image text
* Make suggestions for new categories based on the content

## **Available Resources**
* List of 10 posts and an HTML page with those post `prompt_resources/social-base.html`.

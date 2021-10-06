---
layout: lesson
title: "Performance testing"
desc: "Spend most of the class testing your website using different performance tools—and fixing any problems that arise."

hide_show_for_marks: true
hide_markbot: true

extra_tutorials:
  - title: "Performance"
    url: performance
  - title: "Performance checklist"
    url: performance-checklist
    highlight: true
  - title: "Advanced performance"
    url: advanced-performance
  - title: "Advanced performance checklist"
    url: advanced-performance-checklist
    highlight: true
  - title: "GitHub Issues"
    url: github-issues

goal:
  before: |
    Make your website be fast for all users and all internet connection speeds—*remember faster is better, less is more.*

    ### [Performance testing checklist ➔](/topics/performance-checklist/)
    ### [Advanced performance testing checklist ➔](/topics/advanced-performance-checklist/)
  no_image: true
  notes:
    - label: "Collaboration"
      text: |
        This is collaborative. You personally won’t be doing all the accessibility testing. We’ll each test other people’s websites to remove any pre-conceived notions about how the site should work.

steps:
  - title: "Enable Issues on your repo"
    before: |
      Before we start anything, everybody needs to go to **their own** repository on [GitHub.com](https://github.com) and enable their Issues tab.

      **[Video on enabling Issues on GitHub repos ➔](https://www.youtube.com/watch?v=vTULg-7xycs)**

  - title: "Determine the performance budget"
    before: |
      Referring to the [performance testing checklist](/topics/performance-checklist/), we’ll figure out our baseline performance budget what tests to run.

      *Different people will be assigned different performance tests to cover as much as possible.*

  - title: "Write down the URL to your website"
    before: |
      Using a Gist at the front of class, we’ll write down all our URLs so that everybody has access to your website URL for testing.

      **The URL to this Gist will be displayed on the board so you can get a copy of the list of websites to test.**

      If you fork the Gist you’ll be able to check off each person as you go.
    notes:
      - label: "Notice"
        text: "You need to know—and add—your own URL. If your name isn’t on that list you won’t get the marks."

  - title: "Test everybody’s website"
    before: |
      With everybody working together your website will be performance tested in lots of different situations.

      **You’ll be assigned a specific performance test—it will be your job to test everybody’s website using the tool you’re assigned.**

      *Some tools are a lot of work to test. In those cases the same tool will be distributed to multiple students and the class list will be broken into smaller chunks.*

  - title: "Submitting Issues"
    before: |
      If you find problems with the website you’re testing, create an Issue on GitHub *in their repository.*

      **[Tutorials on using GitHub Issues ➔](/topics/github-issues/)**

      ---

      ### Website URL to repo conversion

      ![](/courses/shared/gh-pages-to-repo.svg)

      1. Cut the username
      2. Remove the starting dot
      3. Change `io` to `com`
      4. Paste the username before the repository name

      ---

      ### Create a detailed issue

      The issue you create for another person’s website should be detailed with at least this information:

      1. An informative title
      2. A screenshot of the problem—if that makes sense
      3. Details and informative description of the problem
      4. Any solutions you can think of to help solve the problem

      *If there already is an Issue for the problem you’re seeing, make a comment on the issue with any extra information you may know.*

  - title: "Fix problems"
    before: |
      If there are any problems with your website in a specific tool—fix them!

      **It’s up to you to make your website work well in all tested situations—we’re developing our websites to empower all humans in the world.**
    notes:
      - label: 'Reminder'
        text: "Remember that your website doesn’t have to function exactly the same in every situation—just that it should be functional in every situation."

---

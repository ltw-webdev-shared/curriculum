---
layout: lesson
title: "Accessibility testing"
desc: "Spend most of the class testing your website using different accessibility tools—and fixing any problems that arise."

hide_show_for_marks: true
hide_markbot: true

extra_tutorials:
  - title: "Accessibility"
    url: accessibility
  - title: "Accessibility checklist"
    url: accessibility-checklist
    highlight: true
  - title: "Accessibility testing checklist"
    url: accessibility-testing-checklist
    highlight: true
  - title: "Validators"
    url: validators
  - title: "GitHub Issues"
    url: github-issues

goal:
  before: |
    Make your website work well for all users—and remember *it doesn’t need to work exactly the same for every human being.*

    ### [Refer to the accessibility testing checklist →](/topics/accessibility-testing-checklist/)
  no_image: true
  notes:
    - label: "Collaboration"
      text: |
        This is collaborative. You personally won’t be doing all the accessibility testing. We’ll each test other people’s websites to remove any pre-conceived notions about how the site should work.

steps:
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
      With everybody working together your website will be accessibility tested in lots of different situations.

      **You’ll be assigned a specific accessibility test—it will be your job to test everybody’s website using the tool you’re assigned.**

      *Some tools are a lot of work to test. In those cases the same tool will be distributed to multiple students and the class list will be broken into smaller chunks.*

  - title: "Submitting Issues"
    before: |
      If you find problems with the website you’re testing create an Issue on GitHub *in their repository.*

      **Make sure “Issues” are enabled on your repository—so other people can add issues for your website.**

      **If the Issues tab is missing go to “Settings” and turn them on.**

      ---

      ### Website URL to repo conversion

      ![](gh-pages-to-repo.svg)

      1. Cut the username.
      2. Remove the starting dot.
      3. Change `io` to `com`.
      4. Paste the username before the repository name.

      ---

      ### Create a detailed issue

      The issue you create for another person’s website should be detailed with at least this information:

      1. An informative title;
      2. A screenshot of the problem—if that makes sense;
      3. Details and informative description of the problem;
      4. Any solutions you can think of to help solve the problem.

      *If there already is an Issue for the problem you’re seeing, make a comment on the issue with any extra information you may know.*

  - title: "Fix problems"
    before: |
      If there are any problems with your website in a specific tool—fix them.

      **It’s up to you to make your website work well in all tested situations—we’re developing our websites to empower all humans in the world.**
    notes:
      - label: 'Reminder'
        text: "Remember that your website doesn’t have to function exactly the same in every situation—just that it should be functional in every situation."

---

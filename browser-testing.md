---
layout: lesson
title: "Browser testing"
desc: "Spend most of the class testing your website in all the different browsers—and fixing any problems that arise."

hide_show_for_marks: true
hide_markbot: true

extra_tutorials:
  - title: "Browser testing"
    url: browser-testing
  - title: "Browser testing checklist"
    url: browser-testing-checklist
  - title: "Validators"
    url: validators
  - title: "GitHub Issues"
    url: github-issues

goal:
  before: |
    Make your website work well in all the browsers—remember it [doesn’t have to look exactly the same](http://dowebsitesneedtolookexactlythesameineverybrowser.com/), but it should be functional.

    ### [Refer to the browser testing checklist →](/topics/browser-testing-checklist/)
  no_image: true
  notes:
    - label: "Collaboration"
      text: |
        This is collaborative. You personally don’t own all the devices you need to test your website on, but as a class we have all the devices.

        **We’ll work together to find out who has what device and with whom you can get your website tested.**

steps:
  - title: "Determine the available devices"
    before: |
      Referring to the [browser testing checklist](/topics/browser-testing-checklist/), we’ll figure out what devices—and versions—need to be tested.

      *We’ll poll the class to see who has what versions are available and make sure as many devices and versions are covered as possible.*

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
      With everybody working together your website will be tested in all the browsers available in the classroom.

      **You’ll be assigned a specific device—it will be your job to test everybody’s website in the browser you’re assigned.**

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
      2. A screenshot of the problem—some devices this may be impossible to achieve, so a photo of the device screen will suffice;
      3. Details and informative description of the problem;
      4. Any solutions you can think of to help solve the problem.

      *If there already is an Issue for the problem you’re seeing, make a comment on the issue with any extra information you may know.*

  - title: "Fix problems"
    before: |
      If there are any problems with your website in a specific browser—fix them.

      **It’s up to you to make your website work well in all tested browsers—we’re developing websites for the World Wide Web (not the Wealthy Western Web).**
    notes:
      - label: 'Reminder'
        text: "Remember that your website [doesn’t have to look exactly the same in every browser](http://dowebsitesneedtolookexactlythesameineverybrowser.com/), but it should be functional and not look broken."

---

---
layout: lesson
title: "Peer evaluation"
desc: "Get peers to evaluate your project, critique it, provide feedback and determine a grade."

hide_show_for_marks: true
hide_markbot: true

extra_tutorials:
  - title: "GitHub Issues"
    url: github-issues

goal:
  before: |
    Get useful feedback from your peers on how to improve your project and a simple grade denoting how well you did.
  no_image: true
  notes:
    - label: "Honesty & politeness"
      text: |
        This is constructive. Be polite & helpful. And honest.

steps:
  - title: "Enable Issues on your repo"
    person:
      icon: "person-1"
      label: "You"
    before: |
      Before we start anything, you need to go to **your own** repository on [GitHub.com](https://github.com) and enable the Issues tab.

      **[Video on enabling Issues on GitHub repos ➔](https://www.youtube.com/watch?v=vTULg-7xycs)**

  - title: "Find a peer"
    person:
      icon: "person-1"
      label: "You"
    before: |
      **Check the assignment requirements to determine how many peers should critique your work.**

      Ask the peer politely if they’d like to critique your project. If they accept give them the GitHub URL to the assignment for them to review.

      *Leave your peer alone so they can have time to consider and look at the project and write valuable feedback.*

  - title: "Evaluate the project"
    person:
      icon: "person-2"
      label: "Peer"
    before: |
      As a peer evaluator, it’s your job to help the other person succeed. You want to give honest, valuable feedback that will enhance and improve the other person’s project.

      ### Some things to consider:
    tasks:
      - Effectiveness of the usability
      - Effectiveness of the message
      - Quality of the project
      - Quality of the code
      - Creativity
      - Design execution
      - Spelling & grammar

  - title: "Create an Issue"
    person:
      icon: "person-2"
      label: "Peer"
    before: |
      Create an Issue on the repository of the person whom you’re critiquing—this is where you’ll write the feedback.

      Write valuable and constructive feedback about their project. Be specific and polite. Think about how if this was your project what information you’d want.

      - Consider sending screenshots
      - Don’t forget about the [critique sandwich](https://www.wikihow.com/Use-the-Compliment-Sandwich-to-Critique)
      - Suggest ways to fix the problems

      ---

      ### Website URL to repo conversion

      ![](/courses/shared/gh-pages-to-repo.svg)

      1. Cut the username
      2. Remove the starting dot
      3. Change `io` to `com`
      4. Paste the username before the repository name

  - title: "Fill out the basic rubric"
    person:
      icon: "person-2"
      label: "Peer"
    before: |
      In the same Issue, or in a comment, copy and paste the below rubric and assign grades for the project you just reviewed.

      **If your assignment has a more specific rubric in the assignment requirements—use that rubric instead of the one below.**

      *The code will turn into a data table on GitHub when it’s previewed or saved.*
    code_can_copy: true
    code_lang: markdown
    code: |
      | | 0 points | 1 points | 2 points | 3 points |
      | --- | --- | --- | --- | --- |
      | **Creativeness** | Bland, boring | Fairly generic, but the colours are nice | Good, works very well and is unique enough | Wow! I never would have thought that would work so well! |
      | **Effectiveness** | I don’t know what this is trying to do | The message isn’t completely clear and it’s difficult to use | It’s obvious and simple to use | The project is super effective and easy to use |
      | **Quality** | Non-existent | Acceptable quality, more work could be done | Good quality, up to the expectations of the teacher | Stunning quality, this person rocks! |
      | **Effort** | Zero effort, incomplete | Decent amount of effort | Goodly amount of effort that shows | Amazing, over-the-top amount of effort |
      | **Code quality** | Barely started | Indentation is barely existent, lots of validation errors, very poor semantics | Decent indentation, just a couple validation errors, decent semantics | Well indented, fully valid, good semantics |
    after: |
      *Sum the rubric and put that value at the bottom.*

      **Confirm that you think this is an appropriate grade for the project you just reviewed.**

  - title: "Read the feedback"
    person:
      icon: "person-1"
      label: "You"
    before: |
      **Carefully read over the feedback from your peer and truely consider what they said.**

      Try not to take the feedback personally; separate your person from your project. They are trying to help your project succeed and improve.

  - title: "Respond with a comment"
    person:
      icon: "person-1"
      label: "You"
    before: |
      Ask any questions of your peer, if anything is unclear. Don’t blame them. Don’t write excuses. *Remember they’re trying to help you—trying to make your project better.*

      **Write a comment thanking your peer for their feedback.**

---

---
title: 'click & hold briqs placement'
disqus: hackmd
---

click & hold briqs placement
===


User story
---

In this section, you can specify the user story and acceptance criteria.[^1]

```gherkin=
Feature: Spraying
  As a user 
  I want to click & hold 
  So that I can place multiple briqs on the canvas, like “spraying”

  Scenario: User sprays briqs
    Given  I am on the builder 
    And I am in “place mode”
    When I click & hold the left-click
    Then I can place multiple briqs
```


User flow
---

(optional) In this section you can describe a user flow.[^2]

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
Note left of Alice: Alice responds
Alice->Bob: Where have you been?
```

References
---

Exactly like magica voxel does it. 
https://ephtracy.github.io/


Labels 
---

Select the 6 appropriate labels for your contribution.[^3]

1. Type (feature, documentation, refactor, test, bug, performances) 
1. Context (isolated, coupled, intricated) 
1. Difficulty (easy, intermediate, hard) 
1. Duration (under a day, few days, weeks) 
1. State (preliminary, open, in progress, review) 
1. Techno (cairo, docker, python, js, rust, …) 

    
tags: `feature` `isolated` `intermediate` `weeks` `open` `js`



[^1]: Read more about Gherkin here: https://docs.cucumber.io/gherkin/reference/

[^2]: Read more about sequence-diagrams here: http://bramp.github.io/js-sequence-diagrams/

[^3]: Read more about Github Label Standard here: https://mirror.xyz/onlydust.eth/zrXDEdrIwvjsgS0bvS_dHGoFx3BbxZMl7aWJXMQAbyM
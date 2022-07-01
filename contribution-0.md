OnlyDust Contribution Wizard
===


User story
---

In this section, you can specify the user story and acceptance criteria.[^1]

```gherkin=
Feature: Shopping Cart
  As a Shopper
  I want to put items in my shopping cart
  So that I want to manage items before I check out

  Scenario: User adds item to cart
    Given I'm a logged-in User
    When I go to the Item page
    And I click "Add item to cart"
    Then the quantity of items in my cart should go up
    And my subtotal should increment
    And the warehouse inventory should decrement
```


References
---

You can add here any useful pointers, examples or resources that can help the contributor get started.

Labels 
---

Select the 6 appropriate labels for your contribution.[^2]

1. Type (feature, documentation, refactor, test, bug, performances) 
1. Context (isolated, coupled, intricated) 
1. Difficulty (easy, intermediate, hard) 
1. Duration (under a day, few days, weeks) 
1. State (preliminary, open, in progress, review) 
1. Techno (cairo, docker, python, js, rust, …) 

    
tags: `<insert>` `<insert>` `<insert>` `<insert>` `<insert>` `<insert>`



[^1]: Read more about Gherkin here: https://docs.cucumber.io/gherkin/reference/

[^2]: Read more about Github Label Standard here: https://mirror.xyz/onlydust.eth/zrXDEdrIwvjsgS0bvS_dHGoFx3BbxZMl7aWJXMQAbyM
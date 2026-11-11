# Assignment 9: AI in Problem Solving

**Project:** Student Homework Checklist

**AI Tool:** ChatGPT

## Prompt 1: Initial Solution

**Prompt:**

Suggest a simple way to build a homework checklist for college students. The website should allow students to add tasks, see their status, mark them as completed, and delete them. Keep the design simple.

**ChatGPT Output:**

A simple homework checklist can be built using HTML, CSS, and JavaScript.

- HTML can create the task input, buttons, and homework list.
- CSS can make the website organized and easy to read.
- JavaScript can add tasks, update their completion status, and delete tasks.

Students can type a homework assignment into a text box and click Add. The assignment will appear in a list with a pending status. After completing the assignment, students can change its status to completed or delete it when it is no longer needed.

## Prompt 2: Improving the Solution

**Prompt:**

What problems might students encounter when using this homework checklist? How can the website be improved without making it complicated?

**ChatGPT Output:**

Some possible problems include:

1. **Empty tasks:** Students might accidentally add a task without entering anything. The website should prevent empty tasks.
2. **Accidental deletion:** Students might delete the wrong task. Each Delete button should affect only its corresponding task.
3. **Small screens:** Students may want to use the checklist on their phones. The webpage should adjust to smaller screens.
4. **Keyboard accessibility:** Some students may navigate without a mouse. The website should allow users to access the controls using a keyboard.

These improvements can make the checklist easier to use while keeping its features simple.

## Prompt 3: Generating Test Cases

**Prompt:**

Create test cases for a homework checklist website. It should allow students to add, view, complete, and delete tasks. It should also prevent empty tasks, work on phones, and support keyboard navigation. Include two additional edge cases.

**ChatGPT Output:**

| Test | Action | Expected Output |
|---|---|---|
| T1 | Add "Math Homework" | Task appears in the list |
| T2 | View the added task | Task and its pending status are displayed |
| T3 | Mark "Math Homework" complete | Status changes to completed |
| T4 | Delete "Math Homework" | Task disappears from the list |
| T5 | Attempt to add an empty task | No task is added |
| T6 | Open the website on a phone-sized screen | Content and controls remain usable |
| T7 | Navigate using only a keyboard | Task controls can be operated |
| T8 | Enter only spaces as a task | Input is rejected |
| T9 | Add two tasks and delete one | The remaining task stays unchanged |

Each test should be performed on the finished website. A test passes if its actual result matches the expected result. Otherwise, it fails.

## Prompt 4: Refining the Solution

**Prompt:**

Based on these requirements and test cases, what is the simplest development strategy? Explain how to verify and validate the website.

**ChatGPT Output:**

The simplest approach is to build the basic checklist first and then add input validation and accessibility improvements.

**Suggested development order:**

1. Create the webpage using HTML and CSS.
2. Add JavaScript to create and display tasks.
3. Add buttons to complete and delete tasks.
4. Prevent empty or whitespace-only submissions.
5. Make the layout work on smaller screens.
6. Check keyboard navigation.
7. Run the test cases and correct any problems.

**Verification:** Compare the website's behavior with its specifications. For example, clicking Complete should change the selected task's status, and entering an empty task should not create a new item.

**Validation:** Determine whether the checklist actually helps students organize their homework. Students should be able to identify unfinished tasks and update their progress without unnecessary steps.

**Functional requirements** cover adding, viewing, completing, deleting, and validating tasks.

**Non-functional requirements** cover mobile usability and keyboard accessibility.

The website should only be considered ready after the requirements have been checked and the necessary tests have passed.

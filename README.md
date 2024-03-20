# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [Insert Link]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style.

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

Example #: [1]

## Imperative Approach [2 Minutes]

1. **Step-by-Step Explanation:** Start by explaining the code logic in the imperative approach.

   - Mention each step of the process in the code.
   - Describe how the code provides explicit instructions for each action.
   - Discuss the use of variables to track the state and progress of the process.

**Explicit Steps**: The code explicitly outlines each step required to cook the steak, such as preheating the grill, seasoning the steak, cooking it until it reaches the desired doneness, and serving it. Each step is described sequentially, resembling a set of instructions.

**Low-level Control**: It involves low-level control over the process, where specific actions are taken at each step. For example, adjusting the grill temperature and cooking time based on the steak's weight and desired doneness.

In contrast, declarative programming focuses on expressing what should be achieved rather than how to achieve it. An example of declarative programming might involve defining the characteristics of a perfectly cooked steak without detailing the steps to cook it.

2. **Emphasis on How:** Highlight how the imperative approach focuses on detailing "how" the task is accomplished.

   - Point out the use of loops, conditions, and explicit instructions.
   - Discuss any mutable variables or states that change during execution. **Mutable State**: Mutable variables like `grillTemperature` and `steakTemperature` are updated throughout the process, reflecting changes in the cooking environment and the steak's temperature.

1. **Step-by-Step Explanation:**

   - The code logic is structured as a series of explicit steps, mirroring a recipe-like approach to cooking a steak.
   - Each step is annotated with a comment to describe its purpose and action.
   - Variables like `grillTemperature` and `steakTemperature` are used to track the state of the cooking process and update it as needed.

1. **Emphasis on How:**
   - The imperative approach details how each task is accomplished through explicit instructions.
   - It utilizes a while loop to continuously check and adjust the cooking process until the steak reaches the desired doneness.
   - Mutable variables like `grillTemperature` and `steakTemperature` change during execution to reflect the progress of the cooking process.

This approach is characteristic of imperative programming, where the focus is on specifying step-by-step instructions to achieve a desired outcome, often using mutable state and control structures like loops and conditions.

Example #: [2]

## Declarative Approach [2 Minutes]

High-Level Process Description:

The code defines the cooking process using a structured array of objects, each representing a step.
Each step is described abstractly, focusing on what needs to be done rather than how it should be done.
By using descriptive labels like "Preheat grill" and "Season steak," the code conveys the intent of each step without specifying implementation details.
Use of Data Structures:

The cooking process is represented as an array of objects (cookingProcess), where each object contains metadata about a specific step.
Objects in the array encapsulate actions such as preheating the grill, seasoning the steak, cooking to desired doneness, and serving the steak.
The use of objects allows for a structured and organized representation of the cooking process, enhancing readability and maintainability.
This approach aligns with declarative programming principles, where the emphasis is on expressing the desired outcome in a clear and concise manner, without getting bogged down in low-level implementation details.

1. **High-Level Process Description:** Explain the code logic in the declarative approach.

   - Describe the cooking process in a high-level, abstract manner. Higher-Level Abstraction: The cooking process is defined using an array of objects, where each object represents a step in the process. This abstraction level allows for expressing the cooking process in a more concise and readable manner, focusing on what needs to be done rather than how it's done.
   - Emphasize that the code defines "what" should happen rather than "how" it should happen.

2. **Use of Data Structures:** Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
   - Explain how the process steps are organized in a structured format.
   - Mention any abstraction layers or functions used to encapsulate actions.

Data-Driven: The cookingProcess array contains data that describes each step, including the action to be taken (action) and any relevant parameters (temperature, seasoning, desiredDoneness). This data-driven approach separates the logic from the data, making the code easier to understand and maintain.

Iterative Execution: The cooking process is executed using a loop that iterates over each step in the cookingProcess array. This approach allows for a more structured and systematic execution of the steps, enhancing readability and maintainability.

# Learning Outcome [1 Minute]

- Reflect on what you've learned from analyzing these code examples in different paradigms.

# Question Editor Component Specification

## Overview

The **Question Editor** is a drag-and-drop modular editor designed for creating exam questions. It facilitates a seamless and intuitive process for users to structure and compose questions efficiently.

## Composition

The component comprises three main areas:

### 1. Toolbar

- Contains draggable items represented by boxes.
- Items include short text, long text, image, question index, and table.

### 2. Droppable Zone

- Users place draggable items in a logical manner.
- Divided into sections:
  - Question description area (supports short text, image, and a combination of both).
  - Alternatives section (supports short text and images).

### 3. Preview Area

- Displays a real-time preview of the question.
- Provides rendering options for both PDF and browser.
- Options to separate visualization in tabs or open PDF in an external tab.

## Text Component Requirements

For Short and Long Text components, ensure the following functionalities:

- **Styles:**
  - Bold
  - Italic
  - Underlined

- **Alignment:**
  - Center
  - Left
  - Right
  - Justified

- **Additional Features:**
  - Add or remove indentation.
  - Add Mathematics equations.


### Low level prototypes:
Here I describe from my point of view (a developer view with zero experience in design) how the components could be arranged, in order to ilustrate my idea).
![image](https://github.com/gustavoteixeirah/QuestionEditorSpecification/assets/10344032/136f40d4-3d50-426d-bb77-451524f3f7fe)

And here is an example of a builded question:
![image](https://github.com/gustavoteixeirah/QuestionEditorSpecification/assets/10344032/cc640372-469f-4959-a09a-842c1fccc31c)

#### Drag and drop
The core idea is to use drag and drop so that the user can better organize his question. 

### The Reference block
This component in the toolbar is intended to be a material reference the user uses to resolve more than one question. For a better understanding, open the pdf in this repository. It contains a SAT Test that ilustrates this example. It is a Long Text (note we have numbered lines, I also want that), and that text is used to solve multiple questions. This is what the reference box in the toolbar means. I think about when the user clicks it, it opens a modal allowing the user to input the text or table as reference, and is should have access also to previously created references. Because it he creates an reference now, he may also want to use that reference later for other question. Also, one question can have only one reference. And a reference can be referenciated by many questions...


### Any suggestions and improvements are welcome!
As I say, I am not a UI/UX Designer... but you may be!

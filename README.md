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


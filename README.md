# Task 5- Interactive Contact Form with HTML5 Validation:
In this task, I enhanced the contact page by building a user-interactive form. The goal was to implement client-side data validation using only HTML5 attributes to ensure data integrity before submission.

Features Implemented:
Semantic Form Elements: Used <form>, <label>, <input>, and <textarea> to create a structured and accessible input area.

HTML5 Input Types: Utilized specific types like type="email" and type="tel" to trigger browser-specific behaviors (like mobile keyboard optimizations).

Native Validation:

required: Ensures fields are not left empty.

maxlength: Limits name input to prevent excessively long strings.

pattern: Used a Regex pattern [0-9]{10} to validate that the phone number contains exactly 10 digits.

Accessibility (A11y): Explicitly linked labels to inputs using the for and id attributes, allowing screen readers to identify form fields correctly.

Visual Feedback: Styled the form using CSS pseudo-classes (:invalid and :valid) to provide real-time color cues to the user as they type.

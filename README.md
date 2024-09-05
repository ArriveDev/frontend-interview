## Objective

Create a Task Management Page using the provided API endpoint (https://my-json-server.typicode.com/ArriveDev/frontend-interview/tasks), where each task and its details are displayed. The goal is to design an intuitive interface that allows users to view the list of tasks, along with their steps and completion status. The visual style should follow the design files provided, maintaining consistency with the overall user interface.

## Requirements

### Task List Display
- Display a list of tasks, showing key details like task name, description, and the author’s name.
- Include a visual indicator of how many steps are completed for each task (e.g., "3/5 steps completed").
- Ensure the tasks are visually separated, allowing users to easily differentiate between them.

### Task Details
- When a user clicks on a task, expand or navigate to a detailed view of that task.
- Display all the steps associated with the task. Each step should clearly show its completion status (e.g., checkbox or similar UI element).
- The detailed view should also show the full description of the task and the author’s information (first name, last name, and username).

### User Interactions
- Allow users to toggle the completion status of each step (e.g., mark a step as completed or not).
- The progress indicator (steps completed) should update in real-time when a step is marked as completed/uncompleted.

### Consistency with Design
- Follow the provided design files for layout, colors, typography, and spacing. The page should fit seamlessly into the broader UI design.
- Make use of existing design patterns like card layouts, buttons, and checkboxes to ensure visual consistency.

## Technical Requirements

### Framework/Library
- Use React to build the frontend page, and feel free to use a UI toolkit such as Tailwind if you feel most comfortable using that.

### Data Handling
- Use the provided API endpoint json structure to populate the page with task data.
- Handle data updates (like marking a step as completed) locally in the component state. No need to persist the changes on a server.

### Component Structure
- Break down the interface into reusable components. For example, create separate components for the task list, task details, and individual steps.
- Consider performance optimizations like avoiding unnecessary re-renders when updating task progress.

## Bonus

- Add filtering or sorting functionality to the task list (e.g., sort by task name, filter by tasks that are fully completed or not).
- Implement animations for transitions when expanding/collapsing task details or updating step completion.

## Evaluation Criteria

- **Code Quality**: Clear and maintainable code structure, appropriate component design, and proper use of React best practices.
- **UI/UX Consistency**: Adherence to the provided design guidelines and ensuring a smooth, intuitive user experience.
- **Functionality**: The ability to accurately render tasks and allow user interaction with task steps.

Good luck, and we look forward to seeing your implementation!

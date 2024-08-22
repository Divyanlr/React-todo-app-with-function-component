
The TodoList component allows users to add new items to a list and delete them. It is built using React's functional components and the useState hook for state management.

	1. State Management:
		○ todos: An array that holds the list of to-do items.
		○ newTodo: A string that stores the current input value from the user.
	2. Input Handling:
		○ handleInputChange(event): This function updates the newTodo state as the user types in the input field, capturing the current value of the input.
	3. Adding Items:
		○ handleAddTodo(): This function is triggered when the "Add" button is clicked. It checks if the input field is not empty (using trim() to avoid adding empty or whitespace-only items), then adds the new item to the todos array and clears the input field.
	4. Deleting Items:
		○ handleDeleteTodo(index): This function removes an item from the todos array based on its index. It uses the filter() method to create a new array without the item at the specified index.
	5. Rendering the UI:
		○ The component returns JSX that includes:
			§ A heading for the to-do list.
			§ An input field where users can type a new to-do item.
			§ A button to add the typed item to the list.
			§ An unordered list (<ul>) that dynamically displays all items in the todos array.
			§ Each list item (<li>) displays the to-do item along with a "Delete" button to remove the specific item from the list.
![image](https://github.com/user-attachments/assets/4ad0f115-6e79-46f6-add3-6cf893044c09)

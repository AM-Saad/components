MultiSelect Component
Props:
- options: an array of objects to be displayed in the dropdown list
- multiple: a boolean indicating whether multiple options can be selected
- closeOnSelect: a boolean indicating whether the dropdown list should close after selecting an option
- placeholder: a string to be displayed as a placeholder in the input field
- id: a string representing the ID of the component
- label: a string representing the name of the field
- trackBy: a string representing the unique key to track items by in the options array
- disabled: a boolean indicating whether the component is disabled
- input: a function to be called when a value is selected, with the selected items passed as an argument
- preSelected: an optional array of pre-selected items
- refresh: a prop to force the component to refresh when it changes

Functions:
- compareStr: a function to compare a string against a search pattern
- search: a function to filter options based on user input
- selectItem: a function to handle the selection of an item
- remove: a function to remove an item from the list of selected items
- checkIfSelected: a function to check whether an item is selected
- closeList: a function to close the dropdown list
*/

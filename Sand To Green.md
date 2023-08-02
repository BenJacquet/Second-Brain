- "Create Plantation" template served by Django View:
	- Form validation by Alpine:
		- Write to store if valid and redirect to "Sections Planning" (by Django or HTMX ?)
		- Highlight incorrect fields if invalid

- Fetch sections from the store and display them in the template

- Create section button redirects to "Section Planning":
	- Form validation by Alpine:
		- Write to store and redirect to "Sections Planning" if valid
		- Highlight incorrect fields if invalid
		- Redirects to "Sections Planning" and Displays Notification if section count is invalid

- When Next button is clicked, the View creates the entry in database and redirects to "Plantation Results" with the plantation ID as query parameter:
	- If plantation ID does not exist, redirect to "All Scenarios" and display notification.
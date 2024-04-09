# Arguments
- Simplicity: Keeps its responsibility simple by focusing solely on displaying an alert message for successful product saves. Its limited scope reduces complexity and makes it easier to maintain.
- Single Responsibility: Adheres strictly to the single responsibility principle by handling only the display of the product saved alert. It does not concern itself with the logic of saving products or other unrelated tasks.
- Reusability: While the product saved alert may be specific to certain pages or actions within the app, isolating it into its own MFE promotes reusability. Developers can easily incorporate the alert into different application parts without duplicating code or introducing inconsistencies.
- Independent Deployment: Updates or changes to the product saved alert MFE can be deployed independently, allowing teams to iterate on its design or functionality without impacting other app parts.

# Responsability
Responsible for displaying an alert message confirming the successful save of a product. It contains the necessary logic and UI elements, such as text description and a button to close the alert.

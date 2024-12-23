# JIRA Task Manager

This Python script provides a GUI-based application to manage JIRA tasks. It enables users to create, edit, and search tasks efficiently, saving the data locally in a CSV file. The intuitive interface ensures a seamless user experience for task management.

## Features

- **Task Creation**: Create new JIRA tasks with fields like prefix, JIRA number, title, description, dates, tags, and URL.
- **Task Editing**: Edit existing tasks by searching via JIRA number or tags.
- **Tag-Based Search**: Quickly find tasks associated with specific tags.
- **Data Persistence**: Automatically saves tasks to a CSV file on your desktop.
- **User-Friendly Interface**: Built with `Tkinter` for easy navigation and interaction.
- **URL Integration**: Open JIRA task URLs directly from the application.

## How to Use

### Prerequisites

- Python 3.x installed on your system.

### Running the Script

1. Clone the repository or download the script:
   ```bash
   git clone https://github.com/moturkmani/jira-task-manager.git
   cd jira-task-manager
   ```

2. Install the required dependencies (if any):
   ```bash
   pip install tk
   ```

3. Run the script:
   ```bash
   python jira_taskmanager.py
   ```

4. Use the main window to:
   - **Create New JIRA Task**: Fill in the required fields and save.
   - **Edit Existing JIRA Task**: Search by JIRA number or tags and make updates.

### Example Usage

1. **Create a Task**:
   - Open the app and click on **Create New JIRA**.
   - Enter details such as `Prefix`, `JIRA #`, `Title`, and `URL` (mandatory fields).
   - Add optional fields like `Description`, `Start Date`, `Due Date`, and `Tags`.
   - Save the task, and it will be added to the CSV file.

2. **Edit a Task**:
   - Click on **Edit Existing JIRA**.
   - Search by `JIRA #` or `Tags`.
   - Update the fields and save the changes.

3. **Search Tasks**:
   - Use tag-based search to find tasks matching specific keywords.

### File Structure

```
jira-task-manager/
├── jira_taskmanager.py  # Main script for managing JIRA tasks
└── JIRA_Tasks.csv       # CSV file created on the desktop for task persistence
```

## Customization

- **Fields**: Add or modify fields in the JIRA task entries.
- **CSV Location**: Change the default path for the CSV file.
- **Search Options**: Extend search functionality to include more fields.

## Troubleshooting

- **File Not Found**: Ensure the CSV file is created on the desktop.
- **Dependencies**: Verify that `tkinter` is installed (comes pre-installed with Python).
- **Error Saving Tasks**: Check permissions for writing to the desktop.


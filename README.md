# AutoFileOrganizer-PowerAutomate

## Overview
AutoFileOrganizer is a Power Automate Desktop script designed to enhance file management efficiency. It automates the process of sorting files from a shared folder into specific directories based on their creation dates. This script is ideal for both personal and professional environments where file organization and time management are crucial.

## How it Works

### Flow Logic
1. **Retrieve Files**: The script starts by fetching all files from a specified shared folder.
2. **File Iteration**: It then iterates through each file, assessing its attributes.
3. **Date Extraction**: For each file, the script extracts the creation date.
4. **Directory Check/Create**: It checks if a directory named after the file's creation date exists. If not, the script creates this new directory.
5. **File Organization**: Finally, each file is moved to its corresponding date-named directory, ensuring organized file management.

### Features
- **Automated Sorting**: Files are automatically sorted based on their creation dates.
- **Directory Management**: Directories are created dynamically, corresponding to the dates.
- **Time Efficiency**: Significantly reduces the time and effort involved in manual file organization.

### Instructions to use in Power Automate Desktop

1. Open Power Automate Desktop and start a new flow.
2. Copy and paste the script text directly into the new flow.
3. Configure each action with the appropriate parameters (folder paths).

# Data Stream Status Task Pipeline
## Overview
This repository contains Power Query M code used to transform and analyze task-level data from the Apollo MDM initiative. The query processes structured Excel input (Table2) and outputs a unified view of tasks with delay status indicators, validator assignments, and key dates.

## Features
Unpivots task-specific columns into a normalized structure
Classifies tasks and attribute types dynamically
Merges validator information from source metadata
Calculates task and project delay status
Outputs a clean, grouped table for reporting or dashboard use

## File Structure
/PowerQuery/
├── TaskPipeline_v1.1.m   # Latest version of the M code
├── CHANGELOG.md                     # Version history and updates
└── README.md                        # Project documentation

# Usage
Open Power BI or Excel Power Query Editor
Paste the contents of Apollo_MDM_TaskPipeline_v1.1.m into a new query
Ensure the source table is named Table2 and includes all expected columns
Refresh the query to generate the transformed output

# Versioning
This project uses manual version control via GitHub. Each version of the M code is saved with a semantic version tag (e.g., v1.0, v1.1). See CHANGELOG.md for details.

# Author
Ashley Brantner
IT Manager, Master Data Management

# Change log
Change log for the RAW Labs VS Code extension

## [1.3.8] - 27-07-2022

### Changed

- Minor Fixes

## [1.3.6] - 20-07-2022

### Added

- Polling long queries
- Raw view
- Large datasets rendering management
  - For Raw View the lines are rendered dynamically while scrolling
  - For Tree View all the entries are chunked and collapsed and render dynamically
  - For Table View if a record is more than 1000 lines of code, render only one row
- Query total execution time (without rendering) output
- All the views both to flat data and nested data

### Changed

- Fixed unauthenticated ctl + click availability
- Activated scratchpad type output

## [1.3.2] - 07-07-2022

### Added

- Scratchpad rql query type view. The view is triggered on save
- Cancellation on any query execution (Scratchpad, yaml, test)

### Changed

- Fixed null, empty string, undefined data visualization issue
- Fixed ctl + click describe queries bug

## [1.3.1] - 04-07-2022

### Changed

- Visualization bugs fixes

## [1.2.8] - 01-07-2022

### Changed

- Added data visualization tab for every type of queries (yaml, scratchpad, describe) both flat and nested.

## [1.2.3] - 19-05-2022

### Changed

- Fixed right click - describe bug
- Changed run code result type

## [1.2.2] - 19-05-2022

### Added

- Steps on the api creation
- `Describe` visualization with copy button
- Auto update when GitHub reader is installed to the current repository

### Changed

- Changed the views and the descriptions on every setting up step
- Fixed dangling play button when all tests are removed
- Stopped showing yaml files in test browser for files without tests 


## [1.1.9] - 11-05-2022

### Added

- API testing
- Get Started View template creation, cloning repository and opening file
- Section formatter for strings copied from Describe -> type field

### Changed

- YAML Schema updated (Now it provides fields explanation on hover and a documentation link)
- Snippets updated
- Made the environment definition in settings a dropdown
- Templates not overriding existing files
- Deleting test object on repose

### Removed

- Templates that are not yet implemented

## [1.1.6] - 29-04-2022

### Changed

- Fixed Memory Leak

## [1.1.5] - 26-04-2022

### Added

- Template generation
- User State Track and Suggestions
- News on start page
- Publish to github for the unpublished repos

### Changed

- Moved login to sidebar
- Moved yaml play button on the same spot as in scratchpad
- Minor UI changes

### Removed

- Custom file system

## [1.0.7] - 28-03-2022

### Added

- Named Argument Sets

### Changed

- Fixed Logs Polling Bug
- Fixed Prod Environment bugs

## [1.0.3] - 23-03-2022

### Added

- Login from within VS Code
- RAW Labs Start page
- Walkthrough to get started

## [0.1.3] - 03-02-2022

### Removed

- Hidden filesystem items
- Play button from raw-site.yaml

## [0.1.2] - 03-02-2022

### Added

- Converted to extension pack

## [0.1.1] - 03-02-2022

### Added

- Changed description and title

## [0.1.0] - 02-02-2022

### Added

- Marketplace Release

## [0.0.9] - 27-01-2022

### Added

- Secret Data Source Visualization Support

## [0.0.8] - 26-01-2022

### Added

- Autocompletion

### Changed

- Fixed indentation bug

## [0.0.7] - 24-01-2022

### Added

- Documentation on hover
- Running DESCRIBE on urls inside RQL file
- Comment toggle by shortcut
- Autocomplete brackets and parentheses
- Surround code with brackets, quotes, parentheses, brackets

### Changed

- Fixed typealias highlighting

## [0.0.6] - 19-01-2022

### Changed

- Fixed Windows File Schema bug

## [0.0.5] - 18-01-2022

### Added

- Scratchpad
- Added back-end cancellation code invocation
- Added all files saving on running code
- Internal readme for running the extension

### Changed

- Result file names from "result-x" to "filename-x"
- Fixed logging warning message
- Fixed comments bug
- Logo

### Removed

- Third party json viewer

## [0.0.4] - 12-01-2022

### Added

- Unit tests mechanisms

### Changed

- Fixed Windows File system bug

## [0.0.3] - 05-01-2022

### Added

- Running YAML file with arguments
- README file
- Added Logout on token expiration
- Added Json Editor color change based on current theme

### Changed

- Test endpoint obtainment from token
- Updated YAML validation schema

### Removed

- Lambda function call
- Organization Pop up
- Organization Settings
- Organization Validation

## [0.0.2] - 22-12-2021

### Added

- Refresh button for RAW file system
- Refresh button for Data Sources
- Extension Logo
- Error Handler

## [0.0.1] - 21-12-2021

### Added

- RAW extension VS Code panel tab
- Basic syntax highlighting for RQL files
- Basic snipets for YAML files
- Basic snipets for RQL files
- Authentication
- Token validation
- Lambda call for organization validation
- RAW organization settings entry
- Organization pop up
- Running YAML files (via play button, right click, shortcut)
- Data Sources visualization
- Data Sources Test Access
- Showing execution logs
- Showing and underlining RQL errors
- YAML validation through JSON schema


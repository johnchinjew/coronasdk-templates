# Corona SDK Templates

## `module.lua`

- For storing related data into the `module` table (effectively a singleton).
- For storing related utility functions.

## `object.lua`

For creating OOP instances. The following are possible:

- Private (file local) constants
- Private (file local) helper functions
- Class attributes and methods
- Instance constructors (and attributes)
- Instance methods

## `scene.lua`

- The Corona SDK scene template with comments explaining everything that must be created and destroyed.

## `extension.lua`

- For extending existing global libraries (e.g. `timer`).
- Just be sure to `require("extension.lua")` in `main.lua`, so that your extension can be used everywhere.

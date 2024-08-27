----------------
**encryptionMessages**\n
**PenguinSnakes product**\n
**version: 1.1**\n

**BASED ON YOUR COMPUTER YOU MAY NEED TO COPY Encryption-Messages-1.1/internals_/codex files/ TO Encryption-Messages-1.1/codex files/ FOR INSERT TO WORK**
----------------

**Important**:
- Message and Library will be used interchangibly in this description

**Important Notes**:
- If a message/library is already installed and you use `insert`, it will return:
  Error: Library with code 'CODE' already exists. Please use a unique code for 'FILENAME'.
  (Use `insert -u` to update the library.)

- This is the developer version, and so two addons come preinstalled:
  - **CreateTool**
  - **AdderTool**
  - (please note you will havev to use insert -i Tool_Code to make them work!)

**Usages**:
- To run CreateTool, use `create`, then follow the prompts to input the following details:
  1. Code (for secrecy)
  2. Message Name (title)
  3. Message Version (put whatever you like)
  4. Author's Name (company name/nick name)
  5. Author's Tag (shortened version of name)
  6. Message Description (actual text)
  7. License Type (e.g., MIT or None)
  8. URL (this field is currently unused)

- To run AdderTool, use `add` followed by the path to the .codex file, like:
  `add C:/downloads/example.codex`
  After that, use `insert -i message_code` to install it, then use `check` to verify or instead use `insert message_code` to just view message details.

**Installation Recommendation**:
- After installing Encryption Messages, it is recommended to run:
  `insert -i 0`,
  `0`
  (Note: If you type in the code of an installed message, it will return the description. Example: 0 = help_description)

**Codes For Preinstalled Addons/Messages**:
- CreateTool.codex: 11224
- AdderTool.codex: 32856
- help.codex: 0
- present.codex: :3
- sad.codex: kms

**WARNING**:
DO NOT TYPE `:3` INTO THE TERMINAL AFTER INSERTING PRESENT.CODEX!!!

**Command Summary**:
- `insert -h` : Displays help for the `insert` command
- `create` : Runs the CreateTool for creating new messages/libraries
- `add [path]` : Runs the AdderTool to add a .codex file
- `insert <optional_flag> [message_code]` : Installs or finds a message/library
- `check` : Displays installed messages/libraries
- `delete [message_code]` : Deletes a message/library

**Have Fun!**

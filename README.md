# Bash Modules
The **Bash Modules** project is a collection of Bash scripts that provides additional functionality.

## Usage

1) Clone (or download + extract) this repository.
2) Set the **BASH\_MODULES\_PATH** variable to correct path: `BASH_MODULES_PATH="[path]/bash_modules"`
3) Source the **module_loader**: `source "${BASH_MODULES_PATH}/module_loader"`
4) To use functionality from any module, all you need to do is to load it: `load_modules "color"`
5) Check if **color\_module** was loaded successfully: `echo "${B_GREEN_FG}SUCCESS${NO_COLOR}"`

## Documentation

Every module has summarized description at the beginning of the file.

For more details you should check the description right above the function definitions.

And of course, for even deeper understanding, you can always study the code.

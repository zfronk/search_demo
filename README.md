```markdown
# File Operations in C

This is a simple C program that demonstrates basic file operations, including creating and writing to a file, reading data, counting lines, and searching for a string within the file.

## Features
- **Create and Write File**: Creates a file if it doesn't exist and appends data to it.
- **Read File**: Reads and displays the content of the file.
- **Count Lines**: Counts the number of lines written in the file.
- **Search String**: Searches for a specific string within the file.

## Functions
1. **create_and_write()**: Creates the file `demo.txt` (if it doesn't exist) and appends data to it.
2. **read_file()**: Reads and displays the content of the `demo.txt` file.
3. **count_written_lines()**: Counts and displays the number of lines in the `demo.txt` file.
4. **search_string(char *string_to_be_found)**: Searches for a specific string in the `demo.txt` file and outputs its position and line number.

## How to Use
1. **Clone the repository** or copy the code to your local machine.
2. **Compile the program**:
   ```bash
   gcc file_operations.c -o file_operations
   ```
3. **Run the program**:
   ```bash
   ./file_operations
   ```

4. **Functions in Action**: The program will automatically attempt to:
   - Read the file content.
   - Count the number of lines.
   - Search for the string `"Boke"` in the file.

## Notes
- Ensure that the `demo.txt` file exists in the same directory as the program, or the program will attempt to create it.

## License
MIT License - see the [LICENSE](LICENSE) file for details.
```

This README explains the key features and functions of the program clearly and concisely. You can update or add further explanations as needed!

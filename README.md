
```markdown
# stdate

A simple bash script to add date and time stamps to text files.

## Usage

```bash
./stdate filename.txt
```

Replace `filename.txt` with the name of the file you want to add timestamps to.

## Requirements

- Bash shell
- Nano text editor

## How It Works

The script prompts you to edit a temporary file using Nano. After editing, it appends a timestamp along with the edited content to the specified file.

## Note

If the editing is canceled or the temporary file is empty, no changes will be made to the main file.

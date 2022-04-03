# PLDGenerator

A (super) script to generate EPITECH's EIP Project Log Documents.

## Requirements

You need to populate the assets' folder with those files:
- primary_logo.svg: Your primary logo in the svg format 
- secondary_logo.svg: Your secondary logo in the svg format 
- *.json: Your PLD document in the form of a json which follow this schema: <https://raw.githubusercontent.com/ThalusA/PLDGenerator/master/pld_schema.json>

## Usage

```bash
# add sudo if you can't use docker as an non-root user
make release
# now you have your Project Log Document in the form of a LaTeX and PDF document in the build folder
```

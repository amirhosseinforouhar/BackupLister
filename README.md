# BackupLister
Backup Lister is a tool designed to generate backup file wordlists from a given input host. It generates filenames with common backup file extensions, such as .bak, .zip, .tar, .sql, etc., appended to the input host.

# Features
- Generates backup filenames for common backup file extensions.
- Provides an option to save the generated filenames to an output file.
- Simple command-line interface with easy-to-use flags.

# Installation
Backup Lister does not require any installation. Simply clone the repository and run the script.

```bash
git clone https://github.com/your_username/backup-lister.git
```
```bash
cd backup-lister
```
```bash
python script.py -i <input_host> [-o <output_file>]
```



# Usage
To use Backup Lister, simply run the script script.py with the following command:


```bash
python script.py -i <input_host> [-o <output_file>]
```
Replace <input_host> with the host name or identifier for which you want to generate backup filenames. Optionally, specify an output file with the -o or --output flag to save the generated filenames.
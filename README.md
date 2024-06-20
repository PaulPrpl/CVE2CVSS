## CVE2CVSS : a simple script to get CVSS scores from your discovered CVEs

## Prerequises
Tu run this script, you'll need:
- Bash
- POSIX builtins such as `cat` and `mkdir`
- jqlang
- cURL
## Usage:

##### Set the script executable :
`chmod +x ./run.sh`
##### Run the script :
`./cve2cvss`

###### Nota :
- Data from NVD database will be stored in the same directory than the script, and a new folder will be made each time to avoid overwriting
- A distinct JSON object will be created for __EVERY__ CVEs you'll process in subdirectory "data"
- You'll need write permissions to the current script directory
- Output is written in CSV for convenience

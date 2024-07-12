# CVE-2024-4879
Bulk scanning tool for ServiceNow CVE-2024-4879 vulnerability.


![Banner](screens/screen.jpg)


## Overview

This tool is designed for bulk scanning of the ServiceNow CVE-2024-4879 vulnerability. It is inspired by [Assetnote](https://www.assetnote.io/resources/research/chaining-three-bugs-to-access-all-your-servicenow-data) security research, which covers the recent ServiceNow CVE-2024-4879, CVE-2024-5178, and CVE-2024-5217 vulnerabilities in detail.

## How to Use

### Minimum Requirements

- Python 3.6 or higher
- `requests` library
  
### Single Target:
```sh
python CVE-2024-4879.py -u https://target:9090
```

### Bulk Sscan:
```sh
python CVE-2024-4879.py -f targets.txt
```

## Contact

For any suggestions or thoughts, please get in touch with [me](https://x.com/MohamedNab1l).


## Disclaimer

I like to create my own tools for fun, work and educational purposes only. I do not support or encourage hacking or unauthorized access to any system or network. Please use my tools responsibly and only on systems where you have clear permission to test.

## References

- https://www.assetnote.io/resources/research/chaining-three-bugs-to-access-all-your-servicenow-data
- https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-4879

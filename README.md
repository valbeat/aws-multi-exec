# AWS Command Line Helper

## Overview
AWS Command Line Helper is a Bash script designed to simplify AWS EC2 instance management. This script provides easy access to common actions such as executing commands on remote instances, clearing cached data, and establishing SSH connections.

## Features
- Execute commands on all remote EC2 instances.
- Clean cache to refresh instance data.
- Select and SSH into a specific EC2 instance.
- List and manage instances interactively.

## Requirements
- AWS CLI must be installed and configured.
- SSH Key for secure access to instances.
- `peco` or similar for interactive filtering (optional).

## Installation
1. Download the script.
2. Make it executable: `chmod +x aws-cmd.sh`
3. Optionally, move it to a directory in your PATH for easy access.

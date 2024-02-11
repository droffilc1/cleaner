# System Cleaner Script

This Bash script automates the process of updating, upgrading, and cleaning up a Debian-based Linux system. It helps maintain a clean and up-to-date system by performing various maintenance tasks, including updating packages, removing unnecessary files, and repairing broken dependencies.

## How to Run

1. **Clone the Repository:**
    
    ```bash    
    git clone https://github.com/droffilc1/cleaner.git
    ```
    
2. **Navigate to the Repository:**
    
    ```bash    
    cliff@ubuntu:~$ ls
    cleaner
    cliff@ubuntu:~$ cd cleaner/
    cliff@ubuntu:~/cleaner$
    ```
    
3. **Add Script to $Path:**
   Locate the file `cleaner` and copy it to your $PATH folder. **This will prompt for the root password**   
    ```bash
    cliff@ubuntu:~/cleaner$ ls
    cleaner  LICENSE  README.md
    cliff@ubuntu:~/cleaner$ sudo cp cleaner /usr/bin/
    [sudo] password for cliff: 
    cliff@ubuntu:~/cleaner$
    ```
    
    
5. **Run the Script:**
   You can update, upgrade and clean-up your linux distro by running janitor anywhere in your terminal.
   ```bash
   cliff@ubuntu: cleaner
   ```    

## Notes

- **Root Privileges:**
    
    - The script requires root privileges to perform system updates and package installations. Ensure you have appropriate permissions or run the script with `sudo`.
- **Use with Caution:**
    
    - While the script aims to maintain a clean and updated system, it's recommended to review the actions it performs and ensure they align with your intentions before proceeding.

## Contributions

Contributions and feedback are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Credits
[Firdaus H. Salim](https://github.com/betascribbles)

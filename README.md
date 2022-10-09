## Exploit Title: PhreeBooks ERP 5.2.3 (Bizuno Library 3.1.7) - Arbitrary File Upload & Remote Code Execution
## Version: 5.2.3
## Tested on: Windows Server 2016 64-bit

### Instructions

1. Modify windows.php, enter your own IP and Port
2. Ensure listener is listening at your Port
3. Run `python3 exploit -t <TARGET HOST> -p <PATH/TO/PAYLOAD.php>` 
4. Receive reverse shell

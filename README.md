iOSMessageExport
================
This is not exactly the best way to use Perl. However, I wanted to create it as simple and readable as I possibly could so that others would be able to modify the code to better suit them. 

Notes

* Emojis would only show up when viewing the pages in Safari. 
* Images are visible within the message threads, but all other content is linked. 

Basic steps: 

1. Make a directory somewhere 
    ```
    mkdir ~/Desktop/iOSBackup
    ```
2. Add backup.pl and iOSSMSBackup.pm to this directory
3. I reccomend copying your iTunes backup into your ~/Desktop/iOSBackup folder, just in case something bad happens (as I am not responsible for your misfortunes). Run backup.pl passing the backup directory. 
    ```
    perl backup.pl --directory_path 9b9f73759fad7b31e330dd26bf7f745acccf1869/
    ```
4. An _export folder will be created in your working directory with all of your files! 

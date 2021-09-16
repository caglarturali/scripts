# Scripts

Shell scripts I wrote mostly for fun. :grin:

## Descriptions

[appimlaunch](appimlaunch): Launches the newest AppImage in the given directory. Nice to have if your AppImage does not care about desktop shortcuts, thus leaving you with a broken one after updating itself to a newer version.

-   Update the `Exec` line in the `.desktop` file as follows after obtaining the script:
    ```bash
    Exec=sh -c "/path/to/appimlaunch /path/to/application/dir/ [optional_keyword]"
    ```

[btconn](btconn): (Auto)connects to a Bluetooth device with the given MAC address. Takes care of the pairing and trusting the device too.

[chgov](chgov): Lists and changes the CPU scaling governor.

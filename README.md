An example library and test program, as a proof of concept for an Arduboy EEPROM management API, as discussed in the Arduboy forums here:
http://community.arduboy.com/t/shared-eeprom-storage-management-across-multiple-apps/125/21

This back-end stores the user data in allocated RAM, so it won't be non-volatile. It could be used during sketch debug to prevent excessive writes to real EEPROM.



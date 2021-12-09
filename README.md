# microsoft365

collection of how to's and (personal) best practice workarounds

#think about using more than one active directory server to sync to azure ad?
>> not supported, but working properly while using immutable-id as cloud anchor (default settings) on each active directory. take care: don't sync duplicate objects!


#convert cloud user to active directory synced users without changing ad-sync default settings to use immutable-id as sync anchor

>> follow me: https://github.com/hirschQ/microsoft365/blob/ace0863c2f6f7615c7c15d5903c2c774442ad83e/delete-user-cloud2aadsynced
      #getting erros while step convert-user-cloud2aadsynced?
      >> follow https://github.com/hirschQ/microsoft365/blob/ed22d50bfdc9bc4ee2b313f3073a26690f1b79f6/connect-to-msonline


>> follow me next: https://github.com/hirschQ/microsoft365/blob/2eb9144942c82ca0b80a3217d475a092eca520b0/convert-user-cloud2aadsynced

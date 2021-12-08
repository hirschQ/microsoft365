# microsoft365

collection of how to's and (personal) best practice workarounds

#think about using more than one active directory server to sync to azure ad?
>> not supported, but working properly while using immutable-id as cloud anchor (default settings) on each active directory. take care: don't sync duplicate objects!


#you want to convert cloud user to active directory synced users without chaning ad-syncs' default settings to use immutable-id as sync anchor?

>> follow file convert-user-cloud2aadsynced



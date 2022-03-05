Simple worked hours apointment lwc component.

SObjetcs used in this sample-project are not included, please adapt to your use case <3
you are free to download, modify, distribute or use this code in any way your heart desires.

Here you can see the SObject relationship/custom used this LWC:

    > Sprint__c

    > WorkedDay__c [lookup]-> User (Owner)

    > Story__c [lookup] -> Sprint__c
    > Story__c [lookup] -> User (Owner)

    > Apointment__c [master-detail] -> WorkedDay__c
    > Apointment__c [lookup]        -> Story__c
    > Apointment__c [lookup]        -> User (Owner)
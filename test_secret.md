Test a fake connection string and check if I can push to the github.

Test connection: Server=tcp:testdb.database.windows.net,1433;Database=testdb;User ID=user@testdb;Password=PA!SSWA@R1fdsafDA;Trusted_Connection=False;Encrypt=True;


Test connection: Server=tcp:mycosmos.database.windows.net,1433;Database=myDataBase;User ID=login@mycosmos;Password=PA!SSWA@RsadA;Trusted_Connection=False;Encrypt=True;

Add a blob URL with valid SAS token: https://storageaccountyipub54a.blob.core.windows.net/demo/empty.txt?sp=r&st=2023-05-12T07:27:05Z&se=2023-05-15T15:27:05Z&spr=https&sv=2022-11-02&sr=b&sig=aibqKsPwMRb7YzNxJGQN%2FfzoA3FgRc0wFlIaFxpqPF8%3D

Add azure function master keys:
{
  "functionKeys": {
    "default": "68ahyfSAT2PF5HfIuGMyc8Bv6NErsFxnk6lT0l2fYacYCnVameOAmw=="
  },
  "masterKey": "N4O1a4ng/gLemQEiDFF9HUpNznT/pFGNSnTj4jQXVOhvZAa8MivuOg==",
  "systemKeys": {
    "durabletask_extension": "DtieTxAOV5x76Zfv6NWBqbbW3/u4YiHVhycZfPgn2VIgkcPAGP8kaA=="
  }
}


Add azure function specific keys:
{
  "default": "ukRsq3yoeayz5ELYgTGK3fbU3yfbHXavy5m9Y6ci0ZSykqFYUxyd3Q==",
  "id": null,
  "kind": null,
  "name": null,
  "properties": null,
  "systemData": null,
  "type": null
}

Navigate to https://app.fabric.microsoft.com/
Logon with the user provided to you. The initial password is FabricDynUG2025

<b>Create Workspace</b>

Use the name "DynUG workshop XX" where XX is the number of your user.

<b>Setup task flow in workspace</b>
Select predesigned task flow "Medallion"
Delete:
- Further transform
- ML serving 
Create link between Silver data and Gold data
Rename "Low-volume data ingest" to "Load from Fabric SQL db" and "High-volume data ingest" to "Load customer reviews"

<b>Create Lakehouse</b>

Use the name "DynUG_Lakehouse"
Assign to task "Bronze data"

Leave Lakehouse open

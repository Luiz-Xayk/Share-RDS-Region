🇺🇸 [English](README.md) | 🇧🇷 [Português](README.pt-BR.md)

# Share-RDS-account-region

Step-by-step guide to sharing Amazon RDS snapshots with other AWS accounts and copying them to other regions.

## Creating and Sharing a Snapshot Across Accounts

- In the RDS console, go to **Snapshots** and click **Take snapshot**.
- Select the generated snapshot, click **Actions**, then **Share snapshot**. Set it to private or public and add the ID of the account you want to share the snapshot with.
- Sign in to the other account, go to **Snapshots**, and open the **Shared with me** tab. Click **Actions**, then **Restore snapshot**.

## Copying a Snapshot to Another Region

- In the RDS console, go to **Snapshots** and click **Take snapshot**.
- Select the generated snapshot, click **Actions**, then **Copy snapshot**. Enter a name for the DB and select the destination region.
- Once the copy status shows **Completed**, click **Actions**, then **Restore snapshot**.

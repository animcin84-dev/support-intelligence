# src/server/integrations/gmail/sync.ts

- SyncCounts · interface · L21-L26 — interface SyncCounts
- clientFor · function · L28-L30 — function clientFor(account: GmailIntegrationAccountRow, override?: GmailClient)
- persistRawMessage · function · L32-L45 — async function persistRawMessage( account: GmailIntegrationAccountRow, client: GmailClient, messageId: string, counts: SyncCounts, )
- listEligibleThreadIds · function · L47-L56 — async function listEligibleThreadIds(client: GmailClient, query: string)
- runFullGmailSync · function · L59-L126 — async function runFullGmailSync(input: { integrationId: string; kind?: "initial" | "manual" | "recovery"; client?: GmailClient; })
- runIncrementalGmailSync · function · L128-L219 — async function runIncrementalGmailSync(input: { integrationId: string; kind?: "incremental" | "manual"; client?: GmailClient; })

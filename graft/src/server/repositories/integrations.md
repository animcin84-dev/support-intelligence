# src/server/repositories/integrations.ts

- IntegrationAccountRow · type · L5-L5 — type IntegrationAccountRow = typeof integrationAccounts.$inferSelect;
- GmailIntegrationAccountRow · type · L7-L7 — type GmailIntegrationAccountRow = IntegrationAccountRow & { provider: "gmail"; emailAddress: string };
- asGmailIntegration · function · L9-L11 — function asGmailIntegration(row: IntegrationAccountRow | undefined): GmailIntegrationAccountRow | undefined
- getIntegrationByProviderAccount · function · L13-L18 — async function getIntegrationByProviderAccount(provider: string, providerAccountId: string)
- recordWhatsAppInboundAccount · function · L20-L30 — async function recordWhatsAppInboundAccount(phoneNumberId: string)
- getActiveGmailIntegration · function · L32-L39 — async function getActiveGmailIntegration()
- getGmailIntegrationByEmail · function · L41-L48 — async function getGmailIntegrationByEmail(email: string)
- getIntegrationById · function · L50-L53 — async function getIntegrationById(id: string)
- upsertGmailIntegration · function · L55-L98 — async function upsertGmailIntegration(input: { providerAccountId: string; emailAddress: string; encryptedRefreshToken: string; grantedScopes: string[]; lastHistoryId?: string | null; syncQuery?: string; backfillDays?: number; })
- updateIntegrationSyncState · function · L100-L102 — async function updateIntegrationSyncState(id: string, syncState: string, lastError: string | null = null)
- updateIntegrationCursor · function · L104-L111 — async function updateIntegrationCursor(id: string, historyId: string, syncedAt = new Date())
- updateWatchState · function · L113-L120 — async function updateWatchState(id: string, expiration: Date)
- getIntegrationDataCounts · function · L122-L131 — async function getIntegrationDataCounts(integrationAccountId: string)
- disconnectIntegration · function · L133-L140 — async function disconnectIntegration(id: string)
- getLatestSyncRun · function · L142-L150 — async function getLatestSyncRun(integrationAccountId: string)
- updateIntegrationSettings · function · L152-L158 — async function updateIntegrationSettings(id: string, input: { syncQuery?: string; backfillDays?: number })

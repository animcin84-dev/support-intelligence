# src/server/services/integration-service.ts

- supportDataMode · function · L23-L25 — function supportDataMode(): "mock" | "database"
- connectGmailFromCode · function · L27-L58 — async function connectGmailFromCode(code: string)
- getGmailIntegrationStatus · function · L60-L96 — async function getGmailIntegrationStatus(): Promise<IntegrationStatusDTO>
- manualGmailSync · function · L98-L104 — async function manualGmailSync()
- renewActiveGmailWatch · function · L106-L110 — async function renewActiveGmailWatch()
- disconnectActiveGmail · function · L112-L137 — async function disconnectActiveGmail()
- updateActiveGmailSettings · function · L139-L149 — async function updateActiveGmailSettings(input: { syncQuery?: string; backfillDays?: number })

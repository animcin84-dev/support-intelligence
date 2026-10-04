# src/server/repositories/sync.ts

- acquireSyncLock · function · L10-L22 — async function acquireSyncLock(integrationAccountId: string, owner: string)
- releaseSyncLock · function · L24-L26 — async function releaseSyncLock(integrationAccountId: string)
- createSyncRun · function · L28-L41 — async function createSyncRun(input: { integrationAccountId: string; kind: "initial" | "incremental" | "manual" | "recovery"; historyIdBefore?: string | null; })
- finishSyncRun · function · L43-L64 — async function finishSyncRun(id: string, input: { status: "succeeded" | "failed"; messagesFound?: number; messagesInserted?: number; messagesSkipped?: number; threadsFound?: number; historyIdAfter?: string | null; errorCode?: string | null; errorMessage?: string | null; })
- registerPubSubNotification · function · L66-L73 — async function registerPubSubNotification(input: { messageId: string; emailAddress: string; historyId: string })
- markPubSubProcessed · function · L75-L77 — async function markPubSubProcessed(messageId: string)
- getOutboundOperation · function · L79-L89 — async function getOutboundOperation(integrationAccountId: string, clientRequestId: string)
- createOrGetOutboundOperation · function · L91-L101 — async function createOrGetOutboundOperation(input: { integrationAccountId: string; conversationId: string; clientRequestId: string; })
- claimOutboundOperation · function · L103-L116 — async function claimOutboundOperation(id: string, expectedStatus: string, expectedAttempt: number)
- markOutboundSent · function · L118-L127 — async function markOutboundSent(id: string, input: { providerMessageId: string; providerThreadId: string })
- markOutboundFailed · function · L129-L136 — async function markOutboundFailed(id: string, input: { errorCode: string; errorMessage: string })

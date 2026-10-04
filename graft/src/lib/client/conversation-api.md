# src/lib/client/conversation-api.ts

- readJson · function · L4-L8 — async function readJson<T>(response: Response): Promise<T>
- getConversationList · function · L10-L12 — async function getConversationList(): Promise<ConversationListItem[]>
- getConversationDetail · function · L14-L18 — async function getConversationDetail(id: string): Promise<ConversationDetail | null>
- analyzeConversation · function · L20-L22 — async function analyzeConversation(id: string): Promise<ConversationAnalysis>
- sendConversationReply · function · L24-L30 — async function sendConversationReply(id: string, input: { text: string; clientRequestId: string }): Promise<SendReplyResponse>
- getInboxIntegrationStatus · function · L32-L36 — async function getInboxIntegrationStatus()
- syncInboxNow · function · L38-L42 — async function syncInboxNow()

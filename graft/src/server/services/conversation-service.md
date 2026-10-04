# src/server/services/conversation-service.ts

- status · function · L28-L32 — function status(value: string): ConversationStatus
- getConversationListForCurrentMode · function · L34-L59 — async function getConversationListForCurrentMode(): Promise<ConversationListItem[]>
- getConversationDetailForCurrentMode · function · L61-L122 — async function getConversationDetailForCurrentMode(id: string): Promise<ConversationDetail | undefined>
- sendManualGmailReply · function · L124-L265 — async function sendManualGmailReply(input: { conversationId: string; text: string; clientRequestId: string; client?: GmailClient; })
- sendManualReply · function · L268-L270 — async function sendManualReply(input: { conversationId: string; text: string; clientRequestId: string })

# src/server/repositories/conversations.ts

- customerAddress · function · L15-L18 — function customerAddress(message: NormalizedMessage, account: IntegrationAccountRow): NormalizedAddress | undefined
- persistNormalizedMessage · function · L20-L124 — async function persistNormalizedMessage(account: IntegrationAccountRow, normalized: NormalizedMessage)
- listConversationRows · function · L126-L138 — async function listConversationRows(limit = 500)
- getConversationContext · function · L140-L154 — async function getConversationContext(id: string)
- getConversationMessages · function · L156-L167 — async function getConversationMessages(conversationId: string)
- getLatestConversationMessage · function · L169-L177 — async function getLatestConversationMessage(conversationId: string)
- getLatestMessagePreview · function · L179-L182 — async function getLatestMessagePreview(conversationId: string)

# src/server/integrations/gmail/gmail-client.ts

- GmailCredentialRecord · interface · L17-L19 — interface GmailCredentialRecord
- GmailHttpError · class · L21-L32 — class GmailHttpError extends SupportError
- constructor · method · L23-L31 — constructor(httpStatus: number, message: string)
- sleep · function · L34-L34 — sleep = (ms: number)
- GmailRestClient · class · L36-L135 — class GmailRestClient implements GmailClient
- constructor · method · L39-L39 — constructor(private readonly credential: GmailCredentialRecord)
- getAccessToken · method · L41-L49 — private getAccessToken()
- request · method · L51-L76 — private async request<T>(path: string, init?: RequestInit, safeRead = false): Promise<T>
- getProfile · method · L78-L80 — getProfile()
- listThreads · method · L82-L89 — listThreads(input: { q: string; pageToken?: string; maxResults?: number })
- getThread · method · L91-L93 — getThread(threadId: string)
- getMessage · method · L95-L97 — getMessage(messageId: string)
- listHistory · method · L99-L107 — listHistory(input: { startHistoryId: string; pageToken?: string })
- searchMessages · method · L109-L113 — async searchMessages(query: string)
- sendMessage · method · L115-L120 — sendMessage(input: { raw: string; threadId: string })
- watch · method · L122-L130 — watch(topicName: string, labelIds?: string[])
- stop · method · L132-L134 — stop()

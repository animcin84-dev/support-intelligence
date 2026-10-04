# tests/server/fixtures/gmail.ts

- rawFixture · function · L12-L47 — function rawFixture(input: { id: string; threadId: string; from: string; to: string; subject?: string; body?: string; messageId?: string; inReplyTo?: string; references?: string[]; unread?: boolean; date?: string; }): GmailMessageResponse
- FixtureGmailClient · class · L49-L85 — class FixtureGmailClient implements GmailClient
- getProfile · method · L63-L63 — async getProfile()
- listThreads · method · L64-L64 — async listThreads()
- getThread · method · L65-L65 — async getThread(threadId: string)
- getMessage · method · L66-L70 — async getMessage(messageId: string)
- listHistory · method · L71-L75 — async listHistory()
- searchMessages · method · L76-L76 — async searchMessages()
- sendMessage · method · L77-L82 — async sendMessage(input: { raw: string; threadId: string }): Promise<GmailSendResponse>
- watch · method · L83-L83 — async watch(): Promise<GmailWatchResponse>
- stop · method · L84-L84 — async stop()

# src/server/integrations/gmail/parser.ts

- addresses · function · L11-L20 — function addresses(value?: AddressObject | AddressObject[] | null): NormalizedAddress[]
- extractPresentationText · function · L22-L29 — function extractPresentationText(text: string)
- decoded · function · L31-L33 — function decoded(data?: string)
- headerValue · function · L35-L37 — function headerValue(part: GmailMessagePart | undefined, name: string)
- flattenParts · function · L39-L42 — function flattenParts(part: GmailMessagePart | undefined): GmailMessagePart[]
- htmlToPlainText · function · L44-L57 — async function htmlToPlainText(html: string)
- normalizeFullMessage · function · L59-L125 — async function normalizeFullMessage(message: GmailMessageResponse, mailboxEmail: string): Promise<NormalizedMessage>
- normalizeRawFixture · function · L127-L166 — async function normalizeRawFixture(message: GmailMessageResponse, mailboxEmail: string): Promise<NormalizedMessage>
- normalizeGmailMessage · function · L168-L176 — async function normalizeGmailMessage(message: GmailMessageResponse, mailboxEmail: string): Promise<NormalizedMessage>

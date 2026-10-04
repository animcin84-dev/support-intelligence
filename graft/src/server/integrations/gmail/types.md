# src/server/integrations/gmail/types.ts

- NormalizedAddress · type · L9-L9 — type NormalizedAddress = EmailAddress;
- NormalizedMessage · type · L10-L15 — type NormalizedMessage = ProviderMessage & { provider: "gmail"; sender?: EmailAddress; recipients: EmailAddress[]; cc: EmailAddress[]; };
- GmailProfile · interface · L17-L22 — interface GmailProfile
- GmailThreadListResponse · interface · L24-L28 — interface GmailThreadListResponse
- GmailThreadResponse · interface · L30-L34 — interface GmailThreadResponse
- GmailMessagePart · interface · L36-L47 — interface GmailMessagePart
- GmailMessageResponse · interface · L49-L58 — interface GmailMessageResponse
- GmailHistoryResponse · interface · L60-L67 — interface GmailHistoryResponse
- GmailSendResponse · interface · L69-L73 — interface GmailSendResponse
- GmailWatchResponse · interface · L75-L78 — interface GmailWatchResponse
- GmailClient · interface · L80-L90 — interface GmailClient

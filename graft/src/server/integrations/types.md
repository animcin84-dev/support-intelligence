# src/server/integrations/types.ts

- IntegrationProvider · type · L1-L1 — type IntegrationProvider = "gmail" | "whatsapp";
- MessageDirection · type · L3-L3 — type MessageDirection = "inbound" | "outbound";
- EmailAddress · type · L5-L5 — type EmailAddress = { name?: string; email: string; phone?: never };
- PhoneAddress · type · L6-L6 — type PhoneAddress = { name?: string; phone: string; email?: never };
- NormalizedAddress · type · L7-L7 — type NormalizedAddress = EmailAddress | PhoneAddress;
- NormalizedAttachment · interface · L9-L14 — interface NormalizedAttachment
- NormalizedMessage · interface · L16-L35 — interface NormalizedMessage
- addressValue · function · L37-L39 — function addressValue(address: NormalizedAddress): string

# src/server/integrations/whatsapp/webhook.ts

- invalidPayload · function · L40-L42 — function invalidPayload(): never
- verifyWhatsAppChallenge · function · L44-L58 — function verifyWhatsAppChallenge(url: URL, verifyToken = process.env.WHATSAPP_WEBHOOK_VERIFY_TOKEN): string
- verifyWhatsAppSignature · function · L61-L73 — function verifyWhatsAppSignature(rawBody: Buffer, signature: string | null, appSecret: string): void
- parseWhatsAppWebhook · function · L76-L138 — function parseWhatsAppWebhook(payload: unknown): ParsedWhatsAppWebhook

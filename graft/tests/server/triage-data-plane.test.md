# tests/server/triage-data-plane.test.ts

- fakeProvider · function · L23-L26 — function fakeProvider(result: unknown = billingResult, model = "fake-triage")
- fakeFallbackProvider · function · L28-L38 — function fakeFallbackProvider(configuration = "synthetic-chain-v1", servedModel = "gemini-2.5-flash")
- seedGmail · function · L40-L46 — async function seedGmail()
- seedConversation · function · L48-L56 — async function seedConversation()
- addInbound · function · L58-L61 — async function addInbound(account: Awaited<ReturnType<typeof seedGmail>>, id = "triage-inbound-2", body = "The duplicate charge is still blocking me.")
- routeContext · function · L63-L65 — function routeContext(conversationId: string)
- analysisRequest · function · L67-L69 — function analysisRequest(conversationId: string)
- analyze · method · L266-L266 — async analyze()
- analyze · method · L284-L284 — async analyze()
- analyze · method · L303-L303 — async analyze()

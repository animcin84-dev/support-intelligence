# src/server/analysis/provider-adapters.ts

- guardProviderExecution · function · L23-L26 — function guardProviderExecution()
- validateProviderInput · function · L28-L33 — function validateProviderInput(input: TriageInput)
- providerSchema · function · L36-L45 — function providerSchema()
- clean · function · L39-L43 — function clean(value: unknown): unknown
- httpError · function · L47-L54 — function httpError(status: number, provider: ProviderId, model: string)
- parseFacts · function · L56-L62 — function parseFacts(text: string, provider: ProviderId, model: string)
- callProvider · function · L64-L113 — async function callProvider(provider: ProviderId, input: TriageInput, timeoutMs = 15_000)

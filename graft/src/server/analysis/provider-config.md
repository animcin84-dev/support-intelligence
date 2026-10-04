# src/server/analysis/provider-config.ts

- ProviderId · type · L4-L4 — type ProviderId = "groq" | "gemini" | "huggingface";
- modelFor · function · L12-L20 — function modelFor(provider: ProviderId): string
- providerOrder · function · L22-L26 — function providerOrder(): ProviderId[]
- providerConfig · function · L28-L32 — function providerConfig(provider: ProviderId)
- getProviderAvailability · function · L34-L50 — function getProviderAvailability()
- getTriageConfigurationVersion · function · L53-L56 — function getTriageConfigurationVersion(): string

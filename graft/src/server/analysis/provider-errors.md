# src/server/analysis/provider-errors.ts

- ProviderErrorCategory · type · L3-L3 — type ProviderErrorCategory = "authentication" | "rate_limited" | "timeout" | "network" | "unavailable" | "unsupported_request" | "invalid_output" | "invalid_input" | "configuration";
- ProviderAttempt · interface · L4-L10 — interface ProviderAttempt
- ProviderError · class · L13-L39 — class ProviderError extends SupportError
- constructor · method · L20-L38 — constructor(category: ProviderErrorCategory, options: { transient?: boolean; status?: number; provider?: string; model?: string } = {})

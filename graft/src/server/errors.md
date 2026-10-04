# src/server/errors.ts

- SupportErrorCode · type · L1-L17 — type SupportErrorCode = | "oauth_expired" | "permission_revoked" | "gmail_rate_limited" | "gmail_unavailable" | "history_expired" | "parse_failed" | "database_failed" | "send_failed" | "watch_expired" | "pubsub_invalid" | "configuration_missing" | "validation_failed" | "sync_locked" | "not_found" | "analysis_failed" | "unknown";
- SupportError · class · L19-L31 — class SupportError extends Error
- constructor · method · L24-L30 — constructor(code: SupportErrorCode, message: string, options?: { status?: number; retryable?: boolean; cause?: unknown })
- toSupportError · function · L33-L36 — function toSupportError(error: unknown): SupportError
- safeErrorResponse · function · L38-L45 — function safeErrorResponse(error: unknown)

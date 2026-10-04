# src/lib/mocks/ai-quality-data.ts

- localeFor · function · L33-L39 — function localeFor(index: number): AIOutcome["locale"]
- knowledgeStateFor · function · L41-L48 — function knowledgeStateFor(intent: string, index: number): AIOutcome["knowledgeState"]
- decisionFor · function · L50-L69 — function decisionFor(intent: string, index: number): AIOutcome["decision"]
- failureTypeFor · function · L109-L121 — function failureTypeFor(outcome: AIOutcome, index: number): AIFailureType | null
- rootCauseFor · function · L123-L131 — function rootCauseFor(type: AIFailureType): FailureCause
- severityFor · function · L133-L138 — function severityFor(type: AIFailureType, intent: string): AIFailure["severity"]
- traceFor · function · L140-L184 — function traceFor(outcome: AIOutcome, type: AIFailureType, index: number): AIFailure["trace"]

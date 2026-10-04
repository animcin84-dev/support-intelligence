# src/server/repositories/analyses.ts

- AnalysisRow · type · L5-L5 — type AnalysisRow = typeof conversationAnalyses.$inferSelect;
- getLatestAnalysis · function · L7-L12 — async function getLatestAnalysis(conversationId: string)
- getLatestAnalyses · function · L14-L19 — async function getLatestAnalyses(conversationIds: string[])
- getInboundAnalysisMessages · function · L22-L30 — async function getInboundAnalysisMessages(conversationIds: string[])
- expireInterruptedAnalyses · function · L32-L44 — async function expireInterruptedAnalyses(conversationId: string | string[])
- createPendingAnalysis · function · L46-L50 — async function createPendingAnalysis(input: typeof conversationAnalyses.$inferInsert)
- updateAnalysis · function · L52-L56 — async function updateAnalysis(id: string, input: Partial<typeof conversationAnalyses.$inferInsert>)

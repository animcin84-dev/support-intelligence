# src/server/services/analysis-service.ts

- getAnalysisAvailability · function · L13-L16 — function getAnalysisAvailability()
- sourceSnapshot · function · L18-L36 — function sourceSnapshot(subject: string, rows: Awaited<ReturnType<typeof getInboundAnalysisMessages>>)
- snapshot · function · L38-L43 — async function snapshot(conversationId: string)
- dto · function · L45-L64 — function dto(row: AnalysisRow | undefined, sourceHash: string): ConversationAnalysis
- getConversationAnalysis · function · L66-L71 — async function getConversationAnalysis(conversationId: string): Promise<ConversationAnalysis>
- getConversationAnalysesForList · function · L73-L85 — async function getConversationAnalysesForList(conversations: Array<{ id: string; subject: string }>)
- analyzeConversation · function · L87-L153 — async function analyzeConversation(conversationId: string, providerOverride?: TriageProvider): Promise<ConversationAnalysis>

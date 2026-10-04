# src/components/automation/procedures/procedures-view.tsx

- WorkspaceData · type · L28-L28 — type WorkspaceData = Awaited<ReturnType<typeof getAutomationWorkspace>>;
- riskTone · function · L45-L50 — function riskTone(risk: ActionDefinition["risk"])
- ProcedureInspector · function · L52-L118 — function ProcedureInspector({ procedure, data, close, embedded = false }: { procedure: AutomationProcedure; data: WorkspaceData; close: () => void; embedded?: boolean })
- ActionCatalog · function · L120-L133 — function ActionCatalog({ data }: { data: WorkspaceData })
- ExecutionPreview · function · L135-L188 — function ExecutionPreview({ data }: { data: WorkspaceData })
- setScenario · function · L138-L138 — setScenario = (value: keyof WorkspaceData["actionPreviews"])
- ProceduresView · function · L190-L225 — function ProceduresView({ data, embedded = false }: { data: WorkspaceData; embedded?: boolean })

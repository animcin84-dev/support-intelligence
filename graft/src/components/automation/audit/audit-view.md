# src/components/automation/audit/audit-view.tsx

- WorkspaceData · type · L22-L22 — type WorkspaceData = Awaited<ReturnType<typeof getAutomationWorkspace>>;
- AuditInspector · function · L24-L96 — function AuditInspector({ event, data, close, embedded = false }: { event: AutomationAuditEvent; data: WorkspaceData; close: () => void; embedded?: boolean })
- AuditView · function · L98-L144 — function AuditView({ data, embedded = false }: { data: WorkspaceData; embedded?: boolean })

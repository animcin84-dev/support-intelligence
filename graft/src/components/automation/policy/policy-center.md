# src/components/automation/policy/policy-center.tsx

- WorkspaceData · type · L21-L21 — type WorkspaceData = Awaited<ReturnType<typeof getAutomationWorkspace>>;
- policyDecision · function · L23-L28 — function policyDecision(policy: AutomationPolicy): PolicyDecision["decision"]
- DecisionCell · function · L30-L32 — function DecisionCell({ active, tone, children }: { active: boolean; tone: "success" | "warning" | "danger"; children: React.ReactNode })
- PolicyInspector · function · L34-L144 — function PolicyInspector({ policy, data, close, embedded = false }: { policy: AutomationPolicy; data: WorkspaceData; close: () => void; embedded?: boolean })
- PolicyCenter · function · L146-L206 — function PolicyCenter({ data, embedded = false }: { data: WorkspaceData; embedded?: boolean })

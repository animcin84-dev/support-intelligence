# src/components/automation/shared/automation-ui.tsx

- CompactStat · function · L20-L42 — function CompactStat({ label, value, note, tone = "neutral", }: { label: string; value: string; note: string; tone?: "neutral" | "success" | "warning" | "danger"; })
- DecisionBadge · function · L44-L50 — function DecisionBadge({ decision }: { decision: PolicyDecision["decision"] })
- StateMark · function · L52-L56 — function StateMark({ state, children }: { state: "pass" | "warning" | "block"; children: ReactNode })
- ReadinessInspector · function · L58-L94 — function ReadinessInspector({ explanation, onClose, embedded = false }: { explanation: ReadinessExplanation; onClose: () => void; embedded?: boolean })
- ApprovalPreview · function · L96-L152 — function ApprovalPreview({ request, actionLabel, onApprove, onReject, onClose, secondStep = false, confirmApprove, }: { request: ApprovalRequest; actionLabel: string; onApprove: () => void; onReject: () => void; onClose: () => void; secondStep?: boolean; confirmApprove?: () => void; })
- AuditLifecycle · function · L154-L176 — function AuditLifecycle({ event }: { event: AutomationAuditEvent })
- ControlPrinciples · function · L178-L187 — function ControlPrinciples()

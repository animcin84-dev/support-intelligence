# src/components/automation/rollouts/rollouts-view.tsx

- WorkspaceData · type · L23-L23 — type WorkspaceData = Awaited<ReturnType<typeof getAutomationWorkspace>>;
- RolloutCard · function · L34-L93 — function RolloutCard({ rollout, override, onChange, }: { rollout: RolloutConfig; override?: { mode: RolloutConfig["mode"]; percentage: RolloutConfig["percentage"] }; onChange: (mode: RolloutConfig["mode"], percentage: RolloutConfig["percentage"]) => void; })
- KillSwitch · function · L95-L133 — function KillSwitch({ paused, setPaused }: { paused: boolean; setPaused: (value: boolean) => void })
- RolloutsView · function · L135-L194 — function RolloutsView({ data }: { data: WorkspaceData })
- changeRollout · function · L139-L152 — changeRollout = (rollout: RolloutConfig, mode: RolloutConfig["mode"], percentage: RolloutConfig["percentage"])

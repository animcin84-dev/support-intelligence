# src/components/reference/reference-layout.tsx

- RouteHeader · function · L12-L15 — function RouteHeader({ title, actions, note }: { title: string; actions?: ReactNode; note?: ReactNode })
- ReferenceMetric · interface · L17-L17 — interface ReferenceMetric
- ActivityPoint · interface · L18-L18 — interface ActivityPoint
- ReferenceSummary · function · L19-L26 — function ReferenceSummary({ metrics, activity = [], activityLabel = "Activity", signal, children }: { metrics: ReferenceMetric[]; activity?: ActivityPoint[]; activityLabel?: string; signal: { label: string; value: string | number; note?: string; options: ReferenceMetric[]; active?: number; action?: ReactNode }; children?: ReactNode; })
- FilterHinge · function · L28-L30 — function FilterHinge({ children, count = 0, label = "Active filters" }: { children?: ReactNode; count?: number; label?: string })
- WorkspaceTabs · function · L32-L47 — function WorkspaceTabs({ items, active, onChange, label = "Workspace views" }: { items: Array<{id:string;label:string;count?:number}>; active:string; onChange:(id:string)=>void; label?:string })
- OperationalWorkspace · function · L49-L81 — function OperationalWorkspace({ master, detail, tabs, title, className, detailKey }: {master:ReactNode;detail:ReactNode;tabs?:ReactNode;title?:string;className?:string;detailKey?:string})
- toggleExpanded · function · L59-L67 — toggleExpanded = ()
- DetailBand · function · L83-L85 — function DetailBand({ metrics, action }: {metrics:ReferenceMetric[];action?:ReactNode})
- ReferenceLink · function · L87-L89 — function ReferenceLink({ href, children, primary = false }: {href:string;children:ReactNode;primary?:boolean})

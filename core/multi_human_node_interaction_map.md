flowchart LR

%% ============================
%%   INDIVIDUAL NODES
%% ============================
A1[Node A<br/>• State<br/>• Forces<br/>• Horizon<br/>• Flows]
A2[Node B<br/>• State<br/>• Forces<br/>• Horizon<br/>• Flows]
A3[Node C<br/>• State<br/>• Forces<br/>• Horizon<br/>• Flows]

%% ============================
%%   INTERACTIONS
%% ============================
A1 -- Shared Forces --> A2
A2 -- Shared Forces --> A3
A1 -- Shared Forces --> A3

A1 -- Flow Exchange --> A2
A2 -- Flow Exchange --> A3
A1 -- Flow Exchange --> A3

A1 -- Horizon Alignment --> A2
A2 -- Horizon Alignment --> A3
A1 -- Horizon Alignment --> A3

A1 -- State Influence --> A2
A2 -- State Influence --> A3
A1 -- State Influence --> A3

%% ============================
%%   EMERGENT SYSTEM
%% ============================
subgraph Group[Emergent Multi‑Human System]
    A1
    A2
    A3
end

Group --> S[System State<br/>• Stability<br/>• Drift<br/>• Coherence]

S --> H[System Horizon<br/>• Shared direction<br/>• Collective goals]

S --> F[System Forces<br/>• Culture<br/>• Expectations<br/>• Constraints]

S --> FL[System Flows<br/>• Time<br/>• Attention<br/>• Emotional energy<br/>• Resources]

```mermaid
gantt
    title Global Exit Survey Rollout
    dateFormat  YYYY-MM
    axisFormat  %m/%Y

    section 2025: Foundations
    Comment Summary Experiments :done, 2025-07, 2025-09
    Dashboard Mockups           :done, 2025-08, 2025-10
    AWS & Data Engineering      :done, 2025-10, 2025-12

    section 2026 Q1: Approvals
    Privacy & GPO Approvals     :active, 2026-01, 2026-03
    Works Council Presentations :2026-01, 2026-03
    Infrastructure Setup        :2026-02, 2026-04

    section 2026 Q2: Pilot
    Swiss Pilot Refinement      :2026-04, 2026-06
    Update Scrubbing Codes      :2026-05, 2026-06
    Global Rollout Plan         :2026-05, 2026-06

    section 2026 Q3: Launch
    GLOBAL SURVEY LIVE          :crit, 2026-07, 2026-08
    GLOBAL DASHBOARD LIVE       :crit, 2026-07, 2026-08
    Decommission Old Surveys    :2026-08, 2026-09

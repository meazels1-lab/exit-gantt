```mermaid
gantt
    title Global Exit Survey Task Timeline
    dateFormat  YYYY-MM
    axisFormat  %m/%Y
    todayMarker off

    section 2025 Q3
    Comment summary experiment (Amer) :done, q3_1, 2025-07, 2025-09
    Review mockups for feasibility     :done, q3_2, 2025-07, 2025-09
    Draft dashboard requirements      :done, q3_3, 2025-07, 2025-09
    Design mockups                    :done, q3_4, 2025-07, 2025-09
    Surveyor confidentiality notice   :done, q3_5, 2025-07, 2025-09
    Set up for global surveys         :done, q3_6, 2025-07, 2025-09
    Typeform confidentiality notice   :done, q3_7, 2025-07, 2025-09

    section 2025 Q4
    Script: Scrub free text           :done, q4_1, 2025-10, 2025-12
    Script: Translate comments        :done, q4_2, 2025-10, 2025-12
    Data engineering consultation     :done, q4_3, 2025-10, 2025-12
    Status update: Clemens/Judit/Carolin :done, q4_4, 2025-10, 2025-12
    Experiment: Dataset summarization  :done, q4_5, 2025-10, 2025-12
    Submit: Rep Bodies/Gov Auth       :done, q4_6, 2025-10, 2025-12
    Survey translated to German       :done, q4_7, 2025-10, 2025-12
    Demo APAC Qlik dashboard          :done, q4_8, 2025-10, 2025-12
    Review data structure (Stanley)   :done, q4_9, 2025-10, 2025-12
    Review data structure (Filip)    :done, q4_10, 2025-10, 2025-12
    AI risk assessment approval       :done, q4_11, 2025-10, 2025-12

    section 2026 Q1
    APAC/Amer data strategy           :done, q1_1, 2026-01, 2026-03
    Infrastructure for APAC/Amer      :active, q1_2, 2026-01, 2026-03
    Reshape data to Qlik requirements :q1_3, 2026-01, 2026-03
    P&C Switzerland info deck         :active, q1_4, 2026-01, 2026-03
    Privacy Notice review             :done, q1_5, 2026-01, 2026-03
    GPO deck completion & approval    :done, q1_6, 2026-01, 2026-03
    Global People Relations approval  :done, q1_7, 2026-01, 2026-03
    German Works Council deck & presentation :active, q1_8, 2026-01, 2026-03
    Austrian Works Council approval   :active, q1_9, 2026-01, 2026-03
    Mock up Qlik sheets (dummy data)  :active, q1_10, 2026-01, 2026-03
    Snowflake retention rules setup   :active, q1_11, 2026-01, 2026-03
    Map responses to Workday fields   :q1_12, 2026-01, 2026-03
    Edit survey (GPO requirements)    :done, q1_13, 2026-01, 2026-03
    Connect Surveyor (Staging)        :active, q1_14, 2026-01, 2026-03
    Typeform AI translator & SSO set up :q1_15, 2026-01, 2026-03

    section 2026 Q2
    Update scrub/translation code     :q2_1, 2026-04, 2026-06
    Swiss stakeholder info sessions   :q2_2, 2026-04, 2026-06
    Write Qlik data requirements      :q2_3, 2026-04, 2026-06
    Design & Test Qlik sheets         :q2_4, 2026-04, 2026-06
    Stop Switzerland pilot            :q2_5, 2026-04, 2026-06
    Review survey wording & fields    :q2_6, 2026-04, 2026-06
    Global rollout plan               :q2_7, 2026-04, 2026-06

    section 2026 Q3
    Report pilot data to Switzerland  :q3_1, 2026-07, 2026-09
    Launch global dashboard           :crit, q3_2, 2026-07, 2026-08
    Launch global survey              :crit, q3_3, 2026-07, 2026-08
    Turn off Amer and APAC surveys    :q3_4, 2026-08, 2026-09

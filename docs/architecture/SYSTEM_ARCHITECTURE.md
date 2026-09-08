                         ┌─────────────────────────┐
                         │      DATA SOURCES       │
                         │                         │
                         │  • Water Sensors        │
                         │  • Historical Dataset   │
                         │  • CSV / Excel          │
                         │  • Manual Input         │
                         └────────────┬────────────┘
                                      │
                                      ▼
                    ┌─────────────────────────────────┐
                    │       DATA INGESTION LAYER      │
                    │                                 │
                    │  • Data Upload                  │
                    │  • Sensor/API Input             │
                    │  • Data Validation              │
                    │  • Timestamp & Location         │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │      DATA PREPROCESSING         │
                    │                                 │
                    │  • Missing Value Handling       │
                    │  • Duplicate Removal            │
                    │  • Outlier Detection            │
                    │  • Normalization / Scaling      │
                    │  • Feature Engineering          │
                    └───────────────┬─────────────────┘
                                    │
                         Clean / Validated Data
                                    │
                 ┌──────────────────┴──────────────────┐
                 │                                     │
                 ▼                                     ▼
     ┌─────────────────────────┐          ┌─────────────────────────┐
     │   STATISTICAL ENGINE    │          │    MACHINE LEARNING     │
     │                         │          │         ENGINE          │
     │ • Descriptive Stats     │          │                         │
     │ • Mean / Median         │          │ • Model Training        │
     │ • Variance / Std Dev    │          │ • Model Evaluation      │
     │ • Correlation           │          │ • Classification        │
     │ • Trend Analysis        │          │ • Regression            │
     │ • Distribution Analysis │          │ • Prediction            │
     └────────────┬────────────┘          └────────────┬────────────┘
                  │                                    │
                  │         Analysis Results           │
                  └────────────────┬───────────────────┘
                                   ▼
                    ┌─────────────────────────────────┐
                    │    WATER QUALITY ASSESSMENT     │
                    │                                 │
                    │  • Quality Classification       │
                    │  • WQI Calculation              │
                    │  • Risk Assessment              │
                    │  • Threshold Checking           │
                    │  • Prediction Confidence        │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │          DATA STORAGE           │
                    │                                 │
                    │       PostgreSQL Database       │
                    │                                 │
                    │  • Measurements                 │
                    │  • Historical Records           │
                    │  • Statistical Results          │
                    │  • ML Predictions               │
                    │  • Quality Assessments          │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │       APPLICATION / API         │
                    │            FASTAPI              │
                    │                                 │
                    │  • Water Data API               │
                    │  • Statistics API               │
                    │  • Prediction API               │
                    │  • Assessment API               │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                    ┌─────────────────────────────────┐
                    │       WEB DASHBOARD             │
                    │           REACT.JS              │
                    │                                 │
                    │  • Current Water Quality        │
                    │  • Parameter Values             │
                    │  • Historical Trends            │
                    │  • Statistical Charts           │
                    │  • ML Predictions               │
                    │  • Risk / Alerts                │
                    └───────────────┬─────────────────┘
                                    │
                                    ▼
                           ┌─────────────────┐
                           │      USER       │
                           │                 │
                           │ • View          │
                           │ • Analyze       │
                           │ • Monitor       │
                           └─────────────────┘
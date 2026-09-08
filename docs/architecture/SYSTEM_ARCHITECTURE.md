┌─────────────────────────────────────────────────────────────┐
│                      DATA SOURCE LAYER                     │
│                                                             │
│ Sensors │ Historical Dataset │ CSV/Excel │ Manual Input    │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                    DATA INGESTION LAYER                     │
│                                                             │
│ Data Collection │ Validation │ Formatting │ Metadata       │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                  DATA PREPROCESSING LAYER                  │
│                                                             │
│ Missing Values │ Duplicates │ Outliers │ Scaling           │
│ Feature Engineering │ Data Transformation                  │
└──────────────────────────────┬──────────────────────────────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
                ▼                             ▼
┌──────────────────────────┐       ┌──────────────────────────┐
│   STATISTICAL ENGINE     │       │    MACHINE LEARNING      │
│                          │       │         ENGINE           │
│ • Descriptive Statistics │       │ • Classification         │
│ • Correlation Analysis   │       │ • Regression             │
│ • Trend Analysis         │       │ • Prediction             │
│ • Distribution Analysis  │       │ • Model Evaluation       │
└─────────────┬────────────┘       └────────────┬─────────────┘
              │                                 │
              └──────────────┬──────────────────┘
                             ▼
┌─────────────────────────────────────────────────────────────┐
│                 WATER QUALITY ASSESSMENT                    │
│                                                             │
│ Quality Classification │ Risk Assessment │ WQI (if used)   │
│ Threshold Evaluation │ Prediction Interpretation            │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                     DATA STORAGE LAYER                      │
│                                                             │
│ Measurements │ Historical Data │ Predictions │ Results      │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                    APPLICATION / API LAYER                  │
│                         FastAPI                             │
│                                                             │
│ Water API │ Statistics API │ Prediction API │ Assessment API│
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                   PRESENTATION LAYER                        │
│                        React.js                             │
│                                                             │
│ Dashboard │ Charts │ Trends │ Predictions │ Alerts          │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
                         ┌────────────┐
                         │    USER    │
                         └────────────┘
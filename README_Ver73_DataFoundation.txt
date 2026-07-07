WaterSystemAnalyzer Version 7.3 DataFoundation
==============================================

Added:
- Data Foundation button.
- Section_Master.xlsx.
- Failure_Type_Master.xlsx.
- Replacement_Type_Master.xlsx.
- Reliability_Model_Config.xlsx.
- Project_Manifest.xlsx.
- Data/Project JSON metadata and docs.

Key design:
- Section is the main reliability analysis unit.
- Failure Type is defined per Component Type.
- Scheduled Replacement is censored data by default.
- Reliability models are configured via master/json.

Validation:
1. Build EXE.
2. Open app.
3. Click Data Foundation.
4. Confirm master files and Data/Project files are created.

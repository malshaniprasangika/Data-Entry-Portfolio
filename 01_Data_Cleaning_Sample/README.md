Problem Area                 Formula or Tool Used      Description
Inconsistent Names/Cities,  =PROPER(TRIM(B2)),       "Used TRIM to remove extra spaces before/after text, and PROPER to ensure correct capitalization (e.g., ""joe Smith"" →                                                            ""Joe Smith"")."
State Code Inconsistency,   =UPPER(D2),              "Used UPPER to force all state codes to uppercase (e.g., ""ny"" → ""NY"")."
Date Format Conversion,     Format Cells...,          Applied a consistent custom format (MM/DD/YYYY) to the entire date column to standardize mixed entries.
Duplicate Records,          Data Tab → Remove        "Used the built-in Excel tool on columns Full Name, Phone Number, and Date of Sign-up to identify and flag the redundant record                      Duplicates  ,            (ID 1005)."
Validation/Standardization, VLOOKUP or INDEX/MATCH,  (Optional/Advanced) Could be used to check if the entered State Code exists in a master list of valid codes.

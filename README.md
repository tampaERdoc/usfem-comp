# USF EM Physician Compensation Model

Enter annual hours by site and shift and the page builds the proforma (Employee, Employer, or Both views).
Same math as USF_EM_Clinical_Asst_Prof_1FTE_Model.xlsx (Box > Recruitment > Open Rank 1.0 Clinical Physician > 1.0 FTE Offer Model).

Rates, TeamHealth payments, salaries and department costs are stored encrypted (AES-256-GCM, PBKDF2 key from the site password).
To change them, edit params.json in the build folder in Box and rebuild with build.py.

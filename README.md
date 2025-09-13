# The-Pima-Indian-Population
The Pima Indian Diabetes Dataset, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, is a well-known benchmark in machine learning for predicting diabetes onset. It contains diagnostic data from 768 Pima Indian women aged 21 or older, the goal of classifying whether a patient has diabetes
Columns in the Dataset
1 Pregnancies
Number of times the woman has been pregnant.

Higher pregnancies may increase diabetes risk due to gestational diabetes.

Studies suggest ≥ 3–4 pregnancies is associated with higher diabetes risk.

Minimum: 0 (never pregnant)

Maximum: 15–20 (very rare, but biologically possible)

2. Glucose (2-hour OGTT plasma glucose, mg/dL)
Plasma glucose concentration (mg/dL) after a 2-hour oral glucose tolerance test.

High values → higher risk of diabetes.

Clinical cut-offs (WHO/ADA):

Normal: < 140 mg/dL
Prediabetes (Impaired glucose tolerance): 140–199 mg/dL
Diabetes: ≥ 200 mg/dL
Minimum: 40 (severe hypoglycemia; below this is life-threatening)

Maximum: 600–800 (hyperosmolar hyperglycemic state in uncontrolled diabetes; above this is often fatal)

3. BloodPressure (Diastolic, mm Hg)
Diastolic blood pressure (mm Hg).

Hypertension often coexists with diabetes.

Hypertension increases diabetes risk.

Normal: < 80 mm Hg
Pre-hypertension: 80–89 mm Hg
Hypertension: ≥ 90 mm Hg
Minimum: 40 (severe shock, not compatible with life for long)

Maximum: 130–140 (extreme hypertension, rarely recorded; systolic may go much higher, but diastolic >130 is unusual)

4. SkinThickness (Triceps skinfold thickness, mm)
Triceps skinfold thickness (mm).

Used as an indirect measure of body fat.

No fixed medical cut-off; used as a proxy for body fat.

Normal: ~10–20 mm
High fat: > 30 mm
Minimum: 5 (very lean individual, almost no subcutaneous fat)

Maximum: 50–60 (severe obesity; some datasets may record up to ~70 mm but very rare)

5. Insulin (2-hour serum insulin, μU/ml)
2-hour serum insulin (mu U/ml).

Measures insulin levels after glucose intake.

Normal fasting insulin: ~16–166 μU/ml (varies by lab).

Low/normal: < 100 μU/ml
High (hyperinsulinemia): > 200 μU/ml → insulin resistance
Minimum: 2–5 (very low insulin, type 1 diabetes or beta-cell failure)

Maximum: 300–400 (severe insulin resistance; some labs may report up to >500 but rare)

7. BMI (Body Mass Index)
Formula: weight (kg) / [height (m)]².

High BMI indicates overweight/obesity, a key diabetes risk factor.

WHO cut-offs:

Underweight: < 18.5
Normal: 18.5 – 24.9
Overweight: 25 – 29.9
Obese: ≥ 30 → higher diabetes risk
Minimum: 10 (severe malnutrition; below 12 is rarely survivable long-term)

Maximum: 60–70 (extreme obesity; values above 80 exist but extremely rare)

8. DiabetesPedigreeFunction (DPF)
A score that estimates diabetes likelihood based on family history.

Higher value → stronger genetic predisposition.

No universal medical cut-off (dataset-specific).

In the Pima dataset, values range 0.08 – 2.42.
Higher (>1.0) = strong family history → higher risk.
Minimum: 0.0 (no family history contribution)

Maximum: ~2.5–3.0 (in dataset; theoretically higher, but very rare)

9. Age
Age in years.

Risk of diabetes increases with age.

Risk increases with age.

Young: < 30 → low risk
Middle age: 30–50 → moderate risk
Older: > 50 → higher risk
Minimum: 18–20 (usually adults; dataset starts at 21)

Maximum: 90–100 (elderly; dataset max is ~81, but real-world diabetics can live past 100)

10. Outcome
Target variable (label).
0 = No diabetes
1 = Diabetes present

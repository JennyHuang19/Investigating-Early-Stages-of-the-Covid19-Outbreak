## Code Book of Variables

The dimensions of our dataset are 1,085 rows by 17 columns, including 1,085 
patients and 17 attributes about each patient.

$ id <fct> -  the patient id.
$ reporting_date <date> - the date that the case was reported.
$ location <chr> - the location the case was reported in.
$ country  <chr> - the country that the case was reported in.
$ gender  <chr> - the gender of the patient
$ age  <dbl> - the age of the patient
$ symptom_onset  <date> - date of reported symptom onset
$ if_onset_approximated <fct> - Is the date of symptom onset approximated?
$ hosp_visit_date  <date> - date of hospital visit
$ exposure_start <date> - what date was the patient first exposed to the virus?
$ exposure_end  <date> - what date did exposure to the virus end?
$ visiting_wuhan  <fct> - Did the patient previously visit Wuhan?
$ from_wuhan  <fct> - Is the patient from Wuhan?
$ death <fct> - Did the patient die?
$ recovered <fct> - Did the patient recover?
$ source  <chr> - What source reported the case?
$ age_group  <chr> - the age group of the patient
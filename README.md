bids-validator@1.15.0
	[33m1: [WARN] Not all subjects contain the same files. Each subject should contain the same number of files with the same naming unless some files are known to be missing. (code: 38 - INCONSISTENT_SUBJECTS)[39m
		./sub-001/fmap/sub-001_acq-test_dir-PA_run-02_epi.json
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_dir-PA_run-02_epi.json
		./sub-001/fmap/sub-001_acq-test_dir-PA_run-02_epi.nii.gz
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_dir-PA_run-02_epi.nii.gz
		./sub-001/fmap/sub-001_acq-test_run-02_magnitude1.json
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_magnitude1.json
		./sub-001/fmap/sub-001_acq-test_run-02_magnitude1.nii.gz
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_magnitude1.nii.gz
		./sub-001/fmap/sub-001_acq-test_run-02_magnitude2.json
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_magnitude2.json
		./sub-001/fmap/sub-001_acq-test_run-02_magnitude2.nii.gz
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_magnitude2.nii.gz
		./sub-001/fmap/sub-001_acq-test_run-02_phasediff.json
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_phasediff.json
		./sub-001/fmap/sub-001_acq-test_run-02_phasediff.nii.gz
			Evidence: Subject: sub-001; Missing file: sub-001_acq-test_run-02_phasediff.nii.gz
		./sub-001/func/sub-001_task-cond_run-02_bold.json
			Evidence: Subject: sub-001; Missing file: sub-001_task-cond_run-02_bold.json
		./sub-001/func/sub-001_task-cond_run-02_bold.nii.gz
			Evidence: Subject: sub-001; Missing file: sub-001_task-cond_run-02_bold.nii.gz
		[33m... and 1243 more files having this issue (Use --verbose to see them all).[39m

[36m	Please visit https://neurostars.org/search?q=INCONSISTENT_SUBJECTS for existing conversations about this issue.[39m

	[33m2: [WARN] Not all subjects/sessions/runs have the same scanning parameters. (code: 39 - INCONSISTENT_PARAMETERS)[39m
		./sub-001/func/sub-001_task-cond_run-01_bold.nii.gz
		./sub-001/func/sub-001_task-test_run-01_bold.nii.gz
		./sub-002/func/sub-002_task-test_run-01_bold.nii.gz
		./sub-003/func/sub-003_task-cond_run-01_bold.nii.gz
		./sub-003/func/sub-003_task-test_run-01_bold.nii.gz
		./sub-004/func/sub-004_task-cond_run-01_bold.nii.gz
		./sub-004/func/sub-004_task-test_run-01_bold.nii.gz
		./sub-005/func/sub-005_task-cond_run-01_bold.nii.gz
		./sub-005/func/sub-005_task-test_run-01_bold.nii.gz
		./sub-006/func/sub-006_task-cond_run-01_bold.nii.gz
		[33m... and 140 more files having this issue (Use --verbose to see them all).[39m

[36m	Please visit https://neurostars.org/search?q=INCONSISTENT_PARAMETERS for existing conversations about this issue.[39m

	[33m3: [WARN] Tabular file contains custom columns not described in a data dictionary (code: 82 - CUSTOM_COLUMN_WITHOUT_DESCRIPTION)[39m
		./sub-001/func/sub-001_task-cond_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-cond_events.json,/run-01_events.json,/task-cond_run-01_events.json,/sub-001/sub-001_events.json,/sub-001/sub-001_task-cond_events.json,/sub-001/sub-001_run-01_events.json,/sub-001/sub-001_task-cond_run-01_events.json,/sub-001/func/sub-001_events.json,/sub-001/func/sub-001_task-cond_events.json,/sub-001/func/sub-001_run-01_events.json,/sub-001/func/sub-001_task-cond_run-01_events.json
		./sub-001/func/sub-001_task-rest_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-rest_events.json,/run-01_events.json,/task-rest_run-01_events.json,/sub-001/sub-001_events.json,/sub-001/sub-001_task-rest_events.json,/sub-001/sub-001_run-01_events.json,/sub-001/sub-001_task-rest_run-01_events.json,/sub-001/func/sub-001_events.json,/sub-001/func/sub-001_task-rest_events.json,/sub-001/func/sub-001_run-01_events.json,/sub-001/func/sub-001_task-rest_run-01_events.json
		./sub-001/func/sub-001_task-test_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-test_events.json,/run-01_events.json,/task-test_run-01_events.json,/sub-001/sub-001_events.json,/sub-001/sub-001_task-test_events.json,/sub-001/sub-001_run-01_events.json,/sub-001/sub-001_task-test_run-01_events.json,/sub-001/func/sub-001_events.json,/sub-001/func/sub-001_task-test_events.json,/sub-001/func/sub-001_run-01_events.json,/sub-001/func/sub-001_task-test_run-01_events.json
		./sub-002/func/sub-002_task-cond_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-cond_events.json,/run-01_events.json,/task-cond_run-01_events.json,/sub-002/sub-002_events.json,/sub-002/sub-002_task-cond_events.json,/sub-002/sub-002_run-01_events.json,/sub-002/sub-002_task-cond_run-01_events.json,/sub-002/func/sub-002_events.json,/sub-002/func/sub-002_task-cond_events.json,/sub-002/func/sub-002_run-01_events.json,/sub-002/func/sub-002_task-cond_run-01_events.json
		./sub-002/func/sub-002_task-rest_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-rest_events.json,/run-01_events.json,/task-rest_run-01_events.json,/sub-002/sub-002_events.json,/sub-002/sub-002_task-rest_events.json,/sub-002/sub-002_run-01_events.json,/sub-002/sub-002_task-rest_run-01_events.json,/sub-002/func/sub-002_events.json,/sub-002/func/sub-002_task-rest_events.json,/sub-002/func/sub-002_run-01_events.json,/sub-002/func/sub-002_task-rest_run-01_events.json
		./sub-002/func/sub-002_task-test_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-test_events.json,/run-01_events.json,/task-test_run-01_events.json,/sub-002/sub-002_events.json,/sub-002/sub-002_task-test_events.json,/sub-002/sub-002_run-01_events.json,/sub-002/sub-002_task-test_run-01_events.json,/sub-002/func/sub-002_events.json,/sub-002/func/sub-002_task-test_events.json,/sub-002/func/sub-002_run-01_events.json,/sub-002/func/sub-002_task-test_run-01_events.json
		./sub-003/func/sub-003_task-cond_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-cond_events.json,/run-01_events.json,/task-cond_run-01_events.json,/sub-003/sub-003_events.json,/sub-003/sub-003_task-cond_events.json,/sub-003/sub-003_run-01_events.json,/sub-003/sub-003_task-cond_run-01_events.json,/sub-003/func/sub-003_events.json,/sub-003/func/sub-003_task-cond_events.json,/sub-003/func/sub-003_run-01_events.json,/sub-003/func/sub-003_task-cond_run-01_events.json
		./sub-003/func/sub-003_task-rest_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-rest_events.json,/run-01_events.json,/task-rest_run-01_events.json,/sub-003/sub-003_events.json,/sub-003/sub-003_task-rest_events.json,/sub-003/sub-003_run-01_events.json,/sub-003/sub-003_task-rest_run-01_events.json,/sub-003/func/sub-003_events.json,/sub-003/func/sub-003_task-rest_events.json,/sub-003/func/sub-003_run-01_events.json,/sub-003/func/sub-003_task-rest_run-01_events.json
		./sub-003/func/sub-003_task-test_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-test_events.json,/run-01_events.json,/task-test_run-01_events.json,/sub-003/sub-003_events.json,/sub-003/sub-003_task-test_events.json,/sub-003/sub-003_run-01_events.json,/sub-003/sub-003_task-test_run-01_events.json,/sub-003/func/sub-003_events.json,/sub-003/func/sub-003_task-test_events.json,/sub-003/func/sub-003_run-01_events.json,/sub-003/func/sub-003_task-test_run-01_events.json
		./sub-004/func/sub-004_task-cond_run-01_events.tsv
			Evidence: Columns: TODO -- fill in rows and add more tab-separated columns if desired not defined, please define in: /events.json, /task-cond_events.json,/run-01_events.json,/task-cond_run-01_events.json,/sub-004/sub-004_events.json,/sub-004/sub-004_task-cond_events.json,/sub-004/sub-004_run-01_events.json,/sub-004/sub-004_task-cond_run-01_events.json,/sub-004/func/sub-004_events.json,/sub-004/func/sub-004_task-cond_events.json,/sub-004/func/sub-004_run-01_events.json,/sub-004/func/sub-004_task-cond_run-01_events.json
		[33m... and 227 more files having this issue (Use --verbose to see them all).[39m

[36m	Please visit https://neurostars.org/search?q=CUSTOM_COLUMN_WITHOUT_DESCRIPTION for existing conversations about this issue.[39m

	[33m4: [WARN] The recommended file /README is very small. Please consider expanding it with additional information about the dataset. (code: 213 - README_FILE_SMALL)[39m
		./README

[36m	Please visit https://neurostars.org/search?q=README_FILE_SMALL for existing conversations about this issue.[39m

        [34m[4mSummary:[24m[39m                    [34m[4mAvailable Tasks:[24m[39m                     [34m[4mAvailable Modalities:[39m[24m 
        3748 Files, 132.62GB        cond                                 MRI                   
        78 - Subjects               rest                                                       
        1 - Session                 test                                                       
                                    Conditioning                                               
                                    Test                                                       
                                    TODO: full task name for rest                              


[36m	If you have any questions, please post on https://neurostars.org/tags/bids.[39m


	010 has two runs and two field maps for “test” (correctly mapped in the json)
    012 only has T1 and rs-fMRI
    041 take “test” and corresponding field maps from run 2 (correctly mapped in the json)
    046 take “test” from run 2 but fieldmaps from run 1 (correctly mapped in the json)
    051 take “cond” from run 2 but fieldmaps from run 1 (correctly mapped in the json)
 
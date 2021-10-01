po@TW05596P01:~/workspace/recipes/edk2-test-parser$ ./parser.py --config EBBR.yaml ../arm-systemready-template/acs_results/sct_results/Overall/Summary.ekl ../arm-systemready-template/acs_results/sct_results/Sequence/EBBR.seq --filter "x['result'] == 'FAILURE'" --uniq --fields 'count,result,name,comments' --print
INFO ident_seq: Identified `../arm-systemready-template/acs_results/sct_results/Sequence/EBBR.seq' as "ACS-IR v21.07_0.9_BETA EBBR.seq".
INFO apply_rules: Updated 2269 test(s) out of 12864 after applying 143 rule(s)
INFO filter_data: Filtered out 12864 test(s), kept 0
INFO <module>: 0 dropped(s), 0 failure(s), 0 pass(s), 0 warning(s)
INFO uniq: 0 unique entries
Count  Result  Name  Comments
-----  ------  ----  --------


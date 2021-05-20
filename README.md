# mosca_bug
python /share/MOSCA/scripts/join_information.py -e /home/home-server/Documentos/libreria_chile/experiments.tsv -t 1 -o /home/home-server/Documentos/libreria_chile/output -if tsv -nm TMM
MissingOutputException in line 262 of /share/MOSCA/scripts/Snakefile:
Job Missing files after 5 seconds:
/home/home-server/Documentos/libreria_chile/output/MOSCA_Protein_Report.xlsx
/home/home-server/Documentos/libreria_chile/output/MOSCA_Entry_Report.xlsx
/home/home-server/Documentos/libreria_chile/output/Metatranscriptomics/expression_matrix.tsv
This might be due to filesystem latency. If that is the case, consider to increase the wait time with --latency-wait.
Job id: 0 completed successfully, but some output files are missing. 0
  File "/home/home-server/anaconda3/envs/mosca/lib/python3.7/site-packages/snakemake/executors/__init__.py", line 584, in handle_job_success
  File "/home/home-server/anaconda3/envs/mosca/lib/python3.7/site-packages/snakemake/executors/__init__.py", line 259, in handle_job_success
Exiting because a job execution failed. Look above for error message
Shutting down, this might take some time.
Exiting because a job execution failed. Look above for error message
Complete log: /home/home-server/Documentos/libreria_chile/.snakemake/log/2021-05-19T205310.482381.snakemake.log

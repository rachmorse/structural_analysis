### Extract volume and thickness
- **Purpose:** Extracts hippocampal volumes, ICV, WM-hypointensities (aseg) and lh/rh mean cortical thickness (aparc) from FreeSurfer 6 outputs, merging per-subject results into a single per-timepoint CSV while skipping already-processed subjects.
- **Scripts:**     
    - `extract_freesurfer_stats.py`: Orchestrates extraction/merging and auto-creates run_asegstats2table.sh (Python-2 wrapper for FS6 tools).
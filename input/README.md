# List of Data Inputs to Run LFP Analysis

- `channel_mapping.xlsx` - (Default) Excel file with the channel mapping for the LFP data.


- `video.xlsx` - Contains the following columns:
  - `file_path` - File name to each sleap file (*.h5) in the experiment.
  - `start_frame` - (Experimenter created) start frame from when mouse enters recording or transferred to box.
  - `stop_frame` - (Experimenter created) start frame from when mouse exits recording or transferred to box.
  - `tracked_subject` - Animal being tracked during start & stop frame.
  - `in_video_subject` - Any animal that is in the recording (regardless of start & stop frames).
  - `box_number` - MedPC box number.
  - `notes` - Event notes.

  
- `labels.xlsx` - Contains the following columns:
  - `video_name` - Name of the video.
  - `sleap_name` - Name of sleap *.h5 file.
  - `session_dir` - Directory of the session (containing *.rec)
  - `tracked_subject` - (List) Name of the subject being tracked.
  - `current_subject` - Name of the subject in the video.
  - `competition_closeness` - Competition closeness of the trial (see encoding dict)
  - `notes` - (Optional) Trial notes.


- 
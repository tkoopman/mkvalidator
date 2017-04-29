# mkvalidator
Used to validate MKV files.

#Usage
docker run --rm \
  -v /path/to/mkv/folder:/data:ro \
  -v /path/to/output/folder:/output \
  tkoopman/mkvalidator  
  
Any MKV file found with an error will have a log file created in output folder with details.
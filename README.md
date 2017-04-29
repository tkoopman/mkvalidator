# mkvalidator
Used to validate MKV files.

#Usage
docker run --rm \
  -v /path/to/mkv/folder:/data:ro \
  -v mkverrors.txt:/mkverrors.txt \
  tkoopman/mkvalidator
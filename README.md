# roboscribe

## Usage
`python -m venv .env`
```
source .env/bin/activate
pip install -r requirements.txt
```
```
python -m roboscribe \
  --audio_path PATH_TO_AUDIO_FILE \
  --hf_token YOUR_HUGGING_FACE_READ_TOKEN \
  --output_file YOUR_OUTPUT_FILE.txt \
  --speakers 2
```


## Original blogpost
https://den.dev/blog/how-i-automated-podcast-transcription-with-local-ai/

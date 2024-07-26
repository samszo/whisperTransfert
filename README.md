# whisperTransfert

## local
whisper test.flac --language French --fp16 False --word_timestamps True --output_format json --verbose True --append_punctuations True --prepend_punctuations False

## ia server
whisper test.flac --language French --word_timestamps True --output_format json --verbose True --append_punctuations True --prepend_punctuations False --mode medium

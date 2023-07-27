# RuntimeAudioImporter

This is an old fork of [RuntimeAudioImporter](https://github.com/gtreshchev/RuntimeAudioImporter/) plugin, quite outdated now. There are two major differences from the current version:

* PCM data is stored in byte (unsigned char) format rather then float;
* UImportedSoundWave class has GetPCMBuffer function exposed to blueprints. It returns PCM buffer as array of bytes (TArray<uint8>).

Useful to analyze/recognize audio data and create lip-sync.

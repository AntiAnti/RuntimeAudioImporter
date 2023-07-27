# RuntimeAudioImporter

This is an old fork of [RuntimeAudioImporter](https://github.com/gtreshchev/RuntimeAudioImporter/) plugin, quite outdated now. There are two major differences here from the current official version of the RuntimeAudioImporter plugin:

* PCM data is stored in byte (unsigned char) format rather then float;
* UImportedSoundWave class has GetPCMBuffer function exposed to blueprints. It returns PCM buffer as array of bytes (TArray<uint8>).

Useful to analyze/recognize audio data and create lip-sync. In general, this fork was created to read **mp3 format** in runtime in my [Ynnk Voice Lip-sync](https://www.unrealengine.com/marketplace/en-US/product/ynnk-voice-lipsync/) plugin.

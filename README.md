# HACS Integration that uses [ElevenLabs.io](https://elevenlabs.io) as a TTS Provider

To use add the following to your configuration.yaml

```
tts:
  - platform: tts_elevenlabs
    api_key: "YOUR_API_KEY"
```

By Default uses Rachel as Voice ([Example](https://storage.googleapis.com/eleven-public-prod/premade/voices/21m00Tcm4TlvDq8ikWAM/dff5d82d-d16d-45b9-ae73-be2ad8850855.mp3)). Can be changed by adding a `type` to your config or service call. The type needs to be the ElevenLabs.io voice_id. All voices [here](https://api.elevenlabs.io/v1/voices)

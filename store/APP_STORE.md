# Apple App Store listing — NeuroSynth

## App identity
- **Name:** NeuroSynth
- **Bundle ID:** `com.synovanexus.neurosynth`
- **Category:** TODO (e.g. Productivity, Developer Tools)

## Subtitle (30 chars)
TODO

## Promotional text (170 chars, editable without review)
TODO

## Description
NeuroSynth - Personal workspace and projects

## Keywords (100 chars, comma separated)
TODO

## Privacy policy URL
TODO — must be a public HTTPS URL (see legal/PRIVACY_POLICY.md)

## Support URL
TODO

## Build & submit
```bash
cd mobile   # or wherever the Expo/RN app lives
npx expo prebuild --platform ios
eas build -p ios --profile production
eas submit -p ios
```
Requires an active Apple Developer Program membership ($99/yr).

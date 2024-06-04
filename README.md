# TD-CHOP-RECORDER

TouchDesigner components to record & play CHOP values into files.
Useful to record OSC, MIDI events etc.

https://github.com/fand/td-chop-recorder/assets/1403842/badb75d7-cc24-4981-8e77-26abf510f4b5

This repo contains 2 tox files:

- CHOP_RECORDER.tox
- CHOP_PLAYER.tox

## CHOP_RECORDER

This component records the input CHOP signals to a CSV file.
To start/stop recording, press "Record" button.

By default, the CSV file will be saved to the same directory as the TouchDesigner project.
To change the directory, edit the `Filename` property.

## CHOP_PLAYER

This component plays the CHOP signals recorded in a CSV file.
Edit the `Filename` property and hit `Play` button to start playing.

## Author

AMAGI (GitHub: [@fand](https://github.com/fand))

## License

MIT

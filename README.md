# Ed's ZMK Config 

This is a ZMK config for my aurora sweep keyboard with nice_nanov2 boards.

## Building
Commit the changes and push it to remote. The github action will take care of creating the firmware that needs to be flashed.
Once the pipeline succeeds, download and extract the artifact.

## Flashing the boards
1. Plug the left board into the computer.
2. Press the board's reset button twice.
3. Within the next 8 seconds, copy the `*_left_*.uf2` firmware file to the mounted removable drive.
4. Repeat steps 1-3 for the right board.
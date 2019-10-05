# Build your PICO-8 games in JavaScript
This project uses jspicl-cli to transpile your JavaScript code into PICO-8 cardridges.

`npm start` - Runs the game in PICO-8 and watches the source files for changes. Whenever a file is updated the cartridge is automatically reloaded with the new changes<sup>1</sup>.

`npm run build` - Only generates the cartridge for you.

<hr>
<sup>1</sup> Currently only works on MacOS. You will have to manually refresh PICO-8 (Ctrl+R) on other platforms.
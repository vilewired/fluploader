# fluploader

This is a simple screenshot uploader that's powered by flameshot. When it's called it will use flameshot to take a screenshot and then upload the file data to a cdn server. The configuration I have is for my bunny.net cdn. But it uses curl to upload the file so it should be easy to change the configuration to use another cdn.
This contains the shell script itself which should be stored at ~/.local/bin/ and the desktop file which should be placed at ~/.local/share/applications/
Run update-desktop-database ~/.local/share/applications to update the desktop database. Then bind the script to a keybinding in your settings.

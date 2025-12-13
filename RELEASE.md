# Release Procedure

1. Grab latest `options.txt` from test instance.

2. Generate pack once with `packwiz mr export`.

3. Install pack to an instance.

4. Run instance at least once, then grab `.config/crash_assistant/modlist.json` and put it in the `yosbr/config` config folder.

5. Generate pack again with `packwiz mr export` to test and upload to Modrinth.

6. Run `packwiz list > modlist.txt` and copy the output to the Modrinth description. Select all the text and make it a bulleted list.

## License

The Universal Permissive License (UPL), Version 1.0 (<https://opensource.org/licenses/UPL>)

Summary: <https://tldrlegal.com/license/universal-permissive-license-1.0-(upl-1.0)>

Real license is included in the root of this repo in the `LICENSE` file. You can't use this code without accepting the terms of this license.

## Testing the result

1. Install Git;
2. Clone the repo: `git clone https://github.com/olegchir/olegchir-demo-tweetplugin.git`;
3. Open the repo directory in a console (`cmd.exe` on Windows works too);
4. Build the plugin: `gradlew buildPlugin`;
5. Test the plugin: `gradlew runIde`;
6. PROFIT.

## Running on a production instance of IDEA without publishing the plugin

1. Follow the steps above;
1. Extract your ZIP: `build\distributions\tweetplugin-1.0-SNAPSHOT.zip`;
2. Find the directory`tweetplugin` inside this ZIP;
3. Copy it in the `plugins` directory inside your IDEA installation. If you use the Toolbox, it's a directory like this:`C:\Users\olegchir\AppData\Local\JetBrains\Toolbox\apps\IDEA-U\ch-0\202.6948.69\plugins`;
4. Run IDEA;
6. PROFIT.

Good luck, little hunter.

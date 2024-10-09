Bing Copilot Desktop Apps from Tauri


Created by Hans Sean Nathanael to bring Bing Copilot apps into Kubuntu. Yeah, this is kind of stupid.
To build the apps, you need Rust compiler and Node.js with NPM. 
Build steps:
1. Run on cmd ```npm install``` inside the project directory
2. Run on cmd ```npm run tauri build```
3. The app installer from build will be based from the OS you are using. 
4. The installer location from build is located in ```/src-tauri/target/release/bundle```
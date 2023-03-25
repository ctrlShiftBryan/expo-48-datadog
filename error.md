[PREBUILD] yarn run v1.22.19
[PREBUILD] $ /private/var/folders/kz/xhv2b6q511v7mq6gmn3rr9nm0000gn/T/eas-build-local-nodejs/2fa815b0-9fdf-4b7e-9514-ac1012792b54/build/node_modules/.bin/expo prebuild --no-install --platform ios
[PREBUILD] - Creating native project directories (./ios and ./android) and updating .gitignore
[PREBUILD] ✔ Created native project | gitignore skipped
[PREBUILD] - Adding Metro bundler config
[PREBUILD] ✔ Added Metro config
[PREBUILD] - Updating your package.json scripts, dependencies, and main file
[PREBUILD] ✔ Updated package.json and added index.js entry point for iOS and Android
[PREBUILD] - Config syncing
[PREBUILD] Using node to generate images. This is much slower than using native packages.
[PREBUILD] › Optionally you can stop the process and try again after successfully running `npm install -g sharp-cli`.
[PREBUILD] - Config syncing
[PREBUILD] ✔ Config synced
[PREBUILD] Done in 2.37s.
[PREBUILD] Running "yarn install" in the root dir of your repository 
[PREBUILD] yarn install v1.22.19
[PREBUILD] [1/4] Resolving packages...
[PREBUILD] success Already up-to-date.
[PREBUILD] Done in 0.20s.
[INSTALL_PODS] Using Expo modules
[INSTALL_PODS] [Expo] Enabling modular headers for pod ExpoModulesCore
[INSTALL_PODS] Auto-generating `.xcode.env.local` with $NODE_BINARY=/Users/bryanarendt/.asdf/installs/nodejs/16.16.0/bin/node
[INSTALL_PODS] Auto-linking React Native modules for target `router48`: DatadogSDKReactNative, RNReanimated, RNScreens, and react-native-safe-area-context
[INSTALL_PODS] Framework build type is static library
[INSTALL_PODS] [Codegen] Generating ./build/generated/ios/React-Codegen.podspec.json
[INSTALL_PODS] Analyzing dependencies
[INSTALL_PODS] Fetching podspec for `DoubleConversion` from `../node_modules/react-native/third-party-podspecs/DoubleConversion.podspec`
[INSTALL_PODS] [Codegen] Found FBReactNativeSpec
[INSTALL_PODS] Fetching podspec for `RCT-Folly` from `../node_modules/react-native/third-party-podspecs/RCT-Folly.podspec`
[INSTALL_PODS] Fetching podspec for `boost` from `../node_modules/react-native/third-party-podspecs/boost.podspec`
[INSTALL_PODS] Fetching podspec for `glog` from `../node_modules/react-native/third-party-podspecs/glog.podspec`
[INSTALL_PODS] Fetching podspec for `hermes-engine` from `../node_modules/react-native/sdks/hermes-engine/hermes-engine.podspec`
[INSTALL_PODS] [!] CocoaPods could not find compatible versions for pod "DatadogSDKCrashReporting":
[INSTALL_PODS]   In Podfile:
[INSTALL_PODS]     DatadogSDKReactNative (from `../node_modules/@datadog/mobile-react-native`) was resolved to 1.4.0, which depends on
[INSTALL_PODS]       DatadogSDKCrashReporting (~> 1.15.0)
[INSTALL_PODS] None of your spec sources contain a spec satisfying the dependency: `DatadogSDKCrashReporting (~> 1.15.0)`.
[INSTALL_PODS] You have either:
[INSTALL_PODS]  * out-of-date source repos which you can update with `pod repo update` or with `pod install --repo-update`.
[INSTALL_PODS]  * mistyped the name or version.
[INSTALL_PODS]  * not added the source repo that hosts the Podspec to your Podfile.
[INSTALL_PODS] 
Error: pod exited with non-zero code: 31
    at ChildProcess.completionListener (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/spawn-async/build/spawnAsync.js:41:23)
    at Object.onceWrapper (node:events:642:26)
    at ChildProcess.emit (node:events:527:28)
    at maybeClose (node:internal/child_process:1092:16)
    at Socket.<anonymous> (node:internal/child_process:451:11)
    at Socket.emit (node:events:527:28)
    at Pipe.<anonymous> (node:net:709:12)
    ...
    at spawnAsync (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/spawn-async/build/spawnAsync.js:7:23)
    at spawn (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/turtle-spawn/dist/index.js:27:47)
    at installPods (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/ios/pod.js:11:38)
    at /Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/builders/ios.js:57:41
    at BuildContext.runBuildPhase (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/context.js:83:34)
    at buildAsync (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/builders/ios.js:56:19)
    at processTicksAndRejections (node:internal/process/task_queues:96:5)
    at async runBuilderWithHooksAsync (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/builders/common.js:13:13)
    at async Object.iosBuilder (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/@expo/build-tools/dist/builders/ios.js:26:16)
    at async buildIosAsync (/Users/bryanarendt/.npm/_npx/ac2fe9123ebf2e7d/node_modules/eas-cli-local-build-plugin/dist/ios.js:62:12)
[CLEAN_UP_CREDENTIALS] Destroying keychain - /var/folders/kz/xhv2b6q511v7mq6gmn3rr9nm0000gn/T/turtle-v2-e70fd95d-b590-4ccc-ab21-8b8cb974680e.keychain
[CLEAN_UP_CREDENTIALS] Removing provisioning profile

Build failed
Unknown error. See logs for more information.
npx exited with non-zero code: 1

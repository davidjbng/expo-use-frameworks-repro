# Expo 51 iOS Build Error

iOS Builds fail when specifying `useFrameworks: 'static'`

> ❌  (node_modules/react-native/ReactCommon/cxxreact/JSExecutor.h:15:10)
> 
  > 13 | #include <cxxreact/NativeModule.h>
  > 14 | #include <folly/dynamic.h>
> 15 | #include <jsinspector-modern/InspectorInterfaces.h>
>      |          ^ 'jsinspector-modern/InspectorInterfaces.h' file not found
>   16 | #include <jsinspector-modern/ReactCdp.h>
>  17 | 
>  18 | #ifndef RN_EXPORT

## How to Reproduce

1. Run `npm install`
2. Run `npm run ios`


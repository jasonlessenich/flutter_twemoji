# 1.0.0
- Renamed to flutter_twemoji

# 0.6.0
- Upgraded to Twemoji 15.1.0 (https://github.com/jasonlessenich/twemoji_v2/pull/5)
- Deprecated TwemojiType#networkSvg as Twitter no longer maintains Twemoji

# 0.5.3
- Fixed an issue where `TwemojiText` wouldn't respect the specified `TextStyle`

# 0.5.2
- Removed 'Include specific emojis' functionality - See https://github.com/DynxstyGIT/twemoji_v2/pull/3#issuecomment-1492372253 for more info

# 0.5.1
- Upgraded `flutter_svg` to `^2.0.4`
- Fixed image on README.md
- Reformatted code

# 0.5.0
- Upgraded to Twemoji 14.1.2
- Switched from `RichText` to `Text.rich` for `TwemojiText` (to, e.g., respect the devices' `textScaleFactor`)
- Added many new options to `TwemojiText`
- Overhauled some documentation
- Introduced `FitzpatrickType`
- Updated example

# 0.4.3
- updated emoji regex
- improved emojiToUnicode method
- updated example
# 0.4.2
downgraded characters to ^1.1.0

# 0.4.1
fix lint problem
# 0.4.0
updated flutter_svg to ^1.0.0


# 0.3.1
Add support network svg
# 0.3.0
Add support for only including specified emojis
# 0.2.3
updated flutter_svg to ^0.23.0+1
# 0.2.2
Added parameter for specifying max lines in TwemojiText
Fixed error when emojiFontMultiplier was null in TwemojiTextSpan.
# 0.2.1
Updated README
# 0.2.0
Added svg support
Created TwemojiText and Twemoji widgets
Created a method to convert emojis to unicodes 
# 0.1.0

Initial Version of the library.

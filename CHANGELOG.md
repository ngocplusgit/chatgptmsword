# CHANGELOG
This changelog file outlines a chronologically ordered list of the changes made on this project. 
It is organized by version and release date followed by a list of Enhancements, New Features, Bug Fixes, and/or Breaking Changes.
<br /><br />

## Version 0.1.4 (Latest) 
**Released:** March 22, 2023<br />
**Tag:** v0.1.4


### Moved

  - The latest ChatgptTextCompletion.bas file has been moved to the src/windows directory and will no longer be stored in the repository root location main.

### Bug Fix

  - Added new error handling for http request timeouts. This occurs when a outage occurs on the OpenAI Chat channel. The Alert message will also point users to OpenAI's status page <a href="https://status.openai.com/">status.openai.com</a> to check for any types of service outages.


<br /><br />
## Version 0.1.3 
**Released:** February 12, 2023<br />
**Tag:** v0.1.3

### Bug Fix

  - Added additional error handling for when ChatGPT is at capacity. When this occurs an Alert Message will display on the screen rather than a Run-time Error 5 message from Microsoft Visual Basic. See <a href="https://github.com/analyticsinmotion/add-chatgpt-to-microsoft-word/issues/2">Issues #2</a> for more details.

<br /><br />
## Version 0.1.2 
**Releasd:** February 10, 2023<br />
**Tag:** v0.1.2 

### Breaking Changes

 - Moved the location of the OpenAI API Key from source to a Windows Environment variable.

<br /><br />
## Version 0.1.1 
**Releasd:** February 8, 2023<br />
**Tag:** v0.1.1

### Bug Fix

  - Added additional error handling for ChatGPT error responses 
  - Responses from ChatGPT often contain '/n' in the returned text strings. We have replaced cases of /n in the text string with a carriage return. This makes output in Word much more readable.

<br /><br />
## Version 0.1.0 (Initial Release)
**Releasd:** February 6, 2023<br />
**Tag:** v0.1.0

This is the initial release

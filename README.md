# Currently most active projects 🧑🏼‍💻

My most popular and demanding project is 🗂️ [erase-install](https://github.com/grahampugh/erase-install), a zsh script for upgrading, reinstalling and erasing macOS. This was updated significantly in 2022 to use [mist-cli](https://github.com/ninxsoft/mist-cli) and [swiftDialog](https://github.com/swiftDialog/swiftDialog), and now includes a built-in method for obtaining installers. The project is frequently updated to keep pace with changes to those projects as well as changes to macOS itself.

<img width="100" height="100" alt="jamfuploader-logo" src="https://github.com/user-attachments/assets/1976ac48-8f3c-49c6-a11f-9a57b5c26889"  align="right" />My other most used project is [JamfUploader](https://github.com/grahampugh/jamf-upload). This is a collection of python processors for use with [AutoPkg](https://github.com/autopkg/autopkg) which is the dominant method for integrating AutoPkg with Jamf Pro. The project also includes `jamf-upload.sh`, a script enabling the use of the JamfUploader framework to create or amend all sorts of API objects without having to write AutoPkg recipes.

The JamfUploader processors are also mirrored in my AutoPkg recipes repo, [grahampugh-recipes](https://github.com/autopkg/grahampugh-recipes), along with a large collection of recipes and examples of how to write `.jamf` recipes.

## Other notable projects 📝

As a first foray into coding with Swift, I have two projects of note: 

* [AutoPkg Wizard](https://github.com/grahampugh/autopkg-wizard) is a SwiftUI convenience application for users of AutoPkg, and
* [PlistYamlPlist](https://github.com/grahampugh/plist-yaml-plist-swift), a swift binary which is an update of my earlier python-based project [plist-yaml-plist](https://github.com/grahampugh/plist-yaml-plist), useful for converting PLIST files to YAML, or vice versa (including AutoPkg recipes).

For those interested in an easy script for setting up AutoPkg on a fresh machine, including (optionally) configuring JamfUploader, check out [AutoPkgSetup](https://github.com/grahampugh/AutoPkgSetup).

If you need a signed package to add to your MDM to install Rosetta 2 at enrollment, check out [Rosetta-2-install](https://github.com/grahampugh/Rosetta-2-install).

MSPs, or anyone working with multiple Jamf Pro instances, may be interested in the [Multitenant Jamf Tools (MJT)](https://github.com/grahampugh/multitenant-jamf-tools), which is a series of scripts using a common framework, designed to perform a range of actions on Jamf Pro instances using the API. This includes `jocads.sh`, an interactive script with the ability to copy a large range of API objects from one instance to multiple other instances in one go, and `jamfuploader-run.sh` and `autopkg-run.sh`, two scripts that wrap on top of AutoPkg and the JamfUploader processors to allow running `jamf-upload.sh` and AutoPkg recipes on multiple instances at once. There's also `mdm-commands.sh`, which allows you to run various MDM commands on multiple devices at once. Handily, MJT stores credentials for all your instances in your Keychain, so you only have to provide them once.

## Archived Projects ☠️

The projects based on [python-jss](https://github.com/jssimporter/python-jss) that I inherited from Shea Craig, namely JSSImporter, Spruce, jss_helper, JSSRecipeCreator, and python-jss itself, are no longer maintained and all now archived. You can still find the code in the [JSSImporter](https://github.com/jssimporter) organisation.

<!--
**grahampugh/grahampugh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

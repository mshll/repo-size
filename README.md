<p align="center">
  <h1 align="center">Github Repo Size</h1>
</p>
<p align="center">
  <a href="https://greasyfork.org/en/scripts/458048-github-repo-size" style="text-decoration: none">
    <img src="https://img.shields.io/badge/download-here-%231A55E6" alt="Download">
    <img src="https://img.shields.io/greasyfork/v/458048?color=%231A55E6&label=version" alt="Version">
    <img src="https://img.shields.io/greasyfork/dt/458048?color=%231A55E6" alt="Installs">
    <img src="https://img.shields.io/greasyfork/l/458048?color=%231A55E6" alt="License">
  </a>
</p>

A userscript that adds the size of Github repositories to the search results and repository pages.

## Preview

![Preview1](images/preview1.png)
![Preview2](images/preview2.png)

## Prerequisites

To use this script, you will need a userscript manager. Some popular choices are:

- [Tampermonkey](https://tampermonkey.net/) (Chrome, Firefox, Safari, Microsoft Edge, Opera Next)
- [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox, Microsoft Edge)
- [Greasemonkey](https://www.greasespot.net/) (Firefox)
- [Userscripts](https://apps.apple.com/us/app/userscripts/id1463298887) (Safari)

## Installation

1. Install Tampermonkey or your preferred userscript manager.
2. Install the script from [here](https://greasyfork.org/scripts/458048-github-repo-size/code/Github%20Repo%20Size.user.js).
3. (Optional) If you want to view the sizes of private repositories, see the instructions below.

## View Private Repositories Size

By default, this script will only display the sizes of public repositories.
To display the sizes of private repositories, you will need to generate a new personal access token with the `repo` scope.
This token will be used to authenticate with the Github API.

1. Generate a new token [here](https://github.com/settings/tokens/new?description=repo-size%20userscript&scopes=repo).
2. Give the token a name and check the `repo` scope.
3. Click on the `Generate token` button and copy the token.
4. Replace the value of the `TOKEN` constant at the top of the script with the token you just generated.

## Usage

This script will automatically run on Github search pages and repository pages, and will display the repository size next to the repository name.

## Important Notice

🚀 **Heads up!** The GitHub API has a limit of 60 public requests per hour. To avoid hitting this limit and ensure smooth operation, it's recommended to obtain an access token from [GitHub Settings](https://github.com/settings/tokens) and add it in the script.

## Support

If you have any issues or feedback, please open an issue [here](https://github.com/mshll/repo-size/issues)

## Disclaimer

This script is not affiliated with Github, Inc. Use it at your own risk.

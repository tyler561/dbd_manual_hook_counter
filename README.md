<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- GETTING STARTED -->

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Install AutoHotkey - https://www.autohotkey.com/
2. Download the correct ahk file for your UI layout and resolution, "defaultUI" is default and "smallUI" is 70% in game UI scale (a lot of streamers use this size to reduce clutter on their screen).
3. Double click the .ahk file after downloading to run it. If it doesn't show the GUI right click and go to "Run Script" (this option should be available if you have AutoHotkey installed). The script will be running in your taskbar, you can pause it or close it out there.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage
The script writes and reads to C:\temp\hook.ini file to display the values. Once loaded the GUI should align properly (relatively, I tried) to the survivor's portraits, use the following hotkeys for interactions with the GUI. The counter goes up to 3 and after 3 it will reset back to 0. 

I've used this for 2-3 hours for about 2 months now and have not been banned but I bear no responsibility for the repercussions using this script. Test it out on a different account or have someone test it for you if you're unsure.

Hotkeys:
* 1 - add a hook state to the first survivor
* 2 - add a hook state to the second survivor
* 3 - add a hook state to the third survivor
* 4 - add a hook state to the fourth survivor
* LShift + 1 = subtract a hook state to the first survivor (corresponding numbers 1-4 will subract from other survivor values)
* CTRL + 0 - reload script (will reset hook state values)
* CTRL + = - show/hide the GUI (in case it's covering something up that you want to show)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- KNOWN ISSUES -->
## Known Issues
* While typing in chat and hitting the number keys you will increase the values, there's no workaround outside of pausing the script.
* Using display capture or screen capture will display the values as well. There's no way around this, OBS or Streamlabs captures everything on your screen.
* "Fullscreen" video settings doesn't work, only "Windowed Fullscreen". There's no way to display the GUI outside of injecting game code which is likely bannable/much more difficult.

<!-- ROADMAP -->
## Roadmap

- [x] Add Readme

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
Feel free to fork this repo and change it to your liking, just please give credit. Thanks.

My info: achilles561/tyler561 - https://www.twitch.tv/achilles_561

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Original credit goes to Reynbow & contributors -  https://github.com/Reynbow/dbd_hook_counter

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

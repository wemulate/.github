## Thanks for visiting WEmulate 👋
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)  
WEmulate is a simple and modern WAN emulator, developed to fulfill the needs of students and network engineers.

### Documentation
You can find the whole documentation of WEmulate under [https://wemulate.github.io/wemulate](https://wemulate.github.io/wemulate).

### Usage
![WEmulate usage cli](/img/animation-wemulate-cli.gif)
![WEmulate usage frontend](/img/animation-wemulate-frontend.gif)

### Repositories
WEmulate has three repositories each of these repositories is one module and is described below.
| Repository | Description |
| --- | --- |
| [wemulate](https://github.com/wemulate/wemulate) | CLI and package module. Can be used as a standalone module or in combination with the `wemulate-api` and `wemulate-frontend` modules. Provides the core functionality for these two modules. |
| [wemulate-api](https://github.com/wemulate/wemulate-api) | Module which provides the API for the `wemulate-frontend` module. Uses the `wemulate` module. |
| [wemulate-frontend](https://github.com/wemulate/wemulate-frontend) | Frontend for the WEmulate application. Uses the `wemulate-api` to make requests to the system. |
| [wemulate-container](https://github.com/wemulate/wemulate-container) | Container image with `wemulate`, `wemulate-api` and `wemulate-frontend`. |
| [wemulate-containerlab-demo](https://github.com/wemulate/wemulate-containerlab-demo) | Containerlab setup to try WEmulate |


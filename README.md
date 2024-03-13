# BasicDockerHeadlessSetup
A very simple docker setup for a Headless Resonite Session, it uses [Shadow Panther's Docker Image](https://github.com/shadowpanther/resonite-headless).

## Setup

### Recommended for Beginners
If you're new to Docker, Docker Compose or git, we'd recommend you use our [wiki guide on how to use this repo](https://wiki.resonite.com/index.php?title=Headless_Client/Docker).

### Quick Instructions
1. Setup Docker & Docker Compose on your target machine.
1. `git clone`.
1. Create an `.env` file.
1. Add a line: `RES_HEADLESS_CODE=<Headless Code>` where `<Headless Code>` is replaced by the code you get from the [Resonite Bot](https://wiki.resonite.com/Patreon#Headless_Server).
1. Add a line: `RES_STEAM_LOGIN=<Steam Username> <Steam Password>` where `<Steam Username>` and `<Steam Password>` are replaced with the username and password of a valid Steam account.
   - We recommend using a separate Steam account from the one you use to play Resonite.
   - It does not need to own any games.
   - It does not need to also be a Patreon on Resonite.
1. Run `docker compose up`.


## Goals for this Repository
This repository is designed to be as stable and simple as possible when it comes to headless operations:
- It is meant to be used for a "Try This" style approach.
- It is not meant for a "Production" headless setup. 

To that end, before contributing keep in mind our goals:
1. Keep it simple.
1. Keep it stable.
1. Avoid any additional software.
1. Avoid any additional credentials.

## Where to go Next?

It is likely we'll create other repositories with more complex setups in the future, we'll link to them from here when we do. Until then remember to check our [wiki's page on Headless Servers](https://wiki.resonite.com/index.php?title=Headless_Client).


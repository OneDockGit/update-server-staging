OneDock app releases are publishing to this repository. Hazel integration refreshes the cache **every 1 minute** (or every 15 min, which is the default, couldn't verify if i could overwrite it).

# Hazel deploy
1. Clone default zeit/hazel repo: https://github.com/zeit/hazel
2. Run deploy command: now -e ACCOUNT="OneDock" -e REPOSITORY="update-server" -e INTERVAL=1
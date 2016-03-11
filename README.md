<!---
[![Circle CI](https://circleci.com/gh/noroutine/dominion.svg?style=svg)](https://circleci.com/gh/noroutine/dominion)
[![wercker status](https://app.wercker.com/status/3f2898a9d294d61a7b7bae8b7ab04df0/s/master "wercker status")](https://app.wercker.com/project/bykey/3f2898a9d294d61a7b7bae8b7ab04df0) 
[![Build Status](https://drone.io/github.com/noroutine/dominion/status.png)](https://drone.io/github.com/noroutine/dominion/latest)
-->

[![Go](https://img.shields.io/badge/Go-1.6-blue.svg)](https://golang.org/) [![Build Status](https://travis-ci.org/noroutine/dominion.svg?branch=master)](https://travis-ci.org/noroutine/dominion) [![Gitter](https://badges.gitter.im/turbovillains/dominion.svg)](https://gitter.im/turbovillains/dominion?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Issue Count](https://codeclimate.com/github/noroutine/dominion/badges/issue_count.svg)](https://codeclimate.com/github/noroutine/dominion)

[![Run Status](https://api.shippable.com/projects/56e21e429d043da07bb60188/badge?branch=master)](https://app.shippable.com/projects/56e21e429d043da07bb60188)

Dominion Client
=====

Dominion client implements P2P protocol designed to allow 2-6 players enjoy the game without centralized server.


How to Use
=====

Write your own AI that communicates with this client or play yourself via CLI

[More about the Dominion](https://en.wikipedia.org/wiki/Dominion_(card_game))

How to Build
===

    make
    ./dominion
    
You will end up in CLI, while in background also HTTP interface starts at port 9999 (controlled by PORT environment variable)

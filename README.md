# 3D Nav Racer

Drop an `.stl`, hit 10 targets as fast as you can: center the dot on each target and look straight down its axis.

Play: https://a3vong.github.io/nav-racer/

- Solo: best times are kept per scan and tolerance level in your browser.
- Battle a friend: click **Battle a friend**, share the link or code. You both race for the same targets; the first to lock one captures it. Most captures out of 10 wins, a tie goes to sudden death. The scan goes browser to browser over WebRTC ([PeerJS](https://peerjs.com/)); it is never uploaded anywhere.
- Music speeds up with every target. `M` mutes.

Everything lives in `index.html` (three.js, three-mesh-bvh and PeerJS from jsDelivr).

# Studio

A mobile-friendly music creation and recording presentation demo.

## Open the hosted demo

After GitHub Pages finishes deploying, open:

https://abelmathew07.github.io/Studio/

## What you can demonstrate

- Create a Malayalam film melody or Carnatic-style starting idea.
- Record a vocal or instrument take using the browser microphone.
- Arrange multiple audio tracks, adjust levels, mute or solo, and play the mix.
- Save projects in this browser, then reopen them from Projects.
- Export the rendered mix as a WAV file.
- Explore a simulated HEOS room playback handoff.

## What is simulated

The hosted site uses a clearly labeled synthesized Web Audio cue. It does not run AI music generation on GitHub Pages. Optional HeartMuLa generation requires a separately configured local GPU model service; model weights are not included. HEOS room discovery and device playback are interface simulations, not a connection to Denon, Marantz, or HEOS hardware.

Microphone permission is requested only when you choose to record. Audio and saved projects remain in your browser; the site does not upload them.

## Local HeartMuLa setup

See the [official HeartMuLa repository](https://github.com/HeartMuLa/heartlib) for model setup and checkpoint requirements. The local app bridge in the original demo source needs Node.js 20+, Python 3.10, compatible CUDA/PyTorch, and the model checkpoints. This GitHub Pages deployment is static and does not provide that GPU backend.

The HeartMuLa repository lists its code and released weights under Apache-2.0; verify current terms and checkpoint licensing in the official repository before distribution.

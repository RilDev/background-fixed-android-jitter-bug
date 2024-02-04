# Background Fixed Android Jitter Bug

## Description

- I scroll down the page.
- The toolbar at the top of the screen scrolls up.
- The fixed background image gets resized.

![demo](./demo.gif)

## How to test

- Start a webserver: `npx live-server`
- Get the local network address: `npx localview --port 8080` ex: `http://192.168.1.70:8080`
- Open the local netword address in Chrome on an Android device

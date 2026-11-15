<div align="center">
  <h1>Donationless XMRig</h1>
  <h3>Pre-compiled XMRig binaries with donations disabled for Linux, MacOS, and Windows.</h3>
</div>

## Why create this when you can use binaries directly from XMRig?
The main reason is to bypass the forced minimum donation set in the pre-compiled binaries. If you want to support their work (you should), consider using the official binaries and donating to them on the [official repo](https://github.com/xmrig/xmrig).

## How does Donationless XMRig work?
It runs a Github Action every 7 days to check whether the main repository has any new Releases. Then, it compiles the binaries on Linux, MacOS, and Windows and adds it as a release here. You can checkout the workflow under [the workflows directory](.github/workflows).

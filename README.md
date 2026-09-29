# firmware-mirror

Backup copies of the third-party firmware images that Lamella's builds download. A build fetches each image from
its publisher first, and uses this repository only when that download fails or its bytes do not match. Every file
here is byte-identical to what the build expects, and the build checks each one against a pinned SHA-256 before
using it.

Each folder names its source, the upstream commits, and the SHA-256 of each file, and keeps the publisher's license
file beside the images. Files are never changed: a new version gets a new folder.

| Folder | What it holds |
|---|---|
| [`cyw43439/7.95.49/`](cyw43439/7.95.49/) | The CYW43439 Wi-Fi radio's firmware, regulatory blob and board-settings image |

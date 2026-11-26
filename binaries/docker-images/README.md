<!--
 Copyright (c) 2025 Innodisk Corp.

 This software is released under the MIT License.
 https://opensource.org/licenses/MIT
-->

# Docker Image Archives

This folder is empty by default. iQ-Studio does not ship Docker images in this repository.

Use it when the platform cannot download the image from Docker Hub, for example when it has no network. Place the Docker image archive (`.tar`) of the application here, and `iqs-launcher` loads it directly without contacting Docker Hub.

- The file name must match the application name, for example `iqs-vlm-demo.tar`.
- If you cannot access Docker Hub, contact Innodisk to obtain the `.tar`.

For how to download, transfer, and launch the image, see [When the Platform Cannot Download the Image](../../docs/how-to-use-iqs-launcher.md#when-the-platform-cannot-download-the-image) in How to Use iqs-launcher.

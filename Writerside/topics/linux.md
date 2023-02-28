[//]: # (title: Linux (Snapcraft))


> *Compatible with [**Ubuntu**](https://releases.ubuntu.com/18.04/) 18 or higher and is currently in beta* 

1. From the Snapcraft Store install the Pieces for Developers | OS Server Snap Package or run the following in the terminal:
```shell 
     $ sudo snap install pieces-os
   ```
2.  Enable Offline and On-Device Local Machine Learning by running the following command in the terminal:
```shell 
  $ sudo snap connect pieces-os:dotnet-runtime-aspnetcore
```
> *This command sets up and configures local application interfaces to properly load our Sandboxed and Secure Machine Learning Model*

3. Launch the Pieces for Developers | OS Server background service by running the following command in the terminal:
```shell
  $ pieces-os
```

4. Launch the [Pieces for Developers | Flagship Desktop App](https://code.pieces.app/install) by running the following command in the terminal:
```shell
  $ pieces-for-developers
``` 

5. Launch JetBrains and install our Pieces for Developers | JetBrains Plugin

If you have already installed our JetBrains Plugin, and it's having trouble connecting the Pieces for Developers | OS Server background service, try the following quick [Troubleshooting Solutions](troubleshooting.md "Troubleshooting").

### Watch our [**Getting Started Video**](https://youtu.be/C8S3URf7MLE)

[![Getting Started ⎸ Pieces for Developers | JetBrains Plugin](https://storage.googleapis.com/pieces_static_resources/jetbrains_marketplace/Graphics/JB_Getting_Started.png){width="650"}}](https://youtu.be/C8S3URf7MLE)

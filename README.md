[ESPAÑOL](README-Español.md)

# VRChat Memories Archiver

This repository contains the VRChat Memories Archiver, a Python script that automatically embeds metadata into screenshots taken in VRChat. It simplifies identifying and recalling the context of each screenshot by including details like the world name and players present.

## How It Works

The VRChat Memories Archiver monitors a specified directory for new screenshots. Upon detecting a new screenshot, it uses the VRChat API to retrieve current session information, including the world name and the players present at the time the screenshot was taken. This information is then embedded as metadata within the image file itself. This process allows for easy organization and retrieval of memories captured in VRChat, enhancing the value of each screenshot by preserving its context.

## Usage

This script is free for use, modification, and distribution in your VRChat projects. It's designed to add value to your VRChat screenshots without the need for explicit permission or credit, though acknowledgment is appreciated.

## Getting Started

To get started with the VRChat Memories Archiver:

1. Install Python on your machine.
2. Download or clone this repository.
3. Install any dependencies as listed in the `requirements.txt` file.
4. Run the script following the instructions provided in the `USAGE.md` file.

Ensure your VRChat screenshots are saved in a supported format and location as specified by the script documentation.

## How to Use

After setting up the VRChat Memories Archiver, run it from the console with the following command:

```bash
python vrchat_memories_archiver.py
```

This command starts the monitoring process. For example, to process an existing screenshot, the script could output something like this:

```bash
INFO: Detected new screenshot: C:\Users\YourName\Pictures\VRChat\VRChat_1920x1080_2021-07-01_23-59-59.99.png
INFO: Metadata embedded successfully.
```

This indicates that the script has found a new screenshot and successfully embedded the metadata.

## Contributing

Contributions are welcome but not required. If you'd like to improve the script or add features, please submit a pull request. Ensure your contributions are well-documented and follow the project's existing code style.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This script is provided "as is", without warranty of any kind. Use it at your own risk. The author is not responsible for any loss or damage resulting from the use of this script.


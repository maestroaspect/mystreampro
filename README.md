# MyStreamPro - An Enhanced Virtual Worlds Viewer for the MyStreamPro Grid.

MyStreamPro is a derivative of the Firestorm Viewer, optimized for use on the MyStreamPro Grid. This viewer is dedicated to enhancing performance, usability, and accessibility within MyStreamPro, with a primary focus on fostering interoperability with the OpenSimulator Server, the backbone of the MyStreamPro Grid.

## Project Background

### About Firestorm Viewer

The genesis of the Phoenix Firestorm Project can be traced back to Linden Lab's pioneering decision to share the source code of their Second Life viewer. The Firestorm Viewer has a rich history and has been shaped by various contributors over the years.

We owe our deepest appreciation to the following groups and individuals who have played a pivotal role in the development of the Firestorm Viewer, upon which MyStreamPro is built:

- **The Development Team at Linden Lab:** Since Second Life's inception in 2003, they have been pioneers in the metaverse landscape.

- **The Firestorm Team:** Their dedication and efforts have created a feature-rich and innovative viewer that has significantly contributed to virtual worlds.

- **The global community of developers, volunteers, and enthusiasts:** These individuals have dedicated their time and expertise to improve the viewer and create a thriving open-source ecosystem.

## Licensing 

MyStreamPro is based on the Firestorm Viewer, which is licensed under LGPLv2. To ensure compliance with the licensing terms, MyStreamPro is released under the LGPLv2  as well.

## Features

MyStreamPro comes with several enhanced features, including:

- **Fine-Tuning of App Settings:** Customized viewer settings to tailor the experience for MyStreamPro users.

- **Features Table:** Changes in the features tables that provide better default graphics settings.

- **Ignorable Dialogs:** Addition of extra dialogs or notifications users don't want to see.

- **Customizing Skin Parameter Values:** Adjustment of the default skin parameters to personalize the viewer's appearance.

- **Customizing Cache Directory Location:** Designation of a new cache location to prevent conflicts with other Firestorm-based viewers.

- **Resource Updates:** Changes to image resources and other graphical elements for a better experience.

- **Minor Bug Fixes:** Continual improvements to ensure a smooth user experience.

- **Improved Model Preview Name Retrieval:** Enhanced retrieval of model preview names for easier model identification.

- **And More:** MyStreamPro is constantly evolving to offer users an unobtrusive and creator-friendly virtual world viewer experience.

These features are designed to enhance your experience on the MyStreamPro Grid and offer customization and performance improvements for your virtual world interactions within MyStreamPro Grid.


## Project Links

- [MyStreamPro GitHub Repository](https://github.com/maestroaspect/mystreampro)


## Building Instructions

These instructions will guide you through the process of building MyStreamPro from the source code. Building MyStreamPro allows you to customize the viewer and adapt it to your specific needs.

### Prerequisites

Before you begin, make sure you have the following prerequisites installed on your system, which are common to the Firestorm Viewer:

**Windows**:
- [Visual Studio](https://visualstudio.microsoft.com/downloads/) (Visual Studio 2017 or later).
- [CMake](https://cmake.org/download/).
- [Python](https://www.python.org/downloads/).		
- [Git for Windows](https://gitforwindows.org/).
- [Autobuild](https://wiki.secondlife.com/wiki/Autobuild). The Linden Lab Autobuild tool.


**macOS**:
- [Xcode](https://developer.apple.com/xcode/) (includes the required development tools).
- [CMake](https://cmake.org/download/).
- [Python](https://www.python.org/downloads/).
- [Git](https://git-scm.com/download/mac).
- [Autobuild](https://wiki.secondlife.com/wiki/Autobuild). The Linden Lab Autobuild tool.


**Linux**:
- Build essentials (compiler, make, etc.). Install these tools using your Linux distribution's package manager.
- Required packages. You must install the following packages on your build system. Some of them may already be installed. You can install these packages using the following command:

  sudo apt install libgl1-mesa-dev libglu1-mesa-dev libpulse-dev libssl-dev libxinerama-dev libxrandr-dev libfontconfig1-dev libfreetype6-dev

- [CMake](https://cmake.org/download/).
- [Python](https://www.python.org/downloads/).
- [Git](https://git-scm.com/download/linux).
- [Autobuild](https://wiki.secondlife.com/wiki/Autobuild). The Linden Lab Autobuild tool.
- Additional dependencies may be required based on your Linux distribution and build environment.


### Building MyStreamPro

Follow these steps to build MyStreamPro:

1. **Clone the Repository**: Start by cloning the MyStreamPro repository to your local machine. You can use the following command to clone the repository via Git:

git clone https://github.com/yourusername/mystreampro.git

Replace `yourusername` with your GitHub username or the appropriate repository URL.

2. **Navigate to the Directory**: Change your working directory to the MyStreamPro project folder:

cd mystreampro

3. **Build the Project**: Depending on the build system and tools used in the project, you have to execute specific build commands. Refer to the project's documentation or build instructions for the exact commands to build MyStreamPro.

4. **Customize Configuration (If Needed)**: If you need to configure or customize any settings for your specific use case, refer to the project's configuration files or documentation. Make any necessary changes as per your requirements.

5. **Compile and Generate Executable**: Compile the source code to generate the executable file. The resulting executable should be located in a designated output directory.

6. **Run MyStreamPro**: You can now run MyStreamPro using the generated executable. Follow the project's usage instructions to get started.

## Contributing

We welcome contributions from the community to help make MyStreamPro even better. If you're interested in contributing, please review our [contribution guidelines](CONTRIBUTING.md).

## Contact

For inquiries or contributions, please contact us at info@aspectsoft.gr.

---

**MyStreamPro** is an independent project and is not affiliated with or endorsed by Linden Research, Inc. (the makers of Second Life) or The Phoenix Firestorm Project, Inc. (the makers of Firestorm Viewer).

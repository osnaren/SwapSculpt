
# SwapSculpt

Next-Generation Face Swapping and Enhancement. Seamlessly swap and enhance faces in just a click!



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

![GitHub last commit (branch)](https://img.shields.io/github/last-commit/osnaren/SwapSculpt/master)


## UI Preview
-------

![Preview](https://raw.githubusercontent.com/facefusion/facefusion/master/.github/preview.png?sanitize=true)
## Installation

Please note that the installation process for SwapSculpt requires technical skills and is not recommended for beginners. If you encounter any platform or installation-related issues, we kindly ask you not to open GitHub issues. Instead, we recommend reaching out to the [FaceFusion community on Discord](https://join.facefusion.io), where experienced users can guide you through the installation process.

For detailed installation instructions, you can refer to the [installation guide](https://docs.facefusion.io/installation) from the FaceFusion project. While SwapSculpt shares some similarities with FaceFusion, please follow the FaceFusion installation guide as the installation process for SwapSculpt aligns closely with it.

Your understanding and patience are greatly appreciated as you embark on your journey with SwapSculpt.

## Usage

To use SwapSculpt, follow these command-line instructions:

```shell
python run.py [options]
```

```

-h, --help                                                                                       show this help message and exit
-s SOURCE_PATH, --source SOURCE_PATH                                                             select a source image
-t TARGET_PATH, --target TARGET_PATH                                                             select a target image or video
-o OUTPUT_PATH, --output OUTPUT_PATH                                                             specify the output file or directory
--frame-processors FRAME_PROCESSORS [FRAME_PROCESSORS ...]                                       choose from the available frame processors (choices: face_enhancer, face_swapper, frame_enhancer, ...)
--ui-layouts UI_LAYOUTS [UI_LAYOUTS ...]                                                         choose from the available ui layouts (choices: benchmark, webcam, default, ...)
--keep-fps                                                                                       preserve the frames per second (fps) of the target
--keep-temp                                                                                      retain temporary frames after processing
--skip-audio                                                                                     omit audio from the target
--face-recognition {reference,many}                                                              specify the method for face recognition
--face-analyser-direction {left-right,right-left,top-bottom,bottom-top,small-large,large-small}  specify the direction used for face analysis
--face-analyser-age {child,teen,adult,senior}                                                    specify the age used for face analysis
--face-analyser-gender {male,female}                                                             specify the gender used for face analysis
--reference-face-position REFERENCE_FACE_POSITION                                                specify the position of the reference face
--reference-face-distance REFERENCE_FACE_DISTANCE                                                specify the distance between the reference face and the target face
--reference-frame-number REFERENCE_FRAME_NUMBER                                                  specify the number of the reference frame
--trim-frame-start TRIM_FRAME_START                                                              specify the start frame for extraction
--trim-frame-end TRIM_FRAME_END                                                                  specify the end frame for extraction
--temp-frame-format {jpg,png}                                                                    specify the image format used for frame extraction
--temp-frame-quality [0-100]                                                                     specify the image quality used for frame extraction
--output-image-quality [0-100]                                                                   specify the quality used for the output image
--output-video-encoder {libx264,libx265,libvpx-vp9,h264_nvenc,hevc_nvenc}                        specify the encoder used for the output video
--output-video-quality [0-100]                                                                   specify the quality used for the output video
--max-memory MAX_MEMORY                                                                          specify the maximum amount of ram to be used (in gb)
--execution-providers {cpu} [{cpu} ...]                                                          choose from the available execution providers (choices: cpu, ...)
--execution-thread-count EXECUTION_THREAD_COUNT                                                  specify the number of execution threads
--execution-queue-count EXECUTION_QUEUE_COUNT                                                    specify the number of execution queries
--skip-download                                                                                  omit automate downloads and lookups
--headless                                                                                       run the program in headless mode
-v, --version   

```
## Disclaimer

At SwapSculpt, we are committed to responsible and ethical usage of our software. We recognize that individuals may use technology in various ways, including for personal creative expression.

We want to make it clear that we do not endorse or support any usage of SwapSculpt for the creation of explicit or adult content. It is essential to use our software within the bounds of legal and ethical standards.

We expect all users to respect our guidelines and engage in ethical and responsible behavior. Any misuse of SwapSculpt for explicit content may result in consequences.

We are dedicated to fostering a responsible and ethical approach to technology use, and your cooperation is crucial in maintaining these standards.
### SwapSculpt Assets

For detailed information about the assets used in SwapSculpt, please refer to the [Assets Documentation](./Assets.md).
## Documentation

For a more in-depth understanding of SwapSculpt and its features, please explore the comprehensive [documentation](https://docs.facefusion.io) available on the FaceFusion project's website.

This documentation covers various aspects of face swapping and enhancement, and while it is primarily associated with FaceFusion, it can provide valuable insights for your journey with SwapSculpt.

Feel free to dive deep into the documentation to unlock the full potential of SwapSculpt.

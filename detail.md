## Selected Personal Projects

- [cmake_examples](https://github.com/zchrissirhcz/cmake_examples): A practical, easy-to-copy project, covering many missing examples in other "cmake-examples" repos.
- [smallcv](https://github.com/zchrissirhcz/smallcv): Re-implementation of OpenCV's imread/imwrite/imshow/draw rect/etc.
- [imageset-viewer](https://github.com/zchrissirhcz/imageset-viewer): A GUI tool implemented in Python tkinter, visualizing ImageNet/VOC images with annotated boxes and names, supporting pick-and-save current image.

## My Contribution List

| id | repo | #PRs |
| --- | ---------- | ---------- |
| 1 | [ncnn](https://github.com/tencent/ncnn) | 52 [merged PRs](https://github.com/tencent/ncnn/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 2 | [opencv](https://github.com/opencv/opencv) | 4 [merged PRs](https://github.com/opencv/opencv/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 3 | [tengine](https://github.com/oaid/tengine) | 3 [merged PRs](https://github.com/oaid/tengine/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 4 | [Ultra-Fast-Lane-Detection](https://github.com/cfzd/Ultra-Fast-Lane-Detection) | 2 [merged PRs](https://github.com/cfzd/Ultra-Fast-Lane-Detection/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 5 | [ArmNeonOptimization](https://github.com/Ldpe2G/ArmNeonOptimization) | 2 [merged PRs](https://github.com/Ldpe2G/ArmNeonOptimization/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 5 | [tnn](https://github.com/tencent/tnn) | 9 [merged PRs](https://github.com/tencent/tnn/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 6 | [vcpkg](https://github.com/microsoft/vcpkg) | 1 [opened PR](https://github.com/microsoft/vcpkg/pulls?q=is%3Apr+author%3Azchrissirhcz) |
| 7 | [AdelaiDet](https://github.com/aim-uofa/AdelaiDet) | 1 [merged PR](https://github.com/aim-uofa/adelaidet/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 8 | [mirrors-china](https://github.com/vra/mirrors-china) | 4 [merged PRs](https://github.com/vra/mirrors-china/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 9 | [nanodet](https://github.com/RangiLyu/nanodet/) | 1 [merged PR](https://github.com/RangiLyu/nanodet/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 10 | [zsh-completions](https://github.com/zsh-users/zsh-completions) | 1 [merged PR](https://github.com/zsh-users/zsh-completions/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 11 | [msnhnet](https://github.com/msnh2012/Msnhnet) | 1 [merged PR](https://github.com/msnh2012/Msnhnet/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |
| 12 | [carla](https://github.com/carla-simulator/carla) | 1 [merged PR](https://github.com/carla-simulator/carla/pulls?q=is%3Apr+author%3Azchrissirhcz+is%3Amerged) |


## Memory checking tools

Writing C/C++ will definitely encounter memory leak / segment fault / unexpected behaviros.

Tools that I use and works:
- [vld](https://github.com/oneiric/vld/): Memory leak checking for Visual Studio
- [AddressSanitizer](https://github.com/google/sanitizers): Invalid memory access (mostly segment fault) checking for VS2019 / Linux / Android NDK
- [Valgrind](http://valgrind.org/): Memory leak checking for Linux.

I've also create a useful tool, **util.cmake** (un-published, send email for access), putting fatal compile flags as error inside, which can be easily integrated into cmake-based projects, and saved my colleagues hours for more that 5 times. A reference blog (in Chinese) is [here](https://www.cnblogs.com/zjutzz/p/10802138.html).

## My Configurations

Good tools boost programming efficiency, avoiding tedious problems with nice configurations. I do keep a **dotfiles**(un-published, send email for access) for every-day tools configurations, including:
- zsh
- vim / tmux
- git, gitlint
- editorconfig
- VSCode
- mirrors for ubuntu/pip/conda/gradle/npm

I also write useful scripts as tiny tools to bring efficiency:
- zero_width_unicode_checker.py
- kill-orphan-process-that-occupy-nvidia-cards.sh
- generate-apt-mirrors.py
- generate-gradle-mirrors.py

I care about indentation and encodings:
- spaces instead of tabs
- tabsize 4 instead of 2
- indent with 4 spaces
- UTF-8 instead of GBK on Windows
- CR/LF separately configure in gitconfig for each system
- follow git commit convention as possible

I use cmake for build management:
- create C/C++ projects with CMake, instead of IDE (Visual Studio, CLion, XCode)
- write `xxxConfig.cmake` for dependencies for maintainable / portable integration with cmake


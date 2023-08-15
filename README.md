# sph4x

## rationale

let's get collaborating on some h4x on everything sp-404 mk2! complete python support for all things serializable from the sp and app would be quite useful for live coding, daw[less] composition, ml/llm hacking, etc.. of course, full sp h/w control would also be worth including as well... for extra credit, reverse engineering the app would be nice to so one wouldn't be limited to only using the app (imagine auv3/vst3 plugins, max8 extensions, mobile, web, etc. version with even more features) and of course a natural language/chat/voice interface for doing our bidding... the sky's the limit!!!

## installation/setup

h4x are primarily in **python**, hit up the following via **miniconda** with initial work done on **MacOS** and optionally **Parallels** for **MacOS**:

1. install various toolchain elements and path appropriately: [vscode](https://code.visualstudio.com), [miniconda](https://conda.io/miniconda.html), [010 editor](https://www.sweetscape.com/010editor/) hex editor, and others via homebrew, including **git**
1. clone project in preferred h4x'n space (why not ~/h4x ftw!):
    ```
    git clone https://github.com/dirkleas/sph4x
    cd sph4x
    ```
1. create **miniconda** virtual environment:

    ```
    conda create --name sph4x
    conda activate sph4x
    ```
1. install `python` packages:
    ```
    pip install -r requirements.txt
    ```

## roadmap

1. create rich python sdk for complete midi support, supported file i/o (projects, pattern chains, patterns, settings, etc.), sample management
1. reverse engineer app for convenient porting to mobil, web, uC, embedded, etc.
1. firmware h4x
1. workflows of all types from resampling, pattern sequencing, etc.. also consider meta-workflows (i.e. lead sheets/fakebooks to complete songs/albums, music for cinema, busking, live shows, improv, etc.)
1. integrations with other gear, both hardware and software focusing on friction free, seamless, and reliable performance rigs



questions? suggestions? wanna help? reach out [here](https://github.com/dirkleas/sph4x/issues) -- it's not just for issues and bugs!

--

This project is licensed under the terms of the MIT license. See [LICENSE](LICENSE) for details.

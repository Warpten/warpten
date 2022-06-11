### Hi there 👋

I'm a (mostly) self-taught software developer; my actual degree is a MSc in Theoretical Chemistry. I started writing my first programs when I was 12. Nowadays, I regularly develop in C++, C#, Java, TypeScript, and have started picking up Rust. Here are some of my public projects that you may find of interest.

## C++

1. [TrinityCore](https://github.com/TrinityCore/TrinityCore) is an open-source cross-platform MMORPG server framework. It uses [Boost](https://www.boost.org), [MariaDB](http://mariadb.org), [Grafana](https://grafana.com/), [InfluxDB](https://www.influxdata.com/), [CMake](https://cmake.org/), and [OpenSSL](https://www.openssl.org/).
3. [Dread](https://github.com/Warpten/Dread) is an [IDA Pro](https://hex-rays.com/) plugin designed to help static analysis of Metroid Dread. It uses IDA's own APIs as well as [Clang](https://clang.llvm.org/) (specifically, Clang's AST matchers) to analyze pseudocode and derive information that is then used to produce C header files, or automate reverse engineering. Development is ongoing.
4. [hzdnptr](https://github.com/Warpten/hzdnptr) is an injectable DLL designed to patch offending assembly in Horizon Zero Dawn's early PC releases (`*((volatile int*)0) = 0xDEADCA7;` to be exact), which triggering during play and caused the game to crash. It uses [Boost](https://www.boost.org), minhook, [fmt](https://github.com/fmtlib/fmt), [Zydis](https://github.com/zyantific/zydis) and [spdlog](https://github.com/gabime/spdlog).
5. [snippetspp](https://github.com/Warpten/snippetspp) is an umbrella repository where I push code I use in some of my projects (some of which are not on GitHub). One in particular is a simple single-header command parser.
6. [vk_jenkins](https://github.com/Warpten/vk_jenkins) is an experiment in writing compute shaders to bruteforce Jenkins hashes.

## C#


1. [DBClientFiles.NET](https://github.com/Warpten/DBClientFiles.NET) is a library designed to parse DBC, DB2 and derivate file formats from World of Warcraft's game client, with a focus on speed and memory efficiency, by leveraging `System.Linq.Expressions` to generate code at runtime. It is a newer version of [DBFilesClient.NET](https://github.com/Warpten/DBFilesClient.NET), but has been put on hold due to lack of time on my end.
2. [WowSniffExplorer](https://github.com/Warpten/WowSniffExplorer) is an attempt at creating a GUI to process and analyze network dumps of World of Warcraft's protocol.
3. [ADBC](https://github.com/Warpten/ADBC2) is very similar to the above, except that it interfaces with World of Warcraft's actual archive files, and provides a fully featured GUI with support for foreign keys, export to CSV, and visualization of textures referenced by DBC files.
4. [MeshViewer](https://github.com/Warpten/MeshViewer) is a .NET application able to render serverside geometry at the location of the player in World of Warcraft, by externally reading process memory. It uses [OpenTK](https://opentk.net/)

> [!NOTE]
> This is the Spaceport template repository.
> 
> Want to package a CMake project as a Gradle dependency? This repository
> gives you what you need to start doing that, with a Spacemaven flavor,
> though the artifacts can be published to any repository that will take
> them.
> 
> Note that the LICENSE of the chosen downstream project must allow
> redistribution like this. If the downstream requires a sources artifact,
> one is made already.
> 
> Various `TODO` comments are left (intentionally) in this repository,
> review them in your copy. In order to publish to Spacemaven, you need
> to correct credentials, which can currently only be requested by email:
> [Direct requests here.](mailto:daedula@derfruhling.net)
> 
> Notably: **This repository expects a git submodule named `downstream` to
> be present in its root.** This should be added as the source repository
> containing CMake files.
> 
> A standard warning follows below, it should be included at the top of 
> the final readme.

> [!IMPORTANT]
> **THIS IS NOT AN OFFICIAL PROJECT**
>
> This project is NOT ENDORSED or contributed to by [Organization],
> or any developer / contributor of the [Project] project.
> 
> This project is forked in an attempt to provide packages
> that are useful on Spacemaven's native repository. Spacemaven is a repository
> mostly dedicated to developing native C/C++ applications with Gradle. 
> 
> The developer(s) of Spaceport packages attempt to make as few changes to the
> project as possible to achieve this packaging. This  project only has an added
> Gradle wrapper over the CMake files.
> 
> Visit the downstream project here:
> https://github.com/google/googletest
> 
> The following packages are published from this repository, click a name to
> get installation instructions:
> - [COORDINATES]<!--[`net.derfruhling.spaceport:[project]`](https://spacemaven.derfruhling.net/repo/native/net.derfruhling.spaceport/[project])-->
> 
> The original `README.md` follows:
---

Put the README.md in the original project here.

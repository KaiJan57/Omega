<h1 align="center"><img src="https://github.com/Omega-Numworks/Omega-Design/blob/master/Omega.png" /></h1>

[![Gitlab pipeline status](https://img.shields.io/badge/Epsilon-12.0.0-yellow?style=for-the-badge&logo=github)](https://github.com/numworks/epsilon)
[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/joachim2lefournis/Omega/lavaos?logo=gitlab&style=for-the-badge)](https://gitlab.com/joachim2lefournis/Omega/pipelines)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?logo=creative%20commons&style=for-the-badge)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![GitHub issues](https://img.shields.io/github/issues/Omega-Numworks/Omega.svg?logo=git&style=for-the-badge)](https://github.com/Omega-Numworks/Omega/issues)

Omega is an extension to the Numworks Epsilon project, which will bring many features to the calculator. Omega is for people who want to add features to the calculator, but can not because it has been rejected by Numworks (and for reasons that are 100% understandable!). For example, there is no point in having a Dark Mode on the calculator. But, it's fun so we add it on Omega! In short, Omega is a kind of Jailbreak.

## Some new features
- Symbolic calculation
- RPN app
- All molar masses (chemistry)
- More Brightness steps (16 instead of 5)
- White, green, blue or yellow LED in exam mode

The complete changelog can be found [here](https://github.com/quentinguidee/Omega/wiki/Complete-changelog)

## Installation

First of all, follow **step 1** [here](https://www.numworks.com/resources/engineering/software/build/). Then:

* For **n0100**:
```
git clone --recursive https://github.com/Omega-Numworks/Omega.git
cd Omega
make MODEL=n0100 clean
make MODEL=n0100
make MODEL=n0100 app_flash
make MODEL=n0100 epsilon_flash
```

<!-- Alternatively, you can use [Omega Installer](https://github.com/Omega-Numworks/installer) `BETA` -->

* For **n0110**:
```
git clone --recursive https://github.com/Omega-Numworks/Omega.git
cd Omega
make MODEL=n0110 clean
make MODEL=n0110
make MODEL=n0110 app_flash
make MODEL=n0110 epsilon_flash
```

## Contribute


## Translations

Everything is translated from French to English/Portuguese/Spanish/German with Google Translate; so, everything is translated, but you could come across translation errors. If so, please open an issue on GitHub, I will correct it :smiley:!

## Omega License

Omega is released under a [CC BY-NC-SA License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

---

<!--<p align="center"><img src="https://www.numworks.com/resources/engineering/software/epsilon.svg" alt="NumWorks Epsilon logo" height="70" ></p>-->
<h1 align="center">Epsilon 12.0.0</h1>

<!-- [![Build Status](https://github.com/numworks/epsilon/workflows/Continuous%20integration/badge.svg)](https://github.com/numworks/epsilon/actions?workflow=Continuous+integration) -->

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg?logo=creative%20commons&style=for-the-badge)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![GitHub issues](https://img.shields.io/github/issues/numworks/epsilon.svg?logo=git&style=for-the-badge)](https://github.com/numworks/epsilon/issues)

Epsilon is a high-performance graphing calculator operating system. It includes eight apps that cover the high school mathematics curriculum.

You can try Epsilon straight from your browser in the [online simulator](https://www.numworks.com/simulator/).

## Diving in

We highly recommend you start by reading the [online documentation](https://www.numworks.com/resources/engineering/software/) for this project. You'll learn how to install the [SDK](https://www.numworks.com/resources/engineering/software/build/) and about the overall architecture of the Epsilon.

## Contributing

If you run into an issue, we would be very happy if you would file a bug on the [issue tracker](https://github.com/numworks/epsilon/issues).

We welcome contributions. For smaller changes just open a pull request straight away. For larger changes we recommend you open an issue first for discussion.

## License

NumWorks Epsilon is released under a [CC BY-NC-SA License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode). NumWorks is a registered trademark.

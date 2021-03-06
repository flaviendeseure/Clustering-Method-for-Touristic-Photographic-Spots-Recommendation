# Clustering Method for Touristic Photographic Spots Recommendation

This paper has been submitted for publication in the 18th International Conference on Advanced Data Mining and Applications (ADMA 2022).

## Abstract

With the soaring popularity of digital photography, it is becoming increasingly explicit that tourists cannot go on vacation without a camera. Tourism and photography have become very complementary, and tourists are constantly seeking the best spots to capture pictures and memorize their vacations. However, the search for the best and unforgettable photographic spots is difficult and time-consuming for tourists, especially during visits new regions.
In this paper, we propose a method for discovering tourist photo spots from geotagged photos using double clustering algorithms. A recommendation system is build based on knowledge extraction from the clusters.
The approach is simulated and experimentally evaluated on a real photographic dataset of the French capital Paris. Our approach identifies the best-known spots in the reference websites, and also quirky or thematic spots.


## Software implementation

All source code used to generate the results and figures in the paper are in
the `code` folder.
The calculations and figure generation are all run inside
[Jupyter notebooks](http://jupyter.org/).
The data used in this study is provided in `data` and the sources for the
manuscript text and figures are in `manuscript`.
Results generated by the code are saved in `results`.
See the `README.md` files in each directory for a full description.


## Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/flaviendeseure/Clustering-Method-for-Touristic-Photographic-Spots-Recommendation.git

or [download a zip archive](https://github.com/flaviendeseure/Clustering-Method-for-Touristic-Photographic-Spots-Recommendation/archive/refs/heads/main.zip).


## Getting the data
You can download the data in the `data` folder with this [access link](https://drive.google.com/file/d/1j_CKuDzeciUccSKZVgqz2VKB3IJHqxwh/view?usp=sharing).


## Dependencies

You'll need a working Python environment to run the code.
The recommended way to set up your environment is through the
[Anaconda Python distribution](https://www.anaconda.com/download/) which
provides the `conda` package manager.
Anaconda can be installed in your user directory and does not interfere with
the system Python installation.
The required dependencies are specified in the file `environment.yml`.

We use `conda` virtual environments to manage the project dependencies in
isolation.
Thus, you can install our dependencies without causing conflicts with your
setup (even with different Python versions).

Run the following command in the repository folder (where `environment.yml`
is located) to create a separate environment and install all required
dependencies in it:

    conda env create


## Reproducing the results

Before running any code you must activate the conda environment:

    source activate ENVIRONMENT_NAME

or, if you're on Windows:

    activate ENVIRONMENT_NAME

This will enable the environment for your current terminal session.
Any subsequent commands will use software that is installed in the environment.

To explore the code results, you can execute the Jupyter notebooks
individually.
To do this, you must first start the notebook server by going into the
repository top level and running:

    jupyter notebook

This will start the server and open your default web browser to the Jupyter
interface. In the page, go into the `code` folder and select the
notebook that you wish to view/run.

The notebook is divided into cells (some have text while other have code).
Each cell can be executed using `Shift + Enter`.
Executing text cells does nothing and executing code cells runs the code
and produces it's output.
To execute the whole notebook, run all cells in order.


## License

All source code is made available under a MIT license. You can freely
use and modify the code, without warranty, so long as you provide attribution
to the authors. See `LICENSE` for the full license text.

The manuscript text is not open source. The authors reserve the rights to the
article content, which is currently submitted for publication in the 18th International Conference on Advanced Data Mining and Applications (ADMA 2022).


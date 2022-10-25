# Initialization

1. Install [`git`](https://git-scm.com/) (for [Windows](https://git-scm.com/download/win), on linux use the package-manager, e.g. `sudo apt install git`)
1. Fork this repository for your self, e.g. [Click on the Fork button on top right of this window](https://github.com/alishakiba/data-mining-fall-2022/fork)
1. Clone this repository by issueing the following command in terminal:
    ```sh
    git clone https://github.com/<your github username>/data-mining-fall-2022.git
    ```
    where `<your github username>` is replaced by your username on GitHub.
1. Install [Anaconda python](https://www.anaconda.com/products/distribution)
1. Change your working directory to the cloned project, e.g. `cd data-mining-fall-2022`
1. Create a virtual environment by the following command:
    ```sh
    conda create -p ./.venv -c local --offline
    ```
1. Activate the virtual environment by `conda activate .venv/`
1. The required packages can be installed using either `pip3` or `conda`, e.g. `conda install jupyter --offline` installs the Jupyter package.
1. Run the Jupyter notebook with `jupyter notebook`

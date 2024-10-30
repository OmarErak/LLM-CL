# LLM CL for Mobile Networks
Code "Large Language Model-Driven Curriculum Design for Mobile Networks" which has been accepted as a symposium paper at IEEE ICCC 2024.
The preprint of the manuscript is available here: [https://arxiv.org/abs/2405.18039]. 
In this paper we explore using an LLM to generate a curriculum for an RL agent to train on. 
## Requirements

To run the code in this repository, you need the following:

- Python 3.8 or higher
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)
- Modified mobile-env (https://github.com/stefanbschneider/mobile-env) github repo, plese make sure to cite their work. This can be added as a submodule.
- This repo will be updated with modified mobile-env repo soon.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/OmarErak/LLM-CL.git
    cd LLM-CL
    ```

2. **Create a virtual environment:**
    ```sh
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Open the Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```

2. **Navigate to the `curriculum_learning.ipynb` notebook and open it.**

3. **Run the notebook cells:**
    - The notebook is organized into sections that correspond to different stages of the implementation.
    - Follow the instructions and comments within the notebook to execute each section.

## Files and Structure

- `curriculum_learning.ipynb`: Jupyter notebook containing the implementation of the LLM-driven curriculum design for RL in mobile networks.
- `one_shot_learning.ipynb`: Jupyter notebook containing the implementation of an RL agent trained on the final environment.
- `requirements.txt`: List of required Python packages.
- `README.md`: This file, providing an overview and usage instructions.

## TODO
- Add the modified mobile-env repo as a submodule

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Citation
If you find the paper or codebase useful, please cite our paper: 
~~~
@misc{erak2024large,
      title={Large Language Model-Driven Curriculum Design for Mobile Networks}, 
      author={Omar Erak and Omar Alhussein and Shimaa Naser and Nouf Alabbasi and De Mi and Sami Muhaidat},
      year={2024},
      eprint={2405.18039},
      archivePrefix={arXiv},
}
~~~


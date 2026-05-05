Toy modelling of Kimi Linear and Mamba2 to see is actually attention all you need?
All experiments were run on Google Colab, so they are comparable with Colab setup, no additional libraries for insallation
31.03.2026: randomly decided to include toy transformer to the analysis

## FILES
### TRAINING FILES
Each Notebook File has code to run KIMI Linear Training. Config Support Training a Full model, Half Model and Quarter size model
1. KIMI_Linear
2. MAMBA2
3. TRANSFORMER

### ANALYSIS FILES
1. ANALYSIS - contains code to make charts and some table based on training logs
2. TESTS - contains code to make evaluation and model tests. Since its also colab-designed, there are also copies of code from models' architectures in order to run checkpoints and do tests.

TODO: Make .py files. All models preserve same training setting, data handling and so on => each training scripts contains similar to other scripts parts. So ideally to separate it so, that no duplicate code or nearly-duplicate code exists

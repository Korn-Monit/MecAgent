# MecAgent

5. Possible Enhancements with More Time
If I had more time and resources, I would focus on the following enhancements:

Experiment with Larger Decoder Models: I would test bigger and more expressive decoder architectures to potentially improve the accuracy of CadQuery code generation.

Train for Longer: More training epochs would allow the model to learn more effectively from the dataset.

Hyperparameter Tuning: I would try different learning rates, batch sizes, and optimizers to optimize performance.

Improve Code Organization: I would refactor the codebase to be more organized and modular, making it easier to understand, maintain, and extend in the future.

Reduce Redundancy: I would clean up the code to eliminate repeated or unnecessary components, ensuring more efficient and readable scripts.


4. Bottlenecks
The primary bottlenecks I encountered in this project were related to both environment setup and compute resources:

Environment Configuration Issues: I ran into conflicting dependencies due to not thoroughly checking the pyproject.toml for version compatibility. Resolving these conflicts and properly configuring the environment took almost three hours, significantly cutting into the time available for model experimentation and tuning. This experience highlights how crucial it is to carefully manage dependencies in machine learning projects, especially when integrating multiple libraries.

GPU and Compute Limitations: My experiments were restricted to using Google Colab, which provides limited GPU resources. This limited the size and complexity of models I could use, as well as the number of experiments I could run within the available time. Training large image-to-code models or running extensive hyperparameter searches was not feasible in this environment.

Together, these bottlenecks—setup time and restricted compute—were the main constraints on what I could achieve in this project.
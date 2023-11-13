# GAN - Generate_New_Faces.ipynb

This Jupyter notebook demonstrates the implementation of a Generative Adversarial Network (GAN) for generating new faces using TensorFlow and Keras.

## Dataset
The code uses the Labeled Faces in the Wild (LFW) dataset, which is deepfunneled for generating realistic faces.

## Getting Started
1. Ensure you have the necessary dependencies installed. You can install them using the following:

    ```bash
    pip install numpy matplotlib tensorflow imageio
    ```

2. Download the LFW dataset and extract it to the specified folder OR other datasets can also be used just remember to change the shape accordingly.

3. Open the Jupyter notebook and run each cell sequentially. Make sure to adjust parameters like `EPOCHS`, `BUFFER_SIZE`, `BATCH_SIZE`, and others based on your preferences.

4. The generator and discriminator models are defined, and the training loop is provided to train the GAN.

5. The training progress is visualized by generating and saving images at different epochs.

## Code Organization
- `make_generator_model()`: Function to create the generator model.
- `make_discriminator_model()`: Function to create the discriminator model.
- Loss functions: `discriminator_loss` and `generator_loss`.
- Optimizers: Adam optimizers for both generator and discriminator.
- Training loop: `train_step` function and `train` function to train the GAN.
- Model checkpoints are saved for future use.

## Results
Generated images are saved at different epochs, providing a visual representation of the training progress.

## How to Use
Run each cell in the notebook sequentially. Adjust parameters if needed, and monitor the generated images to observe how the GAN learns to generate new faces.

## Acknowledgments
This code is adapted from a Colab notebook and uses the LFW dataset.

## Author
Hemant Raj

Feel free to modify and experiment with the code to generate different types of images or use a different dataset.

Happy generating!

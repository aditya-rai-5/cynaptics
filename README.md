# Cynaptics
  Hello, I am Aditya Rai.
  Hi, I'm Aditya Rai, and I'm currently working on tasks assigned as part of my induction into the Cynaptics club. Here's an overview of the subtasks I've been tackling:

## Subtask 1: Image Classification (Real or AI-Generated)
  For this task, I built a model that classifies images as either real or AI-generated. I used the ResNet50 architecture for this purpose, leveraging its robust feature      extraction capabilities to achieve accurate classification.

## Subtask 2: Generative Adversarial Network (GAN)
  This task involved creating a GAN to generate images. The GAN comprises two main components:

    Generator: Produces images from random noise.
    Discriminator: Distinguishes between real and generated images.
  
  The aim is to train the generator to create realistic images by minimizing its loss, while simultaneously training the discriminator to improve its ability to classify     images correctly by maximizing its loss. Additionally, the discriminator from this model is also utilized for Subtask 1.

## Subtask 3: Day-Night Image Transformation using CycleGAN
  For this task, I developed a CycleGAN model to create a day-night image transformation theme. This approach involves:

    Two Generators: One for transforming day images to night and the other for the reverse.
    Two Discriminators: One for evaluating the day-to-night transformations and the other for night-to-day transformations.

  The CycleGAN ensures that transformations are consistent and realistic by enforcing a cyclic consistency loss, allowing seamless image transformations between the two      themes.

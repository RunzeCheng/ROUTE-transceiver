Project-SemCOm empowered AIGC
Author: Runze Cheng
Institution: University of Glasgow

Overview:
Project-SemAIGC explores advanced generative image models, particularly utilizing the Stable Diffusion pipeline and related neural network models for tasks like image generation, segmentation, and token extraction. The notebook is designed for research and educational purposes, showcasing capabilities for image analysis and synthesis using pre-trained models from the Hugging Face ecosystem.

Installation:
To run this project, you need to install the following dependencies:

pip install diffusers transformers scipy mediapy accelerate

Key Components:
Stable Diffusion: Utilized as the primary generative model for creating and modifying images.
CLIP Models: Employed for extracting and tokenizing text, enabling text-conditioned image generation.
Image Segmentation Models: Used for analyzing or segmenting images, enhancing the image generation process.


Setup:
If running in Google Colab, mount Google Drive to access the dataset by running:

from google.colab import drive
drive.mount("/content/drive")

Ensure that your dataset is stored in Google Drive at the location "/content/drive/MyDrive".

Running the Notebook:
Run each cell sequentially to load dependencies, initialize models, and perform image generation or segmentation tasks.
Modify model parameters within the notebook as needed to experiment with different generation and segmentation settings.

Models and Libraries:
Stable Diffusion Pipeline: Incorporates components like PNDMScheduler, AutoencoderKL, and UNet2DConditionModel for stable and optimized image generation.
Schedulers: Various options including PNDMScheduler, LMSDiscreteScheduler, and DDIMScheduler offer flexibility in image generation processes.
CLIP Models: Uses CLIPTextModel and CLIPTokenizer to tokenize and extract text for image conditioning.
Image Segmentation: AutoImageProcessor and UperNetForSemanticSegmentation are employed for semantic image segmentation tasks.

Acknowledgments
This project makes use of models and datasets from Hugging Face, specifically those related to Stable Diffusion, CLIP, and image segmentation tasks. It is intended solely for academic and educational purposes.

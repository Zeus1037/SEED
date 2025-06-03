# SEED: A Benchmark Dataset for Sequential Facial Attribute Editing with Diffusion Models

## For review
-   [x] **Subset of 20K images**: [Google Drive](https://drive.google.com/drive/folders/1DFJMbV4S8nYJ8N6NuTdNW8CbzeNk8nUR)

>   Full dataset: Coming Soon...

-   [x] **Supplementary**: see supplementary_for_SEED.pdf or download from [Google Drive](https://drive.google.com/drive/folders/1DFJMbV4S8nYJ8N6NuTdNW8CbzeNk8nUR)



## Dataset Generation Pipeline

Below is the overview of the SEED Dataset Generation Pipeline. Facial images first undergo mask and prompt generation using Face Parsing and LLaVA. Next, editing sequences and diffusion models (LEdits, SDXL, UltraEdit) are randomly selected at each step for sequential editing. Finally, edited images are rigorously quality-assessed, and detailed annotations—including images, masks, prompts, and quality metrics—are systematically recorded, ensuring dataset realism and diversity.

![dataset_generation_pipeline](./assets/dataset_generation_pipeline.png)



## Support Tasks

By recording detailed information such as masks and prompts during image manipulation, our SEED dataset can support a variety of downstream tasks such as forgery detection, sequence prediction, and spatial localization.

<img src="./assets/support_tasks.png" alt="support_tasks" style="zoom:25%;" />
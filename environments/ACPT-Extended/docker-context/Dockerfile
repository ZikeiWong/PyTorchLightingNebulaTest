# update to latest available, use Azure ML Studio to identify latest
FROM mcr.microsoft.com/azureml/curated/acpt-pytorch-1.12-py39-cuda11.6-gpu:3

# adjust as needed (preferring concatenated commands to accelerate the image build process)
RUN pip install 'scikit-learn==1.1.3' \
                'opencv-contrib-python==4.6.0.66'

RUN pip install torch_nebula==0.1.0dev1840 -f https://azuremlsdktestpypi.blob.core.windows.net/wheels/AzureML-Nebula-py-feed/dev-package/nebula_dev.html

A bus name board classifier built using Fastai. It can identify bus name boards for the routes -'17D', '12G', '11H', '5E', '11G' 

Test it out with the images available in the test_images folder.

**Testing locally on your mac machine:**

Please remove these two lines in requirements.txt if your are using a mac system before you run    `pip install -r requirements.txt`

(These links download pytorch and torchvision for linux).
`https://download.pytorch.org/whl/cpu/torch-1.1.0-cp37-cp37m-linux_x86_64.whl`
`https://download.pytorch.org/whl/cpu/torchvision-0.3.0-cp37-cp37m-linux_x86_64.whl`

Note : pytorch gets downloaded when fastai version 1.0.46 is getting downloaded.If you want to download pytorch for mac (Pytorch Build : 1.2 Pip, python3.7, Cuda: None ). Use the command -

`pip3 install torch torchvision`

For more details refer - [https://pytorch.org/](https://pytorch.org/)

Once you have downloaded the dependencies in the requirements.txt, you can deploy using the command :

`python app/server.py serve`

The app gets deployed on [http://0.0.0.0:5042](http://0.0.0.0:5042). You can test out the app with the images in the test folder. 



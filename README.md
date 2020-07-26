# Brain-Tumor-Detection-And-Classification
#### To create virtual environment
- open terminal and type "virtualenv ENVIRONMENT_NAME"
- activate virtual environment "source ENVIRONMENT_NAME/bin/activate"

#### Install requirements
- pip3 install numpy pandas matplotlib seaborn cython SimpleITK scikit-learn
note:pip if using window

#### Further process
- go to project folder "cd PROJECT_FOLDER_NAME"
- go to libtsvm/optimizer folder "cd libtsvm/optimizer"
- then run "python3 setup.py build_ext --inplace"
- after that fall back to project folder "cd .."

#### Dataset 
- download Brats2015 dataset from https://www.smir.ch/BRATS/Start2015
- after download copy and paste trainig dataset inside dataset folder 

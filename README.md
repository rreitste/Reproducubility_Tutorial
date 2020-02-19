# Reproducubility_Tutorial
FOSS tutorial
    1  cd /scratch
    2  df -h
    3  git clone https://github.com/rreitste/Reproducubility_Tutorial.git
    4  ls
    5  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    6  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    7  ln -s /opt/conda/pkgs/*/bin/* /bin
    8  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    9  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   10  ls /user/lib
   11  ls
   12  ls /
   13  ls /usr/lib
   14  ls //bin
   15  ls /bin
   16  ls /usr/lib
   17  ls /bin
   18  ls /usr/lib
   19  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   20  ls /usr/lib
   21  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   22  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   23  /opt/conda/bin/pip install bash_kernel
   24  /opt/conda/bin/pip install ipykernel
   25  /opt/conda/bin/python3 -m bash_kernel.install
   26  /opt/conda/bin/conda search htseq
   27  /opt/conda/bin/conda search -c bioconda htseq
   28  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   29  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   30  ls
   31  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/Reproducibility-tutorial/'
   32  ls
   33  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/Reproducibility_tutorial/'
   34  ls
   35  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/Reproducibility_Tutorial/'
   36  ls
   37  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' 
   38  /opt/conda/bin/conda search -c bioconda snakemake
   39  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   40  ln -s /opt/conda/bin/* /bin
   41  ln -s /opt/conda/lib/* /usr/lib
   42  snakemake --version
   43  sudo apt-get update
   44  sudo apt-get install -y apt-transport-https \
   45  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   46  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   47  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   48   $(lsb_release -cs) \
   49   stable"
   50  sudo apt-get update
   51  cd scratch
   52  ls
   53  ls
   54  cd /scratch
   55  ls
   56  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   57  docker run hello-world
   58  cd /scratch/Reproducibility_Tutorial
   59  ls
   60  history >>README.md
   61  nano README
   62  ls
   63  cd Reproducubility_Tutorial/
   64  ls
   65  nano README.md 
   66  ls
   67  history >>README.md 

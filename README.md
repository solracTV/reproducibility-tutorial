# reproducibility-tutorial    1  cd /scratch/
    1  git clone https://github.com/solracTV/reproducibility-tutorial.git
    2  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    3  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    4  ln -s /opt/conda/pkgs/*/bin/* /bin
    5  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    6  ls
    8  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
    9  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   10  python3 -m pip install bash_kernel
   11  /opt/conda/bin/conda install -y ipykernel
   12  sudo apt-get install python3-pip
   13  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   14  clear
   15  python3 -m pip install bash_kernel
   16  python3 -m pip install ipykernel
   17  python3 -m bash_kernel.install
   18  sudo apt install -y python3-pip
   19  apt-get update 
   20  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   21  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   22  ln -s /opt/conda/bin/* /bin
   23  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   24  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   25  ln -s /opt/conda/pkgs/*/bin/* /bin
   26  snakemake --version
   56  sudo apt-get update
   57  udo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   58  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   59  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   60  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \ $(lsb_release -cs) \ stable"
   61  sudo apt-get update
   62  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   64  ln -s /opt/conda/bin/* /bin
   65  docker run hello-world
   66  cd /scratch/reproducibility-tutorial/
   67  history >>README.md

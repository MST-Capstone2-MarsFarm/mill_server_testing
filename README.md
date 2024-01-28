# mill_server_testing
running a basic python script using a specific anaconda environment<br/>

# install environment
mamba env create --file environment.yml<br/>

# run command
srun --time=1:00:00 -p general --pty /bin/bash env_test.sh
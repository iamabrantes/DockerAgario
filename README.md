Agar.io Clone
=============
How to:

1-Clone the repository

git clone https://github.com/jonathanabrantes/DockerAgario.git

2-Go to the folder

cd DockerAgario

3-Build the image

docker build -t agarioclone_agar .

4-Run the container to port 80

docker run -it -p 80:3000 agarioclone_agar

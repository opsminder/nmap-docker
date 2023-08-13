# nmap Dockerfile
This project builds an apline linux container to run nmap.  

## Running

Run the container and pass any `nmap` options as arguments:
`docker-compose run -it nmap <options>`

For example:
`docker-compose run -it nmap -v -A gazornaplaten.org`
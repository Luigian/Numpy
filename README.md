# Numpy - 42 School 2-Days Project

### E-commerce

After the first week of the piscine, we had to -in a weekend– create a mini e-commerce online shop. This should cover products and users management with a well organized data base. Our e-commerce should allow a user to register, connect, add articles in his basket and validate his order. Once validated, the order must be visible from an administration section.

## Installation
*Python 3, Docker and VirtualBox must be installed.

`docker-machine start` | Start the "default" virtual machine.

`eval "$(docker-machine env default)"` | Set new IP addresses for started machines.

`docker run -p 8800:8888 -v $(pwd)/notebooks:/notebooks numpy_rush` | Connect to notebook server.

`docker-machine ls` | Check the list of docker machine availables.

*From the last two commands respectively, copy the token and the running virtual box IP address and replace the x's:

`http://xxx.xxx.xx.xxx:8800/?token=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`

*Example:
`http://192.168.99.100:8800/?token=034f1e8164e65bb1b89f376898831faa03aca054dc15300f`

*Then, go to the web browser and paste the link.
*Finally upload to Jupyter the file notebook/numpy.ipynb and resources/images/portrait.png

## Usage
`Register` | Creates new user and password.

`Login` | Start user session.

`Shop` | Add items to the 'basket'.

`MyAccount` | Change password.

## Preview

<img src="resources/images/numpy.png" width="1000">

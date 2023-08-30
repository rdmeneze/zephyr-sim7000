# zephyr-sim7000
test implementation to validate the SIM7000 modem zephyr drive

## Build instructions
* clone repository : ``` git clone https://github.com/rdmeneze/zephyr-sim7000.git ```
* initialize to the forked version: ``` west init -m https://github.com/rdmeneze/zephyr.git ```
* update west: ``` west update ``` 
* change the branch to the correct one: ``` cd zephyr && git branch mdm_sim7000 ```
* build the project: ``` west build -p always -b disco_l475_iot1 .  ``` 

Deployment prerequisities

1. On OPC server, DCOM settings are applied as per standard document
2. User and password of agent machine to be set to same value as OPC server
3. Java jdk to be installed on OPC agent machine
4. Python to be installed on OPC agent machine
5. Admin rights to be given on OPC agent machine
6. Windows Firewall to turnedd off on OPC agent machine
7. You should be able to ping IP address of OPC server from agent machine
8. From PC on which agent is installed, matrokon explorer should be able to connect

How to install

1. Clone and unzip pacakge to desired directory on remote machine
2. Setup OPC server IP, PROGID, USER, PASSWORD in config.properties
3. Setup taglist
4. Setup start_data_agent.bat with correct folder path
5. Double click bat file
6. On success you will see log messages indicating data flow.
7. On fail, the console will be stuck at initial load.

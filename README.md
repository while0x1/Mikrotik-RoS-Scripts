# Mikrotik-RoS-Scripts

Place this script in mikrotik router RoS > system > scripts and set a scheduler to run the script every 120 seconds. 
Use the terminal to create the prevSlot global variable before you run the script so it is initialized: global prevSlot "1";
Requirements: Running Cardano Node with Prometheus installed see:
https://www.coincashew.com/coins/overview-ada/guide-how-to-build-a-haskell-stakepool-node/part-iii-operation/setting-up-dashboards
https://prometheus.io/docs/introduction/overview/

To increase utility you can use SMTP (email) alert system by configuring the email settings in > tools > email and modifying the last else{} statement to trigger
an email alert using this mail server. 

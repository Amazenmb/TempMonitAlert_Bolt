# TempMonitAlert_Bolt
This is a project created for monitoring temperature as per given operational range for the system under observation.
Major Components Used: Bolt Wifi Module, LM35 temperature sensor. 
Applications/Softwares used: Bolt Cloud Platform, VMware Workstation Player, Twilio and Mailgun APIs. 
Programming Language used: Python. 
First data is collected from the sensor environment. Using polynomial regression, data points are then predicted based on the previously collected data points and other tuning parameters. Anomaly detection is also achieved to detect any irregular changes or distrbances in the system temperature and SMS/ E-mail alerts are sent to user via Twilio and Mailgun APIs.

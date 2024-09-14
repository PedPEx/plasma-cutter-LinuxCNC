# plasma-cutter-LinuxCNC
LinuxCNC plasma cutter configuration (EtherCAT IO)

## EtherCAT hardware
Slave     | Manufacturer    | Description                   | Mode      | Installation Location         | Working   
--------  | -------         | -------                       | --------  | --------                      | -------   
 0        | Beckhoff        | EK1100                        | /         | control cabinet               | ✅
 1        | Beckhoff        | EL1008 - 10 µs, 8 Inputs      | /         | control cabinet               | ✅
 2        | Beckhoff        | EL1018 - 3 ms, 8 Inputs       | /         | control cabinet               | ✅
 3        | Beckhoff        | EL2008 - 8 Inputs, 24V, 0.5 A | /         | control cabinet               | ✅
 4        | Beckhoff        | EK1122 - EtherCAT junction    | /         | control cabinet               | ✅
|  |  |  |  |  |    
 5        | Beckhoff        | EK1100                        | /         | junction-box plasma-cutter    | ✅
 6        | Beckhoff        | EL1859 - 8 Inp (3 ms), 8 Outp | /         | junction-box plasma-cutter    | ✅
 7        | Beckhoff        | EL5101 - frequency inp. THC   | /         | junction-box plasma-cutter    | ✅
|  |  |  |  |  |    
 8        | Beckhoff        | EP4374-000 - 2 analog Inp, 2 analog Outp  | /         | Z-Axis    | ✅
 9        | Beckhoff        | EP2316-0008 - 8 Inp (3 ms), 8 Outp        | /         | Z-Axis    | ✅
|  |  |  |  |  |    
10        | RTELLIGENT      | ECT60 - ClosedLoop 6 A Stepper Driver | CiA402: CSP   | control cabinet   | ✅ [Test Config RTELLIGENT](RTELLIGENT_Test/)
11        | RTELLIGENT      | ECT60 - ClosedLoop 6 A Stepper Driver | CiA402: CSP   | control cabinet   | ✅ [Test Config RTELLIGENT](RTELLIGENT_Test/)
12        | RTELLIGENT      | ECT86 - ClosedLoop 7 A Stepper Driver | CiA402: CSP   | control cabinet   | ✅ [Test Config RTELLIGENT](RTELLIGENT_Test/)
13        | RTELLIGENT      | ECT86 - ClosedLoop 7 A Stepper Driver | CiA402: CSP   | control cabinet   | ✅ [Test Config RTELLIGENT](RTELLIGENT_Test/)
|  |  |  |  |  |    
Testing | Hardware:
 /        | JMC             | iHSV57-30-18-36-EC | CiA402: CSP  | In Field | ✅ [Test Config JMC](JMC-Servo_Test/)


## Configs
All (test) configs for the plasma-cutter are tracked in this repo

## Pictures
Coming soon...
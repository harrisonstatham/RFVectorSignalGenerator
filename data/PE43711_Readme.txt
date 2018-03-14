
SnP Filename convention:

S_PExxxx_Temperature_VDD_VCTRL_HIGH_VCTRL_LOW_AttenuationSetting_Serial#

Example file:

S_PE43711_25C_3p300V_3p000V_0p000V_LS_ATT_0p00dB_S2P_SN_5.s2p

S = Scalar de-embedding of PCB trace S-Parameters has been applied to the data
    (if S is not pre-pended to the filename, the data is not de-embedded)

PExxxx = Product number
Temperature = Temperature of DUT when measured
VDD = VDD of test iteration
VCTRL_HIGH = CONTROL VOLTAGE HIGH
VCTRL_LOW = CONTROL VOLTAGE LOW
AttenuationSetting = Attenuation Setting of part tested
Serial# = serial number of part tested
Insertion = Is rarely used and will show as A. this will change if multiple
            insertions are required to collect all S-parameters of a device with
            more than 12 RF ports.
____________________________________
VNA port defintions:
Port 1 = Pin/J1
Port 2 = Pout/J2
____________________________________
PCB Part Number = PRT-45405-01
PCB Date Code = 3813
____________________________________
De-embedding Date = 05/14/2014
Engineer = SKH
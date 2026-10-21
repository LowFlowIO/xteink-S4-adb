add device 1: /dev/input/event1
  bus:      0019
  vendor    0000
  product   0000
  version   0000
  name:     "rk805 pwrkey"
  location: "rk805_pwrkey/input0"
  id:       ""
  version:  1.0.1
  events:
    KEY (0001): 0074 
  input props:
    <none>
add device 2: /dev/input/event3
  bus:      0019
  vendor    0001
  product   0001
  version   0100
  name:     "adc-keys"
  location: "adc-keys/input0"
  id:       ""
  version:  1.0.1
  events:
    KEY (0001): 0072  0073 
  input props:
    <none>
add device 3: /dev/input/event2
  bus:      0018
  vendor    0000
  product   0000
  version   0000
  name:     "gslX680-d708"
  location: ""
  id:       ""
  version:  1.0.1
  events:
    KEY (0001): 0068  006d  009e  00d9 
    ABS (0003): 002f  : value 1, min 0, max 10, fuzz 0, flat 0, resolution 0
                0030  : value 0, min 0, max 255, fuzz 0, flat 0, resolution 0
                0032  : value 0, min 0, max 200, fuzz 0, flat 0, resolution 0
                0035  : value 0, min 0, max 480, fuzz 0, flat 0, resolution 0
                0036  : value 0, min 0, max 800, fuzz 0, flat 0, resolution 0
                0039  : value 0, min 0, max 65535, fuzz 0, flat 0, resolution 0
  input props:
    INPUT_PROP_DIRECT
add device 4: /dev/input/event0
  bus:      0000
  vendor    0000
  product   0000
  version   0000
  name:     "rk817-charger"
  location: "rk817-charger"
  id:       ""
  version:  1.0.1
  events:
    KEY (0001): 008f 
  input props:
    <none>

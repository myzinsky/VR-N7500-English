Android App
===========


JSON Channel-Management
--------------------

.. code-block:: JSON

  {
     "n":"Regional",
     "chs":[
        {
           "n":"Test1",
           "rf":"145.500",
           "ts":6700,
           "rs":6700,
           "id":1,
           "p":0
        },
        {
           "n":"Test2",
           "rf":"145.500",  
           "ts":7190,
           "rs":6930,
           "w":0,
           "id":1,
           "p":-1,
           "td":1
        }
        {
           "rf":"145.550",
           "w":0,
           "s":1,
           "id":1,
           "p":-2
        },
        {
           "n":"OV Y01",
           "rf":"145.325",
           "w":0,
           "s":1,
           "id":1,
           "p":-2
        },
        {
           "rf":"145.600",
           "tf":"145.000",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0PSW",
           "rf":"438.900",
           "tf":"431.300",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0WOL",
           "rf":"439.150",
           "tf":"433.550",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0UM",
           "rf":"439.2375",
           "tf":"431.6375",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0TA",
           "rf":"439.125",
           "tf":"431.525",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0SX",
           "rf":"439.050",
           "tf":"431.450",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0NBB",
           "rf":"438.750",
           "tf":"431.150",
           "w":0,
           "s":1,
           "id":1,
           "p":-2
        },
        {
           "n":"DB0MSP",
           "rf":"438.675",
           "tf":"431.075",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0BLO",
           "rf":"439.275",
           "tf":"431.675",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"DB0ZOD",
           "rf":"438.725",
           "tf":"431.125",
           "w":0,
           "s":1,
           "id":1,
           "p":0
        },
        {
           "n":"OV Y01-1",
           "rf":"145.3375",
           "w":0,
           "s":1,
           "id":1,
           "p":-2
        },
        null
     ]
  }



Legend:
  
* rf: receive frequency  [double]
* tf: transmit frequency [double]
* rs: receive subtone [int in cHz]
* ts: transmit subtone [int in cHz]
* w:  wide [bool]
* s: scan [bool]
* id: ??? [int]
* p: ??? [int] 

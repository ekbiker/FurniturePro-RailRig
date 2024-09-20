Read HMID
Returned: Success
Configuration Name: HOSTMOT2

General configuration information:

  BoardName : MESA7I95
  FPGA Size: 20 KGates
  FPGA Pins: 256
  Number of IO Ports: 2
  Width of one I/O port: 29
  Clock Low frequency: 100.0000 MHz
  Clock High frequency: 160.0000 MHz
  IDROM Type: 3
  Instance Stride 0: 4
  Instance Stride 1: 64
  Register Stride 0: 256
  Register Stride 1: 256

Modules in configuration:

  Module: DPLL
  There are 1 of DPLL in configuration
  Version: 0
  Registers: 7
  BaseAddress: 7000
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: WatchDog
  There are 1 of WatchDog in configuration
  Version: 0
  Registers: 3
  BaseAddress: 0C00
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: IOPort
  There are 2 of IOPort in configuration
  Version: 0
  Registers: 5
  BaseAddress: 1000
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: MuxedQCount
  There are 6 of MuxedQCount in configuration
  Version: 4
  Registers: 5
  BaseAddress: 3600
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: MuxedQCountSel
  There are 1 of MuxedQCountSel in configuration
  Version: 0
  Registers: 0
  BaseAddress: 0000
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: PWM
  There are 1 of PWM in configuration
  Version: 0
  Registers: 5
  BaseAddress: 4100
  ClockFrequency: 160.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: SSerial
  There are 1 of SSerial in configuration
  Version: 0
  Registers: 6
  BaseAddress: 5B00
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 64 bytes

  Module: StepGen
  There are 11 of StepGen in configuration
  Version: 2
  Registers: 10
  BaseAddress: 2000
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: SSR
  There are 1 of SSR in configuration
  Version: 0
  Registers: 2
  BaseAddress: 7D00
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: InMux
  There are 1 of InMux in configuration
  Version: 0
  Registers: 5
  BaseAddress: 8000
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

  Module: LED
  There are 1 of LED in configuration
  Version: 0
  Registers: 1
  BaseAddress: 0200
  ClockFrequency: 100.000 MHz
  Register Stride: 256 bytes
  Instance Stride: 4 bytes

Configuration pin-out:

IO Connections for Step/DIR+Serial+Encoders -> 7I95_0
Pin#                  I/O   Pri. func    Sec. func        Chan     Sec. Pin func   Sec. Pin Dir

TB3-2,3                 0   IOPort       StepGen          0        Step/Table1     (Out)
TB3-4,5                 1   IOPort       StepGen          0        Dir/Table2      (Out)
TB3-8,9                 2   IOPort       StepGen          1        Step/Table1     (Out)
TB3-10,11               3   IOPort       StepGen          1        Dir/Table2      (Out)
TB3-14,15               4   IOPort       StepGen          2        Step/Table1     (Out)
TB3-16,17               5   IOPort       StepGen          2        Dir/Table2      (Out)
TB3-20,21               6   IOPort       StepGen          3        Step/Table1     (Out)
TB3-22,23               7   IOPort       StepGen          3        Dir/Table2      (Out)
TB4-2,3                 8   IOPort       StepGen          4        Step/Table1     (Out)
TB4-4,5                 9   IOPort       StepGen          4        Dir/Table2      (Out)
TB4-8,9                10   IOPort       StepGen          5        Step/Table1     (Out)
TB4-10,11              11   IOPort       StepGen          5        Dir/Table2      (Out)
TB2-14,15              12   IOPort       SSerial          0        RXData0         (In)
TB4-16,17              13   IOPort       SSerial          0        TXData0         (Out)
Internal               14   IOPort       SSerial          0        TXEn0           (Out)
TB4-20,21              15   IOPort       SSerial          0        RXData1         (In)
TB4-22,23              16   IOPort       SSerial          0        TXData1         (Out)
Internal               17   IOPort       SSerial          0        TXEn1           (Out)
TB1-1,2,9,10           18   IOPort       MuxedQCount      0        MuxQ-A          (In)
TB1-4,5,12,13          19   IOPort       MuxedQCount      0        MuxQ-B          (In)
TB1-7,8,15,16          20   IOPort       MuxedQCount      0        MuxQ-IDX        (In)
TB1-17,18 TB2-1,2      21   IOPort       MuxedQCount      1        MuxQ-A          (In)
TB1-20,21 TB2-4,5      22   IOPort       MuxedQCount      1        MuxQ-B          (In)
TB1-23,24,TB2-7,8      23   IOPort       MuxedQCount      1        MuxQ-IDX        (In)
TB2-9,10,17,18         24   IOPort       MuxedQCount      2        MuxQ-A          (In)
TB2-11,12,20,21        25   IOPort       MuxedQCount      2        MuxQ-B          (In)
TB2-15,16,23,24        26   IOPort       MuxedQCount      2        MuxQ-IDX        (In)
Internal               27   IOPort       MuxedQCountSel   0        MuxSel0         (Out)
Internal               28   IOPort       InMux            0        Addr0           (Out)

IO Connections for I/O+Expansion -> 7I95_1
Pin#                  I/O   Pri. func    Sec. func        Chan     Sec. Pin func   Sec. Pin Dir

Internal               29   IOPort       InMux            0        Addr1           (Out)
Internal               30   IOPort       InMux            0        Addr2           (Out)
Internal               31   IOPort       InMux            0        Addr3           (Out)
Internal               32   IOPort       InMux            0        Addr4           (Out)
Internal               33   IOPort       InMux            0        Data0           (In)
TB3-13,14              34   IOPort       SSR              0        Out-00          (Out)
TB3-15,16              35   IOPort       SSR              0        Out-01          (Out)
TB3-17,18              36   IOPort       SSR              0        Out-02          (Out)
TB3-19,20              37   IOPort       SSR              0        Out-03          (Out)
TB3-21,22              38   IOPort       SSR              0        Out-04          (Out)
TB3-23,24              39   IOPort       SSR              0        Out-05          (Out)
Internal               40   IOPort       SSR              0        AC Ref          (Out)
P1-01/DB25-01          41   IOPort       PWM              0        PWM             (Out)
P1-02/DB25-14          42   IOPort       None           
P1-03/DB25-02          43   IOPort       StepGen          6        Step/Table1     (Out)
P1-04/DB25-15          44   IOPort       None           
P1-05/DB25-03          45   IOPort       StepGen          6        Dir/Table2      (Out)
P1-06/DB25-16          46   IOPort       StepGen         10        Step/Table1     (Out)
P1-07/DB25-04          47   IOPort       StepGen          7        Step/Table1     (Out)
P1-08/DB25-17          48   IOPort       StepGen         10        Dir/Table2      (Out)
P1-09/DB25-05          49   IOPort       StepGen          7        Dir/Table2      (Out)
P1-11/DB25-06          50   IOPort       StepGen          8        Step/Table1     (Out)
P1-13/DB25-07          51   IOPort       StepGen          8        Dir/Table2      (Out)
P1-15/DB25-08          52   IOPort       StepGen          9        Step/Table1     (Out)
P1-17/DB25-09          53   IOPort       StepGen          9        Dir/Table2      (Out)
P1-19/DB25-10          54   IOPort       None           
P1-21/DB25-11          55   IOPort       None           
P1-23/DB25-12          56   IOPort       None           
P1-25/DB25-13          57   IOPort       None           



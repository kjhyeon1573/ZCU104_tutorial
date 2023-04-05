# ZCU104_tutorial
ZCU104 tutorial including examples

manual:
https://www.xilinx.com/support/documents/boards_and_kits/zcu104/ug1267-zcu104-eval-bd.pdf

Basic clock constraint setting:
https://www.xilinx.com/video/hardware/creating-basic-clock-constraints.html

tcl command list:
https://docs.xilinx.com/v/u/2019.2-English/ug835-vivado-tcl-commands

# Trouble Shooting
error 01:
  [Labtools 27-3421] xczu7_0 PL Power Status OFF, cannot connect PL TAP. Check POR_B signal.
solve:
  set mode DIP switch as 4'b0000 (for zcu104 evb)

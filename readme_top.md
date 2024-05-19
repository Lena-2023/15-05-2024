iverilog -o qqq top.v note2dds_1st_gen.v dds.v form_wave.v ttop.v
vvp qqq
gtkwave bench.vcd
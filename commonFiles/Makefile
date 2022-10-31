.DEFAULT_GOAL:=help
######################################################
synthesis:
	dc_shell -f run.tcl | tee syn.log
######################################################
.PHONY: synthesis
######################################################
atpg:
	tmax -shell -notcl tmax.script | tee tmax.log
######################################################
.PHONY: atpg

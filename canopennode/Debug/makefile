################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := D:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./CANopen.obj" \
"./CO_Emergency.obj" \
"./CO_HBconsumer.obj" \
"./CO_NMT_Heartbeat.obj" \
"./CO_OD.obj" \
"./CO_PDO.obj" \
"./CO_SDOclient.obj" \
"./CO_SDOserver.obj" \
"./CO_SYNC.obj" \
"./CO_TIME.obj" \
"./CO_driver_blank.obj" \
"./CO_fifo.obj" \
"./crc16-ccitt.obj" \
"./eeprom.obj" \
"./main_blank.obj" \
$(GEN_CMDS__FLAG) \
-lrtsv7M3_T_le_eabi.lib \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
canopennode.out \

EXE_OUTPUTS__QUOTED += \
"canopennode.out" \

BIN_OUTPUTS += \
canopennode.hex \

BIN_OUTPUTS__QUOTED += \
"canopennode.hex" \


# All Target
all: canopennode.out

# Tool invocations
canopennode.out: $(OBJS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"D:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/bin/armcl" -mv7M3 --code_state=16 -me -g --gcc --define=ccs --diag_wrap=off --diag_warning=225 --display_error_number --gen_func_subsections=on --abi=eabi --ual -z -m"canopennode.map" --stack_size=256 --heap_size=0 -i"D:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/lib" -i"D:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/include" --reread_libs --display_error_number --warn_sections --diag_wrap=off --xml_link_info="canopennode_linkInfo.xml" --rom_model -o "canopennode.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

canopennode.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"D:/ti/ccsv6/tools/compiler/arm_15.12.3.LTS/bin/armhex"  -o "canopennode.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "CANopen.d" "CO_Emergency.d" "CO_HBconsumer.d" "CO_NMT_Heartbeat.d" "CO_OD.d" "CO_PDO.d" "CO_SDOclient.d" "CO_SDOserver.d" "CO_SYNC.d" "CO_TIME.d" "CO_driver_blank.d" "CO_fifo.d" "crc16-ccitt.d" "eeprom.d" "main_blank.d" 
	-$(RM) "CANopen.obj" "CO_Emergency.obj" "CO_HBconsumer.obj" "CO_NMT_Heartbeat.obj" "CO_OD.obj" "CO_PDO.obj" "CO_SDOclient.obj" "CO_SDOserver.obj" "CO_SYNC.obj" "CO_TIME.obj" "CO_driver_blank.obj" "CO_fifo.obj" "crc16-ccitt.obj" "eeprom.obj" "main_blank.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets


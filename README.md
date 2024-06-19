st# Awesome-RP2040-Pico-W

## Technical Info

- RP2040 Arm Cortex-M0+ ARMv6-M Little Endian

### Memory Mapping
 - https://petewarden.com/2024/01/16/understanding-the-raspberry-pi-picos-memory-layout/
 - https://github.com/raspberrypi/pico-sdk/blob/master/src/rp2_common/pico_standard_link/memmap_default.ld

## Operating Systems

### FreeRTOS
FreeRTOS is the OS officially supported by Raspberry Foundations (see pico-examples).
- [pico-examples -> FreeRTOS examples](https://github.com/raspberrypi/pico-examples?tab=readme-ov-file#freertos-examples)
- [FreeRTOS Pico SMP Examples](https://www.freertos.org/smp-demos-for-the-raspberry-pi-pico-board.html)
- [Path to RP2040 port in FreeRTOS-Kernel repo](https://github.com/FreeRTOS/FreeRTOS-Kernel/tree/main/portable/ThirdParty/GCC/RP2040)
- [pico_cyw43_arch_lwip_sys_freertos (lwIP full integration, NO_SYS=0)](https://www.raspberrypi.com/documentation/pico-sdk/networking.html)

### Zephyr
- [Official doc](https://docs.zephyrproject.org/latest/boards/raspberrypi/rpi_pico/doc/index.html)

### Eclipse ThreadX (Azure RTOS)

- https://github.com/eclipse-threadx/threadx

### RT-Thread

- https://github.com/RT-Thread/rt-thread/tree/master/bsp/raspberry-pico

### micro-ROS
- https://github.com/micro-ROS/micro_ros_raspberrypi_pico_sdk

### CMSIS-RTOS2
- https://arm-software.github.io/CMSIS_6/latest/RTOS2/index.html

## Trace Visualization Tools

### Tracealyzer (tested with FreeRTOS)
- https://percepio.com/tracealyzer/
- https://github.com/percepio/TraceRecorderSource

## Machine Learning

### TensorFlow Lite Micro
- [Official port](https://github.com/raspberrypi/pico-tflmicro)

### CMSIS-NN
- https://github.com/ARM-software/CMSIS-NN
- https://arm-software.github.io/CMSIS-NN/latest/index.html

### CMSIS-DSP
- https://github.com/ARM-software/CMSIS-DSP
- https://arm-software.github.io/CMSIS-DSP/latest/index.html

## WebSockets

### libwebsockets

- https://github.com/warmcat/libwebsockets/tree/main/minimal-examples/embedded/pico/pico-sspc-binance
- https://libwebsockets.org/git/libwebsockets/tree/minimal-examples/embedded/pico/pico-sspc-binance

### Mongoose

- https://mongoose.ws/documentation/#raspberry-pi-rp2040
- https://github.com/cesanta/mongoose/tree/master/examples/rp2040

### MinnowServer

- https://github.com/RealTimeLogic/MinnowServer
- https://realtimelogic.com/products/sharkssl/minnow-server/

## SDR

- https://github.com/luigifcruz/pico-stuff/tree/main/apps/piccolosdr
- https://github.com/ArjanteMarvelde/uSDR-pico
- https://github.com/dawsonjon/PicoRX/wiki
- https://code.porucha.net/mordae/pico-sdr (https://blog.porucha.net/2024/pico-sdr/)

## Oscilloscope/Logic analyzer
- https://github.com/pico-coder/sigrok-pico
- https://github.com/dotcypress/ula
- https://github.com/fhdm-dev/scoppy
- https://github.com/mars-low/scoppy-pico
- https://github.com/rkarlsba/scoppy
- https://github.com/zaheeroz/scoppy-pico-Oscilloscope

## RNDIS

- https://github.com/hathach/tinyusb/tree/master/examples/device/net_lwip_webserver
- https://github.com/maxnet/pico-webserver
- https://mongoose.ws/documentation/tutorials/rp2040/pico-rndis-dashboard/

## Security

- CTF: https://github.com/mytechnotalent/dc540-0x00001
- Reverse engineering: https://www.youtube.com/watch?v=q4CxE5P6RUE&t=1s
- Pico Reverse engineering: https://github.com/mytechnotalent/Reverse-Engineering?tab=readme-ov-file#pico-hacking-course
- Ghidra SVD Loader: https://github.com/leveldown-security/SVD-Loader-Ghidra
- Ghidra SVD Loader: https://github.com/antoniovazquezblanco/GhidraSVD
- UF2 Loader: https://github.com/wyattearp/ghidra_uf2loader
- uf2 to bin: https://github.com/microsoft/uf2/tree/master/utils
- HSM: https://github.com/polhenarejos/pico-hsm
- FIDO: https://github.com/polhenarejos/pico-fido

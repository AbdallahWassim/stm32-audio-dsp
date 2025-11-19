# STM32 Audio DSP

A real-time Audio Digital Signal Processing (DSP) framework based on STM32 microcontrollers and ARM CMSIS-DSP.  
This project demonstrates filtering, FFT, audio streaming, and embedded signal analysis for low-latency applications.

## 🎧 Features
- Real-time audio pipeline on STM32
- FIR & IIR digital filtering
- FFT, spectrum analysis, windowing
- CMSIS-DSP optimized math functions
- Integration with audio codecs (I2S)
- Low-latency interrupt-driven processing
- Example projects included (FFT demo, filter demo)

## 🛠️ Technologies
- STM32 (F4/F7/H7 series recommended)
- CMSIS-DSP
- C/C++
- I2S / DMA / ADC / DAC
- CubeMX / HAL / LL drivers

## 📁 Project Structure

Core/ → MCU startup & system files
dsp/ → DSP modules (FFT, filters, etc.)
examples/ → Small audio DSP demo applications
docs/ → Theory + architecture
hardware/ → Schematics, codec documentation


## 📄 License
MIT License

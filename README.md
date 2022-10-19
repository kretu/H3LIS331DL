# H3LIS331DL SPI Driver for ESP32 IDF

Simple SPI driver for STMicroelectronics H3LIS331DL MEMS Motion Sensor. All in C using only ESP-IDF base librieries  

#Default configuration
As default sensor is initialised with XYZ axis enabled, Normal mode, 400Hz ODR, 9600 BaudRate

# Main commands

LIS331_init(LIS331_type_t type)                         -Initialisation of sensor by type

LIS331_getMeasurementXYZ(float* X, float* Y, float* Z)  -Get Measurments

LIS331_WhoAmI(void) 				                            -Read device ID corect respond is 0x32

At the moment driver lets change and get status of all main registers without interupts registers (TO DO).




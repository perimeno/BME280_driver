cmake_minimum_required (VERSION 3.13)
project(BME280_CPP)
add_library(bme280driverlib bme280.c bme280.h bme280_defs.h)
target_include_directories(bme280driverlib INTERFACE .)

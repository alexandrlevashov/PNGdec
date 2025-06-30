cmake_minimum_required(VERSION 3.5)


idf_component_register(SRC_DIRS "src"
                       INCLUDE_DIRS "src" 
                       REQUIRES arduino-esp32 
                       PRIV_REQUIRES espressif__esp-dsp
                       )

project(PNGDec)

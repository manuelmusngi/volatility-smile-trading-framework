cmake_minimum_required(VERSION 3.10)
project(VolatilitySmileTrading)

set(CMAKE_CXX_STANDARD 20)

include_directories(include)

add_executable(VolatilitySmileTrading
    src/main.cpp
    src/BlackScholes.cpp
    src/VolatilitySmile.cpp
    src/OptionPricing.cpp
)

CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(CAR_DEMO1)

#Source Directories
AUX_SOURCE_DIRECTORY(.\dir-car\ DIR_CAR)
AUX_SOURCE_DIRECTORY(.\dir-base\ DIR_BASE)
AUX_SOURCE_DIRECTORY(.\dir-main\ DIR_MAIN)

ADD_EXECUTABLE(runcar ${DIR_CAR} ${DIR_BASE} ${DIR_MAIN})
cmake_minimum_required(VERSION 3.5)
project(lingmo-systemicons)

include(FeatureSummary)

install(DIRECTORY Lingmo DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
install(DIRECTORY Lingmo-Dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
